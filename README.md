# 2026 Summer AI Camp

A comprehensive 3-month intensive AI training program designed for CS underclassmen. This camp focuses on practical AI application development, modern coding tools, and building a portfolio of real-world projects.

## Program Overview

**Duration:** 12 weeks  
**Target Audience:** CS freshmen and sophomores  
**Outcome:** 9-10 official Anthropic certificates + portfolio of shippable AI projects

### What You'll Learn

- **AI-First Development:** Master Claude Code, OpenAI Codex, and AI coding assistants
- **Practical Skills:** Build RAG apps, custom MCP servers, AI agents, and production chatbots
- **Real Projects:** Every project is portfolio-worthy and deployable
- **Verified Credentials:** Earn official Anthropic certifications for your LinkedIn

## Curriculum Structure

### Month 1: Get Fluent with AI Tools (Weeks 1-4)
- Setup & First API Calls
- Prompting & API Fundamentals
- Claude Code basics
- OpenAI Codex comparison

### Month 2: Build Real Apps (Weeks 5-8)
- Skills & Subagents
- Chatbots with RAG
- Model Context Protocol (MCP)
- AI Agents & OpenClaw

### Month 3: Capstone & Portfolio (Weeks 9-12)
- Capstone project kickoff
- Build & deploy
- Blog post & documentation
- Resume prep & demo day

## Official Anthropic Certifications

By Week 12, students earn:
- Claude 101
- AI Fluency for Students
- Building with the Claude API
- Claude Code 101
- Claude Code in Action
- Introduction to Agent Skills
- Introduction to Subagents
- Introduction to Model Context Protocol
- AI Capabilities and Limitations
- MCP: Advanced Topics (optional)

## Website

The full curriculum with detailed week-by-week content is available on the website. Open `index.html` in your browser to explore:
- Complete 12-week curriculum
- Detailed training materials for each week
- Session-by-session breakdowns
- Interactive presentations for each week
- Weekly quizzes (in `quiz/` folder)
- Homework assignments and projects
- Certificate information

## Git Setup

```bash
git config user.name "$GITHUB_USER_NAME"
git config user.email "$GITHUB_USER_EMAIL"
git config credential.helper 'cache --timeout=3600'
git config pull.rebase false
```

## StudyTrack

A per-user progress tracker for the 12-week curriculum. Students log in with a username/password and track which weeks they've completed.

- Runs on port **8002**
- SQLite-backed, no external database needed
- Admin panel for user management at `/admin`

## Running Locally

Start both the website and StudyTrack with pm2:

```bash
# Start the static website (port 8001)
pm2 start site.config.js

# Start StudyTrack (port 8002)
pm2 start studytrack/ecosystem.config.js
```

Or start them individually:

```bash
# Website only
npm start --prefix studytrack   # StudyTrack only
```

## Deployment

The static website can be deployed to:
- GitLab Pages
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

Simply point the hosting service to the repository root.

StudyTrack is a Node.js app and requires a server (e.g. a VPS or PaaS like Railway/Render). Set the `JWT_SECRET` environment variable before deploying.

---

**Note:** This program is inspired by practical AI education principles, focusing on hands-on learning over theoretical ML foundations. Students learn by building, not by studying abstractions.
