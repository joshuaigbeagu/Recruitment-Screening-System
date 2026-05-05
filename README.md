# AI Recruitment Screening System

Automated workflow that handles the pre-interview screening process by filtering, evaluating, and routing candidates to HR.

## What Problem It Solves
Manual CV screening is time-consuming and inconsistent. This system automates initial candidate evaluation to reduce workload and improve decision quality.

## Key Features
- Duplicate application detection
- AI-powered candidate scoring (structured criteria)
- Automatic rejection of low-scoring candidates
- Routing qualified candidates to HR
- Human-in-the-loop approval before interviews
- Candidates are notified at every with timed emails

## Tech Stack
- n8n (workflow automation)
- OpenAI API (evaluation)
- Airtable (data storage)
- Slack/Email (notifications)

## How It Works
1. Candidate submits application
2. System checks and filters duplicate application
3. New candidate receive instant email
4. AI evaluates candidate across defined criteria
5. Candidates are scored and filtered
6. Qualified candidates are sent to HR for approval
7. Candidates receive timed emails depending on the outcome
8. All candidates data are logged on to Airtable

## Setup / Usage
- Import the provided JSON file into n8n
- Configure API keys (OpenAI, Airtable, etc.)
- Activate workflow
