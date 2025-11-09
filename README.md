# Compliance-Aware Multi-Domain Advisor

## Overview
This Python-based advisor classifies user queries into **medical**, **legal**, or **financial** domains, retrieves authoritative evidence, applies risk-aware verdict logic, and generates structured **JSON audit logs**.  
It demonstrates how AI systems can deliver domain-specific responses while maintaining transparency, disclaimers, and compliance-grade logging.

## Features
- **Domain Classification**: Automatically detects whether a query is medical, legal, or financial.
- **Evidence Retrieval**: Pulls relevant text chunks from authoritative corpora (e.g., WHO, India Code, SEBI).
- **Verdict Logic**: Applies threshold-aware decision rules (respond, caution, escalate).
- **Disclaimer Integration**: Adds tailored disclaimers for each domain.
- **Audit Logging**: Outputs structured JSON logs with timestamps, request IDs, and verdict rationale.

## Repository Contents
- `advisor.py` → Main Python script containing classification, retrieval, verdict, and logging pipeline.
- `requirements.txt` → Python dependencies.
- `contract_act.pdf` → Sample legal corpus (Indian Contract Act).
- `event_log.json` → Sample audit logs for medical, legal, and financial queries.

## Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/<your-username>/compliance-advisor.git
cd compliance-advisor
pip install -r requirements.txt
