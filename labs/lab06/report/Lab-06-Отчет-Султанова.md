﻿**РОССИИСКИИ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ**

**Факультет физико-математических и естественных наук Кафедра прикладной информатики и теории вероятностей** 

**ОТЧЕТ** 

**ПО ЛАБОРАТОРНОИ РАБОТЕ №6** 

*дисциплина: Операционные системы*

`  `**Студент:** Султанова Лейла   **Группа:** НБИбд-03-22 

Москва 2023 г. 

**Последовательность выполнения работы**  

1. Осуществим вход в систему, используя соответствующее имя пользователя. 

![](Aspose.Words.0dc463d9-7b3f-4255-8525-78b08e3e1e1b.001.jpeg)

2. Запишем в файл названия файлов, содержащихся в каталоге /etc. Допишем в этот же файл названия файлов, содержащихся в вашем домашнем каталоге 

![](Aspose.Words.0dc463d9-7b3f-4255-8525-78b08e3e1e1b.002.png)

3. Выводим имена всех файлов из file.txt, имеющих расширение .conf, после чего запишем их в новый текстовой файл conf.txt. 

![](Aspose.Words.0dc463d9-7b3f-4255-8525-78b08e3e1e1b.003.png)

![](Aspose.Words.0dc463d9-7b3f-4255-8525-78b08e3e1e1b.004.jpeg)

4. Определим, какие файлы в вашем домашнем каталоге имеют имена, начинавшиеся с символа c? Предложим несколько вариантов, как это сделать.  

![](Aspose.Words.0dc463d9-7b3f-4255-8525-78b08e3e1e1b.005.png)

5. Выводим  на экран (по странично) имена файлов из каталога /etc, начинающиеся с символа h.  

![](Aspose.Words.0dc463d9-7b3f-4255-8525-78b08e3e1e1b.006.png)

6. Запускаем в фоновом режиме процесс, который будет записывать в файл ~/logfile файлы, имена которых начинаются с log.  И удаляем файл ~/logfile. 

![](Aspose.Words.0dc463d9-7b3f-4255-8525-78b08e3e1e1b.007.png)

7. Запускаем из консоли в фоновом режиме редактор gedit.  

![](Aspose.Words.0dc463d9-7b3f-4255-8525-78b08e3e1e1b.008.png)

8. Определим идентификатор процесса gedit, используя команду ps, конвейер и фильтр grep.  

![](Aspose.Words.0dc463d9-7b3f-4255-8525-78b08e3e1e1b.009.png)

9. Прочтем справку (man) команды kill, после чего используем её для завершения процесса gedit.  

![](Aspose.Words.0dc463d9-7b3f-4255-8525-78b08e3e1e1b.010.jpeg)

10. Выполним команды df и du, предварительно получив более подробную информацию об этих командах, с помощью команды man.  

![](Aspose.Words.0dc463d9-7b3f-4255-8525-78b08e3e1e1b.011.jpeg)

11. Воспользовавшись справкой команды find, выводим имена всех директорий, имеющихся в вашем домашнем каталоге. 

![](Aspose.Words.0dc463d9-7b3f-4255-8525-78b08e3e1e1b.012.jpeg)

Контрольные вопросы ![](Aspose.Words.0dc463d9-7b3f-4255-8525-78b08e3e1e1b.013.png)

1. Какие потоки ввода вывода вы знаете? 
1. Объясните разницу между операцией > и >>. 
1. Чтотакое конвейер? 
1. Чтотакое процесс? Чем это понятие отличается от программы? 
1. Чтот акое PID и GID? 
1. Чтотакое задачи и какая команда позволяет ими управлять? 
1. Найдите информацию об утилитах top и htop.Каковы их функции? 
1. Назовите и дайте характеристику команде поиска файлов.Приведите примеры ис- пользования этой команды. 
1. Можно ли по контексту (содержанию) найти файл? Если да,то как? 
1. Как определить объем свободной памяти на жёстком диске? 
1. Как определить объем вашего домашнего каталога? 
1. Как удалить зависший процесс? 

Отвeты на вопросы 

1\.  В системе по умолчанию открыто три специальных потока: – stdin — стандартный поток ввода (по умолчанию: клавиатура), файловый дескриптор 0; – stdout — стандартный поток вывода (по умолчанию: консоль), файловый дескриптор 1; – stderr — стандартный поток вывод сообщений об ошибках (по умолчанию: консоль), файловый дескриптор 2. 

–  перенаправление stdout (вывода) в файл. Если файл отсутствовал, то он создаётся, иначе - перезаписывается. 

- перенаправление stdout (вывода) в файл. Если файл отсутствовал, то он создаётся, иначе - добавляется. 
3. Конвейер (pipe) служит для объединения простых команд или утилит в цепочки, в которых результат работы предыдущей команды передаётся последующей. 
3. Процесс это - совокупность программного кода и данных, загруженных в память ЭВМ. Любой команде, выполняемой в системе, присваивается идентификатор процесса (process ID). Получить информацию о 

процессе и управлять им, пользуясь идентификатором процесса, можно из любого окна командного интерпретатора. Процессом называют выполняющуюся программу и все её элементы: адресное пространство, глобальные переменные, регистры, стек, открытые файлы и так далее. 

5. PID — уникальный номер (идентификатор) процесса в многозадачной ОС. GID – идентификатор группы. 
5. Любую выполняющуюся в консоли команду или внешнюю программу можно запустить в фоновом режиме. Запущенные фоном программы называются задачами (jobs). Ими можно управлять с помощью команды jobs, которая выводит список запущенных в данный момент задач. Для завершения задачи необходимо выполнить команду kill %номер задачи. 
5. Команда top в Linux системах позволяет вывести в виде таблицы перечень запущенных процессов и оценить, какой объем ресурсов они потребляют, т.е., какую нагрузку создают на сервер и дисковую подсистему. Команда htop — продвинутый монитор процессов, показывает динамический список системных процессов, список обычно выравнивается по использованию ЦПУ. В отличие от top, htop показывает все процессы в системе. Также показывает время непрерывной работы, использование процессоров и памяти. htop часто применяется в тех случаях, когда информации даваемой утилитой top недостаточно, например при поиске утечек памяти в процессах. 
5. Команда find используется для поиска и отображения имён файлов, соответствующих заданной строке символов. Формат команды: find путь [-опции] Путь определяет каталог, начиная с которого по всем подкаталогам будет вестись поиск. Примеры: 
- вывести на экран имена файлов из вашего домашнего каталога и его подкаталогов, начинающихся на f: find ~ -name “f\*” -print 
- вывести на экран имена файлов в каталоге /etc, начинающихся с символа p: find /etc -name “p\*” -print 
- найти в вашем домашнем каталоге файлы, имена которых заканчиваются символом и удалить их: find ~ -name “\*~” -exec rm “{}” ; 
9. Найти файл по контексту (содержанию) позволяет команда grep. Формат команды: grep строка имя\_файла Примеры: 
- показать строки во всех файлах в вашем домашнем каталоге с именами, начинающимися на f, в которых есть слово begin: grep begin f\* 
- найти в текущем каталоге все файлы, в имени которых есть буквосочетание «лаб»: ls -l | grep лаб 
10. Определить объем свободной памяти на жёстком диске позволяет команда df. 
11. Определить объем домашнего каталога позволяет команда df /home/ 
11. Удалить зависший процесс можно командой kill %номер задачи. 
