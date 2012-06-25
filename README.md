
# Ruby cheatsheet

This is a cheatsheet for Ruby beginners and contains links to resources and
some simple examples to get started with Ruby.

## Ruby Language

### Introduction

TODO: Add some content here.

### Variables

TODO: Add some content here.

### Conditions 

TODO: Add some content here.

### Functions

TODO: Add some content here.

### Objects and classes

*Defining a class*:

    class Foo
      def initialize(name)
        @name = name
      end
    end

This creates a class called Foo. Classes are always named in CamelCase.

*Constructor*: The constructor method for a class should be named `initialize`.
It gets called whenever a new instance of the class is created.

*Instance variable*: Variables that are prefixed with @ are instance variables.
Here, @name is an instance variable of class Foo.

*Creating objects*: Create an object `foo` which is an instance of class Foo 
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
