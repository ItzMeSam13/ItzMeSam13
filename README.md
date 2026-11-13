<h1 align="center">Hi, I'm Sampreet 👋</h1>

<p align="center">
  Computer Engineering student • Backend developer • CTF player<br/>
  B.E. Computer Engineering, Goa Engineering College (Class of 2028)
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sampreet-kalkundrikar-7a732a1b1/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://leetcode.com/u/lqmX9sYru2/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  <a href="https://ctftime.org/team/426943"><img src="https://img.shields.io/badge/CTFtime-E4002B?style=for-the-badge&logo=hackthebox&logoColor=white" alt="CTFtime"/></a>
</p>

---

## 🧑‍💻 About me

- 🎓 3rd-year B.E. Computer Engineering student at **Goa Engineering College**
- ⚙️ I like understanding how backend infrastructure works underneath. I built a **JDBC connection pool from scratch in Java** to learn how pools like HikariCP work internally
- 🔐 **CTF player:** ranked **34th in India** on CTFtime and placed **8th globally at BYU CTF**
- 🤖 I build LLM-powered apps with **LangChain, LangGraph and RAG**, and I'm still learning the deeper parts (evaluation, observability)
- 🧩 Practicing **Data Structures & Algorithms** on LeetCode
- 🏆 Hackathon builder: Goa Police Hackathon, Techfluence

---

## 🛠️ Tech stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Backend & Databases**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

**LLM Applications**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
RAG • Agent workflows • LangGraph (basics)

**Fundamentals & Tools**

DSA • OOP • DBMS • Java multithreading • Networking basics (TCP/IP, OSI model) • ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🚀 Featured projects

### 🔌 [Custom JDBC Connection Pool](https://github.com/ItzMeSam13/jdbc-connection-pool)
`Java` `JDBC` `MySQL`

A connection pool built from scratch implementing `javax.sql.DataSource`, backed by an `ArrayBlockingQueue`.

- Decorator-wrapped connections: `close()` returns the connection to the pool, so try-with-resources works
- Connections are validated with `isValid()`, open transactions are rolled back, and autocommit is reset on return
- Background worker keeps the pool filled and replaces invalid connections
- Leak-detection watchdog reclaims connections held past a configurable timeout
- 8-test suite against a live MySQL database (concurrent access, pool exhaustion, leak recovery, transaction rollback)

### 🧠 [AI-Powered Data Intelligence Platform](https://github.com/Kaarthikeya12/AI-PoweredData_Intelligence_Platform)
`Python` `FastAPI` `LangGraph` `Next.js` `Supabase` &nbsp;•&nbsp; *Team hackathon project*

Takes a natural-language research prompt, discovers web sources, scrapes and extracts structured data, reconciles conflicts across sources, and outputs a consolidated dataset with a markdown report. Uses two LangGraph workflows (planner and executor), streams live progress to a Next.js dashboard via SSE, and handles free-tier LLM rate limits with multi-key rotation and a fallback provider.

### 🎙️ [SecureVox](https://github.com/ItzMeSam13/SecureVox)
`Next.js` `Flask` `AI Audio Analysis` &nbsp;•&nbsp; *Goa Police Hackathon*

A forensic voice intelligence platform for law enforcement. It manages inmate voice prints, detects synthetic/AI-generated voices, and matches crime-scene samples against a structured database.

---

## 🏁 CTF & competitions

| Event | Result |
|-------|--------|
| CTFtime (India, 2026 rating) | Ranked **34th** in India (195.479 pts) |
| BYU CTF | **8th** globally |

Areas: forensic analysis, scripting, and security fundamentals.

---

## 🎯 Currently

- 📚 Practicing DSA regularly
- 🔄 Revisiting Next.js and FastAPI internals in depth
- 🧱 Exploring backend and systems internals (storage engines, networking, concurrency)
- 🔎 Looking for **backend internship opportunities**

---

<p align="center">
  <i>Open to feedback, collaboration, and good backend problems.</i>
</p>
