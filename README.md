# Contract Monthly Claim System (CMCS) — Prototype

## 📌 Overview
The **Contract Monthly Claim System (CMCS)** is a prototype designed to streamline the process of submitting, verifying, and approving lecturer claims in an academic institution. This stage focuses **only on the prototype (front-end and design)** — no functionality is implemented yet.  

The system provides:
- Lecturer claim submission (mockup form)
- Uploading supporting documents (UI placeholder)
- Programme Coordinator & Academic Manager approvals
- Transparent claim tracking with status history
- Consistent UI with a modern, sleek dark theme

---

## 🎯 Goals of Prototype
- Demonstrate the **database structure** using a UML class diagram.
- Provide a **user-friendly, intuitive GUI** (non-functional at this stage).
- Outline a **project plan** with tasks, dependencies, and milestones.
- Show how future development will evolve into a working system.

---

## 🗂 Project Structure
CMCS/
│── Controllers/ # (Placeholder for future controllers)
│── Models/ # Entity models will map to DB (future)
│── Views/ # Razor views for static prototype pages
│ ├── Shared/ # _Layout.cshtml with dark theme
│ ├── Dashboard.cshtml
│ ├── Claims.cshtml
│ ├── SubmitClaim.cshtml
│ ├── Approvals.cshtml
│── wwwroot/css/ # cmcs-proto.css (custom theme)
│── UML/ # PlantUML source for class diagram
│── Docs/ # Design document & project plan
│── README.md

---

## 📊 UML Class Diagram
The UML class diagram defines the entities and relationships in the CMCS database.

- **Lecturer** submits **Claims** linked to a **Programme**  
- **Claims** can have multiple **SupportingDocuments** and **Approvals**  
- **Managers** review claims and provide approvals/rejections  
- **ClaimHistory** tracks all status changes (audit trail)  

👉 PlantUML source is available in `/UML/cmcs-class-diagram.puml`.

---

## 📅 Project Plan (Prototype Phase)
- **Week 1:** Requirements, UML & ERD draft  
- **Week 2:** MVC scaffolding, dark theme layout  
- **Week 3:** Static Views (Dashboard, Submit Claim, Claims List)  
- **Week 4:** Static Views (Documents upload, Approvals, Status tracking)  
- **Week 5–6:** Documentation, PlantUML, polish visuals  
- **Week 7:** Accessibility & UI refinements  
- **Week 8:** GitHub repo packaging, 5 commits, README  

---

## 🖥️ GUI (Prototype Only)
The GUI is built using **ASP.NET Core MVC (.NET 6/7)** with Razor pages.  
It includes:
- **Dashboard:** Summary of claims & approvals  
- **Submit Claim:** Form to add new claim (mock only)  
- **Claims List & Details:** Track claims with status indicators  
- **Approvals:** For Coordinators/Managers to verify claims  

⚠️ **Note:** This is a front-end prototype only. Buttons, forms, and uploads are **non-functional** until the next project phase.

---

## 🔧 Technologies Used
- **.NET Core MVC** (frontend structure)
- **Razor Views** for mockup pages
- **Custom CSS** (dark, minimal, techy theme)
- **PlantUML** for UML class diagrams
- **GitHub** for version control

---

## 🗃️ Version Control Strategy
A minimum of **5 commits** with clear messages were used in this phase:

1. `chore: repo scaffold & initial README`  
2. `feat(ui): add base layout and global styles (dark theme)`  
3. `feat(ui): add static Dashboard and cards`  
4. `feat(ui): add Submit Claim, Claims List, Claim Details mock views`  
5. `docs: add UML, ERD & design documentation`  

Final prototype tagged as: **`v0.1-prototype`**

---

## 🚀 Next Steps
- Implement Entity Framework Core models & migrations
- Add authentication & role-based access (Lecturer, Coordinator, Manager, Admin)
- Implement claim submission logic and document storage
- Develop approval workflows with email notifications
- Add unit tests and CI/CD pipeline

---
GitHub Repo: https://github.com/Kgothatso-Masekwameng/Prog6212.git

## 👨‍💻 Author
**st10440843**  
Contract Monthly Claim System Prototype — 2025
