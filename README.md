Сборка реакта
Убрано все лишнее
Добавлено следующие компоненты

- propTypes
- react deploy
- Material-UI

Для старта необходимо в файле package.json
вставить название проэкта в следующие поля

- name
- homepage

вместо "my app"

после завершения проэкта запускаем

git add .
git commit -m "коментарий к проэкту"

далее на самом гите создаем репозиторий с названием проэкта

- ! Важно: репозиторий должен быть пустой, без файла реад.ми без лицензий и гит.игнор.

далее

git remote add origin <url>

потом

git push -u origin master

Пример:
git remote add origin https://github.com/pashadidychenko/goit-react-hw-02-phonebook.git
git push -u origin master

далее

npm run deploy

Все остальные страницы можно пушить с помощью

git push
