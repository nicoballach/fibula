# Fibula Vision & Roadmap

> "Untangle, understand, connect."

## 🎯 Mission
Fibula is a self-hosted project management tool designed to make **product goals and technical dependencies** visible. While tools like Jira often drown users in lists and sprints, Fibula places the relationships between features, teams, and stakeholders at the center of the workflow.

We believe that successful software development happens when technology and business strategy are thought of together—not in isolation.

## 🔑 Core Values
1.  **Overview over Chaos:** Visualize dependencies as interactive graphs, not flat lists.
2.  **Radical Transparency:** Every team member understands *why* a task is blocked and what it impacts.
3.  **Data Sovereignty:** Self-hosting first. Your data belongs to you, not a cloud vendor.
4.  **Simplicity by Design:** Powerful features without plugin chaos or unnecessary configuration complexity.

## 💡 The Problem
Modern development teams struggle with:
*   **Lost Context:** Developers often don't know *why* a task matters to the bigger picture.
*   **Hidden Blockers:** Dependencies between teams are scattered across different tools or lost in spreadsheets.
*   **Stakeholder Frustration:** Product owners must manually extract roadmaps from thousands of tickets, lacking a clear view of risks.

## 🚀 The Solution
Fibula bridges the gap by providing:
*   **Feature Hierarchies:** Clear structure: `Product > Feature > Task`.
*   **Visual Dependency Graphs:** Interactive maps that instantly show how delaying one feature impacts the entire roadmap.
*   **Deep Integrations:** Seamless connection between GitHub (code), Slack/Teams (communication), and the planning layer.
*   **Stakeholder Mode:** A dedicated dashboard showing only risks, milestones, and progress—without technical noise.

## 🗺️ Roadmap

### Phase 1: Core (Q3/Q4 2026)
*Goal: Build a functional MVP for personal/team validation.*
- [ ] Setup Monorepo (Turborepo, pnpm)
- [ ] Database Design (Prisma, PostgreSQL)
- [ ] Basic CRUD for Features & Tasks
- [ ] Initial Dependency Visualization (React Flow)
- [ ] Local Docker Environment

### Phase 2: Validation (Q1 2027)
*Goal: Acquire external Beta testers.*
- [ ] Real-time Updates (WebSockets)
- [ ] GitHub Integration (PR Status Sync)
- [ ] Simple CSV Import
- [ ] Stakeholder Dashboard (Read-Only View)
- [ ] Onboard 3 Beta Teams

### Phase 3: Open Core Growth (Q2/Q3 2027)
*Goal: Public release and community building.*
- [ ] Public GitHub Release (V0.1)
- [ ] Comprehensive Documentation & Tutorials
- [ ] Automated CI/CD Pipeline
- [ ] Go Migration of Core Services (Performance Optimization)
- [ ] Foster Community Contributions

### Phase 4: Commercialization (Q4 2027+)
*Goal: Sustainable business model via Open Core.*
- [ ] SaaS Offering (Hosted Version)
- [ ] Advanced Import Wizard (Jira Migration) -> *Premium Feature*
- [ ] Enterprise Features (SSO, Audit Logs, SLAs)
- [ ] Payment Integration

## 📄 Licensing
The Fibula core is licensed under **AGPLv3**.
Commercial add-ons (SaaS, Enterprise features) may be offered under proprietary licenses (Dual Licensing).

---
*Last Updated: June 2026*
