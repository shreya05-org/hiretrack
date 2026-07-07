# HireTrack ATS: Lightweight Recruitment System for Startups

🔗 **Live Demo:** https://shreya05-org.github.io/hiretrack/

An accessible, cost-effective, and zero-learning-curve Applicant Tracking System (ATS) designed specifically for early-stage startups to manage hiring pipelines without enterprise software overhead.

## Project Overview

Early-stage startups frequently manage recruitment through fragmented, unstandardized spreadsheets per recruiter, leading to dropped candidates and a lack of clear pipeline visibility. While enterprise ATS platforms solve this, their high annual subscription models are often cost-prohibitive for small teams.

HireTrack addresses this operational gap by providing a structured, data-driven environment delivered in two functional formats:

1. **An Advanced Excel ATS Engine:** Engineered for internal data-driven tracking, reporting, and pipeline analytics.
2. **A Responsive Web Interface:** A lightweight interactive interface designed for rapid deployment via GitHub Pages.

## Repository Structure

- `index.html` — The core web-based tracking application and dashboard interface.
- `Hiretrack_ats_shreya_chopra.xlsx` — The primary Excel data engine utilizing automated formulas and KPI logic.
- `FACEPREP_SHREYA_CHOPRA.pptx` — Detailed project documentation and architecture overview.

## Core Components and Features

### 1. Interactive Web Dashboard (`index.html`)
- **Candidate Lifecycle Tracking:** Options to log, edit, and update candidate records across core hiring stages (Applied, Screened, Interview, HR, Offer, Joined).
- **Pipeline Visibility:** Dynamic rendering of current candidate statuses to provide immediate visibility into recruiting bottlenecks.
- **Local Session Persistence:** Utilizes browser-based local storage to maintain data consistency across sessions without requiring database configuration.

### 2. Core Excel ATS Engine (`.xlsx`)
Built with 38 operational formulas and data validation rules distributed across five dedicated functional sheets:
- **Candidate Database:** Central repository featuring conditional formatting to highlight active pipeline statuses.
- **Status Tracker:** Horizontal visualization mapping candidate movement through individual pipeline stages.
- **Interview Log:** Tracks interview schedules, panel assignments, modes of communication, and performance evaluations.
- **Recruiter Metrics:** Monitors team productivity by automatically calculating throughput and stage-by-stage rejection rates.
- **Visual Dashboard:** Formatted charts and KPI blocks that refresh automatically based on data entry updates.

## Technologies and Tools Used
- **Web Frontend:** HTML5, CSS3, JavaScript (ES6+ for state and data management)
- **Data Architecture:** Microsoft Excel (Advanced formulas, Named Ranges, Conditional Formatting)
- **Presentation and Design:** Microsoft PowerPoint

## Development Notes
This project was developed with the assistance of AI coding tools (IBM BOB) for code generation and iteration, with all logic reviewed, tested, and refined by the author.

## How to Run the Project

**Web Dashboard (index.html):**
1. Visit the live version: https://shreya05-org.github.io/hiretrack/
2. Or run locally: download `index.html` and open it directly in any browser — no installation or server required.
3. Add candidates using the form; data persists automatically in your browser via localStorage.

**Excel ATS Engine (.xlsx):**
1. Download `Hiretrack_ats_shreya_chopra.xlsx`.
2. Open in Microsoft Excel.
3. Enter candidate data in the Candidate Database sheet — the Status Tracker, Interview Log, Recruiter Metrics, and Visual Dashboard sheets update automatically.

## Academic Profile
- **Author:** Shreya Chopra
