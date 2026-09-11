# AI Skill Exchange

### AI-Powered Campus Skill Intelligence & Adaptive Team Network

AI Skill Exchange is an AI-powered campus platform that helps students **discover skills, exchange knowledge, find suitable peers, and build multidisciplinary project teams**.

The platform connects students based on their skills, learning goals, project requirements, and complementary capabilities.

---

## Problem

Students' skills, learning needs, and project capabilities are often fragmented across campus. This makes it difficult to:

- Find students with the right skills
- Discover peers who can teach or learn from each other
- Identify the skills required for a project
- Build balanced multidisciplinary teams
- Understand campus-wide skill demand and shortages

---

## Proposed Solution

AI Skill Exchange creates a unified **Campus Skill Intelligence Network** that uses AI-assisted skill analysis and matching to connect students and projects.

### Core Features

- **Student Skill Profiles** — Manage skills, interests, experience, and learning goals.
- **AI Skill Analyzer** — Extract and structure skills from student/project information.
- **Reciprocal Peer Matching** — Match students who can mutually teach and learn.
- **Project Intelligence** — Analyze projects and identify required skills.
- **AI Team Builder** — Recommend complementary students for project teams.
- **Skill Credit System** — Reward verified peer-to-peer knowledge exchange.
- **Campus Insights** — Identify aggregate skill demand, supply, and shortages.
- **Offline-First Support** — Continue core functionality with local storage and synchronization.
- **Authentication & Security** — Protect user accounts and platform operations.

---

## Technology Stack

### Frontend
- Next.js
- React
- TypeScript
- Tailwind CSS
- IndexedDB / Offline-first storage

### Backend
- Python
- FastAPI
- SQLAlchemy
- Alembic
- SQLite

### AI
- Skill extraction
- Semantic matching
- Embeddings
- Skill graph
- Project analysis
- Team optimization
- Local/Mock AI provider support
- Ollama support

### Development & Deployment
- Docker
- PostgreSQL support
- REST APIs
- Automated testing

---

## System Architecture

```text
Student / Project Input
        ↓
Next.js Frontend
        ↓
FastAPI Backend
        ↓
AI Intelligence Layer
   ├── Skill Analyzer
   ├── Matching Engine
   ├── Skill Graph
   ├── Project Intelligence
   └── Team Builder
        ↓
Database
        ↓
Recommendations / Insights
```

---

## Main Workflow

```text
Create Student Profile
        ↓
Analyze Skills
        ↓
Build Campus Skill Representation
        ↓
Enter Project Requirement
        ↓
Analyze Required Skills
        ↓
Match Student Capabilities
        ↓
Optimize Complementary Team
        ↓
Collaborate & Exchange Skills
```

---

## Project Structure

```text
KH001-TeamName/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── src/
│
