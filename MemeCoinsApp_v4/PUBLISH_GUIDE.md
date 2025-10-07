    # PUBLISH GUIDE

1. Создайте репозиторий `memecoinsapp` в GitHub (или используйте свой):
   - git init
   - git add .
   - git commit -m "Initial"
   - git branch -M main
   - git remote add origin https://github.com/<OWNER>/<REPO>.git
   - git push -u origin main

2. Откройте Settings -> Pages и убедитесь, что GitHub Pages включен (оно будет публиковать папку `docs/`).

3. CI автоматически собирает APK и загружает артефакт на каждое пуш-событие в main.

4. В `docs/index.html` замените `https://github.com/<OWNER>/<REPO>/actions/artifacts` на фактический URL артефактов или оставьте как ссылку на страницу артефактов репозитория.
