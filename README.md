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
| **Languages** | Python • Java • SQL • JavaScript • C++ • C |
| **Frameworks** | Spring Boot • Node.js • Express.js • React.js |
| **Databases** | PostgreSQL • MySQL • MongoDB |
| **Tools** | Git • GitHub Actions • Docker • Postman |

---

## Featured Projects

<!-- Add your featured projects here -->

### [CodeAtlas](https://github.com/shrishaanth/CodeAtlas) · [Live demo](https://code-atlas-app.vercel.app)
Understand an unfamiliar codebase. Point CodeAtlas at a repository and it produces a browsable report computed from the code (Tree-sitter) and its git history (JGit), so every number traces back to a file, line or commit.

- **Reading order** — where to start reading, with files ranked by churn, reach and fan-in and the reasons behind each score
- **Ownership** — who last changed each line, bus factor per directory, single-owner and orphaned flags
- **Change coupling & hotspots** — files that change together, including hidden dependencies with no import between them, and code that is both busy and deeply nested
- **Architecture** — directories layered by import direction, with import cycles marked, plus an interactive import graph
- **Findings** — near-duplicate code, committed build output, untested areas and unimported modules, each with file-and-line evidence
- **Ask** — questions about the code; an optional LLM answers only from retrieved excerpts, and every citation is checked as exact, inside an excerpt, or unsupported

**Tech:** Java 17, Spring Boot, Tree-sitter, JGit, PostgreSQL, React, TypeScript, Docker.

### [Axon](https://github.com/shrishaanth/Axon)
API change-impact analysis. Diff tools say a change is breaking; Axon says *who* would break. It compares what an API promises (its OpenAPI spec), what it actually does (observed traffic) and what a proposed version would change.

- **Impact analysis** — breaking changes ranked by the clients that real traffic shows are affected; request-side impacts are *observed*, response-side ones only *potential*, and the two are never blended
- **Drift detection** — fields and operations that are documented but never used, or used but never documented
- **CI gate** — `axon check` fails a pull request when an observed breaking change hits a set share of active clients
- **Privacy by design** — captured traffic is reduced to field shapes in the browser; values never leave
- **Web UI** — clients × fields matrix, declared vs. observed contract, per-client timeline and an API map
- **Evaluated in the open** — the method was written before any result, and the write-up includes where Axon falls short

**Tech:** Java 17, Spring Boot, PostgreSQL, OpenAPI, React, TypeScript, Docker.

### [Taskify.io](https://github.com/shrishaanth/Taskify.io) · [Live demo](https://taskify-io.vercel.app)
Multi-tenant Kanban project management: Trello-style boards with real access control and live collaboration. One deployment serves many organisations, with work organised into projects, boards and cards.

- **Tenant isolation** — enforced at the database layer; another organisation's data returns 404, so it is never confirmed to exist
- **Two-layer roles** — organisation (owner, admin, member) and project (head, member) roles, re-checked on every request so a demotion applies immediately
- **Real-time boards** — room-scoped Socket.IO updates; drag-and-drop with mouse or touch updates instantly and rolls back if the server rejects it
- **Secure sessions** — rotating, revocable, hashed refresh tokens; reusing an old token signs the user out everywhere
- **Team features** — email invites, @mention notifications, board search and filters, safe account deletion
- **Tested** — 761 tests, led by a dedicated cross-tenant isolation suite

**Tech:** TypeScript, React, Node.js, Express, MongoDB, Socket.IO.

### [SurgeMap](https://github.com/shrishaanth/SurgeMap)
NYC taxi demand forecasting and fleet repositioning. SurgeMap forecasts pickups in each of 258 taxi zones 5, 15, 30 and 60 minutes ahead, then tests in a simulator whether sending idle vehicles to where demand is coming shortens rider waits.

- **Graph forecaster** — a Graph WaveNet over the directed taxi-flow graph plus a zone graph it learns itself, trained on four months of NYC TLC trips
- **Honest baselines** — compared with persistence, historical average, ridge and gradient boosting on the same data, with bootstrap confidence intervals
- **Fleet simulator** — replays real pickups against a simulated fleet, with a min-cost-flow repositioning policy that can run on any forecast
- **Interactive app** — a Streamlit app to explore forecasts zone by zone and run the simulator
- **Reproducible** — one command downloads the data, a CLI runs every step, and runs are seeded

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
