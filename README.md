# Interior-Design-Voice-AI-Agent
A multi-agent voice system that manages incoming leads and automates client communication. 

Interior Design Lead Management System
This project implements an automated lead management system for Interia, a premier interior design company, using n8n, Vapi, and Airtable. The system handles outbound calls to qualify leads, retries unanswered calls, logs call records, and updates lead statuses, all driven by a custom voice AI agent named Alex.

Overview
The workflow (interia-lead-system.json) processes call outcomes from Vapi, updates lead statuses in Airtable, and retries unanswered calls once after a 1-minute delay. The Vapi assistant, Alex, introduces itself, qualifies leads based on their interest and budget, books appointments for qualified leads, and closes calls appropriately. This system aligns with the requirements of the "Technical Assessment: Interior Design Voice AI Agent" document.

Prerequisites
n8n: Workflow automation tool (version compatible with nodes used in the JSON, e.g., 0.236.0+).
Vapi: Voice AI platform for outbound calls (API key and assistant configured).
Airtable: Database for storing leads and call records (base and tables set up).
Git: For version control.
