# Smart Mobile Oil-Water Treatment Dashboard

**UI/UX Design | Data Visualization | AI Decision Support | Real-Time Monitoring**

**Role:** UI/UX Designer & Software Engineer  
**Project Type:** Capstone Project  


---

## 🔗 Project Links

**Dashboard Demo**  
https://canva.link/yeykr6jnb4wttxa

---

# Project Overview

The Smart Mobile Oil-Water Treatment Dashboard is a real-time monitoring platform designed for an AI-powered mobile oil-water treatment system. The dashboard transforms live sensor data into meaningful operational insights, enabling operators to monitor treatment performance, detect abnormal conditions, and make informed decisions.

The project focused on designing an intuitive engineering dashboard that simplifies complex industrial data while integrating AI-assisted decision support into a clear, user-centered experience.

---

# The Problem

Traditional industrial monitoring systems often present operators with large volumes of raw sensor data distributed across multiple screens. This makes it difficult to quickly identify abnormal conditions, understand system health, and respond efficiently to operational issues.

The challenge was to design an interface that could:

- Present complex engineering data without overwhelming users.
- Improve situational awareness.
- Enable rapid identification of abnormal conditions.
- Clearly communicate AI-generated insights.
- Support continuous monitoring with minimal cognitive load.

---

# Users

### Primary Users

- Plant Operators
- Process Engineers
- Maintenance Engineers

### User Goals

- Monitor system performance in real time.
- Detect abnormal operating conditions quickly.
- Track the performance of each treatment stage.
- Understand AI-generated recommendations.
- Make faster and more informed operational decisions.

---

# Research

## User Interviews

The design process began with user interviews involving operators, engineers, and project stakeholders to better understand monitoring workflows, operational challenges, and information needs.

### Key Insights

- Operators found it difficult to monitor multiple sensor readings simultaneously.
- Critical alarms needed to stand out immediately.
- Users preferred viewing information according to treatment stages rather than individual sensors.
- AI predictions were more useful when accompanied by explanations and recommended actions.
- Continuous monitoring required a clean interface that reduced visual fatigue and cognitive load.

These insights guided the dashboard architecture, navigation, and visualization strategy.

---

# Design Challenges

- Displaying a large number of live sensor readings without overwhelming users.
- Presenting engineering data in a way that supports quick interpretation.
- Organizing information to match operator workflows.
- Making AI recommendations understandable and trustworthy.
- Designing an interface suitable for continuous monitoring.

---

# Design Goals

- Simplify complex engineering information.
- Reduce cognitive load through effective information hierarchy.
- Improve visibility of critical operational data.
- Increase situational awareness.
- Design intuitive AI-assisted decision support.
- Ensure readability across different screen sizes.

---

# Design Process

### 🔍 1. User Research

Conducted user interviews to understand:

- User workflows
- Pain points
- Monitoring priorities
- Decision-making process

Research findings were translated into functional and usability requirements.

---

### 📋 2. Define

Based on the interviews, the primary design objectives were established:

- Reduce information overload.
- Prioritize critical system information.
- Improve monitoring efficiency.
- Support AI-assisted decision making.
- Design around operator workflows instead of system architecture.

---

### 🗂 3. Information Architecture

Information was organized according to how operators monitor the treatment process rather than how sensor data is stored.

Dashboard sections include:

- System Overview
- Live KPIs
- Tank Monitoring
- Treatment Stages
- Maintenance
- AI Decision Support
- Alarm Management
- Historical Analytics

This organization allows users to move naturally from high-level monitoring to detailed diagnostics.

---

### ✏️ 4. Wireframing

Created low-fidelity wireframes to define:

- Dashboard layout
- Information hierarchy
- User flow
- Component placement

Multiple layout iterations were explored before selecting the final structure.

---

### 🎨 5. UI Design

Designed high-fidelity interfaces focused on clarity and usability.

The interface includes:

- KPI cards
- Interactive charts
- AI insight panels
- Alarm notifications
- Maintenance indicators
- Responsive layouts

The design uses a dark theme, consistent typography, balanced spacing, and reusable components to support long monitoring sessions.

---

### ✅ 6. Heuristic Evaluation

Before user testing, the interface was evaluated using **Nielsen's 10 Usability Heuristics**.

The evaluation focused on:

- Visibility of system status
- Match between system and the real world
- Consistency and standards
- Recognition rather than recall
- User control and freedom
- Error prevention
- Information hierarchy

The review resulted in refinements to dashboard organization, navigation, visual hierarchy, and feedback mechanisms.

---

### 🧪 7. Usability Testing

After completing the interface, usability testing was conducted using representative monitoring tasks.

Participants completed tasks such as:

- Monitoring overall system health.
- Identifying abnormal sensor readings.
- Locating active alarms.
- Finding maintenance information.
- Understanding AI recommendations.

### Improvements After Testing

- Increased emphasis on critical KPIs.
- Improved spacing between dashboard sections.
- Simplified chart layouts.
- Refined AI insight cards.
- Increased contrast for critical alerts.
- Improved navigation between monitoring sections.

---

# UX Design Decisions

## Progressive Information Hierarchy

Interview participants indicated that they first wanted to understand the overall system status before exploring detailed sensor information.

To support this workflow, the dashboard presents:

- Overall system health
- Critical KPIs
- Active alarms

before displaying detailed process data.

This reduces cognitive load and supports faster decision making.

---

## Stage-Based Monitoring

Rather than grouping data by sensor type, information is organized according to the four treatment stages:

- Feed / DAF
- Sand Filter
- Adsorption
- Membrane

This mirrors the physical treatment process, making it easier to identify where abnormalities originate.

---

## Data Visualization

Different visualization methods were selected based on the type of information presented.

Examples include:

- KPI cards for live measurements.
- Time-series charts for trends.
- Binary indicators for level sensors.
- Gauge charts for operational status.
- Color-coded alerts for abnormal conditions.

Each visualization was selected to minimize interpretation time.

---

## AI Decision Support

User interviews showed that prediction values alone were insufficient for decision making.

Instead of simply displaying predictions, the dashboard answers three questions:

**What happened?**

- Detected violations
- Performance trends

**Why did it happen?**

- Root-cause explanation

**What should I do next?**

- Corrective action recommendations

Providing explanations alongside predictions improves transparency and user trust.

---

## Visual Hierarchy & Color

Color was intentionally used to communicate system health:

🟢 Normal

🟡 Warning

🔴 Critical

Combined with typography, spacing, and component sizing, the visual hierarchy enables operators to recognize abnormal conditions within seconds.

---

## Designing for Continuous Monitoring

Since operators monitor the dashboard for extended periods, the interface was designed to reduce fatigue through:

- Dark theme
- Balanced whitespace
- Readable typography
- Consistent layouts
- Logical grouping of information

---

# Final Solution

The final dashboard combines:

- Real-time monitoring
- AI-assisted decision support
- Interactive visualizations
- Alarm management
- Maintenance monitoring
- Historical analytics

into a unified interface that enables efficient monitoring and faster operational decision making.

---

# My Contributions

- Led the complete UX/UI design process.
- Conducted user interviews and synthesized research findings.
- Designed the information architecture and dashboard workflow.
- Created low-fidelity wireframes.
- Designed high-fidelity interfaces in Figma.
- Conducted heuristic evaluation.
- Planned and conducted usability testing.
- Designed real-time data visualizations.
- Developed the dashboard using Streamlit and Plotly.
- Integrated the interface with Raspberry Pi, InfluxDB, and AI models.

---

# Tools & Technologies

| Category | Tools |
|----------|-------|
| UX/UI Design | Figma |
| Frontend | Streamlit |
| Data Visualization | Plotly |
| Backend | Python, Pandas |
| Database | InfluxDB |
| Hardware | Raspberry Pi 4 |
| AI | Machine Learning Models |

---

# Outcome

The final dashboard provides operators with a centralized platform for monitoring the complete treatment process. By combining real-time visualization with AI-assisted decision support, the interface improves situational awareness, simplifies complex engineering data, and enables faster, more informed operational decisions.

---

# Reflection

This project strengthened my ability to design data-intensive interfaces for complex engineering environments. It reinforced the importance of user research, information architecture, iterative design, and usability evaluation in creating dashboards that are not only visually effective but also support real-world decision making. It also demonstrated how thoughtful UX design can improve the transparency and usability of AI-driven systems.
