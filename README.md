# 15 команд Git, которые нужны в повседневной жизни

1. git push - команда, которая отправляет все коммиты в удаленный репозиторий
10. git pull - команда, которая забирает все коммиты из удаленного репозитория
11. git status - показывает изменения, которые есть в репозитории
12. git rm file - удаляет file
13. git merge hotfix -m "Горячая правка" - влить в ветку, в которой находимся, данные из ветки hotfix (указано сообщение коммита слияния)
14. git clone https://github.com/repo.git . - клонирует удаленный репозиторий в текущую директорию
15. git clean -df - удаляет неотслеживаемые файлы и директории
16. git revert HEAD --no-edit - создает новый коммит, отменяющий изменения последнего коммита без запуска редактора сообщения
17. git mv text.txt test_new.txt - переименовывает файл «text.txt» в «test_new.txt» и индексирует это изменение
15. git mv readme_new.md folder/ - перемещает файл readme_new.md в директорию folder/ (должна существовать) и индексирует это изменение
15. git log master..branch_99 - показать коммиты из ветки branch_99, которые не влиты в master
16. git stash - временно сохранить незакоммиченные изменения и убрать их из рабочей директории
15. git stash pop - вернуть сохраненные командой git stash изменения в рабочую директорию
16. git fetch origin - скачать все ветки с удаленного репозитория (с сокр. именем origin), но не сливать со своими ветками
15. git commit --amend -m "Название" - «перекоммитить» изменения последнего коммита, заменить его новым коммитом с другим сообщением (сдвинуть текущую ветку на один коммит назад, сохранив рабочую директорию и индекс «как есть», создать новый коммит с данными из «отменяемого» коммита, но новым сообщением)
