git branch <имя ветка>   - создание ветки
git checkout -b <имя ветки>  - создание и переход на создпнную ветку
git checkout <имя ветки> - переход на ветку
git add <имя файла>(git add . - все файлы)   -Добавить содержимое файла в КЭШ(индекс)
git commit -m"Коментарий"  - сделать коммит(Записать изменения в хранилище)
git push - Записать изменения в хранилище на GITHub
git push --set-upstream origin feature/implementing-auth - Записать изменения в хранилище на GITHub
git merge <имя фичи> - мерджим нашу фичу 
git branch -d <имя ветки>
git checkout -b release/1.0  - создание релиз ветки
git merge release/1.0   - мерджим наш релиз