# Nexus-AI-Governance-Framework
AI Governance Framework and PII Sanitization tool built for Nexus Financial Solutions to mitigate data privacy risks in Large Language Model (LLM) integration.


This project demonstrates a comprehensive AI Governance Framework designed for Nexus Financial Solutions, a fictional fintech firm. The framework addresses the critical risk of Data Leakage when employees utilize Generative AI for customer escalation logs containing Personally Identifiable Information (PII) and financial metadata.
By mapping organizational risks to the NIST AI Risk Management Framework (AI RMF), this project implements a three-layered defense:
• Administrative Control: An AI Acceptable Use Policy defining sanitization standards.
• Technical Control: A Python-based 'Sanitizer' utilizing Regex patterns to redact SSNs, account numbers, and client names.
• Operational Control: An incident response and root cause analysis process to manage and learn from policy bypass events
