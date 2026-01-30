# IBM Dev Day AI Demystified Hackathon

> **Theme**: AI Demystified — From idea to deployment

## Team Members
| Name | Role | GitHub |
|------|------|--------|
| TBD | Workflow Logic | @username |
| TBD | Demo/UX | @username |
| TBD | Pitch/Submission | @username |

## Project Overview

### Problem Statement
> Teams lose **[X hours/week]** because **[Y process]** is manual and fragmented.

*TODO: Fill in your specific problem*

### Solution
> Our agent uses watsonx Orchestrate to automatically **[action]** by coordinating **[tool 1]**, **[tool 2]**, and **[tool 3]**.

*TODO: Fill in your solution*

### Demo Flow
1. **Trigger event**: [specific event]
2. **Agent decision**: [decision logic]
3. **Tool interaction**: [tools used, sequence]
4. **Outcome**: [measurable result]

### Impact Metrics
- Saves **[X]** minutes per task
- Reduces handoffs from **[X]** → **[Y]**
- Scales to **[X]** users

## Tech Stack
- **Required**: IBM watsonx Orchestrate
- **Optional**: IBM watsonx.ai
- **Additional**: [list any other tools/frameworks]

## Project Structure
```
├── src/                 # Source code
├── docs/                # Documentation
├── assets/              # Images, diagrams, demo materials
├── config/              # Configuration files (DO NOT commit secrets)
├── IBMHackathon.pdf     # Official hackathon guide
└── README.md            # This file
```

## Quick Start

### Prerequisites
- IBM Cloud account (provisioned for hackathon)
- Access to watsonx Orchestrate

### Setup
```bash
# Clone the repo
git clone https://github.com/sinCodes11/iworks1-IBMhackathon.git
cd iworks1-IBMhackathon

# Copy environment template
cp config/.env.example config/.env

# Add your IBM Cloud credentials to config/.env
```

## Development Guidelines

### Before You Code
- [ ] Validate problem fits 1-sentence format
- [ ] Solution uses watsonx Orchestrate explicitly
- [ ] Impact has 3 quantified metrics
- [ ] Demo explainable in 30 seconds

### Do NOT
- Build beyond happy path
- Chase edge cases
- Commit credentials or API keys
- Use restricted models (llama-3-405b-instruct, mistral-medium-2505, mistral-small-3-1-24b-instruct-2503)

## Submission Checklist
- [ ] Working proof-of-concept deployed
- [ ] All 4 pitch components complete
- [ ] Measurable impact documented
- [ ] Demo video/materials prepared
- [ ] Submitted before deadline

## Resources
- [watsonx Orchestrate Docs](https://www.ibm.com/docs/en/watsonx/watson-orchestrate)
- [Hackathon Guide](./IBMHackathon.pdf)

---
*Built for IBM Dev Day AI Demystified Hackathon 2026*
