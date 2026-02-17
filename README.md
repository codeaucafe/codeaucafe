## Intro
### 👋 Hey there! I'm **David**. I am a Senior Software Engineer at Bestow. I have a strong passion for distributed systems, microservices, secure data processing systems, Go, Python, and speciality single-origin coffees.

### 🖥️ I’m currently a Senior Software Engineer at Bestow [(check us out)](https://techcrunch.com/2025/05/13/insurtech-bestow-lands-120m-series-d-from-goldman-sachs-smith-point-capital/). Previously, I was a software engineer at Atlassian on the Jira Align and Bitbucket Cloud teams.

### 📰 Note: I previously went by DataDavd/datadavd online (a relic from my old data engineering days), but now use `codeaucafe` as my GitHub username. Also, if you see `github/CSddansby` come up in your searches of me that is my old Credit Sesame organization GitHub account that Credit Sesame never closed after I left. So, please ignore `CSddansby` as `codeaucafe` is now my primary GitHub username.

## Background
### :mount_fuji: I'm located in the Seattle area.

### 💻 Beyond my day job, I'm committed to continuous growth: contributing to open source (mainly [Dolt](https://github.com/dolthub/dolt) lately, which is a MySQL-compatible SQL database with Git-like version control, written in Go), reading about and exploring software architecture, distributed systems, programming languages, and software design patterns, and advancing my Go proficiency.

### 📚 Outside of software engineering and tech, I enjoy learning French, snowboarding and hiking with my brother and friends, and traveling with my wife.

## :desktop_computer: Open Source Software Contributions
[dolthub/dolt](https://github.com/dolthub/dolt)
- [v1.81.2](https://github.com/dolthub/dolt/releases/tag/v1.81.2) (2026-01): Add new `dolt_status_ignored` system table. [Pull Request #10227](https://github.com/dolthub/dolt/pull/10227)
- [v1.79.0](https://github.com/dolthub/dolt/releases/tag/v1.79.0) (2025-12): Add `--filter` option for `dolt diff`. [Pull Request #10030](https://github.com/dolthub/dolt/pull/10030)
- [v1.76.4](https://github.com/dolthub/dolt/releases/tag/v1.76.4) (2025-11): Make `dolt_diff_summary` respect `dolt_ignore` patterns. [Pull Request #9946](https://github.com/dolthub/dolt/pull/9946)
- [v1.55.6](https://github.com/dolthub/dolt/releases/tag/v1.55.6) (2025-07): Improve argument error messaging during table import. [Pull Request #9429](https://github.com/dolthub/dolt/pull/9429)
- [v1.55.3](https://github.com/dolthub/dolt/releases/tag/v1.55.3) (2025-06): Add early primary key validation during table import to fail fast instead of processing entire large files with invalid primary keys. [Pull Request #9349](https://github.com/dolthub/dolt/pull/9349)
- [v1.53.5](https://github.com/dolthub/dolt/releases/tag/v1.53.5) (2025-05): Add CLI feature to support importing CSV and PSV files without header rows. [Pull Request #9204](https://github.com/dolthub/dolt/pull/9204)

[dolthub/doltgresql](https://github.com/dolthub/doltgresql)
- [v0.55.0](https://github.com/dolthub/doltgresql/releases/tag/v0.55.0) (2026-01): Add `dolt_status_ignored` system table adapter for new Dolt system table added in dolthub/dolt#10227. [Pull Request #2187](https://github.com/dolthub/doltgresql/pull/2187)
- [v0.54.8](https://github.com/dolthub/doltgresql/releases/tag/v0.54.8) (2026-01): Add ValidateCreateSchema analyzer rule to ensure `CREATE SCHEMA` fails gracefully when the database context is invalid. [Pull Request #2139](https://github.com/dolthub/doltgresql/pull/2139)
- [v0.54.8](https://github.com/dolthub/doltgresql/releases/tag/v0.54.8) (2026-01): Unskip the `SELECT DOLT_CLEAN()` zero-argument smoke tests given dolthub/doltgresql#1361 is now fixed by dolthub/doltgresql#1763. [Pull Request #2138](https://github.com/dolthub/doltgresql/pull/2138)
- [v0.54.8](https://github.com/dolthub/doltgresql/releases/tag/v0.54.8) (2026-01): Remove outdated skip list entries for OR index tests given dolthub/doltgresql#1868 is now fixed by dolthub/doltgresql#2123. [Pull Request #2137](https://github.com/dolthub/doltgresql/pull/2137)
- [v0.54.8](https://github.com/dolthub/doltgresql/releases/tag/v0.54.8) (2026-01): Fix `DESCRIBE dolt.status` syntax error by adding `STATUS` to the `simple_ident` grammar rule, which previously didn't recognize unreserved keywords as valid identifiers. [Pull Request #2136](https://github.com/dolthub/doltgresql/pull/2136)

[in-toto/witness](https://github.com/in-toto/witness) ([CNCF project](https://www.testifysec.com/blog/witness-donation))
- [v0.5.2](https://github.com/in-toto/witness/releases/tag/v0.5.2) (2024-06): Small change to add shorthand vars to two common witness run options. [Pull Request #441](https://github.com/in-toto/witness/pull/441)
- [v0.2.0](https://github.com/in-toto/witness/releases/tag/v0.2.0) (2023-12): Add the feature for users to set what hash algorithms they want to use for digest calculation. [Pull Request #292](https://github.com/in-toto/witness/pull/292)

[treeverse/lakeFS](https://github.com/treeverse/lakeFS)
- [v0.63.0](https://github.com/treeverse/lakeFS/releases/tag/v0.63.0) (2022-04): Fix `Create a Repo` minimum character limit wording. [Pull Request #3155](https://github.com/treeverse/lakeFS/pull/3155)
- [v0.62.0](https://github.com/treeverse/lakeFS/releases/tag/v0.62.0) (2022-04): Remove unused functions in tx.go. [Pull Request #3128](https://github.com/treeverse/lakeFS/pull/3128)
- [v0.54.0](https://github.com/treeverse/lakeFS/releases/tag/v0.54.0) (2021-11): Add in-app lakeFS documentation links on the Setup, Create a Repository (Modal), Branches, and Auth/Admin pages of lakeFS UI. [Pull Request #2506](https://github.com/treeverse/lakeFS/pull/2506)
- [v0.48.0](https://github.com/treeverse/lakeFS/releases/tag/v0.48.0) (2021-08): Fix bug to correctly return error when users navigate to routes downstream from `BaseURL`. [Pull Request #2382](https://github.com/treeverse/lakeFS/pull/2382)

[go-delve/delve](https://github.com/go-delve/delve)
- [v1.25.0](https://github.com/go-delve/delve/releases/tag/v1.25.0) (2025-06): Fix build version bug; use commit instead of version file blob hash. [Pull Request #3987](https://github.com/go-delve/delve/pull/3987)

[ktrysmt/go-bitbucket](https://github.com/ktrysmt/go-bitbucket)
- [v0.9.30](https://github.com/ktrysmt/go-bitbucket/releases/tag/v0.9.30) (2021-11): Update `GetDiffStat` functionality to filter response fields. [Pull Request #171](https://github.com/ktrysmt/go-bitbucket/pull/171)
- [v0.9.24](https://github.com/ktrysmt/go-bitbucket/releases/tag/v0.9.24) (2021-07): Create `RepositoryRefsOptions` type and `ListRefs` method. [Pull Request #155](https://github.com/ktrysmt/go-bitbucket/pull/155)
- [v0.9.21](https://github.com/ktrysmt/go-bitbucket/releases/tag/v0.9.21) (2021-07): Add `Diff-Stat` feature. [Pull Request #145](https://github.com/ktrysmt/go-bitbucket/pull/145)
- [Pull Request #156](https://github.com/ktrysmt/go-bitbucket/pull/156) (2021-07): This PR simplifies TagOptions and BranchOptions types into a single RefOptions type (since git tags and branches are both refs) and adds DeleteBranch and DeleteTag functionality.

[mingrammer/diagrams](https://github.com/mingrammer/diagrams)
- [v0.23.2](https://github.com/mingrammer/diagrams/discussions/828#discussioncomment-4673351) (2023-01): Update GCP icons using the [official, updated GCP icons](https://cloud.google.com/icons). [Pull Request #666](https://github.com/mingrammer/diagrams/pull/666)

## 🚀 Skills
### Programming Languages
- **Go**
- **Python**
- **JavaScript/TypeScript**
- **C#**

### Software Engineering
- **Backend Development**: distributed systems, microservices, Django, Go net/http
- **API Development**: RESTful services, gRPC with Protocol Buffers, Buf ecosystem
- **Concurrent Programming**: Go (goroutines, channels, select, sync package - Mutex, WaitGroup, atomic), Python (threading - Lock, Event, Semaphore, asyncio, concurrent.futures, multiprocessing)
- **Frontend**: React
- **System Design**: scalability, high availability, fault tolerance
- **Architectural Patterns**: event-driven architecture, event sourcing & CQRS
- **CLI Development**: Cobra framework (Go)

### Tech Stack
#### Cloud & Infrastructure
- **AWS**: EC2, RDS (PostgreSQL), SQS, SNS, S3, Lambda, EMR, ElastiCache (Redis), CDK & CloudFormation, SDK (Go/Python/boto3), LocalStack
- **GCP**: Google Kubernetes Engine (GKE), Cloud SQL, Pub/Sub, MemoryStore (Redis), Cloud Deploy, SDK (Go)

#### Containerization
- **Kubernetes**
- **Docker**
- **Docker Compose**

#### Databases & Storage
- **Database**: PostgreSQL, Microsoft SQL Server
- **Cache**: Redis

#### DevOps & Operations
- **CI/CD**: GitHub Actions, CircleCI, Bitbucket Pipelines, GCP Cloud Deploy
- **Observability**: New Relic, Splunk, Sentry, StatsD
- **Incident Management**: incident.io, Opsgenie, Statuspage
- **Code Quality**: SonarQube, LaunchDarkly (feature flags)

#### Data Engineering
- **Data Processing**: Apache Spark, PySpark, Databricks
- **Workflow Orchestration**: Apache Airflow
- **Big Data Query Languages**: SparkSQL, HiveSQL, Presto

## ⌨️ Mechanical Keyboards
- daily driver: Boardsource lulu ergonomic mechanical keyboard with Alpaca V2 linear switches lubed with 205g0, Deskeys V2 switch films, and official Star Wars Galactic Empire DSA keycaps from [NovelKeys](https://novelkeys.com/products/star-wars-galactic-empire-dsa-keycap-set). What does it look like? [Find out](https://imgur.com/a/daily-driver-lulu-uxowLYo)! Also, if you are interested, check out my [QMK Layout](https://github.com/codeaucafe/qmk_firmware/blob/ddansby/lulu-keymap/keyboards/boardsource/lulu/keymaps/datadavd/keymap.c).
- debug keyboard: I use a [Rama Dual Shot M6-C](https://imgur.com/a/debug-keyboard-bUQWYTZ) macro keyboard with the keys mapped specifically to my custom shortcuts for easy debugging. The keyboard uses Rama artisan aluminum keycaps. Also, I use Zealio V2 65G tactile switches lubed with 205g0 with Deskeys V2 switch films.
- travel keyboard: [Lily58](https://imgur.com/a/WlNtPUB) (which is what the Lulu is based upon) with the same keymap.

## Note on authenticity: I sign all my commits
![Github All Contributors](https://img.shields.io/badge/codeaucafe-Verified-brightgreen)

## 📫 How to reach me
<a href="https://www.linkedin.com/in/davidldansby/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>

<!--
**codeaucafe/codeaucafe** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
