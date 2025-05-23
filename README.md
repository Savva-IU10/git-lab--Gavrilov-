<<<<<<< HEAD
# Git Lab Project - Savva Gavrilov
=======
# git-lab--Gavrilov-
>>>>>>> 6dbc0ed765afa901252162c87ba3733b58045c52

## Задание 6: Разделение коммита
- Цель: Разделить один коммит с изменениями в двух файлах на два отдельных коммита
- Команды:
  ```bash
  git rebase -i HEAD~1  # Заменить pick на edit
  git reset HEAD~1
  git add A.txt; git commit -m "Изменения в A"
  git add B.txt; git commit -m "Изменения в B"
  git rebase --continue
  ```
- Результат: Один коммит разделён на два независимых коммита

## Задание 5: Разделение коммита
- Цель: Разделить один коммит с изменениями в двух файлах на два отдельных коммита
- Команды:
  ```bash
  git rebase -i HEAD~1  # Заменить pick на edit
  git reset HEAD~1
  git add A.txt; git commit -m "Изменения в A"
  git add B.txt; git commit -m "Изменения в B"
  git rebase --continue
  ```
- Результат: Один коммит разделён на два независимых коммита
