# EcoSwap — Campus Reuse & Exchange Platform

> **WIX2002 Project Management** · Universiti Malaya (FCSIT) · OCC2 – Team 5  
> *Reuse. Exchange. Upcycle.*

EcoSwap is a free, campus-only web application that helps university students give unwanted items a second life through **Swap**, **Giveaway**, and **Upcycling** listings—with no selling, prices, or payments.

---

## Repository Structure

```text
.
├── app/                          # [Reserved] EcoSwap source code (Java 21, Spring Boot 3.5, MySQL, Thymeleaf)
└── docs/                         # Project management & engineering documentation
    ├── 01-proposal/              # Team roles, proposal summary, deliverables checklist
    ├── 02-backlog/               # Product backlog & user stories
    ├── 03-risk-management/       # Risk assessment form & risk response matrix
    ├── 04-sprints/               # Sprint reviews & retrospectives (Sprint 1–3)
    ├── 05-research-and-testing/  # Student survey & usability testing records
    └── 06-meeting-notes/         # Weekly meeting minutes
```

---

## Technology Stack (Implemented Product)

- **Backend**: Java 21, Spring Boot 3.5 (MVC, Security, Data JPA/Hibernate, Validation, Mail)
- **Database**: MySQL 8 with Flyway schema migrations
- **Frontend**: Thymeleaf, HTML5, CSS3, Vanilla JS (ES modules)
- **Maps**: OpenStreetMap + Leaflet
- **Testing & Deployment**: Maven, JUnit 5 & Mockito (35 automated tests), Docker

---

## Team Roles & Responsibilities (OCC2 – Team 5)

| Role | Member(s) | Responsibilities |
| :--- | :--- | :--- |
| **Group Leader / Project Manager** | LIZHAOZIYU | Kanban board, Gantt chart, weekly meetings, overall progress & deadlines |
| **Product Owner** | WANG ZIMING | Product backlog, feature priority, scope management |
| **External Liaison** | PENG YIHAO | Collaboration letter, external stakeholder communication, review meetings |
| **Requirements & Testing** | WANG CHENGHAO | Requirements gathering, user testing (10+ students), feedback evaluation |
| **Product Delivery Team** | ari Iqbal Ibn Abdul, Abdur Rahman Shezan, Chen ManXi | UI/UX design & application development |
| **Content & Visual** | PENG YI | Proposal infographic, report layout, Upcycling content |
| **Video Team** | Wasim, MUJAHID | Filming, editing, subtitling, final project video |
| **Documentation & Quality** | BIAN HONGZHAO | Final report compilation, walkthrough testing, retrospective records |

---

## For Developers: How to Upload Source Code

Please place the EcoSwap source code inside the `app/` directory (e.g., `app/src/`, `app/pom.xml`, `app/Dockerfile`) and push to this repository.
