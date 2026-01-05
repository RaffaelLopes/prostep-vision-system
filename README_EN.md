ProStep Vision System
**English** | 🇧🇷 [Português](README.md)

ProStep Vision System is a functional web system prototype developed to demonstrate quality control through step-based verification in industrial processes.

This project is not the final system, but rather a conceptual and technical proof of concept, created to:

Validate business rules

Demonstrate step-by-step control flows

Serve as a foundation for future expansion into a larger system

The complete project vision, business context, and functional scope are documented in the PDF files available in the /docs
 folder.

🎯 Purpose

To demonstrate, in a practical way, how a system can:

Control confirmations per Step

Detect sequence gaps between steps

Centralize validations in a Gate control panel

Generate shift-based performance indicators

Serve as a foundation for a larger corporate-quality system

🧩 System Structure
🔹 STEP (Operation)

Mandatory checklist per step

Confirmation allowed only after full checklist interaction

Visual status indicators:

🟢 Confirmed

🔴 Pending (when a gap exists)

🟠 In progress

🔹 GATE (Central Control)

Shift start and end control

Dynamic shift target (goal) definition

Real-time visualization of confirmations

Automatic detection of missing steps

Dashboard consolidated by Step, not by serial number

📊 Shift Dashboard

The dashboard was designed to reflect real operational logic, considering:

Shift target applied independently of serial numbers

Completion calculated based on:

Number of confirmations per Step

Expected total = target × number of steps

Automatic updates when:

The shift target changes

Steps are confirmed

Pending steps are corrected via Gate

📁 Project Structure
prostep/
│
├── css/          # System styles
├── js/           # System logic (Gate, Step, Sessions)
├── pages/        # HTML pages
├── data/         # Auxiliary data (JSON)
├── docs/         # Project documentation (PDF PT-BR and EN)
│
├── README.md     # Documentation in Portuguese
├── README_EN.md  # Documentation in English

📄 Project Documentation

The complete conceptual and functional documentation is available at:

📘 Portuguese:
docs/Sistema de Qualidade por Conferência.pdf

📗 English:
docs/System_Quality_Conference_SQC_EN.pdf

These documents describe the larger system vision, of which this repository represents only a demonstration model.

⚠️ Important Notice

This repository is a demo / proof-of-concept project.
It was developed for study, validation of ideas, and technical demonstration, and should not be used directly in production environments without proper adaptations.

👤 Author

Rafael Lopes Ferreira
