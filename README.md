# Git Commands
<!-- утіліта конфігурації роботи гіта (імʼя, пошта) -->
- git config
<!-- создаємо репозиторій в робочої директорії  -->
- git init
<!-- відображення стану гіт репозиторія -->
- git status
<!-- добавляємо файл з робочої директорії в Staging Area -->
- git add filename
<!-- добавляємо всі файли з робочої директорії в Staging Area -->
- git add .
<!-- переміщаємо файли з Staging Area в локальний репозиторій -->
- git commit -m "message"
<!-- обʼєднання двух команд -->
- git commit -a -m "message"
<!-- видаляємо попередній коміт -->
- git reset --hard <id last commit>
<!-- видаляє коміт з облака-->
- git push --force
<!-- відновлення файла з історії -->
- git restore filename
<!-- відновлення всіх файлів з історії -->
- git restore .
<!-- log в короткому форматі -->
- git log --pretty=format:"%h - %an, %ar - %s"
<!-- перехід на комміт по його номеру -->
- git checkout 2cc2e90
<!-- перехід до останнього актуального комміта -->
- git checkout master
<!-- переключення на вказану гілку -->
- git checkout branch name
<!-- виводить список гілок -->
- git branch
<!-- виводить список гілок з коротким хеш-кодом -->
- git branch -v
<!-- створення нової гілки dev -->
- git branch dev
<!-- створення нової гілки dev та перехід на неї -->
- git checkout -b dev
<!-- злиття з гілкою -->
- git merge branch-name
<!-- відміна злиття гілок -->
- git merge --abort
<!-- добавляємо локальний репозиторій на віддалений репозиторій (облако гітхаб) -->
- git remote add origin https://github.com/shege68/lesson_6.git
<!-- перейнування гілки master в main -->
- git branch -M main
<!-- перша вигрузка файлів на віддалений репозиторій -->
- git push -u origin main
<!-- відображення підключених до локального проекта віддалених серверів -->
- git remote
<!-- відображення відповідності псевдоніма та адреси репозиторія -->
<!-- fetch - шлях, звідки забираємо файли -->
<!-- push - шлях, куда будем загружати файли -->
- git remote -v
<!-- видалення ссилки (звязки з репозиторієм) на віддалений сервер origin, звязаний з локальним репозиторієм -->
- git remote rm origin
<!-- вигрузка любої локальної гілки по її імені на гітхаб -->
- git push -u origin branch-name
<!-- вигрузка відразу всіх гілок -->
- git push -u origin --all
<!-- вигрузка активної гілки -->
- git push
<!-- клонування репозиторія з гіта в любу локальну директорію -->
- git clone https://github.com/shege68/lesson_6.git
<!-- загружаємо віддалені запушені зміни (в роботі з іншої папки або компа) в локальний репозиторій проекта -->
- git pull
 