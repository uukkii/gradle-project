# Домашнее задание к занятию 1.4: Сборка проектов. Maven и Gradle

## Задача 2: Многомодульный проект на Gradle

**v. 1.0**

Задача реализована.

После запуска в консоли отображается следующее:
```
10:50:53 AM: Executing task 'build'...

> Task :compileJava NO-SOURCE
> Task :processResources NO-SOURCE
> Task :classes UP-TO-DATE
> Task :jar
> Task :assemble
> Task :compileTestJava NO-SOURCE
> Task :processTestResources NO-SOURCE
> Task :testClasses UP-TO-DATE
> Task :test NO-SOURCE
> Task :check UP-TO-DATE
> Task :build
> Task :db:compileJava
> Task :db:processResources NO-SOURCE
> Task :db:classes
> Task :db:jar
> Task :service:compileJava
> Task :service:processResources NO-SOURCE
> Task :service:classes
> Task :service:jar
> Task :api:compileJava
> Task :api:processResources NO-SOURCE
> Task :api:classes
> Task :api:jar
> Task :api:assemble
> Task :api:compileTestJava NO-SOURCE
> Task :api:processTestResources NO-SOURCE
> Task :api:testClasses UP-TO-DATE
> Task :api:test NO-SOURCE
> Task :api:check UP-TO-DATE
> Task :api:build
> Task :db:assemble
> Task :db:compileTestJava NO-SOURCE
> Task :db:processTestResources NO-SOURCE
> Task :db:testClasses UP-TO-DATE
> Task :db:test NO-SOURCE
> Task :db:check UP-TO-DATE
> Task :db:build
> Task :service:assemble
> Task :service:compileTestJava NO-SOURCE
> Task :service:processTestResources NO-SOURCE
> Task :service:testClasses UP-TO-DATE
> Task :service:test NO-SOURCE
> Task :service:check UP-TO-DATE
> Task :service:build

BUILD SUCCESSFUL in 623ms
7 actionable tasks: 7 executed
10:50:53 AM: Task execution finished 'build'.
```