# AI Full-Stack Structure

An interactive single-page website that explains how a simple AI demo flow
expands into a production-ready AI healthcare service architecture.

Live site:
https://chloedaunjeong.github.io/ai-full-stack-structure/

> Note: GitHub Pages must be enabled for this repository before the live link
> becomes available. In GitHub, go to Settings > Pages, choose `Deploy from a
> branch`, select `gh-pages`, choose `/ (root)`, and save.

## Project Overview

This project is designed as a portfolio artifact for AI Healthcare Project
Manager, Technical Project Manager, and technology-business bridge roles.

The page explains the difference between:

- Demo flow: a simple stakeholder-friendly view of how an AI service works
- Production expansion: the real operational, security, data, governance, and
  clinical safety responsibilities behind each stage

The goal is to make AI service architecture understandable for both technical
and non-technical stakeholders.

## Problem Statement

Many AI demos look simple:

User -> Frontend -> Backend -> AI Model -> Result

However, real healthcare AI services require much more than a model and a
screen. They need permissions, data privacy, API design, monitoring, model
governance, error handling, human review, and project management oversight.

This website turns that hidden production complexity into a clear interactive
learning tool.

## Intended Users And Stakeholders

- AI Healthcare Project Managers
- Technical Project Managers
- SaaS product and operations teams
- Healthcare innovation teams
- Business analysts
- Students learning AI service architecture
- Non-technical stakeholders reviewing AI product scope

## Key Features

- Horizontal Demo Flow diagram
- Eight production stages:
  - User
  - Client Device
  - Frontend
  - Network / Web Basics
  - Backend
  - AI Model
  - Result
  - Supporting Layers
- Clickable stage cards
- Interactive component detail panels
- Korean and English language toggle
- Related technologies and service examples
- Final Summary toggle
- Project Management View toggle
- Healthcare AI examples and safety notes

## Production Concepts Covered

The website includes production-ready concepts such as:

- REST API / JSON Flow
- Consent & Data Privacy
- Human-in-the-loop Review
- Model Version Tracking
- Error / Fallback Flow
- Authentication and permissions
- Security and compliance
- Monitoring and operations
- Audit logs and traceability
- Clinical safety messaging

## Technology Stack

- HTML
- CSS
- Vanilla JavaScript
- GitHub Pages

No frontend framework is required. The page is intentionally built as a simple
static website so it is easy to open, deploy, and maintain.

## How To Run Locally

Open the file directly in a browser:

```text
index.html
```

Or run a simple local server:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Deployment

This repository is prepared for GitHub Pages using the `gh-pages` branch.

Expected public URL:

```text
https://chloedaunjeong.github.io/ai-full-stack-structure/
```

If the URL returns `404`, enable GitHub Pages:

1. Open repository Settings
2. Go to Pages
3. Source: `Deploy from a branch`
4. Branch: `gh-pages`
5. Folder: `/ (root)`
6. Save

GitHub may take 1-2 minutes to publish the page.

## Responsible AI And Healthcare Notes

This project is educational and architectural. It does not provide medical
diagnosis, treatment advice, or clinical decision automation.

The healthcare examples emphasize:

- Human review
- Clear clinical safety messaging
- Consent and privacy
- Least-privilege access
- Auditability
- Model version tracking
- Safe fallback behavior

## Project Management Value

This project demonstrates that an AI PM or Technical Project Manager should not
only focus on model performance. A production AI healthcare service also needs
clear ownership across:

- Users and stakeholders
- Data access and privacy
- API contracts
- Backend reliability
- Model governance
- Monitoring and incident response
- Clinical safety review

## My Role And Contributions

I designed and built this interactive architecture explainer to communicate AI
healthcare full-stack concepts in a stakeholder-friendly way.

The project reflects my focus on:

- Technical storytelling
- Healthcare AI product thinking
- Project management structure
- Bilingual communication
- Responsible AI awareness
- Translating technical systems for non-technical audiences
