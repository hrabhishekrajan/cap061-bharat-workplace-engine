# Bharat Workplace Engine — CAP-061

A frontend MVP prototype for a sovereign enterprise operations workspace: operational work tracking, chat-to-KPI demo parsing, compliance controls, logistics shipments, safety actions, peer guilds and CSV reports.

> **Prototype status:** This repository currently serves a static, browser-only MVP. The records are illustrative demo data, with user-entered changes stored in the browser's `localStorage`. This is not a production collaboration platform, legal/compliance system, emergency reporting channel, or AI-backed KPI engine.

## Run locally

Open `index.html` directly in a modern browser, or serve this folder with any static web server. The app has no build step or runtime dependencies.

## Included interactions

- Navigate between Overview, Operations, Compliance, Logistics, Safety, Reports, Desi Baithak and Workspace Settings.
- Search tasks, filter work items and change task statuses.
- Add work items, controls, shipments, safety actions and demo guilds.
- Capture operational updates with lightweight local keyword suggestions for category, location and status. Suggestions are not AI-generated or verified.
- Update logistics and safety statuses, and review sample compliance controls.
- Export demo work items, controls, shipments, safety actions and summary data to CSV.
- Persist demo changes in browser-local storage and reset to the sample dataset from Workspace Settings.
- Responsive desktop and mobile layouts; no external UI libraries or analytics scripts are required by the app.

## Important limitations and next steps

This frontend does not include authentication, authorization, a server/database, Matrix/Rocket.Chat integration, n8n workflows, Ollama inference, federation, encryption, cryptographic evidence verification, audit-grade retention, or validated DPDP/POSH compliance. Do not enter real employee, sensitive personal, legal, health, incident or confidential business data. The prototype's sample scores and records are not operational measurements.

A production system needs a reviewed threat model and privacy design, secure identity and role-based access, a backend with data retention/deletion controls, tested integrations, auditable human review of extracted metrics, and jurisdiction-specific legal/compliance review. Avoid using automated message-derived KPIs as the sole basis for individual performance decisions.

## Project

Sovereign Enterprise Mesh & Chat-to-KPI Engine · IIT Delhi CEP DTI Batch 10 · Capstone CAP-061.
