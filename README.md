# TestGit
1. git clone + url
TO START
1. git status
2. git add [files] - подготавливает наши файлы к записи = git add .
3.   "comment" - добавления комментарий
4. git log - отображает комментарий // git log --oneline
5. git push [rep_link] [branch_name] - отправить измения на Git [our_link]
    git push origin main


1. git remote -v - узнать ссылку на репозиторий
2. git branch - узнать ветку
3. git reset - помагает удалить некорые файлы из промежучтоной области
4. git diff - позволяем рассмотреть те строки, которые мы изменяли или добавляли // git diff [namefile]
5. git reset --hard - удалит все изменения и вернется все, что было да этого

Если мы не хотим, чтобы папка или файлы были на общем ресурсе добавляем ее название в .gitignore

Основы ветвления и слияния
1. git branch
2. git branch [develop]
3. git checkout [название ветки] - - переключение с ветки на ветку
main
develop
feature/main-page
feature/about-company

4. - pull request - перенос данных с одной ветки на другую
   - git pull origin main 
5.  перенос содной ветки на другую
- git checkout [название главноеб куда будет идти перенос ветки]
- git merge [название ветки, откуда мы хотим перенести код]
-  git push origin main


6. git branch -D [name] - удаление ветки
