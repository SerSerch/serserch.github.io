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
``` bash
// список  файлов вместе с скрытыми
ls -a
// создание директории
mkdir "[dir_name]"
// переход в директорию
cd /D "[dir_path]"
// создание файла
touch "[file_name]"
// копирование файла
cp "[file_name]" "[file_name_copy]"
// переименование файла
mv "[file_name]" "[new_file_name]"
// вывод текста в файл
echo "[text]" > "[file_name]"
// чтение файла
cat "[file_name]"
// полное удаление файла
rm "[file_name]"
// полное удаление директории
rm -R "[dir_name]"
// очистка консоли
clear
```

## lesson 4
``` git
// первая инициализация репозитория
git init
// статус репозитория
git status
// создание связи с удаленным репозиторием
git remote add [origin] [repo_link]
// список подключенных связей
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
// отмена всех изменений в файле
git restore "[file_name]"
// .gitkeep добавление пустого репозитория
// .gitignore правила игнорирования
```

## lesson 6
``` git
// история коммитов
git log --oneline --all
// история операций
git reflog
// возврат к определенному коммиту
git reset [hash]
// отмена действия
git revert [hash]
```

## lesson 7
``` git
// доступные ветки
git branch
// создание ветки
git branch [branch_name] [parent_branch_name]
// создание и переход в ветку
git checkout -b [branch_name] [origin/branc_hname]
```

## lesson 8
``` git
// создание ssh ключа
ssh-keygen
// клонирование репозитория
git clone [repo_link] [dir_name]
// загрузка изменений на удаленный репозиторий
git push -u [origin] [branch_name]
// получение изменений с удаленного репозитория
git push
// обновление синхронизации
git fetch
```

## lesson 9
``` git
// слияние веток
git merge [branch_name]
// удаление веток
git branch -d [branch_name]
// удаление веток в удаленном репозитории
git push --delete [origin] [branch_name]
// смена начала ветки
git rebase [branch_name]
// принудительная перезапись удаленной ветки
git push --force
```

## lesson 10
``` git
// добавление тега
git tag [tag_name]
// список всех тегов
git tag --list
// загрузка тегов в удаленный репозиторий
git push --tags
// удаление тега
git tag -d [tag_name]
// удаление тегов в удаленном репозитории
git push --delete [origin] [tag_name]
```

## lesson 12
``` git
// создание временного хранилища
git stash
// список временных хранилищ
git stash list
// добавление новых файлов в временное хранилище
git stash push [file_name]
// загрузка изменений из временного хранилища
git stash pop [stash_name]
// слияние веток с объединением коммитов
git merge [bransh_name] --squash
// отмена операции
git reset --hard
// объединение коммитов
git rebase -i HEAD~[number]
// перенос коммита
git cherry-pick [hash]
// перезапись коммита
git commit --amend
// отмена слияния
git merge --abort
```
