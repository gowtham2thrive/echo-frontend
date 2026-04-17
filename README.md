# Echo | Evidence-based Complaint & Hostel Oversight

![Echo Banner](https://github.com/gowtham2thrive/echo-frontend/blob/main/src/assets/banner.svg)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](License.txt)

**Echo** is a modern, real-time hostel management platform designed to bridge the communication gap between students and administration. Built with **React** and **Supabase**, it features distinct portals for students and staff, utilizing a custom glassmorphism design system for a premium user experience.

---

### 🏆 Achievements
**🥈 Second Place Winner** – National Technical Meet (Synergy 2026)

<p align="center">
  <img src="src/assets/Echo%20Hostel%20Management%20System%20–%20Second%20Place,%20National%20Technical%20Meet%20(Synergy%202026).jpg" 
       alt="Echo Hostel Management System – Second Place, National Technical Meet (Synergy 2026)"
       width="600">
</p>

---

## 🌟 Core Highlights

* **🔐 Role-Based Access Control (RBAC):** Distinct, secure portals for Students and Staff with tailored permissions and dashboards.
* **💎 Modern Glassmorphism UI:** A sleek, responsive interface featuring glass-blur effects, interactive toasts, and smooth transitions.
* **🎨 Theme Support:** Fully customizable appearance with **Light**, **Dark**, and **System** modes.
* **🧠 AI-Powered Intelligence:** Integrated LLM (Large Language Model) features to professionalize text and analyze data trends.

---

## 🎓 Student Portal
*Empowering residents with digital tools for safety and grievance redressal.*

* **Smart Complaint Filing**
    * **AI Rewrite:** Built-in AI tool to help students rephrase angry or unclear complaints into professional, neutral language before submission.
    * **Categorization:** Structured filing under *Hygiene, Food, Maintenance, Discipline,* and *Other*.
    * **Live Tracking:** Real-time status updates (Submitted → Acknowledged → Resolved) with staff notes.

* **Digital Gate Pass (Outing System)**
    * **Request Workflow:** Easy form to request outings with departure time, return time, and purpose.
    * **Live Status Indicator:** Visual badge showing **"🟢 ON CAMPUS"** or **"🔴 ON OUTING"** at a glance.
    * **History Log:** A searchable archive of all past outings and permissions.

* **Profile Management**
    * **Edit Requests:** Students can request profile updates (e.g., name correction), which enter a **pending approval queue** for staff verification to ensure data integrity.

---

## 🛡️ Staff Portal
*A powerful command center for hostel administration.*

### 1. Complaint Management Board
* **AI Insight Panel:** Instantly analyzes hundreds of pending complaints to generate a **Root Cause Analysis** summary (e.g., *"Multiple reports of low voltage on 2nd floor"*), allowing staff to fix the core issue rather than treating symptoms.
* **Priority Feed:** Complaints are auto-sorted into **Critical**, **Medium**, and **Low** priority queues using interactive filter chips.
* **Bulk Actions:** High-efficiency tools to **Acknowledge All** or **Resolve All** complaints in a specific category with a single click.
* **PDF Reporting:** One-click generation of professional vector PDF reports for official audits and meetings.

### 2. Outing & Security Control
* **Live Dashboard:** A real-time list of **"Currently Out"** students with countdown timers for overdue returns.
* **One-Tap Check-In:** Instantly mark students as returned to close their gate pass.
* **Visual Analytics:** Interactive bar charts visualizing outing trends (Weekly/Monthly) to monitor student movement patterns.

### 3. Student Directory & Approvals
* **Digital Directory:** Searchable database of all registered students with contact details (Phone / Parent Phone).
* **Approval Workflow:** Review and approve/reject new student registrations and profile update requests.
* **Strict Validation:** Prevents unauthorized changes to sensitive data (like Roll Numbers) without staff oversight.

---

## ⚡ Technical & UX Features

* **Real-Time Toast Notifications:** Floating glass-style notifications for success, error, and system alerts.
* **Data Visualization:** Integrated **Chart.js** analytics for complaint severity and outing frequencies.
* **Secure Authentication:** Powered by Supabase Auth for robust user session management.
* **Edge Functions:** Serverless backend logic for secure AI processing and data summarization.
* **Export Capabilities:** Client-side PDF generation using `jspdf-autotable` for offline record-keeping.

---

## 🛠️ Tech Stack

### **Core Framework**
* **Frontend:** [React.js](https://react.dev/) (Vite) – Fast, component-based UI development.
* **Styling:** Pure CSS3 (Custom Glassmorphism Design System) – No heavy CSS frameworks; fully custom responsive styles.
* **State Management:** React Context API – For handling Authentication (`AuthContext`) and Theming (`ThemeContext`) globally.

### **Backend & Database**
![Schema Visualizer](https://github.com/gowtham2thrive/Echo/blob/main/backend/Schema%20Visualizer.svg)
* **Platform:** [Supabase](https://supabase.com/) – The open-source Firebase alternative.
* **Database:** PostgreSQL – Relational database for structured data (Complaints, Profiles, Outings).
* **Authentication:** Supabase Auth – Secure email/password login with Row Level Security (RLS) policies.
* **Serverless Logic:** Supabase Edge Functions (Deno) – For secure backend processing.

### **🤖 AI & Intelligence**
* **LLM Provider:** [Groq Cloud](https://groq.com/) – Ultra-fast inference API.
* **Model:** `llama-3.3-70b-versatile` – Used for rewriting complaints and generating root cause analysis summaries.
* **Runtime:** Deno – Running TypeScript Edge Functions to bridge the frontend and the AI API securely.

### **Key Libraries**
* **Data Visualization:** `Chart.js` & `react-chartjs-2` – For rendering interactive analytics bars and trends.
* **PDF Generation:** `jspdf` & `jspdf-autotable` – Client-side vector PDF creation for reports.
* **Icons:** Custom SVG Icon System (Lucide-style line art) – Lightweight and theme-adaptive.

---

### Clone the repository

```bash
git clone https://github.com/gowtham2thrive/Echo.git
cd Echo

```
