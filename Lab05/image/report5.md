## РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ
##### Факультет физико-математических и естественных наук
##### Кафедра прикладной информатики и теории вероятностей

### ОТЧЕТ 
#### ПО ЛАБОРАТОРНОЙ РАБОТЕ № 5
*дисциплина:	Операционные системы*		 

Студент:Саинт Амур Измаэль                                   
Группа: НРИбд-02-20                                       
**МОСКВА**
2021 г.
###### Цель работы: 
>приобретение практических навыков взаимодействия пользователя с системой посредством командной строки.
###### Ход работы:
1. Определяю полное имя нашего домашнего каталога.
 ![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture1.png)
2.1 Перехожу в каталог /tmp.
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture2.png)
2.2. Вывожу на экран содержимое каталога /tmp. Для этого используем ко-
манду ls с различными опциями. Поясняю разницу в выводимой на экран
информации.
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture3.png)
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture4.PNG)
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture5.png)
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/ls%20alf.PNG)
  
2.3. Определяю, есть ли в каталоге /var/spool подкаталог с именем cron
 ![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture6.png)
3.1. В домашнем каталоге создаю новый каталог с именем newdir.
 ![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture9.png)
 ![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture7.png)
 ![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture8.PNG)
3.2. В каталоге ~/newdir создаю новый каталог с именем morefun
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture10.png)
3.3. В домашнем каталоге создаю одной командой три новых каталога с име-
нами letters, memos, misk. Затем удаляю эти каталоги одной командой.
![](https://github.com/Ismaelesn/Operating-System/blob/main/Lab05/image/picture11.png)
3.4. Пробую удалить ранее созданный каталог ~/newdir командой rm. Каталог не был удален
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture12.png)
3.5. Удаляю каталог ~/newdir/morefun из домашнего каталога. Проверяю,
был ли каталог удалён.
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture13.png) 
4. С помощью команды man определяю, какую опцию команды ls нужно исполь-
зовать для просмотра содержимое не только указанного каталога, но и подката-
логов, входящих в него.
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture14.png)
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/lsR.PNG)
5. С помощью команды man определяю набор опций команды ls, позволяющий от-
сортировать по времени последнего изменения выводимый список содержимого
каталога с развёрнутым описанием файлов.
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture15.png)
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/lst.png)
 
6. Использую команду man для просмотра описания следующих команд: cd, pwd,
mkdir, rmdir, rm. Поясняю основные опции этих команд.
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture16.png)
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture18.png)
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture19.png)
 ![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture19.png)
7. Используя информацию, полученную при помощи команды history, выполняю
модификацию и исполнение нескольких команд из буфера команд
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture21.PNG)
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture22.PNG)
![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture23.PNG)
 ![](https://raw.githubusercontent.com/Ismaelesn/Operating-System/main/Lab05/image/picture24.PNG)
**Вывод:** В ходе работы я приобрела практические навыки взаимодействия пользователя с системой посредством командной строки.
**Ответы на контрольные вопросы:**
1. Интерфейс командной строки - управление программами с помощью команд. Команды состоят из букв, цифр, символов, набираются построчно, выполняются после нажатия клавиши Enter. Основной инструмент здесь клавиатура. Данный интерфейс встроен в ядро системы, он будет доступен, даже если графический интерфейс не запустится. Добраться до командной строки можно двумя способами: через консоль или терминал.
2. При помощи команды realpath можно определить абсолютный путь текущего каталога. Например, если вбить realpath var на экран выведется /home/<username>/var.
3. При помощи команды ls -F можно определить только тип файлов и их имена в текущем каталоге.
4. Файл (или директория) считается скрытым, если его название начинается с символа точка «.». Например, «.myfile». Обычно такие файлы используются приложениями для хранения настроек, конфигураций и другой информации, которую нужно скрыть от пользователя. Зачастую пользователю требуется отредактировать соответствующий конфигурационный скрытый файл, чтобы настроить какую-нибудь программу, и пользователи сталкиваются с тем, что не знают, как их вообще просмотреть. По умолчанию файловые менеджеры обычно не отображают такие файлы.
Для просмотра списка файлов в командной строке используется команда ls. Чтобы по команде ls также выводились скрытые файлы, существует опция -a.
5. При помощи команд rm и rmdir можно удалить файл и каталог. Это нельзя сделать одной и той же командой. rmdir используется, чтобы удалить файлы, которые должны быть пустые. rm используется, чтобы удалить непустые файлы или целые деревья каталогов.
6. Определить какие команды выполнил пользователь в сеансе работы можно с помощь команды history.
7. Исправить и запустить на выполнение команду, которую пользователь уже использовал в сеансе работы, можно с помощью команды: !<номер_команды>:s/<что_меняем>/<на_что_меняем> Например,
history
.
.
3 ls -a
.
.
!3:s/a/F
ls -F
8. В одной строке можно записать несколько команд. Если требуется выполнить последовательно несколько команд, записанный в одной строке, то для этого используется символ точка с запятой. Пример: cd; ls.
9.Экранирование — это способ заключения в кавычки одиночного символа. Экранирующий символ (\) сообщает интерпретатору, что следующий за ним символ должен восприниматься как обычный символ. Пример:
echo "Привет"                    # Привет
echo "Он сказал: \"Привет\"."    # Он сказал: "Привет".
10. Если используется опция l в команде ls, то на экран выводится подробный список, в котором будет отображаться владелец, группа, дата создания, размер и другая информация о файлах и каталогах.
11. Относительный путь – это путь к файлу относительно текущей папки. При использовании команды pwd на экран выведется относительный путь текущей директории, а при использовании команды realpath на экран выведется абсолютный путь текущей директории.
12. Получить информацию об интересующей вас команде можно с помощью команды man. Например, команда man ls выведет все опции команды ls.
13. Сочетание клавиш Ctrl+C прерывает текущий процесс, запущенный в терминале.
