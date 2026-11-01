# University Clubs Portal

**Course:** DevOps Fundamentals [Fall, 2026] — Assignment 01  
**Project:** Student Portfolio - University Club Information Website  
**Repository:** [https://github.com/Rabisandhu/student-portfolio](https://github.com/Rabisandhu/student-portfolio)

---

## 📌 Project Overview
The **University Clubs Portal** is an informational web application designed to introduce university students to various on-campus student clubs and societies. It serves as a central hub for new and continuing students to discover club categories, track upcoming events, learn the membership process, and celebrate club milestones and accomplishments.

---

## 📂 Project Structure

```text
student-portfolio/
├── .gitignore
├── README.md
├── src/
│   ├── index.html        # Main landing page introducing the portal & campus life
│   ├── clubs.html        # Overview of club categories (Tech, Sports, Cultural, Debates)
│   ├── events.html       # Schedule of upcoming events, workshops, and competitions
│   ├── join.html         # Onboarding guide, registration steps, and participation guidelines
│   └── highlights.html   # Showcases major achievements, awards, and event highlights
└── styles/
    └── style.css         # Shared stylesheet with responsive layout and media queries
```

---

## 👥 Page Assignments & Team Responsibilities

| Page | Description | Assigned Role |
| :--- | :--- | :--- |
| `src/index.html` | Portal home page, introduction to student clubs, core navigation | Team Lead |
| `src/clubs.html` | Details on club categories (Technology, Sports, Cultural, Debate) | Member 1 |
| `src/events.html` | Upcoming events calendar, workshops, seminars, and competitions | Member 2 |
| `src/join.html` | Membership guide, registration steps, meeting schedules | Member 3 |
| `src/highlights.html`| Major achievements, competition victories, hall of fame | Member 4 |

---

## 🌿 Git Branching Strategy & Workflow

This project adheres to professional Git branching and collaboration standards:

1. **`main`**: Production-ready code. Direct pushes are restricted.
2. **`develop`**: Active integration branch where features are gathered and tested before release.
3. **`feature/<page-name>`**: Individual feature branches created from `develop` by team members (e.g., `feature/clubs-page`).
4. **`release/v1.0`**: Release candidate branch created by the Team Lead for final testing and QA before production deployment.

### Pull Request & Review Requirements
- All feature work is submitted via Pull Requests targeting `develop`.
- PRs into `develop` require at least **2 approvals**.
- PRs into `main` require at least **3 approvals**.
- Feature branches are rebased with `origin/develop` prior to merge to maintain a clean commit history.

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Rabisandhu/student-portfolio.git
   cd student-portfolio
   ```

2. **Checkout develop branch:**
   ```bash
   git checkout develop
   ```

3. **Preview the website:**
   Open `src/index.html` in any modern web browser.

