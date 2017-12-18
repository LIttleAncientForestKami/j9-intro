# Java 9 introduction

git checkout ...

## Quick-start

`/usr/java/jdk-9.0.1/bin/javac -d mods/com.greet src/com.greet/module-info.java src/com.greet/com/greet/Main.java` to run, change your path to where you have JDK9/bin

`java --module-path mods -m com.greet/com.greet.Main` to run, path omitted here for brevity

`--module-path dir-where-you-have-your-modules`
`-m main-module-name/package.ClassWithMainMethod`

TBA: doing this in steps so you get it better.

## Everything else 

1. start - write a hello modules program
2. jshell - use the java shell
3. pack - package the program into a modularized JAR - not ready yet
4. simple-mod - simple modularized app that exports something

