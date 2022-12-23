# Git Commands

- git config
- git init
- git status

- git add filename
- git add .

- git commit -m "message"
- git commit -a -m "message"

<!-- удаляємо попередній коміт -->
- git reset --hard HEAD^
<!-- відновлення файла з історії -->
- git restore filename
<!-- відновлення всіх файлів з історії -->
- git restore .
<!-- log в короткому форматі -->
- git log --pretty=format:"%h - %an, %ar - %s"


