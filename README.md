## Kotlin AST parser for extracting typing information

> Usage: ./gradlew run --args="<path_to_kotlin_file>"

The program will traverse the given file and output a JSON containing data about
each class' methods (return type and parameter type) aswell as data class constructor
typing information