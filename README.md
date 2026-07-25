# HackVault

HackVault is a command center built for hackathon competitors who are tired of dealing with tool chaos. 

When building projects, teams end up jumping between Claude, ChatGPT, Lovable, GitHub, Figma, and Google Drive. Copy-pasting your prompt or project idea over and over again wastes valuable time, and deadlines often get missed because they are buried in Discord chats or crowded inboxes. 

HackVault fixes this by acting as a single home base to manage your hackathons, team rosters, project briefs, and quick tool handoffs in one place.


## Live Demo

You can check out the live version deployed here:
[https://hack-vault-oj7o-cykbxbth7-himaanishri01-9809s-projects.vercel.app](https://hack-vault-oj7o-cykbxbth7-himaanishri01-9809s-projects.vercel.app)


## The Problem It Solves

Hackathon builders bleed hours across multiple disconnected tools. Every context switch introduces a tax:
* **Alignment Drift:** AI tools receive conflicting project specs because you have to re-explain your concept from scratch every time.
* **Buried Deadlines:** Important registration windows and round submissions get lost in personal inboxes or fast-moving chat channels.
* **Scattered Assets:** Code repositories, design files, and documentation end up scattered across different drives and DMs.

HackVault eliminates this friction by organizing everything into an isolated workspace layer.



## Key Features

* **Workspace Sandbox:** Keeps all your ongoing competitions, tracks, timelines, and team details separated into dedicated blocks.
* **Smart Tool Launcher:** Lets you launch directly into external platforms (Claude, ChatGPT, Gemini, Grok, Manus, Lovable, Figma, Replit) with pre-configured prompts so you never have to re-explain your project setup manually.
* **Submission Vault:** A central repository to store your pitch deck links, documentation, and live prototype URLs per block.
* **Activity & Streak Tracking:** Built-in streak heatmap to keep track of your daily building momentum.
* **Customization Engine:** Includes multiple background themes, card styles, and color palettes so you can configure your command center how you like it.


## MVP Engineering Scope

The core architecture is built around five foundational pillars:
1. **Block Sandbox:** Creating and rendering isolated competition environments.
2. **Context Indexing:** Storing primary concept string arrays, milestones, and team layouts.
3. **Smart Tool Launcher:** Establishing the redirect framework with pre-loaded string context.
4. **Deadline Hooks:** Automated schedule tracking and milestone reminders.
5. **Output Vault:** Persistent asset and document aggregation per block.



## Tech Stack

* **Frontend:** HTML5, Tailwind CSS, Vanilla JavaScript
* **Hosting:** Vercel
