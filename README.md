# Elevator Simulator

Учебный проект (тема 15). Java 17+, сборка Maven.
Промежуточная версия для практики 3: `pom.xml`, структура Maven, исполняемый JAR.

## Структура

```
pom.xml
README.md
src/main/java/ru/mirea/elevatorsim/Main.java
src/main/resources/
src/test/java/
```

## Сборка и запуск

```bash
mvn clean package
java -jar target/elevator-simulator-1.0.0-SNAPSHOT.jar
```

Ожидаемый вывод: `Привет мир!`

## Сторонние библиотеки

Внешних runtime-зависимостей нет.
Плагины: maven-compiler-plugin, maven-jar-plugin, maven-shade-plugin.
