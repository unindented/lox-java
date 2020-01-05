# Lox Interpreter (Java)

Lox interpreter written in Java, following Bob Nystrom's book [Crafting Interpreters](https://craftinginterpreters.com/).

## Setup

Make sure you have JDK 8 or later installed, and do the following:

```
git clone https://github.com/unindented/lox-java.git
cd lox-java
mvn package
```

## Build

```
mvn compile
```

## Test

```
mvn test
```

## Run

```
mvn package
java -jar ./target/lox-1.0.0-SNAPSHOT.jar
```

## Meta

- Code: `git clone https://github.com/unindented/lox-java.git`
- Home: <https://unindented.org/>

## Contributors

Daniel Perez Alvarez ([unindented@gmail.com](mailto:unindented@gmail.com))

## License

Copyright (c) 2020 Daniel Perez Alvarez ([unindented.org](https://unindented.org/)). This is free software, and may be redistributed under the terms specified in the `LICENSE.txt` file.
