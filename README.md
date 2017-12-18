# Java 9 introduction

git checkout ...

## Quick-start

`/usr/java/jdk-9.0.1/bin/javac -d mods/com.greet src/com.greet/module-info.java src/com.greet/com/greet/Main.java` to run, change your path to where you have JDK9/bin

`java --module-path mods -m com.greet/com.greet.Main` to run, path omitted here for brevity

`--module-path dir-where-you-have-your-modules`
`-m main-module-name/package.ClassWithMainMethod`


1. com.greet module-info gets created (and is empty)
2. Main class is created which just outputs greetings!
3. org.astro module-info is created, it exports org.astro package
4. World class is created which justs contains String name() method (outputs "World")
5. compilation and execution

### 2nd example commands:

```
javac -d mods/org.astro src/org.astro/module-info.java src/org.astro/org/astro/World.java
javac --module-path mods -d mods/com.greet src/com.greetings/module-info.java src/com.greet/com/greet/Main.java
java --module-path mods -m com.greetings/com.greetings.Main
    Greetings world!
 ```

## Everything else 

1. start - write a hello modules program
2. jshell - use the java shell
3. pack - package the program into a modularized JAR - not ready yet
4. simple-mod - simple modularized app that exports something

