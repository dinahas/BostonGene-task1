# BostonGene-task1
Часть 1. Многопоточность

Вам нужно реализовать многопоточное приложение на языке Java 8.

Условия:
- в приложение должно быть реализовано два потока:
первый поток считывает введённые с клавиатуры числительные на английском языке
(от one до nine thousand nine hundred ninety nine) и помещает их в память,
второй поток обращается к памяти один раз в пять секунд, извлекает (удаляет его из
памяти) самое маленькое из записанных чисел и выводит его на экран;
- задачу запрещается решать с помощью имеющихся потокозащищённых коллекций из
пакета java.util.concurrent и других специальных библиотек от сторонних разработчиков.


## Сборка и запуск 

После установки проекта на устройсво необходимо с помощью командной строки перейти в директорию проекта, собрать и запустить проект (используется Java SE 7 и выше)::
- mvn compile 
- mvn exec:java -Dexec.mainClass="org.dinahas.task1"
