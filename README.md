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
<!-- удаляємо попередній коміт -->
- git reset --hard HEAD^
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
