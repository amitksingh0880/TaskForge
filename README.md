# 🛠️ TaskForge

**TaskForge** is an open-source, real-time task management system built with modern developer tooling:  
Bun, Express, PostgreSQL, Kafka, Prisma, React (Vite), and Docker.

![TaskForge Screenshot](./docs/preview.png)

---

## 📦 Tech Stack

| Layer        | Tech                         |
|--------------|------------------------------|
| Backend      | [Bun](https://bun.sh/), Express |
| Database     | PostgreSQL + Prisma ORM      |
| Messaging    | Apache Kafka (Bitnami image) |
| Frontend     | React + Vite (TypeScript)    |
| Containerized| Docker + Docker Compose      |

---

## ✨ Features

- 🔐 JWT-based authentication (coming soon)
- ✅ Create, update, assign tasks within projects
- 🏷️ Tag & categorize tasks
- 📬 Kafka-powered task notifications & events
- 🔄 Real-time task updates via event streams
- 📊 AI suggestions (planned): auto-prioritize & smart reminders

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/taskforge.git
cd taskforge
