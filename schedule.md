# 2026 summer ai camp planning 


## focus on practical use of ai

A freshman who just finished intro CS shouldn't be fine-tuning models or building eval harnesses 
from scratch — that's overshooting. The realistic goal for two CS underclassmen over one summer is: 
become genuinely productive with AI coding tools, build a few impressive shippable projects, and 
understand how modern AI apps work well enough to talk about them in an interview. Theory and ML internals 
can wait for later coursework.

Here's a leaner, more practical version.


## 3-Month AI Training Camp Plan (with Verified Anthropic Courses)


#### Month 1 — Get Fluent with AI Tools (Weeks 1–4)

Week 1 — Setup & First API Calls

Pre-work: Claude 101 + AI Fluency for Students (both are short and foundational; AI Fluency for Students is genuinely well-designed for their exact demographic).

Session 1: Environment setup (Python, VS Code, Git, API keys, billing caps). Discuss the AI Fluency framework from the course — the "4 D's" (Delegation, Description, Discernment, Diligence) become a vocabulary you'll use all summer.

Session 2: First API calls with both OpenAI and Anthropic SDKs. Build a CLI chatbot together. Homework: customize it.


Week 2 — Prompting & API Fundamentals

Pre-work: Building with the Claude API (this is the comprehensive API course — covers prompting, tool use, vision, streaming. It's longer; spread across the week).

Session 1: Practical prompting techniques. Apply them to a hard prompt of their own. System prompts deep dive.

Session 2: Structured output (JSON mode, tool use / function calling). Build a tool that extracts structured info from text — e.g., parse job postings into fields.


Week 3 — Claude Code (Part 1)

Pre-work: Claude Code 101 (start here) + begin Claude Code in Action.

Session 1: Claude Code setup with their own project, CLAUDE.md, slash commands, plan mode. Add a feature to an existing small open-source repo.

Session 2: Build something from scratch with Claude Code — small web app or CLI tool. Focus on how to prompt the agent well and when to intervene.


Week 4 — OpenAI Codex (CLI + Cloud)

Pre-work: Finish Claude Code in Action. Light reading from OpenAI's Codex docs.

Session 1: Codex CLI — run similar tasks, compare to Claude Code. Build a comparison matrix.

Session 2: Codex cloud — delegate a longer task. Discussion: when to use each tool. Project 1 due: a useful CLI tool or small web app built mostly with AI assistance, clean README.


#### Month 2 — Build Real Apps (Weeks 5–8)

Week 5 — Claude Code Power Features: Skills & Subagents

Pre-work: Introduction to Agent Skills + Introduction to Subagents. These are genuinely high-leverage — Skills and Subagents are how power users get the most out of Claude Code.

Session 1: Write a custom Skill for a workflow they care about (e.g., a "code review checklist" Skill, a "blog post draft" Skill). Test it in Claude Code.

Session 2: Set up Subagents for a multi-step task — e.g., one Subagent that researches, another that drafts, another that critiques. This is a concrete demonstration of agent orchestration that's easy to explain in an interview.


Week 6 — Building a Useful Chatbot + RAG Intro

Pre-work: Review relevant sections of Building with the Claude API (streaming, tool use). No new course.

Session 1: Build a chatbot with a real purpose (study buddy for a class, code explainer, etc.). Streaming, conversation history, basic tool use. Add a simple Streamlit UI.

Session 2: What RAG is and why it exists. Walk through embeddings + Chroma. Build a basic "chat with a PDF" app. Deploy both apps free (Streamlit Cloud, Vercel, Render).


Week 7 — MCP: Connecting Claude to Everything

Pre-work: Introduction to Model Context Protocol. This is one of the most resume-valuable courses in the catalog — MCP is a major focus area for 2026.

Session 1: MCP overview. Connect Claude Code to existing MCP servers (filesystem, GitHub). Use them to do something real.

Session 2: Write a simple custom MCP server in Python (the course walks through this). Hook it into Claude Code. Homework: think of one MCP server they wish existed.


Week 8 — Agents and OpenClaw

Pre-work: AI Capabilities and Limitations (good grounding for understanding what agents can and can't do reliably).

Session 1: What an agent is — the think-act-observe loop. Build a tiny one from scratch (~50 lines) that searches the web and answers questions.

Session 2: OpenClaw — self-host on a free-tier VPS or locally. Connect to Telegram or Discord. Write one custom skill. Discussion: agent security and permissions — what could go wrong, how to think about blast radius.


#### Month 3 — Capstone & Portfolio (Weeks 9–12)

Week 9 — Capstone Kickoff

Pre-work: Model Context Protocol: Advanced Topics if their capstone involves MCP. Otherwise no new course — they should be building.

Session 1: Finalize capstone scope individually. Suggested directions that leverage what they've learned: a useful MCP server, a Claude Code Skills pack for a specific domain, a polished RAG app, an OpenClaw skill suite, or an AI feature added to an existing open-source project.

Session 2: Architecture sketch, weekly milestones, repo setup.


Week 10 — Build

Pre-work: None.

Session 1: Working session. Heavy use of Claude Code with their own custom Skills and Subagents from Week 5.

Session 2: Open-source contribution — find one real issue in an AI tooling repo and submit a PR.


Week 11 — Finish + Write

Pre-work: None.

Session 1: Final features, deploy.

Session 2: Write a blog post about the capstone. Publish on dev.to, Medium, or a personal site.


Week 12 — Resume & Interview Prep

Pre-work: Collect all Anthropic course completion certificates. Add a "Certifications" section to LinkedIn.

Session 1: Resume review. Every project needs a clean README with screenshots. Add the certificate stack to LinkedIn — this is real evidence.

Session 2: Mock interviews. Demo day.


## Anthropic Certificate Stack (End of Camp)

By Week 12, each student should have these certificates:

- Claude 101 (Week 1)
- AI Fluency for Students (Week 1)
- Building with the Claude API (Week 2)
- Claude Code 101 (Week 3)
- Claude Code in Action (Week 3–4)
- Introduction to Agent Skills (Week 5)
- Introduction to Subagents (Week 5)
- Introduction to Model Context Protocol (Week 7)
- AI Capabilities and Limitations (Week 8)
- Model Context Protocol: Advanced Topics (Week 9, optional based on capstone)

That's 9–10 official Anthropic certificates on their LinkedIn before they apply for sophomore/junior internships. For a freshman, that's a striking credential stack — most applicants will have zero.

Courses I Intentionally Skipped

Claude with Amazon Bedrock / Google Vertex AI — Enterprise cloud deployment isn't relevant for them yet. Skip unless their capstone needs it.

Introduction to Claude Cowork — Cowork is the knowledge-work product, not the dev-focused one. Skip for a CS-focused camp; their attention is better spent on Claude Code.

AI Fluency: Framework & Foundations — Redundant with AI Fluency for Students, which is the student-tailored version. Pick one (I chose the student version).

AI Fluency for Educators / Nonprofits / Small Businesses / Teaching — Wrong audience.


