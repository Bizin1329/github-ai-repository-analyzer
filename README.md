# github-ai-repository-analyzer

AI-powered n8n automation for collecting, filtering, ranking and analyzing GitHub repositories.

## What it does

This workflow:

1. Fetches GitHub repositories via GitHub API.
2. Collects repositories from multiple API pages.
3. Filters repositories by stars.
4. Sorts repositories by popularity.
5. Selects the top 10 projects.
6. Uses an LLM to analyze each repository.
7. Saves the analysis to Google Docs.

## Workflow

GitHub API → Merge → Split → Normalize Data → Filter → Sort → Top 10 → AI Analysis → Google Docs

<img width="1693" height="695" alt="2026-09-26_14-50-27" src="https://github.com/user-attachments/assets/9dba722b-375a-4f51-8d99-92c99a5322ad" />

The automation can be used for:

* GitHub research
* discovering interesting open-source projects
* market and technology research
* automated competitor/project analysis
* building AI-powered research workflows

## Tech Stack

* n8n
* GitHub API
* LLM API
* JavaScript
* Google Docs

## Setup

1. Import the workflow JSON into n8n.
2. Configure GitHub API credentials.
3. Configure the LLM API credentials.
4. Connect a Google Docs account.
5. Run the workflow manually.

> API keys and credentials are not included in this repository.
