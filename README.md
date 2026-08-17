# Advitronic MongoDB Pipelines

Small Java starter repository for experimenting with Advitronic MongoDB pipeline work.
The current application contains a single `Main` class and has no external dependencies or
dedicated build tool.

## Requirements

- JDK 21

## Build and run

```bash
mkdir -p build/classes
javac -d build/classes src/Main.java
java -cp build/classes Main
```

The expected output is:

```text
Hello world!
```

GitHub Actions runs the same compile and smoke-test commands on every push and pull request.
