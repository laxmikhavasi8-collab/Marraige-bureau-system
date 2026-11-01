Eternal Bond — Matrimonial Bureau Management Portal

A full-featured, responsive, frontend-only Single-Page Web Application (SPA) for managing client registration, matchmaking, inquiries, internal communication, and demographic reporting for a matrimonial bureau.

📌 Project Overview

Eternal Bond Portal is designed to streamline day-to-day matrimonial bureau operations. Staff and clients can track profiles, execute automated matrix-driven compatibility matching, manage expressions of interest, and analyze bureau demographics—all inside a clean, modern interface.

🎨 Design & Theme Guidelines

Primary Color Palette: Deep Blue (#1A5276), Light Blue (#D6EAF8), White (#FFFFFF).

Vibe: Professional, trustworthy, organized, and elegant.

Layout: Fixed top navigation bar with search & quick actions, collapsible sidebar with icons, and a dynamic single-page view area.

Modes: Fully functional Dark Mode and Light Mode toggle.

🚀 Key Modules & Features

1. 📊 Dashboard View

Real-time counter metrics for Total Clients, Active Matches, Pending Inquiries, and Success Stories.

Quick summary table showcasing recently registered profiles.

Overview widget displaying real-time incoming interest expressions.

2. 📝 Multi-Step Client Registration

A 4-step wizard for capturing client profiles with state tracking:

Personal Information: Name, Gender, Date of Birth, Marital Status, Religion & Caste, Mother Tongue, Photo URL.

Family Details: Family Type (Nuclear/Joint), Values (Traditional/Moderate/Liberal), Father/Mother Occupations, Siblings.

Education & Career: Education Level, Occupation, Annual Income, Work Location.

Partner Preferences: Age Range, Preferred Religion/Caste, Desired Education, Occupation, and Location.

3. 👥 Client Directory & Profile Detail View

Complete list of registered profiles with status tags (Active, Matched, Pending).

Dynamic live multi-attribute filtering (Keyword search, Gender filter, Status filter).

Comprehensive individual Profile Detail Card rendering all 4 record categories.

4. 🪄 Automated Matchmaking Engine

Select any client to compute compatibility matrix scores against opposite-gender profiles.

Algorithmic scoring evaluating religion alignment, age range preferences, and educational background.

Visual compatibility progress bars (e.g., 92% Match).

5. 💌 Inquiry & Interest Management

Log of all incoming and outgoing interest requests.

Actionable controls for bureau staff to Accept or Reject pending expressions of interest.

6. 💬 Internal Messaging System

Real-time client-to-bureau chat interface simulation.

Active conversation selection sidebar and instant message dispatcher.

7. 💎 Success Stories & Community Showcase

Gallery displaying married couples united by the bureau.

Modal interface for staff to record and publish new success stories.

8. 📈 Analytics, Reports & Export

Graphical demographic representations (Gender ratios via Doughnut charts & Status breakdown via Bar charts powered by Chart.js).

One-click CSV Data Export (exportClientsCSV()) to download all client records directly.

🛠️ Built With

HTML5: Semantic structural layout.

Tailwind CSS: Utility-first CSS library for layout, typography, and dark mode handling.

FontAwesome 6.4.0: Icon kit for intuitive UI navigation.

Vanilla JavaScript (ES6+): In-memory data store, DOM rendering, matrix matching calculations, dynamic routing, and CSV generation.

Chart.js: Dynamic chart rendering for analytics.

⚙️ How to Run the Project

Download or save the application code into an index.html file.

Open index.html in any modern web browser (Google Chrome, Mozilla Firefox, Safari, Microsoft Edge).

No backend, server installation, database setup, or npm install required!

🔒 Session & Authentication Simulation

Click the "Switch Auth" button in the top navigation bar to toggle between:

Bureau Staff / Admin Officer: Full administrative privileges.

Client Mode: Simulated experience as registered client (Priya Patel).# Marraige-bureau-system
