# JOB-SNAP-EXTENSION-MINI-PROJECT
## JobSnap - Job Application Tracker
Overview: JobSnap is a comprehensive, AI-powered browser extension designed to help job seekers track and manage their applications with high efficiency. It automates repetitive tasks like form auto-filling, provides smart deadline reminders, and leverages the Gemini 2.5 Flash model to offer deep ATS (Applicant Tracking System) resume optimization and recruiter impact analysis.

## Features:

AI-Driven ATS Optimization: Analyzes resumes against job descriptions to provide a mathematical match score and keyword saturation reports.

Recruiter Impact Analysis: Evaluates human appeal factors such as quantifiable achievements, action verb strength, and professional tone.

Smart Reminders & Notifications: Automatically checks for upcoming application deadlines and interviews on browser startup or via periodic alarms.

Intelligent Auto-Fill: Streamlines the application process by auto-filling fields on major job boards like LinkedIn, Indeed, and Naukri.

Career Intelligence Slider: Provides horizontal, interactive "Career Intel" cards with real-time market trends and personalized action tips.

Advanced Analytics Dashboard: Visualizes the job search funnel, including conversion rates and application-to-interview metrics.

Theme Customization: Supports a sleek "Aurora Borealis" animated background with fully integrated Dark Mode.

## Software Tools Used:

JavaScript (ES6+): Core logic for background workers, content scripts, and UI interactions.

HTML5 & CSS3: Frontend structure and premium styling (Glassmorphism, CSS Variables, and Keyframe animations).

Chrome Extension API: Manifest V3, including sidePanel, alarms, notifications, and scripting.

Google Gemini AI API: Powers the "JobSnap AI" expert for resume auditing and career insights.

Python: Used for backend model listing and auxiliary scripts.

## Project Architecture: The project follows a modular extension architecture:

manifest.json: Configuration, permissions, and service worker registration.

background.js: Manages lifecycle events, alarms, and system-level notifications.

contentScript.js: Injects the persistent floating FAB widget and handles DOM-level job detection.

popup.js: Orchestrates the main UI logic, navigation, AI integration, and state management.

popup.html / popup.css: Provides the responsive user interface and premium visual effects.

models.json: Configuration for supported generative AI models.

## Supported Functionalities:

Job Tracking (Applied, Shortlisted, Interviewed, Rejected, Offer).

Resume & JD Comparison (Dual Score System).

Task Management (Custom checklists per job application).

CSV Export (Download job data for external tracking).

Premium License Verification (Integrated payment and trial logic).

Secure Data Storage (Chrome Local Storage with cloud sync potential).

## Future Enhancements:

Multi-Domain Expansion: Extend career intelligence to niche fields like embedded systems and ERP modules.

Secure Backend Proxy: Route all AI API calls through a secure server to protect sensitive API keys.

CI/CD Integration: Automate testing of content script injections across evolving job board layouts.

Enhanced Resume Parsing: Incorporate more granular visual parsing for complex multi-column resume layouts.

## OUTPUT 

## Conclusion

JobSnap represents a significant advancement in personal job search management by bridging the gap between manual tracking and intelligent automation. By integrating Gemini AI directly into the browser workflow, it empowers candidates to optimize their profiles for both bots (ATS) and humans (Recruiters). The modular architecture and premium UI design ensure it remains a scalable, high-performance tool that reduces the manual burden of the job hunt while providing the analytical insights necessary to secure offers in a competitive market.
