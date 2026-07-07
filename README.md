# CareBridge — AI-Enabled OR-to-ICU Bed Escalation System

**[▶ Live Demo](https://nbhandari3.github.io/CareBridge)**

An AI-enabled surgical escalation and ICU bed management prototype that replaces
informal, phone-based OR-to-ICU coordination with a structured, real-time digital
workflow. Built as a capstone consulting project (HMI 7910 — AI in Healthcare,
Kennesaw State University) for a simulated 550-bed Level I Trauma Center
(Acworth Regional Medical Center).

## Features
- 🏥 6 role-based dashboards: OR Workstation, Bed Board, ICU Intensivist, ICU Charge Nurse, Receiving Nurse, and AI Insights
- 🛏 Real-time ICU bed board with live SVG bed grid and status tracking
- 🤖 Automated bed-request / consult engine that notifies the intensivist and charge nurse simultaneously
- 📉 AI-assisted patient downgrade recommendations with confidence scoring to free ICU beds proactively
- 📋 ICU waiting list with priority-based patient-to-bed matching
- 🔄 Swimlane-accurate escalation workflow from OR request to bed assignment
- 🔌 Documented Epic / HL7 FHIR R4 integration approach (ServiceRequest, Encounter, Location resources)
- ♻️ One-click Reset Demo to restore the full scenario

## Tech Stack
Pure HTML, CSS, and vanilla JavaScript — no frameworks, no dependencies.

## How to Run Locally
Just open `index.html` in any browser.

## Credits
Built by Nitika Bhandari and Jean Dunac for HMI 7910 (Prof. Dr. Soo Il Shin),
Kennesaw State University, Summer 2026. All patient data is fictional.
