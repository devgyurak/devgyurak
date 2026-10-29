<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F52FF,100:3670A0&height=200&section=header&text=Hello%20there%20👋&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Software%20Engineer%20·%20AX%20Engineer%20·%20이규락&descAlignY=58&descSize=20&animation=fadeIn" width="100%" alt="header"/>

<a href="https://github.com/devgyurak">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=1000&color=7F52FF&center=true&vCenter=true&width=600&lines=%24+whoami;Software+Engineer;AX+Engineer+%C2%B7+AI+Lover;Building+with+%F0%9F%A7%91%E2%80%8D%F0%9F%92%BB+%2B+%F0%9F%A4%96;Python+%C2%B7+Kotlin+%C2%B7+Django+%C2%B7+FastAPI+%C2%B7+Spring;Thanks+for+visiting+my+GitHub+profile!" alt="typing"/>
</a>

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-devgyurak.com-000000?style=flat-square&logo=googlechrome&logoColor=white)](https://devgyurak.com)
[![Blog](https://img.shields.io/badge/Blog-velog-20C997?style=flat-square&logo=velog&logoColor=white)](https://velog.io/@devgyurak/posts)
[![CV Download](https://img.shields.io/badge/CV-download-E5383B?style=flat-square&logo=readdotcv&logoColor=white)](https://cdn.devgyurak.com/resume_leegyurak.pdf)
<br/>
![Visitors](https://komarev.com/ghpvc/?username=devgyurak&base=1714&style=flat-square&color=7F52FF&label=Visitors)
[![Open Source](https://img.shields.io/badge/Open%20Source-Love%20%E2%9D%A4-3DA639?style=flat-square&logo=opensourceinitiative&logoColor=white)](https://github.com/devgyurak?tab=repositories)

</div>

<br/>

## 🧑‍💻 About Me

```kotlin
interface AILover {
    val pairProgrammer: String get() = "🤖 AI"
    fun build(project: String) = "💡 $project → 🧑‍💻 + 🤖 → 🚀"
}

data class Engineer(
    val name: String,
    val roles: List<String>,
    val languageSpoken: List<String>,
) : AILover {
    fun introduce() = println("Hi, I'm $name — ${roles.joinToString(" · ")}. Thanks for visiting 🙌")
}

fun main() {
    val me = Engineer(
        name = "이규락",
        roles = listOf("Software Engineer", "AX Engineer", "AI Lover"),
        languageSpoken = listOf("ko_KR", "en_US"),
    )
    me.introduce()
    listOf("pykorail", "mysql-gcm", "syncintosh").forEach { println(me.build(it)) }
}
```

- 🛠️ **Software Engineer** — building SDKs, database extensions, and developer tools
- 🔄 **AX Engineer** — bringing AI into how software gets designed, written, reviewed, and shipped
- 🤖 **AI Lover** — every project I'm currently working on is built together with AI

## 🔧 Tech Stack

| Category | Stack |
| :-- | :-- |
| **Languages** | ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Kotlin](https://img.shields.io/badge/kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white) |
| **Frameworks** | ![Django](https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white) |
| **OS & Deploy** | ![Docker](https://img.shields.io/badge/docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-2671E5?style=for-the-badge&logo=githubactions&logoColor=white) |
| **Databases** | ![MySQL](https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/redis-DD0031?style=for-the-badge&logo=redis&logoColor=white) |

## 🚀 Featured Projects

| Project | Description | Stack |
| :-- | :-- | :-- |
| 🚄 [**pykorail**](https://github.com/devgyurak/pykorail) [![stars](https://img.shields.io/github/stars/devgyurak/pykorail?style=flat-square&color=7F52FF&label=★)](https://github.com/devgyurak/pykorail/stargazers) | Unofficial Python SDK for the Korail Talk API — search, book, pay, refund, waitlist, and watch for cancelled KTX tickets in a few lines of code | ![Python](https://img.shields.io/badge/-Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54) |
| 🔐 [**mysql-gcm**](https://github.com/devgyurak/mysql-gcm) | AES-GCM for MySQL 8.0+ as a server component — keeps server-side `LIKE` on the encrypted plaintext, with a deterministic variant for joins and `UNIQUE` | ![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| 🍎 [**syncintosh**](https://github.com/devgyurak/syncintosh) | sync + Macintosh — CLI that keeps developer-environment settings in step across Macs through an end-to-end encrypted git repository, with format-aware 3-way merge — 🚧 early stage | ![Python](https://img.shields.io/badge/-Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54) |
| 🎤 [**hipchapedia**](https://github.com/devgyurak/hipchapedia) | Hipchapedia — AI-powered hip-hop lyrics analysis | ![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) |

<p align="right"><a href="https://github.com/devgyurak?tab=repositories">👉 more repositories</a></p>

## 📔 Latest Blog Posts

<!-- BLOG-POST-LIST:START -->
- [AI가 역공학 비용을 0으로 만들 때, 메인테이너가 그어야 할 선](https://velog.io/@devgyurak/AI%EA%B0%80-%EC%97%AD%EA%B3%B5%ED%95%99-%EB%B9%84%EC%9A%A9%EC%9D%84-0%EC%9C%BC%EB%A1%9C-%EB%A7%8C%EB%93%A4-%EB%95%8C-%EB%A9%94%EC%9D%B8%ED%85%8C%EC%9D%B4%EB%84%88%EA%B0%80-%EA%B7%B8%EC%96%B4%EC%95%BC-%ED%95%A0-%EC%84%A0)
- [내 서버에 적절한 worker 할당하기 &lpar;Feat. Nginx, Gunicorn, Uvicorn&rpar;](https://velog.io/@devgyurak/%EB%82%B4-%EC%84%9C%EB%B2%84%EC%97%90-%EC%A0%81%EC%A0%88%ED%95%9C-worker-%ED%95%A0%EB%8B%B9%ED%95%98%EA%B8%B0-Feat.-Nginx-Gunicorn-Uvicorn)
- [어쨌든 완성했으니까 좋았쓰! &lpar;좋았쓰! 변환기 프로젝트 회고&rpar;](https://velog.io/@devgyurak/%EC%96%B4%EC%A8%8C%EB%93%A0-%EC%99%84%EC%84%B1%ED%96%88%EC%9C%BC%EB%8B%88%EA%B9%8C-%EC%A2%8B%EC%95%98%EC%93%B0-%EC%A2%8B%EC%95%98%EC%93%B0-%EB%B3%80%ED%99%98%EA%B8%B0-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%ED%9A%8C%EA%B3%A0)
- [다신 만나지 말자, 2023년](https://velog.io/@devgyurak/%EB%8B%A4%EC%8B%A0-%EB%A7%8C%EB%82%98%EC%A7%80-%EB%A7%90%EC%9E%90-2023%EB%85%84)
- [뭔가 엄청났던 2022년을 끝내면서](https://velog.io/@devgyurak/%EB%AD%94%EA%B0%80-%EC%97%84%EC%B2%AD%EB%82%AC%EB%8D%98-2022%EB%85%84%EC%9D%84-%EB%81%9D%EB%82%B4%EB%A9%B4%EC%84%9C)
<!-- BLOG-POST-LIST:END -->

<p align="right"><a href="https://velog.io/@devgyurak/posts">👉 more posts on velog</a></p>

## 📊 GitHub Stats

<div align="center">

<a href="https://github.com/devgyurak">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=devgyurak&show_icons=true&include_all_commits=true&hide_border=true&theme=transparent&title_color=7F52FF&icon_color=7F52FF" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=devgyurak&layout=compact&hide_border=true&theme=transparent&title_color=7F52FF" alt="Top languages"/>
</a>

<img src="https://streak-stats.demolab.com?user=devgyurak&hide_border=true&theme=transparent&ring=7F52FF&fire=7F52FF&currStreakLabel=7F52FF" alt="GitHub streak"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F52FF,100:3670A0&height=120&section=footer" width="100%" alt="footer"/>
