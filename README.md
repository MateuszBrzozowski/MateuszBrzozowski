### 🟩 Expert (Daily Work)
<div align="center">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/maven/maven-original.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/hibernate/hibernate-plain-wordmark.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/spring/spring-original-wordmark.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original-wordmark.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-plain-wordmark.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/json/json-plain.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/junit/junit-plain-wordmark.svg" width="60" height="60"/>
</div>
<br><br>

## 🟦 Intermediate (Practical Knowledge)
<div align="center">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-plain-wordmark.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-plain-wordmark.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/firebase/firebase-plain-wordmark.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/flutter/flutter-original.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/dart/dart-original.svg" width="60" height="60"/>
</div>
<br><br>

## 🟪 Beginner / Exploratory (Some Experience)
<div align="center">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/redis/redis-plain-wordmark.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-plain-wordmark.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-plain-wordmark.svg" width="60" height="60"/>
</div>

<br><br><br><br><br>
##
<div align="right">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/intellij/intellij-original.svg" width="30" height="30"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/androidstudio/androidstudio-original.svg" width="30" height="30"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" width="30" height="30"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postman/postman-plain.svg" width="30" height="30"/>
<img src="https://img.shields.io/badge/Claude_Code-CLI-black?style=flat&logo=anthropic&logoColor=white" height="30"/>
</div>

<br><br>

##
<div align="center">
<a href="https://intesto.pl">
<img src="https://intesto.pl/opengraph-image.png" width="480" alt="Intesto — niezależna inspekcja samochodu przed zakupem"/>
</a>
<br><br>
<b><a href="https://intesto.pl">intesto.pl</a></b>
</div>

<br>

A two-sided marketplace connecting car buyers with independent inspection experts.
Buyer posts a brief → specialists bid → buyer pays into escrow → gets a PDF report.
Built solo, backend to frontend. Pre-launch.

- **Escrow payments** — Stripe, funds held until the report is delivered, delayed payouts via schedulers
- **Order state machine** — server-enforced transitions, optimistic locking
- **PDF report engine** — checklist defined as data, not code
- **Real-time chat** — WebSocket / STOMP, scoped per order
- **Push** — Firebase Cloud Messaging
- **Admin panel** — dispute resolution, role + permission model
- **Auth** — JWT access + refresh, rate limiting

`Java 21` `Spring Boot 4` `PostgreSQL` `Redis` `Stripe` `Next.js 16` `React 19` `TypeScript`
