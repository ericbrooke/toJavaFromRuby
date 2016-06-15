# toJavaFromRuby
You are a Ruby programmer and you need to learn enough Java to create Android Apps

**Similarities:**

1. Memory is managed for you via a garbage collector
1. Objects are strongly typed
1. There are public, private, and protected methods

**Differences**

1. Java you need to compile your code
1. Java uses braces around blocks of code not **end** keyword
1. Java uses import instead of require
1. In Ruby All member variables are private. From the outside, you access everything via methods
1. In Ruby Parentheses in method calls are usually optional and often omitted,  not so in Java
1. Not everything in Java is an object
1. In Java there is static type checking
1. In Java Variable names are not just labels. They have a type associated with them.
1. There are no type declarations. You just assign to new variable names as-needed and they just “spring up” (i.e. a = [1,2,3] rather than int[] a = {1,2,3};)
1. There is casting
1. It’s Foo foo = new Foo("hi") instead of foo = Foo.new("hi")
1. The Java constructor is the name of the class instead named “initialize”
1. Java uses interfaces instead of “mixins”
1. XML tends to be favored over YAML
1. It’s null instead of nil
1. == and equals() are handled differently in Ruby. Use == when you want to test equivalence in Ruby (equals() in Java). Use equal?() when you want to know if two objects are the same (== in Java)
