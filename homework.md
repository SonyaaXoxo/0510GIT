# <span style="color:yellow"> __Инструкция по Git__<div>

## <span style="color:yellow">__Git__</span> это - реалицаций распределённой системы управления версиями на локальном или удаленном репозитории.

### Основные команды git для настройки и окружения
|<span style="color:orange"><div style="width:160px"> __команда__ </div></span>      |<span style="color:orange">*описание*</span>
|                -                |                 -                                       |
|<span style="color:yellow"> __git__ <span style="color:white"> __config__<span style="color:white">  __--global user.email "[valid-email]”__</span>|<span style="color:green">*Вносим в систему Git контактную информацию укажите ваш действующей e-mail* </span>|
|<span style="color:yellow"> __git__ <span style="color:white"> __config__<span style="color:white">  __--global user.name  “[firstname lastname]”__</span>|<span style="color:green">*Вносим в систему Git контактную информацию укажите ваш имя* </span>|
|<span style="color:yellow"> __git__ <span style="color:white"> __config__<span style="color:white">  __--global --global color.ui auto”__</span>|<span style="color:green">*установливает автоматическую раскраску командной строки для Git для удобства просмотра* </span>|
|<span style="color:yellow"> __git__ <span style="color:white"> __config__<span style="color:white">  __--list__</span>|<span style="color:green">*Просмотр настроек в виде списка* </span>|
### Основные команды git для работы с репозитарием (Добавление и отслеживание)
|<span style="color:orange"><div style="width:160px"> __команда__ </div></span>      |<span style="color:orange">*описание*</span>
|                -                |                 -                                       |
|<span style="color:yellow"> __git__ <span style="color:white"> __init__</span>|<span style="color:green">*Инициализирует локальный католог, как  репозиторий*</span>|
|<span style="color:yellow"> __git__   <span style="color:white">__add__ <span style="color:white"> *<имя_файла>* |<span style="color:green">*Добавление файла в репозиторий для отслеживания* </span>|
|<span style="color:yellow"> __git__   <span style="color:white"> __status__</span>|<span style="color:green">*Выводит состояние проекта, измененные и не добавленные файлы, индексированные файлы*</span>|
|<span style="color:yellow"> __git__   <span style="color:white"> __commit__</span>|<span style="color:green">*Совершение коммита*</span>|
|<span style="color:yellow"> __git__<span style="color:white"> __log__</span>|<span style="color:green">*Выводит разнообразну информация о коммитах в целом, по отдельным файлам и различной глубины погружения в историю*</span>|
|<span style="color:yellow"> __git__ <span style="color:white"> __log__<span style="color:white"> __--oneline__</span>|<span style="color:green">*Показывает лог  commit в одну строчку, после угазания ключа <span style="color:white">__--oneline__* </span>|

### Основные команды git для работы с репозитарием (Ветвление и слияние)
|<span style="color:orange"><div style="width:160px"> __команда__ </div></span>      |<span style="color:orange">*описание*</span>
|                -                |                 -                                       |
|<span style="color:yellow"> __git__ <span style="color:white"> __branch__</span>|<span style="color:green">*Показывает список веток и текущую отмеченной* (<span style="color:yellow">\*</span>) |
|<span style="color:yellow"> __git__ <span style="color:white"> __branch__<span style="color:white">  __\<name>__</span>|<span style="color:green">*Создание новой ветки с именем <span style="color:white">name* </span>|
|<span style="color:yellow"> __git__ <span style="color:white"> __checkout__<span style="color:white">  __-b \<name>__</span>|<span style="color:green">*Создание новой ветки с именем <span style="color:white">name* <span style="color:green">*и переключением на нее*|
|<span style="color:yellow"> __git__ <span style="color:white"> __checkout__<span style="color:white">  __\<name>__</span>|<span style="color:green">*Переключение на ветку <span style="color:white">name* |
|<span style="color:yellow"> __git__ <span style="color:white"> __merge__<span style="color:white">  __\<name>__</span>|<span style="color:green">*Вливание в текущую ветку <- ветки с именем( <span style="color:white">name* <span style="color:orange">)|

**Git** — *это система контроля версий. Или другими словами — хранилище, база данных истории разработки проекта. Такая система нужна для учета всех версий файлов когда-либо созданных в проекте и содержащихся в Git (базе данных).*

В данной методичке, мы используем специальный язык- *Markdown*
или *маркдаун*, — это язык разметки для текстовых документов. Он позволяет создавать тексты без использования Word и других редакторов. Разметку можно прочитать и воспроизвести в любой системе или браузере.


## <span style="color:green"> Синтаксис языка Markdown


-#  Заголовок – выделение заголовков. Количество символов “#” задаёт уровень заголовка (поддерживается 6 уровней)















>>Заголовок
 ===
 подзаголовок

 -**Полужирное начертание** или __Полужирное начертание__
 >например:
 >>**Заголовок**
 ___
Поддерживается 6 уровней заголовков. 

>например:

>># Заголовок

>>### Заголовок

>>#### Заголовок

___

-= или - – подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки первого (“=”) и второго (“-”) уровней.

>например:
