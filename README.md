# EEG_Project_Final_Year



🖼️ UI Flow (Phase 1)
1. Landing Page / Login Screen

Project Title: “EEG-Based Biometric Authentication”

Input fields: Username / ID

Button: Start Authentication

Footer: Powered by Deep Learning + EEG Signals

2. EEG Capture Simulation Page

Header: “Capturing EEG Signals…”

Visual:

Animated brainwave graphic (static image or small animation).

Progress bar (0–100%). For Phase 1 → stop at 20% filled.

Text: “Please relax and listen to the auditory stimulus (music).”

Button (disabled during progress): Processing…

3. Authentication Result Page (Mock)

Card with result:

✅ Authentication Successful (if simulated user = valid).

❌ Authentication Failed (if not).

Show basic details: User ID, Date/Time.

Button: Go Back to Login.

🛠️ Tech Stack for UI (Light Phase 1)

Frontend: React (basic components, useState for progress bar).

Styling: TailwindCSS / simple CSS.

Simulation: Hardcoded progress bar reaching 20% only.

Optional: Lottie animation for brainwave visuals.
