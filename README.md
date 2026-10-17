# Algorithms (Tel-Ran, 2022)

[English](README.md) | [Русский](README.ru.md)

Java exercises in searching, sorting and recursion from the Tel-Ran course.

## Topics

| Topic | Source |
| --- | --- |
| Linear search, bubble sort and insertion sort | [lesson1](src/main/java/lesson1) |
| Binary search, recursion and two pointers | [lesson2](src/main/java/lesson2) |
| Binary search exercises and arrays | [lesson3](src/main/java/lesson3) |
| Merge sort and merging arrays | [lesson4](src/main/java/lesson4) |
| Quicksort | [lesson5](src/main/java/lesson5) |

Homework is stored alongside lesson examples. The project uses the standard Java library and has a [Maven configuration](pom.xml) for Java 18.

## Run an example

Use JDK 18 or newer, with `java` and `javac` available in your terminal.

```bash
git clone https://github.com/ivan-zamula/algorithms-2022-tel-ran.git
cd algorithms-2022-tel-ran
```

From the project root, compile and run the merge sort example:

```bash
mkdir -p out
javac -encoding UTF-8 -d out src/main/java/lesson4/MergeSort.java
java -cp out lesson4.MergeSort
```

Output:

```text
[23, 4, 334, 3, 2, 23, 8]
[2, 3, 4, 8, 23, 23, 334]
```

To browse the project in IntelliJ IDEA, open `pom.xml` as a Maven project and select your JDK. Each class with a `main` method is a separate console example.
