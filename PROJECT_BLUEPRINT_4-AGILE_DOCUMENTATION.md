# 📘 PROJECT_BLUEPRINT_4.md: Agile Project Documentation

**Project Name:** Smart Traffic Violation Pattern Detector Dashboard  
**Platform Name:** CollisionX India  
**Role:** Agile Project Manager & Technical Team Lead  
**Team Size:** 15 Developers (Interns)  
**Duration:** 2 Months (Oct 2025 - Dec 2025, 4 Sprints)  
**Tools:** Python, Streamlit, Pandas, Matplotlib, Folium  

---

## 1. 📋 Product Backlog

This backlog tracks the internship progress from Training to Product Delivery.

| Planned Sprint | Actual Sprint | US ID | User Story Description | MOSCOW | Dependency | Assignee | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Sprint 1 | Sprint 1 | US-00 | As a team, we need to **collaborate on a Shared Learning Repo** to practice Python/Pandas. | Must Have | None | All Team | Done |
| Sprint 2 | Sprint 2 | US-01 | As a lead, I want to **initialize the Main Project Repo** with a 7-branch strategy. | Must Have | None | Sami (Lead) | Done |
| Sprint 2 | Sprint 2 | US-02 | As a user, I want a **Data Upload Page** to load traffic CSVs. | Must Have | US-01 | Divija | Done |
| Sprint 2 | Sprint 2 | US-03 | As a system, I need **Feature-Branch workflows** (6-7 branches) to manage 15 devs. | Must Have | None | Anshu | Done |
| Sprint 3 | Sprint 3 | US-08 | As a user, I want **Home & About Pages** for project info. | Must Have | US-01 | Ishwari | Done |
| Sprint 3 | Sprint 3 | US-04 | As a user, I want distinct **Visualization Pages** for different insights. | Must Have | US-02 | Divija | Done |
| Sprint 3 | Sprint 3 | US-05 | As a user, I want **Visual Plots** (Bar/Pie) for traffic trends. | Must Have | US-04 | Harika | Done |
| Sprint 3 | Sprint 3 | US-06 | As a user, I want **Scatter & Bar Plots** for variable correlation. | Must Have | US-04 | Poojitha | Done |
| Sprint 3 | Sprint 3 | US-07 | As a user, I want **Donut Charts** for violation composition. | Should Have | US-04 | Anshu | Done |
| Sprint 3 | Sprint 3 | US-08 | As a user, I want **Risk & Heatmap Plots** for severity analysis. | Must Have | US-04 | Divija | Done |
| Sprint 4 | Sprint 4 | US-09 | As a brand, I want a custom **Logo and Platform Identity (CollisionX India)**. | Should Have | None | Mrunalini | Done |
| Sprint 4 | Sprint 4 | US-10 | As a user, I want a **Map Visualization** using specific GeoJSONs for accurate regions. | Must Have | US-02 | Saidul | Done |

---

## 2. 🏃 Sprint Backlog (Sprint 2: Foundation & Kickoff)

**Sprint 2 Goal (Oct 27 - Nov 09):** Transition from Learning Repo to Main Repo. Initialize "CollisionX India" with limited branches to avoid chaos.

| US ID | Task ID | Task Description | Team Member | Status | Est. Effort (Hrs) | Day 1-7 | Day 8-14 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| US-01 | T-101 | Initialize Main Repo & Define 7 Core Branches | Sami | Done | 10 | 10 | 0 |
| US-03 | T-102 | Setup Branch Protections (Backend, UI, Data, etc.) | Anshu | Done | 15 | 8 | 7 |
| US-02 | T-103 | Build `09_Upload_Dataset.py` Page | Divija | Done | 8 | 5 | 3 |
| US-04 | T-104 | Develop `01_Numerical_Analysis.py` Page | Mrunalini | Done | 8 | 4 | 4 |
| US-04 | T-105 | Develop `11_About_Page.py` structure | Ishwari | Done | 6 | 0 | 6 |
| US-07 | T-106 | Research & Find Open Source GeoJSON Maps | Saidul | Done | 12 | 2 | 10 |
| US-05 | T-107 | Implement Basic Visual Plots (Matplotlib) | Sanjana | Done | 8 | 0 | 8 |

---

## 3. 🗣️ Stand-up Meeting Log

Daily syncing, focusing on "CollisionX India" platform blockers.

| Sprint | Day | Date | Impediments / Blockers | Action Taken |
| :--- | :--- | :--- | :--- | :--- |
| **Sp 2** | Day 3 | Nov 03 | **Blocker:** 15 members pushing to main caused chaos in the Learning Repo. | **Action:** Saidul/Anshu moved to **Feature-Branch** strategy (only ~7 active branches) for the Main Project. |
| **Sp 3** | Day 5 | Nov 15 | **Issue:** Ishwari & Harika flagged HTML rendering issues in Streamlit tables. | **Action:** **Mrunalini & Ishwari** wrote custom CSS variables to fix the layout colors and spacing. |
| **Sp 4** | Day 2 | Dec 02 | **Blocker:** Map plotting failing. Standard maps don't match our data regions. | **Action:** Saidul spent 2 days finding the correct Open Source **GeoJSON** files from the internet. |
| **Sp 4** | Day 4 | Dec 04 | **Task:** Need a unique identity. | **Action:** Mrunalini designed the **"CollisionX India"** logo and theme assets. |

---

## 4. 🔄 Retrospection

Reflecting on the "CollisionX India" team performance.

| SL # | Sprint # | Team Member | Start Doing | Stop Doing | Continue Doing |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Sprint 2 | Anshu | Grouping PRs by Feature Branch (UI, Data, Core). | Allowing direct commits to Main. | Managing the shared repository protections. |
| 2 | Sprint 3 | Sami | Leveraging **Gemini/Claude** for tricky Pandas debugging. | Writing custom CSS without checking Streamlit support. | guiding the 15-member team on architecture. |
| 3 | Sprint 3 | Mrunalini | Creating assets (Logo) earlier in the sprint. | Using hardcoded paths. | improving UI aesthetics. |
| 4 | Sprint 4 | Saidul | Validating GeoJSON files before implementation. | Ignoring projection errors. | searching for open-source resources. |
| 5 | Sprint 4 | All | Using standard Variable names (Data Variables). | Hardcoding column names in pages. | collaborating on plotting logic. |

---

## 5. 🐛 Defect Tracker

| Sl No | Description | Detected Sprint | Assigned To | Type | Action Taken | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| BUG-01 | **Map Visibility:** Map not loading for certain States. | Sprint 4 | Saidul | Data | Swapped broken GeoJSON with valid Open Source files found online. | Closed |
| BUG-02 | **Merge Conflict:** Logic overwrites in `app.py`. | Sprint 2 | Anshu | Process | Restricted main branch; enforced 7-branch workflow. | Closed |
| BUG-03 | **Visuals:** Bar charts overlapping on mobile. | Sprint 3 | Sanjana | UI | Adjusted figure size and rotation using Matplotlib params. | Closed |
| BUG-04 | **Analysis:** Complex filters causing slow load. | Sprint 3 | Darsana | Perf | Optimization assistance from AI tools (Claude). | Closed |
| BUG-05 | **Encoding Error:** CSVs with special chars failing. | Sprint 2 | Divija | Data | Added `latin-1` fallback in `utils.py`. | Closed |
| BUG-06 | **UI Glitch:** Sidebar overlapping text on mobile. | Sprint 3 | Ishwari | UI | Applied custom CSS media queries for responsive layout. | Closed |

---

## 6. 🧪 Unit Test Plan

| Sl No | Test Case Name | Test Procedure | Condition to be Tested | Expected Result | Actual Result |
| :--- | :--- | :--- | :--- | :--- | :--- |
| TC-01 | **GeoJSON Validity** | Load map with new GeoJSON file. | `map_plot.py` check. | Map renders without polygon errors. | Matches Expected |
| TC-02 | **Logo Rendering** | Check Sidebar logo display. | `sidebar.py` render. | "CollisionX India" logo appears correctly. | Matches Expected |
| TC-03 | **Git Workflow** | Merge 'UI-Feature' Branch to Main. | Conflict resolution. | Clean merge due to branch alignment. | Matches Expected |
| TC-04 | **Variable Consistency** | Check column names across pages. | `data_variables.py` usage. | All pages use unified constants. | Matches Expected |
| TC-05 | **Error Handling: Invalid File** | Upload a `.txt` or `.exe` file instead of CSV. | `09_Upload_Dataset.py` validator. | System rejects file with "Invalid format" error. | Matches Expected |
| TC-06 | **Error Handling: Schema Check** | Upload CSV with missing columns. | `app.py` Schema Validation. | "Missing Columns" warning displayed; App prevents crash. | Matches Expected |

---

> **Acknowledgment:** We leveraged AI tools (Claude & Gemini) primarily for **complex debugging** where Sami & Anshu led the analysis to resolve deep technical issues.
