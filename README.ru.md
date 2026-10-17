# Алгоритмы (Tel-Ran, 2022)

[English](README.md) | [Русский](README.ru.md)

Учебные задачи на Java по поиску, сортировке и рекурсии из курса Tel-Ran.

## Темы

| Тема | Исходники |
| --- | --- |
| Линейный поиск, сортировка пузырьком и вставками | [lesson1](src/main/java/lesson1) |
| Бинарный поиск, рекурсия и два указателя | [lesson2](src/main/java/lesson2) |
| Задачи на бинарный поиск и массивы | [lesson3](src/main/java/lesson3) |
| Сортировка слиянием и объединение массивов | [lesson4](src/main/java/lesson4) |
| Быстрая сортировка | [lesson5](src/main/java/lesson5) |

Домашние задания находятся рядом с примерами занятий. Проект использует стандартную библиотеку Java; в [настройках Maven](pom.xml) указана Java 18.

## Запуск примера

Нужен JDK 18 или новее с доступными в терминале командами `java` и `javac`.

```bash
git clone https://github.com/ivan-zamula/algorithms-2022-tel-ran.git
cd algorithms-2022-tel-ran
```

Из корня проекта скомпилируйте и запустите пример сортировки слиянием:

```bash
mkdir -p out
javac -encoding UTF-8 -d out src/main/java/lesson4/MergeSort.java
java -cp out lesson4.MergeSort
```

Результат:

```text
[23, 4, 334, 3, 2, 23, 8]
[2, 3, 4, 8, 23, 23, 334]
```

Для работы в IntelliJ IDEA откройте `pom.xml` как Maven-проект и выберите JDK. Каждый класс с методом `main` — отдельный консольный пример.
