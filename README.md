# InsuraIQ: Your virtual health insurance agent

InsuraIQ is a multi-agent AI system built to solve the overwhelming and confusing process of choosing health insurance. It guides users from understanding their own medical profile to receiving transparent, personalized policy recommendations.

## The Problem
The health insurance market is a maze of complex jargon, hidden clauses, and tedious paperwork. Users often make decisions in the dark, leading to surprise rejections, unaffordable premiums, inadequate coverage or outright rejection.

## Our Solution
InsuraIQ acts as a trusted advisor, using a team of specialized AI agents to:
- **Securely Collect Information:** An opaque agent running in an isolated A2A server handles all Personal Identifiable Information (PII) with maximum security.
- **Analyze Your Health Profile:** A "Doctor Agent" analyzes the anonymized data to create a risk profile, identifying potential red flags for insurers.
- **Recommend the Best Policies:** A "Policy Recommender" agent matches the user's profile against a database of policies, presenting the best options with clear pros and cons.

## How It's Built: Core Architecture
This project uses a **multi-agent system** orchestrated on Google Cloud.

- **Frontend:** **Angular**
- **Backend & AI:**
    - **Agent Framework:** **Agent Development Kit (ADK)**
    - **Core Logic:** Multi-agent system (Information Collector, Doctor Agent, Policy Recommender).
    - **Intelligence:** **Gemini 2.5 Pro, Gemini 2.5 Flash** for complex reasoning.
    - **Infrastructure:** **Google Cloud** (Agent Engine, Cloud Run).
    - **Security:** **A2A Server** for handling all PII in a completely opaque environment.

## Flow Diagram

![Flow diagram of the solution](/assets/flow-diagram.png)

## Architecture Diagram

![Architecture diagram of the solution](/assets/insuraiq-arch.png)

## Repository details
This repository consists of 4 parts.
    - 1. A2A server
    - 2. MCP server
    - 3. Multi Agent System
    - 4. UI

Please read the individual README for more details.
---
