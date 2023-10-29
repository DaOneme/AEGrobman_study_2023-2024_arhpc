# РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ

## _Факультет физико-математических и естественных наук_ 
## направление: _Компьютерные и информационные науки_









## Лабораторная работа №2

### дисциплина: *Архитектура компьютеров и операционные системы*



#### студент:     Гробман Александр Евгеньевич
#### Группа:     НКАбд-02-23

### Цель работы 

Освоение процедуры компиляции и сборки программ, написанных на ассемблере NASM.


### Задание 

1. В каталоге ~/work/arch-pc/lab04 с помощью команды cp создайте копию файла
hello.asm с именем lab4.asm
2. С помощью любого текстового редактора внесите изменения в текст программы в
файле lab4.asm так, чтобы вместо Hello world! на экран выводилась строка с вашими
фамилией и именем.
3. Оттранслируйте полученный текст программы lab4.asm в объектный файл. Выполните
компоновку объектного файла и запустите получившийся исполняемый файл.
4. Скопируйте файлы hello.asm и lab4.asm в Ваш локальный репозиторий в каталог ~/work/study/2023-2024/"Архитектура компьютера"/arch-pc/labs/lab04/.
Загрузите файлы на Github.5. 



### Выполнение лабораторной работы

1. #### Создание программы 'hello world'
Выбираем директорию и создаём файл через команду touch

![](https://github.com/DaOneme/AEGrobman_study_2023-2024_arhpc/blob/main/Labs/Lab04/Resourses/Images/Image01.png?raw=true)

открываем mousepad, заполняем программу

![](https://github.com/DaOneme/AEGrobman_study_2023-2024_arhpc/blob/main/Labs/Lab04/Resourses/Images/Image02.png?raw=true)



2. #### Работа с трансляторами и расширенным синтаксисом.

Превращаю текст программы для вывода *"hello world"* в объектный код с помощью транслятора NASM. Используем команду *nasm -f elf hello.asm*.

Проверяем правильность выполнения команды.

![](https://github.com/DaOneme/AEGrobman_study_2023-2024_arhpc/blob/main/Labs/Lab04/Resourses/Images/Image03.png?raw=true)


Обрабатываем компановщиком LD

![](https://github.com/DaOneme/AEGrobman_study_2023-2024_arhpc/blob/main/Labs/Lab04/Resourses/Images/Image04.png?raw=true)



3. #### Запуск программы

![](https://github.com/DaOneme/AEGrobman_study_2023-2024_arhpc/blob/main/Labs/Lab04/Resourses/Images/Image05.png?raw=true)


4. #### Выполнение заданий.

Копируем файл *hello_world.asm* в той же директории, переименовывая его как *"Lab04.asm"*
Меняем код так, чтобы вместо *hello world* выводилась наши имя и фамилия
Компилируем файл также как было сделано ранее.
Запускаем программу. 

![](https://github.com/DaOneme/AEGrobman_study_2023-2024_arhpc/blob/main/Labs/Lab04/Resourses/Images/Image06.png?raw=true)


4. #### Отправляем файлы на гитхаб.

Ссылка на отчёт <https://github.com/DaOneme/AEGrobman_study_2023-2024_arhpc/tree/main/Labs/Lab04>










