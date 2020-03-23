# serserch.github.io

## lesson 2
``` git
// начальная настройка гита
git --version
git config --global user.name "[name]"
git config --global user.email "[email]"
git config --global color.io auto
git config --global core.editor "[program]"
git config --list
```

## lesson 3
``` bush
// список  файлов вместе с скрытыми
ls -a
// создать директорию
mkdir "[dir_name]"
// переход в директорию
cd /D "[dir_path]"
// создать файл
touch "[file_name]"
// копировать файл
cp "[file_name]" "[file_name_copy]"
// переименовать файл
mv "[file_name]" "[new_file_name]"
// вывод текста в файл
echo "[text]" > "[file_name]"
// чтение файла
cat "[file_name]"
// полное удаление файла
rm "[file_name]"
// полное удаление директории
rm -R "[dir_name]"
```

## lesson 4
``` git
// первая инициализация репозитория
git init
git status
git remote add origin [repo_link]
git remote -v
```

## lesson 5
``` git
// добавление всех файлов в индекс
git add .
// добавление файла в индекс
git add "[file_name]"
// удаление файла из индекса
git rm --cached "[file_name]"
// создание коммита
git commit -m "[text]"
// добавление в индекс и коммит
git commit -am "[text]"
// отменяет все изменения в файле
git restore "[file_name]"
// .gitkeep добавление пустого репозитория
// .gitignore правила игнорирования
```

## lesson 6
``` git
// история коммитов
git log --oneline
// история операций
git reflog
// возврат к определенному коммиту
git reset [hash]
// отменяет действия
git revert [hash]
```
