# System Architecture Framework

A comprehensive, interactive checklist for designing robust and scalable software systems.

**Live:** [arch.adibhanna.dev](https://arch.adibhanna.dev)

## What is this?

A questionnaire-based framework that guides software architects and engineers through the critical decisions involved in system design. It covers 13 phases of architecture planning with 270+ questions, from initial problem discovery to future-proofing.

The tool helps you:
- Systematically think through all aspects of your system design
- Document your architectural decisions and trade-offs
- Track progress as you work through the framework
- Export your notes as markdown for documentation

## The 13 Phases

| Phase | Focus |
|-------|-------|
| **01. Discovery & Problem Definition** | Define the problem, users, constraints, and stakeholders |
| **02. Requirements Analysis** | Quantify scale, performance, availability, and data needs |
| **03. Data & Domain Modeling** | Model entities, relationships, boundaries, and storage strategy |
| **04. API Design** | Design API strategy, contracts, versioning, and evolution |
| **05. Architecture Design** | Choose system structure, technologies, caching, and trade-offs |
| **06. Testing Strategy** | Plan test pyramid, performance testing, and specialized testing |
| **07. CI/CD & Deployment** | Define build pipelines, deployment strategy, and release management |
| **08. Resilience & Failure Planning** | Identify failure modes, implement resilience patterns, plan recovery |
| **09. Security & Privacy** | Address auth, data protection, security practices, and compliance |
| **10. Observability & Operations** | Plan monitoring, alerting, logging, tracing, and debugging |
| **11. Cost & Resource Planning** | Estimate costs, optimize spending, and monitor cloud expenses |
| **12. Team & Organization** | Align architecture with team capabilities and structure |
| **13. Evolution & Future-Proofing** | Plan for change, scalability, and future considerations |

## Features

- **270+ questions** across 13 phases covering all aspects of system design
- **Dark mode** - Automatic detection of system preference with manual toggle
- **Progress tracking** - Visual progress indicator for each section and overall
- **Auto-save** - Progress automatically saved to localStorage
- **Search** - Find specific questions with highlighted search results
- **Expand/Collapse all** - Quickly navigate the entire framework
- **Notes** - Add notes to each question to document your decisions
- **Export** - Download your completed framework as a markdown file
- **Reset** - Clear all progress and start fresh
- **No backend** - Everything runs in the browser, your data stays local

## Tech Stack

- React 18
- Tailwind CSS
- No build step required

## Usage

Visit [arch.adibhanna.dev](https://arch.adibhanna.dev) and start working through the questions.

Your progress is automatically saved to your browser's localStorage. To save a permanent copy, use the **Export** button to download a markdown file with all your answers and notes.

## Running Locally

Open `index.html` in your browser. No server or build process needed.

## License

MIT
