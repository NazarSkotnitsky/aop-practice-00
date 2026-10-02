# Практичне заняття № 0. Підготовка робочого середовища розробника

- **Прізвище, ім'я:** Скотніцький Назар
- **Група:** 212

## 1. Посилання на профілі
- GitHub: [https://github.com/NazarSkotnitsky](https://github.com/NazarSkotnitsky)
- LeetCode: [https://leetcode.com/u/NazarSkotnitsky/](https://leetcode.com/u/NazarSkotnitsky/)
- HackerRank: [https://www.hackerrank.com/profile/nazar2008skotni1](https://www.hackerrank.com/profile/nazar2008skotni1)

## 2. Перевірка версій середовища та Git
- PowerShell:
![Перевірка версії PowerShell](image_2fbdba.png)
- Git:
![Перевірка Git](image_301b94.png)
- Java JDK:
![Перевірка Java](image_303214.png) 


## 3. Перевірка SSH-з'єднання з GitHub
![SSH Check](image_302e79.png)

## 4. IntelliJ IDEA (Hello, World!)
![IntelliJ IDEA Run](image_3a22e4.png)

## 5. HackerRank (Welcome to Java!)
- Задача успішно розв'язана на платформі HackerRank.

## 6. Інструменти ШІ
- **ChatGPT:**
![ChatGPT запит](image_3a145d.png)
- **Claude Code:** *(Не використовувався)*

## 7. Проблеми та способи їх усунення
- **Проблема 1:** Під час першого підключення до GitHub через SSH виникла помилка `Host key verification failed`.
  - **Усунення:** Оновлено список відомих хостів за допомогою команди `ssh-keyscan -t ed25519 github.com >> ~/.ssh/known_hosts` та підтверджено відбиток сервера.
- **Проблема 2:** У IntelliJ IDEA з'явився напис `Git is not installed`.
  - **Усунення:** У налаштуваннях середовища (`Settings -> Version Control -> Git`) вручну вказано шлях до виконуваного файлу `git.exe`.