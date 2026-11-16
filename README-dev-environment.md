# Development Environment Guide

## GitHub Copilot in the Cloud Development labs

This Codespace supports your learning in Level 5 Cloud Development. **You are the developer**: you are responsible for writing, debugging, testing, deploying and explaining your own application.

The repository provides **one Cloud Development Tutor** custom agent. It can use specialist skills as needed, so you do not need to switch between FastAPI, Database, Git, Testing, CI/CD, Deployment or Postman agents.

## Getting help

Open GitHub Copilot Chat in VS Code/Codespaces and select **Cloud Development Tutor** in the agent picker. Ask normal questions; the tutor can draw on skills for Python, FastAPI, API design, databases (SQLite, PostgreSQL, MariaDB/MySQL and SQL Server), Postman, Git, CI/CD, security, deployment, debugging, testing and more.

Useful prompts:

- “Why is my FastAPI endpoint returning 422? Explain what to inspect without writing the fix.”
- “My SQL Server foreign key insert fails; what evidence should I check?”
- “Why does this GitHub Actions job fail only in CI?”
- “How do Postman environment variables work for localhost and deployed APIs?”
- “Review the approach in my existing code and suggest debugging steps.”

## What Copilot **may** generate

The current assessment permits two specific kinds of generated artefact:

**Automated tests:** You may ask the tutor to write complete unit and integration tests, test-only fixtures/mocks, API/authorisation checks and Postman automated test scripts for behaviour you have specified or implemented. **You must inspect, run and understand these tests.** The tutor must not change your application code to make tests pass or weaken assertions to hide bugs.

**Your project README:** You may ask the tutor to create or improve your project's `README.md` using evidence from the actual repository. Check that setup instructions, example usage and claims about deployment and tests are correct. Do not replace the lab's tutor-written exercise README; that contains the instructions for the practical.

The tutor may also explain concepts, interpret errors, suggest checks and discuss broad project ideas and options.

## What Copilot **must not** generate

Do not ask it to write or replace:

- Application code, FastAPI routes, CRUD logic, database models or SQL implementations.
- Authorisation, validation, error handling or third-party integration code.
- Dockerfiles, deployment scripts, GitHub Actions workflows or other deployment configuration.
- The assessed requirements, endpoint design, architecture diagrams or decision rationale.
- Your assessed report, evaluation, conclusions or personal reflections.

You must make and justify your own implementation and design decisions. If the tutor suggests prohibited code, do not use it; ask instead for an explanation or a diagnostic hint.

## Inline suggestions and limitations

The workspace disables Copilot inline code suggestions while allowing Copilot Chat. This and the custom instructions **guide behaviour but cannot guarantee** that every AI interface complies. Follow the assignment's academic-integrity requirements regardless of what a tool offers.

## Verification and GenAI declaration

Review, run and verify any permitted tests or README content before retaining it. Explain your own decisions and never claim a test or deployment succeeded if it was not checked.

**Record GenAI assistance in the required assignment declaration appendix**, including concept explanations, debugging, test generation and README generation. Declare the tool/model when shown, the use, what you retained and how you reviewed it. A declaration does not make prohibited use acceptable.

Never paste passwords, tokens, API keys or sensitive personal information into Copilot.

## Further help

Your lecturer, lab resources and peers remain available. Use the tutor for understanding and verification, not as a substitute for your own engineering judgement.
