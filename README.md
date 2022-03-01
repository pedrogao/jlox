# jlox

> lox implement by java

## run

example：

```lox
class Doughnut {
  cook() {
    print "Fry until golden brown.";
    inner();
    print "Place in a nice box.";
  }
}

class BostonCream < Doughnut {
  cook() {
    print "Hello, you will see me, from plox";
  }
}

BostonCream().cook();
```

```sh
mkdir output
javac -d ./output src/main/java/com/pedrogao/jlox/* 
java -Dfile.encoding=UTF-8 -classpath ./output com.pedrogao.jlox.Lox ./scripts/class.lox
```

## features

- tokens and lexing
- abstract syntax trees
- recursive descent parsing
- prefix and infix expressions
- runtime representation of objects
- interpreting code using the Visitor pattern
- lexical scope
- environment chains for storing variables
- control flow
- functions with parameters
- closures
- static variable resolution and error detection
- classes
- constructors
- fields
- methods, and finally
- inheritance

## references

- https://craftinginterpreters.com/contents.html