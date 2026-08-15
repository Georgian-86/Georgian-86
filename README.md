<div align="center">

# Golu Kumar

**Full Stack Developer Intern @ upGrad School of Technology**
**DevOps & Cloud Engineer · AWS Certified Cloud Practitioner · B.Tech CSE 2027**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-golukumar15-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/golukumar15)
[![Email](https://img.shields.io/badge/Email-optimus4586prime-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:optimus4586prime@gmail.com)
[![AWS](https://img.shields.io/badge/AWS-Certified%20Cloud%20Practitioner-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://www.credly.com/users/golu-kumar)
![Profile views](https://komarev.com/ghpvc/?username=Georgian-86&style=flat-square&color=0A66C2)

</div>

---

## About

B.Tech Computer Science student at **Lovely Professional University** (2023-2027), currently a Full Stack Developer Intern at **upGrad School of Technology**, where I build the internal operations platform used every day by the admissions, finance and campus teams.

I work across the stack and into infrastructure: REST APIs and payment ledgers on one end, VPC design, Docker builds and AWS deployments on the other. Most of what I build handles money or student records, so correctness matters more than speed.

- Shipping production code at **upGrad SOT** (React, Node.js, PostgreSQL, MongoDB)
- Previously **founding contributor at TeachGenie.ai**, a DPIIT-recognised EdTech startup
- **AWS Certified Cloud Practitioner** with 18 Google Cloud skill badges
- Running a public **60 Days of Cloud & DevOps** challenge
- **CTO of Student Organization Oasis** and **Tech Head & Joint Secretary of the Student Career Committee** at LPU

---

## Experience

### Full Stack Developer Intern - upGrad School of Technology
**Jun 2026 - Present · Bengaluru, India**

Internal operations platform used daily by the admissions, finance and campus teams.

- Designed and built REST API endpoints for **payments, bookings, document generation and admin reporting**, with request validation, structured error handling and per-role access control.
- Implemented a **multi-installment fee-payment ledger** tracking running balances across semesters, with per-payment admin verification, over-payment allocation and offline receipt capture.
- **Eliminated double-allocation and overbooking race conditions** using atomic database guard conditions and exactly-once state transitions.
- Reconciled payment-gateway transactions against internal records by sourcing live transaction references from the provider API.
- Wrote SQL queries and MongoDB aggregation pipelines to reconcile records across upstream systems, and delivered admin dashboards with multi-sheet Excel and CSV exports that replaced manual spreadsheet work.
- **137 merged pull requests**, 30+ reviewed for teammates, working in Git feature branches with Agile delivery tracked on Jira.

**Stack:** React · Node.js · Express · PostgreSQL · MongoDB · REST APIs · SQL · Git · Jira

### SDE Intern & Founding Contributor - TeachGenie.ai
**Feb 2026 - Jun 2026 · Punjab, India**

AI-powered academic assessment platform serving 3,000+ faculty. Joined on a performance trial and was retained onto the founding team. The startup earned **DPIIT recognition** during my tenure.

- Built Python and **FastAPI** backend services in a modular, service-oriented architecture.
- **Migrated the production database from SQLite to a VPC-secured Amazon RDS PostgreSQL instance with zero data loss**, redesigning the schema and adding connection pooling to hold throughput under peak load.
- Containerised the services with **multi-stage Docker builds that cut image size by roughly 60%**, and automated deployments through **Amazon ECR onto AWS App Runner** with auto-scaling.
- Ran the backend live through **Assess-A-Thon 2026** - a 48-hour challenge across 24 categories for 3,000+ faculty - with **zero downtime**.
- **Closed a live brute-force attack** on the login API with a dual-layer defence combining sliding-window IP rate limiting and database-persisted OTP attempt tracking.
- Represented the product as an exhibitor at the **AI Impact Summit 2026, Bharat Mandapam, New Delhi**.

**Stack:** Python · FastAPI · PostgreSQL · Amazon RDS · Docker · Amazon ECR · AWS App Runner · VPC

### Blockchain Developer Intern - BlockseBlock
**Jun 2025 - Sep 2025 · Remote**

- Worked on **smart contract development** and decentralised applications.
- Built and shipped a **DApp on the Internet Computer Protocol (ICP)**, delivering against weekly sprint milestones in a fully remote team.

**Stack:** Rust · ICP · Smart Contracts · React

### Campus Ambassador - LetsUpgrade
**Mar 2025 - Jun 2025 · Remote**

- Promoted programmes and workshops to the student community and ran weekly activities with fellow ambassadors.
- Fed student insight back to the platform team to improve the learning experience.

---

## Leadership

### Chief Technical Officer - Student Organization Oasis, LPU
**Dec 2024 - Jun 2026** · Technical Trainee → Technical Manager → **CTO**

- Promoted twice in three months, then held the organisation's top technical post for 16 months.
- Managed the technical crew across live events and stood accountable for delivery on the day.
- Provided the technical backbone for campus-wide programming, including TechFluence 4.0.

### Tech Head & Joint Secretary - Student Career Committee, LPU School of CSE
**Dec 2024 - Jun 2026**

- Held office for 19 months across two successive posts, accountable to faculty leadership for the industry-academia calendar.
- **Headed the organising teams (12-15 members) behind 10+ conclaves, summits, ideathons and workshops.**
- **Hosted 30+ industry leaders** from Google, GitHub, Microsoft for Startups, Zepto, Salesforce, Walmart Global Tech, JPMorgan Chase, Accenture, Autodesk and Capgemini.
- Owned guest management, sponsor relationships, crowd management and on-the-day escalations.

### Senior Division Cadet - National Cadet Corps, 8 Punjab Battalion
**Nov 2020 - Mar 2024**

- Earned the **'C' Certificate with 'Alpha' grade**, the highest grading, over three and a half years of service.
- Represented the university at national-level camps and led community service drives.

---

## Featured Projects

| Project | What it does | Stack |
|---|---|---|
| **[60 Days of Cloud & DevOps](https://github.com/Georgian-86/60-days-cloud-devops)** | Public 60-day hands-on challenge: VPC design and peering, NAT/IGW, EC2, S3, EFS, IAM governance, load balancing and high-availability design, documented daily | AWS · Docker · NGINX · Linux |
| **[Trade, Valuation & P&L Control Platform](https://github.com/Georgian-86/trade-pnl-control-platform)** | Daily mark-to-market and P&L attribution pipeline with a severity-ranked control suite, served over an API and packaged into an Excel sign-off workbook. Tests run in CI | Python · pandas · PostgreSQL · FastAPI · GitHub Actions |
| **[Three-Tier Django Notes App](https://github.com/Georgian-86/Django-Notes-App)** | React + Django application split into app, database and web tiers, containerised with Docker behind an NGINX reverse proxy | Django · React · Docker · NGINX |
| **[Student Career Committee Platform](https://github.com/Georgian-86/student-career-committee)** | Next.js 16 platform with Supabase PostgreSQL, RBAC admin dashboard, announcements module and image gallery. Live on Vercel | Next.js · TypeScript · Supabase · Tailwind |
| **[Health Management System](https://github.com/Georgian-86/Health-Management-System)** | Blockchain-backed health records with patient-owned access, deployed live as an Internet Computer canister | TypeScript · ICP · Smart Contracts |
| **[IPV Fair Value Toolkit](https://github.com/Georgian-86/ipv-fair-value-toolkit)** | Independent price verification: multi-source consensus, variance analysis and configurable tolerance breaches | Python · pandas · SQL |
| **[Malware Detection & Classification](https://github.com/Georgian-86/Malware-Identication-and-Classification)** | Two-stage pipeline: 230+ static features from byte and assembly data, LightGBM reaching 0.998 AUC on EMBER 2018 | Python · scikit-learn · LightGBM |
| **[Two-Tier Flask + MySQL on Docker](https://github.com/Georgian-86/two-tier-flask-app)** | Flask backend and MySQL database as separate containers on a shared Docker network, with Compose and manual setups | Flask · MySQL · Docker |

---

## Tech Stack

**Languages** · Python · JavaScript · TypeScript · SQL · C++ · C · Bash · Rust

**Frontend** · React · Next.js · HTML5 · CSS · Tailwind CSS

**Backend** · Node.js · Express · FastAPI · Django · Flask · REST APIs · Microservices

**Databases** · PostgreSQL · MongoDB · MySQL · SQLite · Supabase · Prisma

**Cloud & DevOps** · AWS (EC2, S3, RDS, ECR, App Runner, VPC, IAM, CloudFormation) · Docker · NGINX · GitHub Actions · Linux · Google Cloud · Vercel

**Data & ML** · NumPy · pandas · scikit-learn · LightGBM

---

## Certifications & Achievements

| | |
|---|---|
| **AWS Certified Cloud Practitioner** | Amazon Web Services, 2026 |
| **18 Google Cloud skill badges** | BigQuery ML, Predictive Modeling, ML APIs, Cloud Vision API |
| **AICTE Internship on AI (TechSaksham)** | Selected - an initiative by Microsoft and SAP |
| **2nd place, HackTheBlock** | ICP Hub India, LPU, 2025 |
| **2nd place, Hack AI Hackathon** | LPU, 2025 |
| **National-round qualifier** | World Hackers Computer League, 2025 |
| **NCC 'C' Certificate, 'Alpha' grade** | 8 Punjab Battalion, 2024 |
| **Top 5 HoD-recommended innovation** | SDG-aligned, presented at Googlify Project Display |

---

<div align="center">

![Golu's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Georgian-86&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Georgian-86&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## Get in touch

**Email** · optimus4586prime@gmail.com
**LinkedIn** · [linkedin.com/in/golukumar15](https://www.linkedin.com/in/golukumar15)
**Location** · Bengaluru, India

Open to Full Stack Developer, Backend Engineer, DevOps Engineer and Cloud Engineer roles.
