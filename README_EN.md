ProStep Vision System
**English** | 🇧🇷 [Português](README.md)

⚠️ Important Notice
This repository contains a functional prototype / reference model created to demonstrate the core concepts of a larger industrial quality control system.
It is not the final production system, but a simplified version intended for study, demonstration, and future expansion.

The complete project concept, business rules, and operational vision are described in detail in the PDF documentation available in the docs/ folder.

📌 Project Overview

ProStep Vision System is a web-based quality control model designed to monitor and validate production steps in an industrial environment.

The system simulates a Gate & Step validation flow, where each production step must confirm its checklist in sequence, allowing supervisors (Gate) to monitor progress, identify gaps, and ensure process compliance.

🎯 Project Objectives

Demonstrate a step-by-step quality validation workflow

Ensure sequential confirmation of production steps

Provide real-time visibility of production gaps

Offer a shift-based dashboard with performance indicators

Serve as a foundation model for a scalable industrial system

🧠 Key Concepts

Gate
Central control panel responsible for:

Starting and ending shifts

Defining production targets

Monitoring step confirmations

Identifying missing or skipped steps

Generating shift reports

Step (Operation)
Individual production stations responsible for:

Completing mandatory checklists

Confirming their operation only after all checklist items are validated

Respecting the production sequence logic

Shift-Based Control

Each shift has a configurable production target

Completion percentage is calculated per step, not per serial number

Data is reset only when the shift is officially closed

📊 Dashboard Logic

The shift dashboard is based on step completion, not serial continuity.

100% completion means:

Every step reached its production target

Independent of which serial numbers were used

This approach ensures:

Accurate performance tracking

No distortion when serial numbers cross shifts

🗂️ Documentation

The full system concept is documented in the following files:

📄 Portuguese (PT-BR)
docs/Sistema de Qualidade por Conferência.pdf

📄 English (EN)
docs/System_Quality_Conference_SQC_EN.pdf

These documents describe:

Business rules

Operational flow

Future scalability vision

System responsibilities

🛠️ Technologies Used

HTML5

CSS3

Vanilla JavaScript

LocalStorage (state simulation)

SessionStorage (session control)

No backend is used in this prototype.
All logic is implemented on the client side for demonstration purposes.

🚀 Purpose of This Repository

This repository exists to:

Serve as a reference architecture

Demonstrate logic and UX concepts

Support discussions with stakeholders

Act as a base for future backend integration

📌 Disclaimer

This project is a conceptual and educational model.
It should be adapted, secured, and expanded before any production use.

👤 Author

Rafael Lopes Ferreira