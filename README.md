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

# My job page 
<img width="706" height="925" alt="Screenshot 2025-12-26 101227" src="https://github.com/user-attachments/assets/349409a6-7c26-448a-8b75-a6417c23737c" />
# Add job page
<img width="711" height="923" alt="Screenshot 2025-12-26 101258" src="https://github.com/user-attachments/assets/0e62326e-dbb6-44be-a021-6f8223c09e6d" />
# Side bar 
<img width="706" height="921" alt="Screenshot 2025-12-26 101241" src="https://github.com/user-attachments/assets/6367b3f9-16f5-4080-8e09-50e3ce7fa56f" />
# ATS page
<img width="701" height="924" alt="Screenshot 2025-12-26 101308" src="https://github.com/user-attachments/assets/754e9977-ff94-4793-a155-465edee66c3a" />
# Analytics page
<img width="701" height="924" alt="Screenshot 2025-12-26 101308" src="https://github.com/user-attachments/assets/a94c4ac2-ca7e-4ab1-8e5d-a4e4516b7912" />
# Carrer intel page 
<img width="702" height="912" alt="Screenshot 2025-12-26 101352" src="https://github.com/user-attachments/assets/cba3e507-3291-42f5-af3e-fda513f5975c" />
<img width="699" height="911" alt="Screenshot 2025-12-26 101343" src="https://github.com/user-attachments/assets/f06343d9-de14-40f9-80e2-a5a64da9a244" />
#Info page 
<img width="698" height="917" alt="Screenshot 2025-12-26 101402" src="https://github.com/user-attachments/assets/40a5afea-0159-46a2-b870-c9dd01262690" />
#Dark mode 
<img width="584" height="564" alt="Screenshot 2025-12-26 101409" src="https://github.com/user-attachments/assets/b493584b-7fcd-4ab9-a0f1-a130fedf31c5" />
<img width="584" height="564" alt="Screenshot 2025-12-26 101409" src="https://github.com/user-attachments/assets/c1a6f83f-30c1-4db3-a826-0c99d4ab4320" />
<img width="687" height="917" alt="Screenshot 2025-12-26 101416" src="https://github.com/user-attachments/assets/d1174bb9-7b88-4de0-bfcd-ad9a2c67ecaa" />
<img width="701" height="913" alt="Screenshot 2025-12-26 101425" src="https://github.com/user-attachments/assets/09c88504-8179-4984-a830-1406839300e0" />
<img width="683" height="915" alt="Screenshot 2025-12-26 101434" src="https://github.com/user-attachments/assets/d2dfb023-f8ce-41a3-ad5f-7181b3cd3705" />
<img width="678" height="919" alt="Screenshot 2025-12-26 101442" src="https://github.com/user-attachments/assets/d8459f95-fa4f-4f1a-bb9c-bac25adabc2f" />

# At web pages
<img width="1920" height="1080" alt="Screenshot 2025-12-26 101456" src="https://github.com/user-attachments/assets/0126b2f9-99dd-4f5b-9efe-f60c6720b251" />
<img width="1920" height="1080" alt="Screenshot 2025-12-26 101504" src="https://github.com/user-attachments/assets/2af8fe32-ed49-4ebb-984a-0183b3331d74" />




## Conclusion

JobSnap represents a significant advancement in personal job search management by bridging the gap between manual tracking and intelligent automation. By integrating Gemini AI directly into the browser workflow, it empowers candidates to optimize their profiles for both bots (ATS) and humans (Recruiters). The modular architecture and premium UI design ensure it remains a scalable, high-performance tool that reduces the manual burden of the job hunt while providing the analytical insights necessary to secure offers in a competitive market.
