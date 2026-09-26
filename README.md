# Github Readme Generator

Generate a README that acts as both documentation and a landing page. The goal is to help visitors quickly understand the project, verify it works, and take action (star, contribute, self-host, use, or sponsor).

## Process

### 1. Understand the Repository

Read in order:

* Existing README
* Dependency manifests (`package.json`, `pyproject.toml`, `go.mod`, etc.)
* Entry points (`src`, `app`, `routes`, `cmd`, `packages`)
* Config files (`.env.example`, Docker, CI)
* Tests and examples

Never write before understanding the codebase.

### 2. Classify the Project

Determine:

* Frontend
* Backend/API
* Full-stack
* CLI
* Library/SDK
* Monorepo
* AI Agent
* Mobile App
* Infrastructure Tool

Only include sections relevant to the project type.

### 3. Extract Facts

Identify:

* Purpose
* Target users
* Tech stack
* Main features
* Routes/APIs
* Commands
* Public exports
* Deployment methods
* Environment variables
* Trust signals (stars, releases, demos, benchmarks, users)

Never invent information.

### 4. Build the README

Include when relevant:

* Title
* One-line tagline
* What it does
* Why it exists
* Features
* Screenshots/Demo
* Tech Stack
* Architecture
* Quick Start
* Usage Examples
* API / Routes / Commands
* Environment Variables
* Deployment
* Alternatives
* Contributing
* License
* Support/Sponsorship

Avoid empty sections.

### 5. AI Discovery Block

Add a compact machine-readable summary containing:

* Project type
* Language
* Framework
* Entry point
* Purpose
* Main directories
* API location
* Test location

### 6. Generate Extras

Also generate:

* GitHub Description (160 chars)
* Recommended GitHub Topics
* Documentation Audit
* Missing Documentation Recommendations

### 7. Validation

Verify:

* Commands exist
* Scripts exist
* Routes are real
* APIs are real
* Examples are valid
* Links work
* Tech stack is confirmed

If something cannot be verified, explicitly say so.

Never hallucinate features, benchmarks, screenshots, deployment steps, routes, APIs, or integrations.

## Output

Return:

1. README.md
2. GitHub Description
3. GitHub Topics
4. Documentation Audit
5. Missing Documentation Recommendations

Accuracy over marketing. Trust over hype.
