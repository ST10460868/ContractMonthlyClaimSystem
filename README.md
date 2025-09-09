# Contract Monthly Claim System – Part 1: Project Planning and Prototype Development

## Overview
This repository contains the **prototype design** for the Contract Monthly Claim System.  
At this stage, the system is **not functional** — it only provides documentation, UML diagrams, project plan, and GUI mockups as required by the assignment brief.

---

## Contents
- **docs/**
  - `Report.docx` – Full project report (Design choices, UML diagram, Project plan, GUI design).
  - `uml.png` – UML class diagram for the database.
  - `gantt_chart.png` – Project plan Gantt chart.
  - `gui1.png` – Lecturer Claim Submission screen (mockup).
  - `gui2.png` – Verification Queue screen (mockup).
  - `gui3.png` – Claim Status Tracking screen (mockup).
- **README.md** – This file.

---

## 📝 Design Highlights
- **Design Choices & Assumptions**
  - Role-based access: Lecturers submit claims, Coordinators/Managers verify and approve.
  - Transparent claim tracking with consistent and reliable information.
  - Prototype stage: GUI is non-functional, only mockups are provided.

- **Database & UML**
  - Entities: Lecturer, Claim, Supporting Document, Verification.
  - Relationships:
    - A Lecturer can submit many Claims.
    - A Claim can have multiple Supporting Documents.
    - A Claim can go through multiple Verifications.

- **GUI Design**
  - Lecturer Claim Submission form (upload supporting docs).
  - Verification Queue for Coordinators/Managers.
  - Claim Status Tracking for Lecturers.

- **Project Plan**
  - Documentation → UML → GUI Mockups → Report Compilation → Version Control.
  - Version control used throughout development (5 commits with descriptive messages).

---

## Version Control
This repo demonstrates proper GitHub usage:
- **Commit 1** – Initial commit: Added project folder structure.  
- **Commit 2** – Added Part 1 project report with design choices, assumptions, and constraints.  
- **Commit 3** – Added UML class diagram and project plan Gantt chart.  
- **Commit 4** – Added GUI prototype mockups.  
- **Commit 5** – Finalized report and organized docs folder.  

---

## Next Steps
Future parts of the POE will extend this prototype by adding:
- Functional database integration.
- Backend logic for claim submissions.
- Role-based authentication (Lecturer, Coordinator, Manager).
- Complete WPF/MVC application.

---

 *This repository is for academic purposes (Part 1 of the POE).*
