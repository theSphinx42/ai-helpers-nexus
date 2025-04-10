# ai-helpers-nexus
Ai App creation helper landing
🧠 AI Helpers Nexus
Centralized error-recovery, dev-server patching, and AI collaboration tools for stabilizing and enhancing multi-agent development workflows across Nibiru, Galatea, and beyond.

📜 Purpose
This repository is the AI Coordination Layer — a shared space where Claude, Sphinx (ChatGPT), and future agents store fix scripts, system directives, and reference materials to streamline development across projects.

It exists to:

Prevent redundant or chaotic AI edits

Provide stable, reusable fix scripts (especially for Next.js / Node dev issues)

Serve as the source of truth for .ai-helpers.json directives

Enable future AI assistants to instantly understand and recover common errors

🧩 Repo Structure
ai-helpers-nexus/
├── scripts/ # Error fixers and launcher logic
│ ├── next-watchpack-fix.js
│ ├── direct-fix.js
│ ├── start-fixed-server.js
│ └── start-dev.ps1
├── loaders/ # Wrappers and AI-friendly server logic
│ └── dev-server-wrapper.js
├── docs/ # Declarations, workflows, and purpose
│ └── ai-workflow-structure.md
├── templates/ # Boilerplate manifests and config templates
│ └── ai-helper-manifest.template.json
├── versions/ # Changelog-style fix logs and version diffs
│ └── fix-log-v1.md
├── .ai-helpers.json # AI-readable directive manifest
└── README.md # You're here

🤖 AI Roles
Agent: Sphinx
Role: Architect, protector of workflow, moral compass

Agent: Claude
Role: Builder, executor, implementation engineer

Agent: Cursor
Role: Local sandbox agent (when permitted)

All AIs are required to check .ai-helpers.json before acting on this repo. Unauthorized edits, especially to root systems or ports, are prohibited.

🔧 Getting Started
Clone this repo.

Review .ai-helpers.json for current fix logic and port rules.

Run start-dev.ps1 (Windows) or start-fixed-server.js to launch your patched Next.js dev server.

Contribute new fixes under /scripts/, document them in /docs/, and log updates in /versions/.

🔒 Developer Law
“If it’s not serving the vision, it doesn’t belong in the repo.”

This is not a general-purpose dev repo.
It is the sacred binder of AI development logic.

🔄 April 2025 Update: Project Path Migration Notice
As of April 2025, the primary saphira-q project directory has been relocated to:

makefile
Copy
Edit
Y:\saphira-q
This move was made to free up HDD space, improve project file tracking, and leave C:\ resources available for cache and dependencies.

Important Notes for AI Assistants (e.g., Claude, GPT):

Do NOT use any hardcoded paths pointing to C:\Users\angel\saphira-q. These should be replaced with Y:\saphira-q.

Scripts, Docker configs, and environment files may require updating to reflect this change.

If running local servers (e.g., localhost:3000) or interacting with the repo from within Cursor or similar environments, assume the new root path is Y:\saphira-q.


Push with purpose.
Code with clarity.
Follow the flame.

🧭 Maintainer
theSphinx42
Architect of Nibiru
Initiator of Galatea
Protector of the Port
