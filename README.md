# 🧠 AI‑Assisted SCRUM Companion

A lightweight **AI‑enhanced SCRUM management sandbox** built for learning, experimentation, and portfolio demonstration.  
Designed using clean architecture, modular NestJS services, and structured AI agents.

---

## 🚀 Vision

Create a minimal, extensible SCRUM system where the AI acts as a **SCRUM Coach**, not just a generator — helping teams refine stories, break down tasks, plan sprints, and analyze retrospectives.

---

## 🎯 Core Features (MVP Scope)

- 🧩 **Projects**  
  Create and manage simple project containers.

- 🏃 **Sprints**  
  Define sprint goals, dates, and associate stories.

- 📝 **User Stories**  
  Use AI to refine rough ideas into well‑structured stories.

- ✅ **Tasks & Kanban**  
  Break down stories into tasks; move tasks through statuses:
  `TODO → IN_PROGRESS → REVIEW → DONE`

- 🤖 **AI Assistance**
  - **StoryRefinerAgent** → converts ideas into user stories + acceptance criteria  
  - **TaskDecomposerAgent** → breaks down stories into actionable tasks  
  - **SprintPlannerAgent** → suggests story allocations into sprints  
  - **RetrospectiveAgent** → analyzes sprint outcomes

---

## 🧱 Tech Stack

### Backend
- **TypeScript** / **NestJS**
- **PostgreSQL** with **Prisma ORM**
- **OpenAI (or Anthropic)** for AI services
- Dockerized for deployment
- REST API (Expandable to GraphQL later)

### Frontend
- **Next.js (App Router)**
- **TypeScript + TailwindCSS**
- **shadcn/ui** for lightweight components

### Dev Environment
- **Monorepo → Turborepo**
- Shared types via `/packages/types`
- ESLint + Prettier + Strict TypeScript
- `.env` management with dotenv

---

## 🏗️ Architecture Overview

