<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=600&size=28&duration=3000&pause=800&color=38BDF8&center=true&vCenter=true&width=620&lines=Hi%2C+I'm+Aftab+%F0%9F%91%8B;I+build+%26+ship+on+AWS;Serverless+%C2%B7+Containers+%C2%B7+CI%2FCD" alt="Aftab Mulani" />

**Cloud & DevOps Engineer** — I build serverless systems on AWS and ship them through automated pipelines.
Below are four things I built and what made each one interesting to engineer. 👇

<p>
<a href="https://aftabmulani11.github.io/Online-Portfolio/"><img src="https://img.shields.io/badge/Portfolio-0b0b0e?style=for-the-badge&logo=googlechrome&logoColor=38bdf8" alt="Portfolio"/></a>
<a href="https://linkedin.com/in/aftabmulani11"><img src="https://img.shields.io/badge/LinkedIn-0b0b0e?style=for-the-badge&logo=linkedin&logoColor=38bdf8" alt="LinkedIn"/></a>
<a href="mailto:aftabmulani010@gmail.com"><img src="https://img.shields.io/badge/Email-0b0b0e?style=for-the-badge&logo=gmail&logoColor=fbbf24" alt="Email"/></a>
</p>

</div>

---

## 🔬 Lambda Benchmark Dashboard &nbsp;·&nbsp; [`repo →`](https://github.com/AftabMulani11/lambda-benchmark-dashboard)

> **The problem I wanted to solve:** AWS Lambda pricing is a trap — more memory costs more per ms, but often runs so much faster that total cost *drops*. There's no way to know your sweet spot without measuring.

I built a **FastAPI dashboard that benchmarks Lambda across 6 memory configs (128MB → 3008MB)** and 3 workload profiles, measuring cold starts, billed duration, and cost per million requests. Results stream **live over Server-Sent Events** into 8 interactive Chart.js views — and a demo mode replays a full run in the browser with no AWS account needed.

`Python` · `FastAPI` · `AWS Lambda` · `Server-Sent Events` · `Chart.js`

## 🏨 GreenStay — Hotel Operations Platform &nbsp;·&nbsp; [`repo →`](https://github.com/AftabMulani11/greenstay)

> **The engineering challenge:** a booking triggers a confirmation email. Send it inline and a slow SES call makes the guest's booking hang. So I decoupled it.

**4 independent services** (web · API · worker · notification) with an **async SQS → Lambda → SES pipeline** — the API confirms the booking instantly and queues the email, so delivery latency never touches the user and a downed email service never blocks a booking. DynamoDB single-table design, containerized, shipped through a 4-stage Jenkins pipeline.

`AWS SQS` · `Lambda` · `SES` · `DynamoDB` · `Flask` · `React` · `Docker` · `Jenkins`

## 📈 CryptoFolio — Portfolio Platform + Full CI/CD &nbsp;·&nbsp; [`repo →`](https://github.com/AftabMulani11/cryptofolio)

> **What I'm proud of here:** the pipeline. One `git push` runs static analysis, a SonarCloud quality gate, security scan, Docker build, ECR push, and Elastic Beanstalk deploy — and a failing quality gate *stops the deploy*.

A secure crypto tracker — **13 JWT-authenticated REST APIs**, live prices over a Binance WebSocket, **8 automated test suites**, and a **6-stage Jenkins pipeline**. Security is fail-closed: the app refuses to start if its JWT secret isn't in the environment.

`Jenkins` · `SonarCloud` · `AWS ECR` · `Elastic Beanstalk` · `JWT` · `Flask` · `React`

## 🎙️ SAARUSH 2.0 — Face-Authenticated Voice Assistant &nbsp;·&nbsp; [`repo →`](https://github.com/AftabMulani11/saarush-assistant)

> **The twist:** it won't listen to a stranger. Commands only run after **OpenCV face authentication** matches you.

A hands-free desktop assistant with **12+ voice commands** — web search, email dictation, system control, media, live news — combining speech-to-text, text-to-speech, and a Gemini-powered conversational fallback. Biometric data stays fully local.

`Python` · `OpenCV` · `Speech Recognition` · `Gemini API`

---

<div align="center">

### 🧱 More work

[**Terraform + Ansible AWS Infra**](https://github.com/AftabMulani11/Terraform-Learning) — VPC-to-EC2 from scratch, keys generated in-flight &nbsp;•&nbsp; [**Dockerized Flask App**](https://github.com/AftabMulani11/DockerProject) — hashed-auth, one-command build &nbsp;•&nbsp; [**QA Automation Portfolio**](https://github.com/AftabMulani11/qa-automation-portfolio) — Selenium · Cucumber · REST Assured

</div>

---

## 🧰 Built with

<div align="center">

![AWS Lambda](https://img.shields.io/badge/Lambda-0b0b0e?style=flat-square&logo=awslambda&logoColor=FF9900)
![SQS](https://img.shields.io/badge/SQS-0b0b0e?style=flat-square&logo=amazonsqs&logoColor=FF4F8B)
![SES](https://img.shields.io/badge/SES-0b0b0e?style=flat-square&logo=amazonsimpleemailservice&logoColor=DD344C)
![DynamoDB](https://img.shields.io/badge/DynamoDB-0b0b0e?style=flat-square&logo=amazondynamodb&logoColor=4053D6)
![ECR](https://img.shields.io/badge/ECR-0b0b0e?style=flat-square&logo=amazonecs&logoColor=FF9900)
![Elastic Beanstalk](https://img.shields.io/badge/Beanstalk-0b0b0e?style=flat-square&logo=amazonwebservices&logoColor=FF9900)
&nbsp;
![Docker](https://img.shields.io/badge/Docker-0b0b0e?style=flat-square&logo=docker&logoColor=2496ED)
![Jenkins](https://img.shields.io/badge/Jenkins-0b0b0e?style=flat-square&logo=jenkins&logoColor=D24939)
![SonarCloud](https://img.shields.io/badge/SonarCloud-0b0b0e?style=flat-square&logo=sonarcloud&logoColor=F3702A)
![Terraform](https://img.shields.io/badge/Terraform-0b0b0e?style=flat-square&logo=terraform&logoColor=844FBA)
![Ansible](https://img.shields.io/badge/Ansible-0b0b0e?style=flat-square&logo=ansible&logoColor=EE0000)
&nbsp;
![Python](https://img.shields.io/badge/Python-0b0b0e?style=flat-square&logo=python&logoColor=3776AB)
![FastAPI](https://img.shields.io/badge/FastAPI-0b0b0e?style=flat-square&logo=fastapi&logoColor=009688)
![Flask](https://img.shields.io/badge/Flask-0b0b0e?style=flat-square&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-0b0b0e?style=flat-square&logo=react&logoColor=61DAFB)
![Linux](https://img.shields.io/badge/Linux-0b0b0e?style=flat-square&logo=linux&logoColor=FCC624)

</div>

## 📊 Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=AftabMulani11&show_icons=true&theme=github_dark&bg_color=0b0b0e&title_color=38bdf8&icon_color=fbbf24&text_color=c9d1d9&border_color=1c1c22" alt="GitHub stats" height="160"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=AftabMulani11&theme=dark&background=0b0b0e&ring=38bdf8&fire=fbbf24&currStreakLabel=38bdf8&sideLabels=c9d1d9&dates=8b949e&border=1c1c22" alt="GitHub streak" height="160"/>

</div>

<div align="center">

<sub>💼 Cloud Engineer @ Accenture &nbsp;·&nbsp; 🎓 B.Tech Cloud Technology & Information Security &nbsp;·&nbsp; 📜 AWS Certified</sub>

<sub>⚡ Full case studies with visuals on my <a href="https://aftabmulani11.github.io/Online-Portfolio/">portfolio</a></sub>

</div>
