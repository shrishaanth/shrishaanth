<div align="center">

# Shrishaanth

**M.Sc. (Integrated) Software Systems @ PSG College of Technology**

Building software • Solving problems • Learning every day

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shrishaanth-dev)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/shrishaanth)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:shrishaanth2024@gmail.com)

</div>

---

## About Me

I'm a Computer Science student pursuing an **M.Sc. (Integrated) in Software Systems** at **PSG College of Technology**.

I enjoy designing and building software that solves practical problems. My interests lie in **software engineering**, **backend development**, **full-stack development**, and **algorithmic problem solving**.

Currently, I'm focused on strengthening my programming fundamentals while building projects that help me understand how real-world applications are designed.

---

## Currently Exploring

- Data Structures & Algorithms
- Backend Development
- System Design Fundamentals
- Artificial Intelligence & Machine Learning

---

## Technical Skills

| Category | Technologies |
|-----------|--------------|
| **Languages** | C • C++ • Python • JavaScript • TypeScript |
| **Frontend** | HTML • CSS • React |
| **Backend** | Node.js • Express.js • Socket.IO |
| **Databases** | Oracle • MongoDB |
| **Tools** | Git • Docker • Postman • VS Code |

---

## Featured Projects

<!-- Add your featured projects here -->

### [CodeAtlas](https://github.com/shrishaanth/CodeAtlas)
Built a repository-analysis platform in Spring Boot and PostgreSQL that parses Python with Tree-sitter and mines git history with JGit. It produces a reading order, blame-based ownership with bus factor, change coupling, hotspots and evidence-linked findings, and is deployed on Vercel and Render with 138 tests.

- Replaced the first reading-order formula after a train/held-out evaluation on 20 repositories showed it lost to sorting by file size. The tuned version scored 0.69 mean percentile on 10 unseen repositories, against 0.67 for file size, 0.67 for commit count and 0.50 for random.
- Raised definition retrieval for code Q&A to 98–100% in the top 8 results on two repositories. I traced the misses to AND-combined full-text terms and a per-file cap that dropped definitions, and fixed both.
- Verified every LLM citation against the retrieved excerpts (exact, inside an excerpt, or unsupported) after the model cited line numbers that held different code.

**Tech:** Java 17, Spring Boot, Tree-sitter, JGit, PostgreSQL, React, TypeScript, Docker.

### [Axon](https://github.com/shrishaanth/Axon)
Built an API change-impact tool in Java 17, Spring Boot and PostgreSQL that ranks breaking OpenAPI changes by which clients observed traffic shows are affected, labelling response-side impacts “potential” since traffic can’t show who reads a field.

- Wrote the evaluation method before running it: on 100 held-out synthetic populations the ranking scored tau 0.69, against 0.48 for traffic volume and −0.03 for spec-only. Diffing alone matched only 73% of `oasdiff` on 200 real version pairs, and I published that.
- Stored traffic as order-independent counters, so replaying 1M events reproduced live ingestion exactly (4,700 events/s on one Postgres). Shipped a CI gate (`axon check`), a browser-side sanitiser that uploads only field shapes, and a React UI; 70+ tests.

**Tech:** Java 17, Spring Boot, PostgreSQL, OpenAPI, React, TypeScript, Docker.

### [Taskify.io](https://github.com/shrishaanth/Taskify.io)
Built a multi-tenant Kanban platform in React, TypeScript, Express and MongoDB with organisations, projects and boards, role-based access, and guards against edge cases like removing the last owner or deleting a column that still has cards. It passes 761 tests.

- Synced boards live across users with Socket.IO rooms per organisation, project and board. Each update applies straight to the client cache and skips the user who made it. Drag-and-drop updates the screen immediately and rolls back if the server rejects the change.
- Secured sessions with rotating, hashed refresh tokens. Rotation is atomic, and a reused token signs the user out everywhere. Tabs share one refresh through Web Locks. Account deletion anonymises the user and is blocked while they are the only owner of an organisation.

**Tech:** TypeScript, React, Node.js, Express, MongoDB, Socket.IO.

### [SurgeMap](https://github.com/shrishaanth/SurgeMap)
Built a spatio-temporal forecasting system for NYC taxi demand, predicting pickups for 258 zones 5 to 60 minutes ahead from 13M trips; a Graph WaveNet (dilated temporal convolutions plus graph convolutions over trip-flow and learned zone graphs) beat tuned gradient boosting by 2.4-3.4% RMSE (4-7% in surge periods) and persistence by 23-35%, with bootstrap confidence intervals.

- Traced inflated early results to a truncated source file that had zeroed the last two test days, rebuilt the data pipeline on official TLC files with strictly chronological splits, and used single-change ablations to find what actually mattered (shuffled windows, Poisson loss, and the architecture swap that added a further 1-2%).
- Built a fleet simulator with an LP-based repositioning policy (SciPy) that cut unmet requests from 42.8% to 26.5% at 2,000 vehicles, and showed that beyond a good forecast the fleet size, not the forecaster, was the limit; packaged everything as a 16-command Python CLI with 99 tests and seeded, reproducible runs.

**Tech:** Python, PyTorch, NumPy, Pandas, Scikit-learn, SciPy, Streamlit.


---

## Tech Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=c,cpp,java,python,javascript,html,css,react,nodejs,express,flask,mysql,mongodb,sqlite,git,docker,postman,linux,vscode"/>
</p>

---

## Beyond Programming

Apart from coding, I enjoy exploring new technologies, learning through projects, and continuously improving my problem-solving skills.

I believe that building real-world applications is one of the best ways to grow as a software developer.

---

## Contact

- 📧 **Email:** shrishaanth2024@gmail.com
- 💼 **LinkedIn:** www.linkedin.com/in/shrishaanth-dev
- 🌐 **GitHub:** https://github.com/shrishaanth

Feel free to reach out if you'd like to collaborate, discuss projects, or connect.
