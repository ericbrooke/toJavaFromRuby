
**Similarities:**

1. In both Java and Ruby memory is managed for you via a garbage collector
1. Objects are strongly typed in Java and Ruby
1. There are public, private, and protected methods

**Differences**

1. Java you need to compile your code
1. Java uses braces {} around blocks of code not **end** keyword
1. Java uses import instead of require
1. In Ruby all member variables are private. From the outside, you access everything via methods
1. In Ruby parentheses () in method calls are usually optional and often omitted,  not so in Java
1. Not everything in Java is an object
1. In Java there is static type checking
1. In Java variable names are not just labels. They have a type associated with them.
1. There are are type declarations. In Ruby you just assign to new variable names as-needed and they just “spring up” (i.e. a = [1,2,3] rather than int[] a = {1,2,3};)
1. In Java there is casting i.e. taking an Object of one particular type and “turning it into” another Object type
1. It’s Foo foo = new Foo("hi") - Java instead of foo = Foo.new("hi") - Ruby
1. The Java constructor is the name of the class instead named “initialize” in Ruby
1. Java uses interfaces instead of “mixins”. Java interfaces are considered contracts
1. XML tends to be favored over YAML
1. It’s null instead of nil
1. == and equals() are handled differently in Ruby. Use == when you want to test equivalence in Ruby (equals() in Java). Use equal?() when you want to know if two objects are the same (== in Java)
