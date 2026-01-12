# Startup Advisor Backend – n8n Automation Workflows

## Overview
This repository contains the backend automation layer of an AI-powered startup advisor platform.
The backend is implemented using n8n workflows and is responsible for receiving startup ideas,
orchestrating AI-driven analysis, and returning structured strategic insights to the frontend.

Instead of a traditional backend server, this project uses workflow-based automation to enable
fast iteration, modular logic, and AI-powered reasoning.

---

## Backend Responsibilities
The backend workflows handle:
- Receiving startup ideas via webhook endpoints
- Validating and structuring incoming user input
- Orchestrating AI-powered analysis using LLMs
- Evaluating startup risks, competitors, and feasibility
- Returning clean, structured JSON responses for frontend consumption

---

## Tech Stack
- n8n (workflow automation and orchestration)
- Webhook-based API endpoints
- AI / LLM integration via n8n AI nodes
- JavaScript-based data transformation inside workflows
- JSON-based input and output contracts

---

## How It Works
1. The frontend sends a startup idea to a webhook endpoint
2. n8n receives and preprocesses the input
3. AI-powered nodes analyze the idea across multiple dimensions
4. The workflow validates and structures the AI output
5. A clean JSON response is returned to the frontend

---

## Workflow Capabilities
- Startup problem analysis
- Target customer and persona identification
- Competitor landscape evaluation
- Risk assessment (technical, market, adoption)
- MVP feature and scope recommendations

---

## Repository Contents
- Startup Idea Validator & Mentor (3).json  
  Main n8n workflow definition powering the startup analysis logic
- README.md  
  Project documentation

---

## Design Philosophy
The backend is designed as a stateless, automation-first system:
- No traditional backend server
- No persistent database
- Logic is encapsulated entirely in workflows
- Easy to modify, extend, and experiment with AI prompts and logic

This approach enables rapid prototyping and clear separation between frontend and automation layers.

---

## Usage
1. Import the JSON workflow file into your n8n instance
2. Configure required AI credentials (OpenAI or compatible provider)
3. Activate the webhook trigger
4. Connect the frontend or API client to the webhook endpoint
5. Test the workflow with sample startup ideas

---

## Limitations
- No user authentication or session management
- No persistent data storage
- Designed for advisory and analytical use cases only

---

## Future Improvements
- Modularize workflows for specific analysis types
- Add logging and monitoring for executions
- Integrate external data sources (market, competitors)
- Extend workflows for iterative founder mentoring

---

## License
This project is intended for educational and portfolio purposes.

---

## Author
Can Zorlu
LinkedIn: https://www.linkedin.com/in/can-zorlu-26b115307
