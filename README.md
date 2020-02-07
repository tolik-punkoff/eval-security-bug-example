# eval-security-bug-example
The example shows the danger of using the eval in bash. There is an example of dangerous and safe code.

## English

Files:

maketestdir - script for create test directories

testfile.txt - Test file. Danger fixed if you use single quotes in you code.

testfile2.txt - Test file. Danger fixed if you delete in code single quotes from input string and use single quotes in you code.

wrongcode - Script with no fix (using double quotes in code)

wrongcode - Script with first fix (using single quotes in code)

goodcode - Final fix. Code remove single quotes from input string and use single quotes in code

Using scripts:

script_name test_file

e.q.

wrongcode testfile2.txt



## Русский язык

Пример показывает опасность использования eval в bash. Имеется пример опасного и безопасного кода.

Файлы:

maketestdir - скрипт для создания тестовых каталогов.

testfile.txt - Тестовый файл. Ошибку безопасности можно обойти, заменив двойные кавычки одинарными в коде.

testfile2.txt - Замена двойных кавычек одинарными не поможет. Необходимо дополнительно удалять одинарные кавычки во входной строке.

wrongcode - файл без исправлений кода (в коде используются двойные кавычки)

wrongcode2 - только первое исправление (в коде используются одинарные кавычки)

goodcode - окончательно исправленный код (удаляются одинарные кавычки из входных строк).

Вызов скриптов: <скрипт> <тестовый файл>

Например:

wrongcode testfile2.txt