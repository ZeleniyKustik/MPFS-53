# Mindustry Potato File System


Mindustry Potato File System - MPFS. A project for the game Mindustry, which develops its own file system for logic

Mindustry Potato File System - MPFS. Проект для игры Mindustry, который разрабатывает свою файловую систему для логики

| Possible command list |
| --- |

| System |
| --- |
| INI - Сброс всего до начального состояния и начальная настройка MPFS |
| RELOAD - Удалить всю информацию из процессора и загрузить её заново |
| INFO - Дать информацию об текущем состоянии MPFS |
| FASTFORM - Удалить оглавление в корне, тем самым убирая доступ к файлам |
| SLOWFORM - Полность заполнить память нулями, за исключением настроек MPFS |

| File logic |
| --- |
| CAP - Захват объекта для дальнейших действий с ним |
| CAPUP - Захват папки являющийся родителем объекта |
| CAPROOT - Захват корня |
| COPY – Копирование объекта в другое место |
| INSCOPY - Копирование объекта объекта в тот-же каталог где находится оригинал и придание ему нового имени |
| DEL – Удаление объекта |
| MDIR – Создать папку |
| MFILE - Созать файл |
| RENAME – Переименовать объект |
| DIR – Отобразить файлы и папки в выбраном каталоге |
| OBJINFO - Отобразить основную информацию об объекте |
	
| Edit file |
| --- |
| READ - Прочитать столько бит в файле начиная с выбраной ячейки и бита |
| WRITE - Записать число в стоько бит в файле начиная с выбраной ячейки и бита |
| TCELL - Выводит настоящий адрес ячейки с которой начинается файл |
