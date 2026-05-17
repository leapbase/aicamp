# AI Camp Quiz Answer Key

This comprehensive answer key contains all questions, answer choices, correct answers, and explanations from the 12-week AI Camp curriculum.

---

## Week 1: Setup & First API Calls

### Question 1
What are the "4 D's" of the AI Fluency framework taught in Week 1?

**Answer Choices:**
- A) Data, Design, Development, Deployment
- B) Delegation, Description, Discernment, Diligence
- C) Define, Develop, Debug, Document
- D) Discover, Design, Deliver, Diagnose

**Correct Answer:** B

**Explanation:** The 4 D's are: Delegation (what to give to AI), Description (clear prompts), Discernment (evaluating output), and Diligence (iterating and refining).

---

### Question 2
Why should you NEVER hardcode API keys directly in your source code?

**Answer Choices:**
- A) It makes the code run slower
- B) API keys in code can be accidentally committed to GitHub, exposing your credentials and potentially costing you money
- C) API keys need to be in a separate file to work properly
- D) It's required by Python syntax

**Correct Answer:** B

**Explanation:** Hardcoded API keys can be accidentally committed to public repositories like GitHub, exposing your credentials to anyone. This can lead to unauthorized usage and unexpected charges.

---

### Question 3
Which command creates a new Python virtual environment?

**Answer Choices:**
- A) pip install venv
- B) python -m venv myenv
- C) virtualenv --create
- D) python create-env myenv

**Correct Answer:** B

**Explanation:** The correct command is 'python -m venv myenv' which creates a new virtual environment. This isolates your project's dependencies from other Python projects.

---

### Question 4
In the context of the 4 D's framework, what does "Discernment" mean?

**Answer Choices:**
- A) Knowing which tasks to delegate to AI versus doing yourself
- B) Writing clear and specific prompts for AI
- C) Evaluating AI output critically and verifying it works correctly
- D) Iterating and refining your approach when AI gives wrong code

**Correct Answer:** C

**Explanation:** Discernment is about critically evaluating AI output - verifying that AI-generated code actually works, is secure, and meets your requirements.

---

### Question 5
What is the recommended approach when setting up API billing for the first time?

**Answer Choices:**
- A) Set an unlimited budget to avoid interruptions
- B) Set a billing cap (like $10 to start) to control costs and monitor usage
- C) Don't set up billing until you're ready to deploy to production
- D) Use a credit card with a low limit as the only safety measure

**Correct Answer:** B

**Explanation:** Setting a billing cap (like $10 initially) helps you control costs while learning. You can always increase it later once you understand your usage patterns.

---

### Question 6
What file should you add to your .gitignore to prevent accidentally committing secrets?

**Answer Choices:**
- A) requirements.txt
- B) README.md
- C) .env
- D) config.py

**Correct Answer:** C

**Explanation:** The .env file typically contains environment variables including API keys and secrets. It should ALWAYS be in your .gitignore to prevent committing secrets to version control.

---

### Question 7
Which of the following is a key difference between the OpenAI and Anthropic API structures mentioned in Week 1?

**Answer Choices:**
- A) OpenAI requires Java while Anthropic uses Python
- B) They have differences in how system prompts and max_tokens are handled
- C) OpenAI doesn't support chat completions
- D) Anthropic doesn't support streaming responses

**Correct Answer:** B

**Explanation:** While both APIs are similar, they have differences in parameter names and handling, such as how system prompts are specified and the max_tokens parameter.

---

### Question 8
What is one of the stretch goals suggested for the Week 1 CLI chatbot project?

**Answer Choices:**
- A) Adding streaming responses character-by-character
- B) Implementing a web interface
- C) Deploying to a cloud server
- D) Adding voice recognition

**Correct Answer:** A

**Explanation:** Adding streaming responses (showing tokens as they arrive character-by-character) is a stretch goal that improves user experience by showing progress in real-time.

---

## Week 2: Prompting & API Fundamentals

### Question 1
What is "few-shot prompting"?

**Answer Choices:**
- A) Using as few words as possible in your prompt
- B) Providing examples in your prompt to show the format and handle edge cases
- C) Making only a few API calls to save money
- D) Using multiple AI models simultaneously

**Correct Answer:** B

**Explanation:** Few-shot prompting involves providing examples in your prompt to demonstrate the desired format and handle edge cases. This helps the AI understand exactly what you want.

---

### Question 2
What is the main purpose of a system prompt?

**Answer Choices:**
- A) To test if the API is working
- B) To set rules, personality, and behavior that influence all responses in a conversation
- C) To authenticate with the API
- D) To specify which model version to use

**Correct Answer:** B

**Explanation:** System prompts are set once at the conversation start and control the AI's personality, tone, expertise level, output format, and safety guardrails throughout the conversation.

---

### Question 3
Why is structured output (JSON mode or function calling) better than free-form text for production applications?

**Answer Choices:**
- A) It's faster to generate
- B) It's easier to parse reliably, has consistent format, and integrates well with applications
- C) It uses fewer tokens
- D) It's required by all AI APIs

**Correct Answer:** B

**Explanation:** Structured output like JSON mode and function calling provides reliable, parseable data with consistent formatting, making it much easier to integrate AI outputs into production applications.

---

### Question 4
In the chain-of-thought prompting technique, what do you ask the AI to do?

**Answer Choices:**
- A) Give the answer as quickly as possible
- B) Think through the problem step-by-step and show reasoning before giving the final answer
- C) Connect to external databases
- D) Use multiple AI models in a chain

**Correct Answer:** B

**Explanation:** Chain-of-thought prompting asks the AI to 'think out loud' by showing its reasoning step-by-step before giving the final answer. This improves accuracy on complex reasoning tasks.

---

### Question 5
What is the main advantage of function calling (tool use) in AI applications?

**Answer Choices:**
- A) It makes the AI run faster
- B) It gives LLMs the ability to invoke external functions and APIs, extending their capabilities beyond text generation
- C) It reduces token costs
- D) It eliminates the need for prompts

**Correct Answer:** B

**Explanation:** Function calling is foundational to advanced AI applications because it allows LLMs to invoke external functions, APIs, and tools, extending their capabilities far beyond text generation. This is how you build AI agents.

---

### Question 6
When writing an effective prompt, which approach is generally better?

**Answer Choices:**
- A) Vague instructions to let the AI be creative
- B) Specific, direct instructions with clear requirements and constraints
- C) Using technical jargon to sound professional
- D) Asking multiple questions at once

**Correct Answer:** B

**Explanation:** Specific, direct instructions with clear requirements eliminate ambiguity and produce better results. Vague prompts lead to vague outputs.

---

### Question 7
In the job posting parser project, what is the main benefit of using JSON mode or function calling?

**Answer Choices:**
- A) The AI can parse longer job postings
- B) You get reliable, structured data that can be directly inserted into a database
- C) It's free to use
- D) It automatically validates the job posting

**Correct Answer:** B

**Explanation:** Using JSON mode or function calling for the job posting parser ensures you get structured data in a predictable format that can be easily validated and inserted into databases.

---

### Question 8
What does "role prompting" mean in the context of AI prompts?

**Answer Choices:**
- A) Assigning the AI a specific role or expertise (e.g., "You are an expert Python developer") to activate relevant training data
- B) Defining user roles and permissions in your application
- C) Using role-based access control for API keys
- D) Switching between different AI models based on the task

**Correct Answer:** A

**Explanation:** Role prompting assigns the AI a specific expertise or role (like 'expert Python developer') which helps activate relevant training data and sets appropriate tone and depth for responses.

---

## Week 3: Claude Code Part 1

### Question 1
What is the major paradigm shift from Weeks 1-2 (APIs) to Week 3 (Claude Code)?

**Answer Choices:**
- A) From Python to JavaScript
- B) From calling AI APIs directly to using an agentic tool that can read files, edit code, and iterate
- C) From local development to cloud deployment
- D) From command-line to web interfaces

**Correct Answer:** B

**Explanation:** Week 3 introduces a major shift from calling AI APIs directly to using Claude Code—an agentic tool that can read files, edit code, run commands, and iterate on its own work. This is your first exposure to AI as a collaborator, not just a function you call.

---

### Question 2
What is the purpose of CLAUDE.md in a project?

**Answer Choices:**
- A) It's a Markdown file for project notes
- B) It documents API keys and secrets
- C) It serves as a system prompt for your codebase, telling Claude Code about your project's architecture, conventions, and requirements
- D) It's a configuration file for the Claude CLI

**Correct Answer:** C

**Explanation:** CLAUDE.md serves as a system prompt for your codebase. It tells Claude Code about your project's overview, architecture, coding conventions, common commands, areas requiring caution, and testing requirements. Think of it as context that helps Claude work more effectively with your project.

---

### Question 3
What does the /plan slash command do in Claude Code?

**Answer Choices:**
- A) Immediately executes code changes
- B) Creates a multi-step plan, waits for your approval, then executes step by step
- C) Plans project architecture without implementation
- D) Generates documentation only

**Correct Answer:** B

**Explanation:** The /plan command creates a multi-step plan, proposes it to you for review, waits for approval, and then executes the plan step by step. This prevents chaos and ensures you're aligned with Claude's approach before execution begins.

---

### Question 4
When should you use plan mode in Claude Code?

**Answer Choices:**
- A) For all changes, no matter how small
- B) Only for documentation updates
- C) For complex features, refactoring, or anything that touches multiple files
- D) Never use plan mode; direct editing is always better

**Correct Answer:** C

**Explanation:** Plan mode is best for complex features, major refactoring, or anything that touches multiple files. Skip it for simple bug fixes, single-file changes, or small additions where the scope is clear and limited.

---

### Question 5
Which of the following is a core slash command in Claude Code?

**Answer Choices:**
- A) /execute
- B) /edit
- C) /compile
- D) /deploy

**Correct Answer:** B

**Explanation:** /edit is one of the core slash commands in Claude Code for making targeted changes to files. Other core commands include /add, /ask, /debug, /test, and /plan.

---

### Question 6
When contributing to open source with Claude Code, what is the most important principle to remember?

**Answer Choices:**
- A) Claude Code automatically reviews all code
- B) You're still responsible for every change—you must understand and be ready to defend all code in the PR
- C) Open source maintainers prefer AI-generated code
- D) No testing is needed for AI-generated contributions

**Correct Answer:** B

**Explanation:** Claude Code wrote the code, but you're the one submitting the PR. You must understand every change and be ready to defend it in code review. This is Discernment from the 4 D's in action—critically evaluating AI output.

---

### Question 7
What should a good CLAUDE.md file include?

**Answer Choices:**
- A) Only the project name and description
- B) Project overview, architecture, coding conventions, common commands, testing requirements, and areas requiring caution
- C) Just the installation instructions
- D) Only error messages and troubleshooting

**Correct Answer:** B

**Explanation:** A comprehensive CLAUDE.md includes: project overview and purpose, architecture and key components, coding conventions and style guide, common commands and setup instructions, areas where Claude should be cautious, and testing requirements.

---

### Question 8
What is a key takeaway about Claude Code from Week 3?

**Answer Choices:**
- A) Claude Code is a magic button that requires no human oversight
- B) Claude Code is a collaborator—you still need to guide it, review its work, and intervene when needed
- C) Claude Code only works with Python projects
- D) Claude Code should never be used for production code

**Correct Answer:** B

**Explanation:** Claude Code is a collaborator, not a magic button. You still need to guide it, review its work, and intervene when needed. It's a powerful tool, but human judgment and oversight remain essential.

---

## Week 4: OpenAI Codex (CLI + Cloud)

### Question 1
What is the end-of-month-1 milestone achievement by Week 4?

**Answer Choices:**
- A) Learning only one AI tool
- B) Building simple scripts only
- C) Going from zero to building real applications with AI—calling APIs, writing effective prompts, using Claude Code, and contributing to open source
- D) Completing a college degree

**Correct Answer:** C

**Explanation:** By Week 4, you've completed Month 1 and gone from zero to building real applications with AI. You can call APIs, write effective prompts, use Claude Code, and contribute to open source. Next month, you'll build increasingly complex systems.

---

### Question 2
Why should you build a comparison matrix of AI coding tools?

**Answer Choices:**
- A) It's required for certification
- B) In interviews, a nuanced answer comparing tools with specific examples shows depth; generic answers like "I use ChatGPT" don't differentiate you
- C) To prove one tool is always superior
- D) Just for personal record keeping

**Correct Answer:** B

**Explanation:** In interviews, you'll be asked 'What AI tools do you use?' A nuanced answer comparing tools with specific examples shows depth and differentiation. Generic answers like 'I use ChatGPT' don't stand out. Your comparison matrix becomes your cheat sheet for thoughtful responses.

---

### Question 3
What are key evaluation dimensions when comparing AI coding tools?

**Answer Choices:**
- A) Only the price
- B) Setup complexity, code quality, context awareness, speed, cost, iteration ease, and best use cases
- C) Just the user interface design
- D) Only which company made it

**Correct Answer:** B

**Explanation:** When comparing AI coding tools, evaluate: setup complexity (ease of getting started), code quality (suggestion quality), context awareness (project understanding), speed (response latency), cost (pricing/subscriptions), iteration (ease of refinement), and best use cases (when to use each tool).

---

### Question 4
When should you use OpenAI Codex Cloud vs. CLI?

**Answer Choices:**
- A) Always use Cloud for everything
- B) Use CLI for quick edits and local development with tight feedback loops; use Cloud for large refactors, research tasks, and complex features spanning multiple files
- C) Never use Cloud, CLI is always better
- D) It doesn't matter; they're identical

**Correct Answer:** B

**Explanation:** Use CLI when you need quick edits, local development, and a tight feedback loop. Use Cloud when handling large refactors, research tasks, complex features spanning multiple files, or when you need longer context windows and persistent sessions.

---

### Question 5
What is a critical step when delegating a complex task to an AI agent?

**Answer Choices:**
- A) Give vague instructions and let AI figure it out
- B) Write a detailed spec with features, tech stack preferences, edge cases, and testing requirements; set checkpoints for review
- C) Never review the output until it's completely done
- D) Just say "make it work" and walk away

**Correct Answer:** B

**Explanation:** Effective delegation requires a detailed spec (2-3 paragraphs) describing features, tech stack preferences, edge cases, and testing requirements. Set checkpoints like 'After completing the basic structure, show me the code for review before proceeding.' Don't let AI work for hours without review.

---

### Question 6
What does OpenAI Codex Cloud offer that CLI doesn't?

**Answer Choices:**
- A) Faster execution speed
- B) Longer context windows, persistent sessions, async execution, and collaboration features
- C) Lower cost
- D) Better code quality

**Correct Answer:** B

**Explanation:** OpenAI Codex Cloud offers longer context windows (can handle larger codebases), persistent sessions (maintains state), async execution (work on tasks while you do other things), and collaboration features (share sessions with team members).

---

### Question 7
What is a key requirement for Project 1 (polished CLI tool or web app)?

**Answer Choices:**
- A) It just needs to run once without errors
- B) Comprehensive README with screenshots/demo, installation instructions, architecture overview, automated tests, and a reflection on the development process
- C) Only the code files, no documentation
- D) Just upload to GitHub without testing

**Correct Answer:** B

**Explanation:** Project 1 requires portfolio-quality work: all features working without errors, clean readable code, comprehensive README with screenshots/demo, installation and setup instructions, architecture overview, automated tests, and a reflection section describing which AI tools you used and your development process.

---

### Question 8
What's a key takeaway about AI tool selection from Week 4?

**Answer Choices:**
- A) One tool is always best for everything
- B) No single tool is best for everything—each AI coding tool has strengths and ideal use cases
- C) Always use the most expensive tool
- D) Tools don't matter; only the developer matters

**Correct Answer:** B

**Explanation:** No single tool is best for everything. Each AI coding tool has strengths and ideal use cases. Understanding when to use which tool—based on task complexity, speed requirements, quality needs, and context—makes you fluent in AI-assisted development.

---

## Week 5: Skills & Subagents

### Question 1
What are Skills in the context of Claude Code?

**Answer Choices:**
- A) Programming languages Claude understands
- B) Reusable, shareable capabilities that extend what Claude Code can do—like plugins or macros for your AI assistant
- C) Error messages that Claude generates
- D) Data structures in Python

**Correct Answer:** B

**Explanation:** Skills are reusable, shareable capabilities that extend what Claude Code can do. Think of them as plugins or macros for your AI assistant—pre-defined workflows that Claude Code can execute to maximize productivity.

---

### Question 2
What makes a good Skill?

**Answer Choices:**
- A) It only works once and is complex
- B) Reusable (solves repeated problems), well-defined (clear inputs/outputs), composable (combines with other skills), and documented
- C) It requires manual configuration every time
- D) It has no documentation

**Correct Answer:** B

**Explanation:** A good Skill should be: Reusable (solves a problem you encounter repeatedly), Well-defined (clear inputs and outputs), Composable (can combine with other skills), and Documented (clear description and usage examples). These qualities make Skills valuable and maintainable.

---

### Question 3
What are Subagents?

**Answer Choices:**
- A) Bugs in the agent code
- B) Specialized AI instances that handle specific parts of a complex task—an introduction to agent orchestration
- C) Helper functions for debugging
- D) Backup copies of the main agent

**Correct Answer:** B

**Explanation:** Subagents are specialized AI instances that handle specific parts of a complex task. This is your introduction to agent orchestration—a hot topic in AI development where multiple specialized agents collaborate on complex workflows.

---

### Question 4
Why use multiple agents instead of a single agent?

**Answer Choices:**
- A) It's always faster
- B) Separation of concerns, specialized expertise, checks and balances, and parallel processing benefits
- C) To make the system more complicated
- D) Single agents are always better

**Correct Answer:** B

**Explanation:** Multiple agents offer: Separation of concerns (each has a specific role), Expertise (agents can have specialized knowledge), Checks and balances (one creates, another critiques), and Parallel processing (multiple agents can work simultaneously). Single agents struggle with complex workflows.

---

### Question 5
What is the "Sequential Pipeline" orchestration pattern?

**Answer Choices:**
- A) All agents work at the same time without coordination
- B) Agent 1 → Agent 2 → Agent 3, where each agent passes its output to the next in a linear chain
- C) Random agent selection
- D) Agents never communicate

**Correct Answer:** B

**Explanation:** In a Sequential Pipeline, Agent 1 → Agent 2 → Agent 3, where each agent passes its output to the next. For example: Researcher → Writer → Editor. This is one of the common orchestration patterns for multi-step workflows.

---

### Question 6
In a multi-agent Research Report Generator, which agent role synthesizes information into an outline?

**Answer Choices:**
- A) Researcher Agent
- B) Analyst Agent
- C) Writer Agent
- D) Critic Agent

**Correct Answer:** B

**Explanation:** The Analyst Agent receives research findings, identifies key themes and patterns, and structures information into an outline. It sits between the Researcher (who gathers data) and the Writer (who creates prose).

---

### Question 7
What is a key component of a Skill?

**Answer Choices:**
- A) Only the skill name
- B) Trigger (when to activate), Instructions (what to do), Context (what information needed), and Output (result format)
- C) Just random code snippets
- D) A single line of documentation

**Correct Answer:** B

**Explanation:** A Skill has four key components: Trigger (when should this skill activate?), Instructions (what should Claude do?), Context (what information does it need?), and Output (what format should the result take?). These components define how the skill operates.

---

### Question 8
Why is understanding agent orchestration valuable for interviews?

**Answer Choices:**
- A) It's not valuable for interviews
- B) Very few students understand agent orchestration at this level—it's a fundamental pattern in modern AI systems and makes you conversant with cutting-edge AI architecture
- C) Everyone already knows it
- D) Interviewers never ask about it

**Correct Answer:** B

**Explanation:** Very few students understand agent orchestration at this level. These concepts apply beyond Claude—agent orchestration is a fundamental pattern in modern AI systems. Understanding it makes you conversant with cutting-edge AI architecture, which is impressive in interviews.

---

## Week 6: Chatbot + RAG

### Question 1
What does RAG stand for and what is its purpose?

**Answer Choices:**
- A) Random AI Generation for creating random content
- B) Retrieval-Augmented Generation, which solves LLM limitations by retrieving relevant documents, augmenting prompts with context, and generating grounded responses
- C) Rapid Application Generator for faster coding
- D) Real-time AI Gateway for API management

**Correct Answer:** B

**Explanation:** RAG stands for Retrieval-Augmented Generation. It solves LLM limitations through a three-step process: (1) Retrieve relevant documents or passages, (2) Augment the prompt by adding that context, (3) Generate responses with grounded, factual information.

---

### Question 2
What problems does RAG solve with LLMs?

**Answer Choices:**
- A) Only speed issues
- B) Static knowledge (training cutoff date), no access to private data (your documents/company data), and hallucination (making up facts)
- C) Just memory limitations
- D) Only cost problems

**Correct Answer:** B

**Explanation:** RAG solves three major LLM problems: Static knowledge (training data has a cutoff date), No private data access (can't know about your documents, codebase, or company data), and Hallucination (will confidently make up facts when it doesn't know).

---

### Question 3
What are embeddings in the context of RAG?

**Answer Choices:**
- A) Images embedded in documents
- B) Vector representations of text where similar concepts are close together in vector space
- C) Database tables
- D) CSS styles for text

**Correct Answer:** B

**Explanation:** Embeddings are vector representations of text. Similar concepts are close together in vector space—'dog' and 'puppy' have similar embeddings, while 'dog' and 'blockchain' have very different embeddings. This enables semantic search.

---

### Question 4
What is the typical RAG implementation process?

**Answer Choices:**
- A) Just send documents directly to LLM
- B) Split docs into chunks → Generate embeddings → Store in vector DB → When user asks: embed question, find similar chunks, include in prompt
- C) Store everything in SQL database
- D) No processing needed

**Correct Answer:** B

**Explanation:** The RAG process: Split documents into chunks → Generate embeddings for each chunk → Store embeddings in a vector database → When user asks a question: embed the question, find chunks with similar embeddings (cosine similarity), include those chunks in the prompt.

---

### Question 5
Why is streaming important for chatbot UX?

**Answer Choices:**
- A) It's not important; users prefer waiting
- B) Streaming improves perceived performance—users prefer seeing incremental progress over waiting for complete responses
- C) It only reduces costs
- D) Streaming has no real benefit

**Correct Answer:** B

**Explanation:** Streaming displays tokens as they arrive (not all at once), providing better perceived performance. Users prefer seeing incremental progress over waiting for complete responses. Users can also stop generation mid-stream if needed.

---

### Question 6
What is Chroma in the context of Week 6?

**Answer Choices:**
- A) A color scheme for UIs
- B) A vector database that's easy to use with no server needed, perfect for storing and querying embeddings
- C) A web browser
- D) A CSS framework

**Correct Answer:** B

**Explanation:** Chroma is a vector database that's easy to use with no server needed, making it perfect for RAG applications. It stores embeddings with metadata and enables efficient similarity search to retrieve relevant document chunks.

---

### Question 7
Why is chunk size important in RAG?

**Answer Choices:**
- A) Chunk size doesn't matter at all
- B) Too small loses context; too large wastes tokens and dilutes relevance. Finding the right balance (500-1000 tokens) is crucial
- C) Always use the largest chunks possible
- D) Always use 1-word chunks

**Correct Answer:** B

**Explanation:** Chunk size significantly impacts RAG performance. Too small chunks lose context and coherence. Too large chunks waste tokens and dilute relevance. The typical sweet spot is 500-1000 tokens with some overlap to maintain context continuity.

---

### Question 8
What's a key principle when building purpose-driven chatbots?

**Answer Choices:**
- A) Make it as generic as possible
- B) Purpose-driven chatbots are more valuable—specialized tools stand out while generic assistants are commoditized
- C) Copy ChatGPT exactly
- D) Don't focus on specific use cases

**Correct Answer:** B

**Explanation:** Purpose-driven chatbots are more valuable than generic ones. Generic assistants like ChatGPT are commoditized—everyone has access. Specialized tools that solve specific problems stand out and provide genuine value by being tailored to particular use cases.

---

## Week 7: MCP (Model Context Protocol)

### Question 1
What is MCP (Model Context Protocol)?

**Answer Choices:**
- A) A programming language
- B) A standardized protocol for connecting AI models to external data sources and tools—think of it as USB for AI
- C) A database management system
- D) A web framework

**Correct Answer:** B

**Explanation:** MCP (Model Context Protocol) is a standardized protocol for connecting AI models to external data sources and tools. Think of it as USB for AI—a universal interface that lets Claude connect to anything through a standardized, reusable protocol.

---

### Question 2
Why is MCP knowledge valuable on your resume?

**Answer Choices:**
- A) Everyone knows it already
- B) MCP is new (2025) and strategically important to Anthropic. Most developers don't know it yet, making you an early adopter who understands modern AI architecture
- C) It's required by law
- D) It's not valuable

**Correct Answer:** B

**Explanation:** MCP is new (launched in 2025) and strategically important to Anthropic. Most developers haven't heard of it yet, which makes you an early adopter. Being able to say 'I built custom MCP servers' signals you're ahead of the curve and understand modern AI architecture.

---

### Question 3
What do MCP servers expose?

**Answer Choices:**
- A) Only database connections
- B) Resources (read-only data) and Tools (actions the AI can perform)
- C) Just HTML pages
- D) Only error messages

**Correct Answer:** B

**Explanation:** MCP servers expose two types of capabilities: Resources (read-only data like files, database records, API responses) and Tools (actions the AI can perform like creating files, sending emails, running queries). This separation enables secure, controlled access.

---

### Question 4
How does MCP compare to function calling?

**Answer Choices:**
- A) They're identical
- B) Function calling is one-off and custom per app; MCP is standardized, reusable, discoverable, and composable—function calling + a universal protocol
- C) Function calling is always better
- D) MCP doesn't support functions

**Correct Answer:** B

**Explanation:** Function calling is one-off and requires custom implementations per app. MCP is standardized (same protocol everywhere), reusable (one server works across contexts), discoverable (clients can query capabilities), and composable (servers work together). MCP is essentially function calling + a universal protocol.

---

### Question 5
What capabilities does the Filesystem MCP Server provide?

**Answer Choices:**
- A) Only reading files
- B) Read files/directories, search by name or content, watch for changes, and create/edit/delete files (with permission)
- C) Nothing useful
- D) Just formatting code

**Correct Answer:** B

**Explanation:** The Filesystem MCP Server gives Claude access to your filesystem with permissions: read files and directories, search for files by name or content, watch for file changes, and create/edit/delete files (with explicit permission). It enables powerful file-based workflows.

---

### Question 6
What are the key components of an MCP server?

**Answer Choices:**
- A) Only database connections
- B) Server Manifest (declares capabilities), Resource Handlers (return data), Tool Handlers (perform actions), and Initialization (setup/auth)
- C) Just HTML templates
- D) Only CSS files

**Correct Answer:** B

**Explanation:** An MCP server has four key components: Server Manifest (declares available resources, tools, and prompts), Resource Handlers (functions that return data), Tool Handlers (functions that perform actions), and Initialization (setup, authentication, configuration). Together these enable full MCP functionality.

---

### Question 7
What is a major advantage of MCP?

**Answer Choices:**
- A) Makes everything slower
- B) MCP eliminates integration boilerplate—you don't write integration code, just connect servers. Focus on what to connect, not how to wire it
- C) Requires more manual configuration
- D) Only works with one programming language

**Correct Answer:** B

**Explanation:** MCP's major advantage is eliminating integration boilerplate. You don't write custom integration code—you just connect servers. MCP handles all the plumbing (discovery, invocation, error handling), letting you focus on what to connect, not how to wire everything together.

---

### Question 8
What does the GitHub MCP Server enable?

**Answer Choices:**
- A) Only viewing repository names
- B) List repos/issues/PRs, read files from any branch, create issues and PRs, comment on PRs, and search code across repos
- C) Just git commands
- D) Nothing useful

**Correct Answer:** B

**Explanation:** The GitHub MCP Server connects Claude to GitHub repositories: list repos/issues/pull requests, read file contents from any branch, create issues and PRs, comment on PRs, and search code across repositories. This enables powerful GitHub automation workflows through Claude.

---

## Week 8: Agents & OpenClaw

### Question 1
What is an agent in the context of AI systems?

**Answer Choices:**
- A) Just another chatbot
- B) An AI system that can perceive its environment, make decisions, and take actions to achieve goals—autonomously and iteratively
- C) A database connector
- D) A web server

**Correct Answer:** B

**Explanation:** An agent is an AI system that can perceive its environment, make decisions, and take actions to achieve goals—autonomously and iteratively. Unlike simple tools, agents can work through multi-step problems with minimal human intervention.

---

### Question 2
What is the "Think-Act-Observe" loop?

**Answer Choices:**
- A) A programming language
- B) Think (analyze and decide what to do), Act (execute an action), Observe (see results), Repeat until goal achieved or stopping condition met
- C) A database query pattern
- D) A user interface design principle

**Correct Answer:** B

**Explanation:** The Think-Act-Observe loop is the core of agent operation: (1) Think - analyze the current state and decide what to do next, (2) Act - execute an action (call API, run command, write file), (3) Observe - see the results of the action, (4) Repeat - continue until the goal is achieved or stopping condition is met.

---

### Question 3
How do agents differ from tools like Claude Code?

**Answer Choices:**
- A) They're exactly the same
- B) Tools are human-in-the-loop with step-by-step approval; Agents are autonomous with multi-step execution and minimal human intervention
- C) Agents are slower
- D) Tools are always better

**Correct Answer:** B

**Explanation:** Tools like Claude Code are human-in-the-loop, requiring step-by-step approval for actions. Agents are autonomous, executing multi-step workflows with minimal human intervention. This autonomy makes agents powerful but also requires careful design for safety.

---

### Question 4
Why is understanding AI limitations crucial when building agents?

**Answer Choices:**
- A) It's not important
- B) Agents are autonomous and make decisions without constant oversight—understanding limitations is critical for designing safe, reliable systems and knowing when to add guardrails
- C) AI has no limitations
- D) Humans don't need to understand AI

**Correct Answer:** B

**Explanation:** Agents are autonomous—they make decisions without constant human oversight. Understanding AI's limitations (where it struggles with math, reasoning, consistency, novel problems) is critical for designing safe, reliable agent systems. You need to know when to trust an agent and when to add guardrails or human checkpoints.

---

### Question 5
What is a common agent failure mode?

**Answer Choices:**
- A) Working too well
- B) Looping (repeating same action endlessly), Hallucination (claiming actions it didn't take), Tool misuse, Premature completion, or Excessive steps
- C) Being too fast
- D) Using too little memory

**Correct Answer:** B

**Explanation:** Common agent failure modes include: Looping (repeating same action endlessly), Hallucination (claiming to have taken actions it didn't), Tool misuse (wrong tool or malformed arguments), Premature completion (answering before gathering enough info), and Excessive steps (overthinking simple questions). Debugging requires logging and inspection.

---

### Question 6
What is "blast radius" in the context of agent security?

**Answer Choices:**
- A) How fast the agent runs
- B) The potential scope of damage if an agent malfunctions or is misused—controlling permissions limits blast radius
- C) The agent's memory usage
- D) Network latency

**Correct Answer:** B

**Explanation:** Blast radius is the potential scope of damage if an agent malfunctions or is misused. For example, an agent with full filesystem access has a larger blast radius than one limited to reading specific directories. Controlling permissions (principle of least privilege) limits blast radius and improves safety.

---

### Question 7
What are essential safety limits for a basic agent implementation?

**Answer Choices:**
- A) No limits needed
- B) Max iterations to prevent infinite loops, timeout to prevent hanging, and logging all actions for debugging and accountability
- C) Only speed limits
- D) Just memory limits

**Correct Answer:** B

**Explanation:** Essential safety limits for basic agents include: Max iterations (e.g., 10) to prevent infinite loops, Timeout (e.g., 60 seconds) to prevent hanging processes, and Logging all actions for debugging, accountability, and understanding agent behavior. These limits prevent runaway agents.

---

### Question 8
What type of agent creates a full plan upfront before executing?

**Answer Choices:**
- A) Reflexive agent
- B) Plan-and-Execute agent
- C) Random agent
- D) Passive agent

**Correct Answer:** B

**Explanation:** Plan-and-Execute agents create a full plan upfront before executing. They analyze the task, propose a complete plan, wait for approval or refinement, then execute step by step. This differs from ReAct (reason before each action) or Reflexive agents (react without explicit planning).

---

## Week 9: Capstone Kickoff

### Question 1
What is the key philosophy behind choosing a capstone project according to Week 9?

**Answer Choices:**
- A) Build the most ambitious project possible with the newest technologies
- B) Quality over quantity - a well-executed, focused project beats an ambitious, half-finished one
- C) Copy existing successful projects to ensure your project works
- D) Focus only on features that look good in demos

**Correct Answer:** B

**Explanation:** The capstone philosophy emphasizes quality over quantity. A well-executed, focused project that's polished and complete is far more valuable than an ambitious project that's only half-finished. This demonstrates professionalism and ability to deliver.

---

### Question 2
When defining your project scope, what is the purpose of explicitly stating "Non-Goals"?

**Answer Choices:**
- A) To make the project look more professional in documentation
- B) To show what features you couldn't implement
- C) To prevent scope creep by explicitly defining what you won't build
- D) To list features you plan to add later

**Correct Answer:** C

**Explanation:** Explicitly stating Non-Goals is critical for preventing scope creep. By clearly defining what you won't build, you protect yourself from adding too many features and losing focus on your core value proposition.

---

### Question 3
According to Week 9, which of these is a suggested capstone direction?

**Answer Choices:**
- A) A mobile game with AI-powered NPCs
- B) Custom MCP Server solving a real problem
- C) A blockchain-based social media platform
- D) An e-commerce website with payment processing

**Correct Answer:** B

**Explanation:** Building a Custom MCP Server is one of the suggested capstone directions because MCP is new and resume-valuable. A well-built server solving a real problem could be used by others and demonstrates understanding of modern AI tooling.

---

### Question 4
Why is creating an architecture document important before building your capstone?

**Answer Choices:**
- A) It's required for GitHub repositories
- B) An hour of planning saves days of refactoring, and it shows engineering maturity in interviews
- C) To make the README look more professional
- D) It helps pass code reviews faster

**Correct Answer:** B

**Explanation:** Architecture documentation is essential because an hour of planning saves days of refactoring. Additionally, in interviews you'll be asked to explain your capstone's design, and a clear architecture shows engineering maturity and systematic thinking.

---

### Question 5
What should your Week 9 milestone goal be?

**Answer Choices:**
- A) Complete the entire project and deploy it
- B) Write comprehensive documentation for all features
- C) Complete architecture and setup, implement core data structures, get one end-to-end flow working
- D) Research all possible technologies and frameworks

**Correct Answer:** C

**Explanation:** Week 9's goal is to complete architecture and setup, implement core data structures, and get one end-to-end flow working (even if minimal). This provides a solid foundation for Week 10's intensive building phase.

---

### Question 6
Which essential file should you add to .gitignore when setting up your project repository?

**Answer Choices:**
- A) README.md
- B) .env
- C) requirements.txt
- D) ARCHITECTURE.md

**Correct Answer:** B

**Explanation:** The .env file should always be in .gitignore because it contains environment variables including API keys and secrets. Accidentally committing this file to version control could expose sensitive credentials.

---

### Question 7
What should be included in your project specification's "Success Criteria"?

**Answer Choices:**
- A) How many GitHub stars you want to get
- B) How do you know it works and what does "done" look like
- C) How many lines of code you plan to write
- D) How many hours you estimate it will take

**Correct Answer:** B

**Explanation:** Success Criteria should define how you know the project works and what 'done' looks like. This provides clear, measurable goals that help you stay focused and know when you've achieved your objectives.

---

### Question 8
According to Week 9, what's the recommended approach for implementation philosophy?

**Answer Choices:**
- A) Build all features simultaneously to save time
- B) Start simple, iterate - get one thing working end-to-end, then expand
- C) Implement the most difficult features first
- D) Focus on UI/UX polish before implementing core functionality

**Correct Answer:** B

**Explanation:** The recommended implementation philosophy is to start simple and iterate - get one thing working end-to-end first, then expand. This approach ensures you always have a working product and can incrementally add complexity.

---

## Week 10: Build

### Question 1
What is the primary philosophy of Week 10 (Build Week)?

**Answer Choices:**
- A) Learn new AI frameworks and tools through tutorials
- B) This is a working week, not a learning week - apply your skills intensively to build
- C) Research best practices and plan for future implementation
- D) Focus on writing comprehensive documentation

**Correct Answer:** B

**Explanation:** Week 10 is a working week, not a learning week. You have the skills from the previous weeks - now you apply them intensively. The focus is on building and implementation, not learning new concepts or tools.

---

### Question 2
According to the feature-by-feature implementation approach, what should you do immediately after implementing a feature?

**Answer Choices:**
- A) Move on to the next feature to maintain momentum
- B) Test manually, handle errors, test edge cases, write tests, document, and commit
- C) Deploy to production immediately
- D) Share it on social media for feedback

**Correct Answer:** B

**Explanation:** The feature-by-feature approach emphasizes completing each feature fully before moving on: implement, test manually, handle errors, test edge cases, write automated tests, document, and commit. This ensures quality and prevents accumulating incomplete work.

---

### Question 3
Why should you leverage your Week 5 custom Skills and Subagents during Build Week?

**Answer Choices:**
- A) To show off your skills to peers
- B) Because they're required for Week 10 assignments
- C) They were designed for exactly this type of intensive development and can accelerate your work
- D) To practice using them before they expire

**Correct Answer:** C

**Explanation:** Your Week 5 custom Skills and Subagents were designed specifically for intensive development work like Build Week. They can accelerate your work through code review, documentation generation, test creation, and multi-agent orchestration patterns.

---

### Question 4
What is the recommended approach regarding quality versus speed during Build Week?

**Answer Choices:**
- A) Speed is everything - complete all features as quickly as possible
- B) A polished 80% is better than a sloppy 100%
- C) Quality doesn't matter yet - focus on quantity of features
- D) Spend equal time on every feature regardless of importance

**Correct Answer:** B

**Explanation:** Quality over speed is crucial - a polished 80% complete project is better than a sloppy 100% complete one. It's better to have fewer features that work well than many features that are buggy or half-baked.

---

### Question 5
When should you ask for help when you're stuck on a problem?

**Answer Choices:**
- A) Immediately - don't waste any time
- B) Never - figure it out yourself
- C) After trying for 30 minutes, or sooner for architecture decisions or security-sensitive code
- D) Only after you've spent at least 3 hours on the problem

**Correct Answer:** C

**Explanation:** The recommendation is to try solving problems yourself for about 30 minutes before asking for help. However, for architecture decisions or security-sensitive code, it's appropriate to ask sooner. This balances learning through struggle with efficient problem-solving.

---

### Question 6
Why is making an open-source contribution important during Week 10?

**Answer Choices:**
- A) It's required to pass the course
- B) It gives back to tools you use, looks great on your resume, and shows you can work with real codebases
- C) To increase your GitHub contribution graph
- D) To practice using Git and GitHub

**Correct Answer:** B

**Explanation:** Open-source contributions during Week 10 serve multiple purposes: giving back to the AI tools you've been using, building your resume with real-world contributions, and demonstrating that you can work with existing codebases - a critical skill for internships.

---

### Question 7
What should you do about technical debt during the 3-week capstone project?

**Answer Choices:**
- A) Avoid it completely by spending more time on each feature
- B) Ignore it - technical debt doesn't matter for small projects
- C) Some debt is okay, but track it with GitHub issues for 'known issues' and 'future improvements'
- D) Fix all technical debt immediately before moving forward

**Correct Answer:** C

**Explanation:** For a 3-week project, some technical debt is acceptable and realistic. The key is to track it by creating GitHub issues for 'known issues' and 'future improvements.' This shows interviewers you understand trade-offs and engineering decisions.

---

### Question 8
What is the target feature completeness goal by the end of Week 10?

**Answer Choices:**
- A) 100% complete with all nice-to-have features
- B) 80%+ feature completeness with all core features working
- C) 50% complete with basic prototype
- D) Just the architecture and planning completed

**Correct Answer:** B

**Explanation:** The goal for Week 10 is 80%+ feature completeness with all core features working. This leaves Week 11 for polish, deployment, documentation, and demo creation rather than scrambling to finish basic functionality.

---

## Week 11: Finish & Write

### Question 1
What is the 80/20 rule of polish according to Week 11?

**Answer Choices:**
- A) 80% of your code should be tested, 20% can be untested
- B) 20% of polish gives 80% of the "wow factor" - focus on first launch, error messages, visual consistency, and performance
- C) Spend 80% of time on features, 20% on documentation
- D) 80% of features should be complete, 20% can remain unfinished

**Correct Answer:** B

**Explanation:** The 80/20 rule states that 20% of polish gives 80% of the wow factor. Focus your polishing efforts on high-impact areas: smooth first launch experience, friendly error messages, consistent visual styling, and acceptable performance. These create the best impression with minimal effort.

---

### Question 2
Why should you create a "Known Issues" section in your README?

**Answer Choices:**
- A) To warn users about bugs so you won't be blamed
- B) It's required for all GitHub projects
- C) It shows maturity - you understand trade-offs and can honestly discuss limitations
- D) To make the README longer and more impressive

**Correct Answer:** C

**Explanation:** Creating a 'Known Issues' section shows maturity and engineering judgment. It demonstrates that you understand trade-offs, can be honest about limitations, and know what you'd improve given more time. Interviewers appreciate this level of self-awareness and transparency.

---

### Question 3
What should be at the very top of your README?

**Answer Choices:**
- A) Installation instructions
- B) Project title, tagline, and a demo (screenshot, GIF, or video link)
- C) License information
- D) Your name and contact information

**Correct Answer:** B

**Explanation:** Your README should lead with the most important information: project title, tagline, and a visual demo (screenshot, GIF, or video). This immediately communicates what your project does and proves it works, capturing attention before diving into details.

---

### Question 4
What is the recommended length for a demo video?

**Answer Choices:**
- A) 30 seconds - keep it very brief
- B) 3-5 minutes with structured sections: intro, tour, features, technical highlights, and conclusion
- C) 10-15 minutes to cover everything in detail
- D) 1 minute - just show the main feature

**Correct Answer:** B

**Explanation:** A demo video should be 3-5 minutes with a structured format: introduction (30s), quick tour (30s), feature demonstrations (2-3 min), technical highlight (30s), and conclusion (30s). This length is long enough to be substantive but short enough to maintain attention.

---

### Question 5
In your technical blog post, what should the "Lessons Learned" section cover?

**Answer Choices:**
- A) Only the successes and achievements
- B) Technical lessons (what worked, what didn't), process lessons, and what you'd do differently next time
- C) A list of all the technologies you used
- D) Why other approaches are inferior to yours

**Correct Answer:** B

**Explanation:** The 'Lessons Learned' section should cover technical lessons (what worked and what didn't), process lessons (planning, time management), and what you'd do differently next time. Being honest about both successes and failures demonstrates growth mindset and reflective thinking.

---

### Question 6
Which hosting platform is recommended for Streamlit apps?

**Answer Choices:**
- A) AWS EC2
- B) Streamlit Cloud
- C) Heroku
- D) DigitalOcean

**Correct Answer:** B

**Explanation:** Streamlit Cloud is the recommended hosting platform for Streamlit applications. It's specifically designed for Streamlit apps, making deployment straightforward. Other platforms like Vercel (Next.js), Render (Python/Docker), Railway (full-stack), and Fly.io are better suited for other types of applications.

---

### Question 7
What should you avoid showing in your demo video?

**Answer Choices:**
- A) Real, interesting examples of your features
- B) Your code or architecture
- C) Bugs, broken features, rambling, or apologizing
- D) The user interface

**Correct Answer:** C

**Explanation:** In your demo video, avoid showing bugs or broken features, rambling or going off-script, and apologizing (e.g., 'sorry this is rough'). Also don't spend too much time on setup/installation. Focus on the happy path and what works well to make the best impression.

---

### Question 8
Why are the Anthropic certificates important to collect and display?

**Answer Choices:**
- A) They look good on your wall
- B) They're required to graduate from the camp
- C) For a student, having 9-10 official Anthropic certificates is rare and provides real, verifiable evidence of your skills
- D) They give you free API credits

**Correct Answer:** C

**Explanation:** For a freshman or sophomore, having 9-10 official Anthropic certificates is striking because most internship applicants have zero. These certificates provide real, verifiable evidence that you've invested in structured learning and understand modern AI systems - valuable credentials for job applications.

---

## Week 12: Resume & Interview Prep

### Question 1
What is the most important section on a resume for AI/ML internship applications?

**Answer Choices:**
- A) Education
- B) Projects (with 3-4 best projects showing specific accomplishments)
- C) Skills
- D) Certifications

**Correct Answer:** B

**Explanation:** The Projects section is the most important for AI/ML internship applications. This is where you demonstrate your practical capabilities through 3-4 well-documented projects with specific accomplishments, metrics, and technical details. Projects prove you can actually build things.

---

### Question 2
How should you write project bullets on your resume?

**Answer Choices:**
- A) List all the technologies you used
- B) Start with action verbs, include metrics, highlight technical decisions, and explain challenges solved
- C) Keep them vague so you can explain in the interview
- D) Focus on team collaboration and soft skills

**Correct Answer:** B

**Explanation:** Project bullets should start with action verbs (Built, Implemented, Designed), include quantifiable metrics where possible (e.g., 'reduced latency by 200ms'), highlight technical decisions made, and explain specific challenges you solved. This shows impact and technical capability.

---

### Question 3
What is a better LinkedIn headline than just "Student at [University]"?

**Answer Choices:**
- A) Looking for internship opportunities
- B) CS Student | AI/ML | Building with Claude, OpenAI APIs | 10 Anthropic Certifications
- C) Aspiring Software Engineer
- D) Computer Science Major

**Correct Answer:** B

**Explanation:** A strong LinkedIn headline communicates your focus, skills, and credentials clearly. 'CS Student | AI/ML | Building with Claude, OpenAI APIs | 10 Anthropic Certifications' immediately tells recruiters what you do and what differentiates you from other students.

---

### Question 4
What is the STAR framework used for in interviews?

**Answer Choices:**
- A) A method for solving coding problems
- B) Situation, Task, Action, Result - a framework for answering behavioral questions
- C) A rating system for interview performance
- D) A technique for negotiating salary

**Correct Answer:** B

**Explanation:** The STAR framework (Situation, Task, Action, Result) is used for answering behavioral interview questions. It provides a structured way to tell stories about your experiences, ensuring you cover context, your specific role, what you did, and the outcomes achieved.

---

### Question 5
What should you pin on your GitHub profile?

**Answer Choices:**
- A) All your repositories
- B) Your best 6 repositories with clean READMEs
- C) Only your capstone project
- D) Your fork of popular open-source projects

**Correct Answer:** B

**Explanation:** You should pin your best 6 repositories on GitHub with clean, professional READMEs. This is what recruiters will see first when they visit your profile, so choose projects that best demonstrate your capabilities and have good documentation.

---

### Question 6
When answering "Tell me about your capstone project" in an interview, what should you cover?

**Answer Choices:**
- A) Only the technical implementation details
- B) Just explain why you're proud of it
- C) Problem, architecture, tech choices, challenges solved, results, and what you'd improve
- D) Focus on how much time you spent on it

**Correct Answer:** C

**Explanation:** When discussing your capstone, cover: the problem and why it matters, your architecture and technology choices, challenges you solved, results or metrics, and what you'd improve given more time. This comprehensive answer demonstrates both technical skills and engineering judgment.

---

### Question 7
What is recommended for staying sharp after the AI Camp ends?

**Answer Choices:**
- A) Take a break from coding to avoid burnout
- B) Focus only on academic coursework
- C) Build one project per month, contribute to OSS, write technical content, and keep learning
- D) Only apply to internships without building new projects

**Correct Answer:** C

**Explanation:** To stay sharp, build one focused project per month, make at least one open-source contribution monthly, write technical blog posts to teach others, and continuously learn about new AI developments. This maintains and grows your skills while building your portfolio and network.

---

### Question 8
What should you include in your 5-minute capstone demo presentation?

**Answer Choices:**
- A) Detailed code walkthrough of every file
- B) Introduction, problem & motivation, demo, technical highlights, and lessons & future plans
- C) Only the demo without any explanation
- D) A list of all challenges you faced during development

**Correct Answer:** B

**Explanation:** A 5-minute capstone demo should include: introduction (name, project name, description), problem & motivation (30-45 sec), live demo of features (2-3 min), technical highlights (architecture, key decisions), and lessons learned plus future plans. This structure tells a complete story efficiently.

---

## Summary Statistics

- **Total Questions:** 96
- **Average Questions per Week:** 8
- **Coverage:** All 12 weeks of curriculum
- **Topics Covered:**
  - Week 1: API setup and 4 D's framework
  - Week 2: Prompting techniques and structured output
  - Week 3: Claude Code and CLAUDE.md
  - Week 4: Tool comparison and project delivery
  - Week 5: Skills and agent orchestration
  - Week 6: RAG architecture and embeddings
  - Week 7: Model Context Protocol (MCP)
  - Week 8: Autonomous agents and safety
  - Week 9: Capstone planning and architecture
  - Week 10: Intensive development strategies
  - Week 11: Deployment and documentation
  - Week 12: Career preparation and presentations
