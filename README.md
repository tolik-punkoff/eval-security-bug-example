# eval-security-bug-example
The example shows the danger of using the eval in bash. There is an example of dangerous and safe code.

## English

Using:

1. Download all files an put in test directory

2. Make test directory use 'maketestdir' script

3. Test bug use 'wrongcode' script

4. Go 2 pt

5. Test fix, use 'goodcode'

6. Compare the results of execution and output to the console.


## Русский язык

Пример показывает опасность использования eval в bash. Имеется пример опасного и безопасного кода.

Использование:

1. Положите файлы в отдельный подкаталог.

2. Выполните скрипт maketestdir.

3. Выполните скрипт wrongcode: каталог ./testdir со всеми подкаталогами и файлами исчезнет.

4. Првторите пункт 2.

5. Выполните скрипт goodcode: каталог ./testdir со всеми подкаталогами и файлами остается.

6. Сравните код скриптов, результаты работы и вывод на экран.
