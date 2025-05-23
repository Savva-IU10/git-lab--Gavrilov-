<<<<<<< HEAD
# Git Lab Project - Savva Gavrilov
=======
# git-lab--Gavrilov-
>>>>>>> 6dbc0ed765afa901252162c87ba3733b58045c52

## Задание 5: Разделение коммита
- Цель: Разделить коммит с изменениями в двух файлах на два отдельных коммита
- Команды:
  ```bash
  git rebase -i HEAD~1
  git reset HEAD~1
  git add A.txt; git commit -m "Изменения в A"
  git add B.txt; git commit -m "Изменения в B"
  git rebase --continue
  ```
- Результат: Один коммит разделен на два независимых
