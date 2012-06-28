
# Ruby cheatsheet

This is a cheatsheet for Ruby beginners and contains links to resources and
some simple examples to get started with Ruby.

## Installation

**Linux/OSX**: [RVM](https://rvm.io/rvm/install/) (Ruby Version Manager) is the
best way to manage Ruby installations on Linux and Mac OSX.

**Windows**: [RubyInstaller](http://rubyinstaller.org/) is the quickest way to
get Ruby installed on Windows.
  

## Ruby Language Basics

### Introduction

The classic "hello world" program:

    puts "Hello, world!"

**Strings**

Ruby strings belong to class String, and can be either single- or double-
quoted.

    'Hello, world!'        #=> "Hello, world!"
    "Hello, world!".class  #=> String
    "Hello".size           #=> 5

**Numbers**

Ruby numbers beong to class Fixnum. 

    2 + 2           #=> 4
    2.class         #=> Fixnum
    
    2 + 1.5         #=> 3.5
    3.5.class       #=> Float

Numbers larger than the integer size on the machine automatically get converted
to Bignum object. So the size of numbers in Ruby is, in theory, only limited by
the available memory on the machine.
    
    2**100          #=> 1267650600228229401496703205376 
    (2**100).class  #=> Bignum

### Variables

Ruby variables are created when a value is assigned to them. Once created, a
variable can be assigned another object of a different type, since Ruby 
variables don't have a fixed type.

    x = 1                # x is a Fixnum object
    x = x + 1.5          # x is now a Bignum
    
    x = "Matz"           # x is now a string
    puts "Hello, #{x}!"  #=> "Hello, Matz!"

You can also interpolate strings as shown in the above example. Anything inside
`#{...}` gets evaluated and interpolated into the string.

### Conditions 

TODO: Add some content here.

### Functions

TODO: Add some content here.

### Objects and classes

**Defining a class**:

    class Foo
      def initialize(name)
        @name = name
      end
    end

This creates a class called Foo. Classes are always named in CamelCase.

**Constructor**: The constructor method for a class should be named 
`initialize`. It gets called whenever a new instance of the class is created.

**Instance variable**: Variables that are prefixed with @ are instance 
variables. Here, @name is an instance variable of class Foo.

**Creating objects**: Create an object `foo` which is an instance of class Foo 
and initialize it with the name "bar".

    foo = Foo.new("bar")

### Arrays

TODO: Add some content here.

### Hashes

TODO: Add some content here.

### Looping and iteration

TODO: Add some content here.

## Online Ruby resources

### Tools

* [Tryruby](http://tryruby.org/) - Try Ruby in your browser.
* [Rubymonk](http://rubymonk.org/) - Interactive Ruby tutorials.

### Books

* [_why's Poignant Guide to Ruby](http://mislav.uniqpath.com/poignant-guide/)
* Chris Pine's [_Learning to Program_](http://pine.fm/LearnToProgram/)
* [_Mr Neighborly's Humble Little Ruby Book_](http://humblelittlerubybook.com/)
* Michael Hartl's [_Learn Rails by Example_](http://ruby.railstutorial.org/ruby-on-rails-tutorial-book)

### Articles

* [15 things for a Ruby beginner](http://www.jasimabasheer.com/posts/meta_introduction_to_ruby.html)

### Blogs

* [Ruby Inside](http://www.rubyinside.com/)
* [Ruby Flow](http://www.rubyflow.com/)
