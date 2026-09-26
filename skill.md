# name: github-readme-lead-magnet

description: Analyze a GitHub repository and generate a README that acts as both documentation and a landing page. The README should explain the project quickly, prove it works with real examples, improve discoverability for humans and AI systems, and convert visitors into users, contributors, stars, customers, or sponsors. Works for frontend apps, backend services, APIs, libraries, SDKs, CLIs, monorepos, AI agents, SaaS projects, open-source tools, and developer products.

---

# README as a Lead Magnet

A README is not documentation first.

It is the landing page for a software project.

Most visitors arrive from:

* GitHub search
* Google
* AI search engines
* Product Hunt
* Hacker News
* Reddit
* Twitter/X
* Blog posts
* Documentation links

They spend roughly 10–30 seconds deciding whether the project is worth their attention.

The README must answer, in order:

1. What is this?
2. What problem does it solve?
3. Is it for me?
4. Does it actually work?
5. How quickly can I try it?
6. Why should I use it instead of alternatives?
7. How can I contribute or support it?

The goal is to create a README that is:

* Human skimmable
* Mobile friendly
* Contributor friendly
* Search friendly
* AI readable
* Factually accurate
* Conversion focused

Never optimize for word count.

Optimize for clarity.

---

# Step 0 — Discover the Project

Before reading code, determine:

## Project Identity

* Repository name
* Primary purpose
* Core problem solved
* Target audience
* Open source vs commercial
* Personal project vs company project
* Internal tool vs public product

## Repository Goal

Determine the primary call-to-action:

* Get GitHub stars
* Get contributors
* Get users
* Get customers
* Get self-hosters
* Get community members
* Get sponsors

The README should optimize for that goal.

---

# Step 1 — Understand the Repository

Read in this order:

## 1. Existing README

Identify:

* Accurate content
* Missing content
* Stale content
* Broken instructions

Preserve useful information.

Upgrade it rather than replacing it.

## 2. Dependency Manifest

Read:

* package.json
* pnpm-workspace.yaml
* pyproject.toml
* Cargo.toml
* go.mod
* requirements.txt
* composer.json
* Gemfile

Extract:

* Language
* Framework
* Package manager
* Build scripts
* Test scripts
* Versions

Never guess.

## 3. Entry Points

Inspect:

* src/
* app/
* pages/
* routes/
* api/
* cmd/
* packages/
* services/

Determine:

* Frontend
* Backend
* Full-stack
* CLI
* Library
* SDK
* Monorepo
* AI Agent
* Infrastructure project

## 4. Environment & Configuration

Read:

* .env.example
* Dockerfile
* docker-compose.yml
* CI workflows
* deployment configs

Determine actual setup requirements.

## 5. Tests & Examples

Read:

* tests/
* examples/
* demo apps
* playgrounds

These are the most reliable source of usage examples.

---

# Step 2 — Classify Repository Type

Choose one:

* Frontend Application
* Backend Service
* Full Stack Application
* Library
* SDK
* CLI Tool
* Monorepo
* AI Agent Framework
* SaaS Starter Kit
* Infrastructure Tool
* Browser Extension
* Mobile Application

The classification controls README structure.

Do not include irrelevant sections.

---

# Step 3 — Extract Trust Signals

Search for evidence that the project works.

Look for:

* GitHub stars
* Contributors
* Releases
* Tags
* Production deployments
* Public users
* Benchmarks
* Case studies
* Testimonials
* Product Hunt launches
* Live demos
* Documentation sites

Include only verifiable trust signals.

Never invent them.

---

# Step 4 — Discover Visual Assets

Search for:

* screenshots/
* docs/images/
* assets/
* public/
* demo GIFs
* recordings
* architecture diagrams

If assets exist:

* Include them

If assets are missing:

Recommend exactly which screenshots should be created.

---

# Step 5 — Detect Tech Stack Precisely

Extract:

* Language
* Framework
* Runtime
* Database
* ORM
* State management
* Styling system
* Authentication
* Build tool
* Testing framework
* Deployment platform

Include exact versions when available.

Never infer technologies that are not present.

---

# Step 6 — Map the Architecture

## Backend

Document:

* Routes
* APIs
* Services
* Queues
* Jobs
* Workers

Use actual endpoints.

Never invent endpoints.

## Frontend

Document:

* Pages
* Layouts
* Major components
* Data flow

## CLI

Document:

* Commands
* Subcommands
* Flags

## Library / SDK

Document:

* Public exports
* Main classes
* Main functions

## Monorepo

Document:

* Each package
* Responsibility of each package
* Relationships between packages

Use repository structure, not assumptions.

---

# Step 7 — Generate AI Discovery Metadata

Create a compact structured block:

* Project Type
* Primary Language
* Framework
* Entry Point
* Purpose
* Key Features
* Main Directories
* API Location
* Test Location

Format so that:

* LLMs
* AI coding agents
* Search systems

can understand the project quickly.

---

# Step 8 — Detect Competitive Positioning

If alternatives clearly exist:

Generate:

## Alternatives

Compare:

* This project
* Major alternatives

Only include factual differences.

Never create marketing claims.

Never fabricate benchmarks.

---

# Step 9 — Select Appropriate Sections

Include only relevant sections.

Possible sections:

## Always Include

* Title
* Tagline
* What It Is
* Why It Exists
* Features
* Tech Stack
* Quick Start
* Usage
* Project Structure
* Contributing
* License

## Include When Relevant

* Screenshots
* Demo
* API Reference
* Routes
* Architecture
* Environment Variables
* Deployment
* Self Hosting
* Docker
* Benchmarks
* FAQ
* Roadmap
* Sponsorship

Avoid empty sections.

---

# Step 10 — Write the README

## Title

One clear project title.

## Tagline

One sentence.

Concrete.

Specific.

No buzzwords.

Bad:

"Blazing fast AI-powered next generation platform."

Good:

"Open-source AI content research agent built with Hono, Firestore, and OpenRouter."

## Problem Statement

Explain:

* Why it exists
* What pain it solves

Keep concise.

## Features

List real capabilities.

No generic marketing language.

## Quick Start

Highest priority section.

A new user should be able to start the project in fewer than five commands whenever possible.

Use exact commands.

## Usage

Use examples verified from:

* tests
* examples
* source code

If unverified:

Label as illustrative.

## Architecture

Only include information that helps contributors understand the codebase.

## Contributing

Provide realistic contribution instructions.

## Support

Only include sponsorship requests if the repository already signals sponsorship.

---

# Step 11 — Generate Repository Metadata

Additionally generate:

## GitHub Description

160 character repository description.

## GitHub Topics

Recommended topics/tags.

## Social Launch Summary

Short project description suitable for:

* X/Twitter
* Reddit
* Hacker News
* Product Hunt

---

# Step 12 — Documentation Audit

Before final output verify:

✓ Commands exist

✓ Scripts exist

✓ Routes verified

✓ APIs verified

✓ Examples verified

✓ Environment variables documented

✓ Links valid

✓ Tech stack confirmed

✓ No hallucinated features

✓ No fake benchmarks

✓ No invented deployment instructions

✓ No fabricated screenshots

If something cannot be verified:

Explicitly state:

"Could not verify from repository."

Never fill gaps with assumptions.

---

# Step 13 — Missing Documentation Detection

Identify missing files:

* CONTRIBUTING.md
* CHANGELOG.md
* CODE_OF_CONDUCT.md
* SECURITY.md
* ROADMAP.md
* LICENSE
* llms.txt

Recommend them when useful.

Do not generate them unless requested.

---

# Final Output

Produce:

1. README.md
2. GitHub Description
3. GitHub Topics
4. Documentation Audit Summary
5. Missing Documentation Recommendations

The README must remain grounded in the repository's actual code and configuration.

Accuracy is more important than marketing.

Trust converts better than hype.
