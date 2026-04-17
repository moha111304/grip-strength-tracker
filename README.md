# GripStrength
**A Recovery-First Physical Therapy Tracker for Hand & Wrist Rehabilitation.**

GripStrength is a mobile-oriented health utility designed for patients recovering from metacarpal fractures and wrist injuries. It replaces messy paper logs with a data-driven interface that tracks daily therapeutic progress, measures dexterity through typing tests, and visualizes the journey from injury to 100% recovery.

---

## The Vision
After a traumatic hand injury (like a snowboarding accident), the hardest part of recovery is the "Invisible Progress." `GripStrength` makes that progress visible, providing the psychological motivation needed to stick to a 12-week physical therapy plan.

### Key Features
* **Progress Photo Timeline:** A specialized "Before & After" gallery to track swelling reduction and surgical scar healing.
* **Pain & Mobility Logging:** Quick-entry sliders to log daily pain levels and range-of-motion (ROM) percentages.
* **Integrated Dexterity Test:** A built-in "Typing Speed" module (WPM) to measure real-world functional recovery of the fingers.
* **Recovery Analytics:** Interactive line charts showing the correlation between exercise frequency and pain reduction.

---

## Technical Architecture



### The Stack
* **Frontend:** React with **Tailwind CSS** (for a sleek, mobile-first "App" feel).
* **Backend:** Node.js / Express (The "Health Engine").
* **Database:** PostgreSQL — optimized for time-series data (logging entries by date).
* **Visualization:** **Chart.js** or Recharts to render the recovery curves.

### The User Flow
1.  **Daily Log:** The user opens the app and spends 30 seconds moving sliders for pain and stiffness.
2.  **Exercise Check:** User ticks off completed PT exercises (Tendon Glides, Stress Ball, etc.).
3.  **The "Test":** Once a week, the user performs a 1-minute typing test to update their "Functional Dexterity" score.
4.  **Insights:** The app generates a report: *"Your WPM has increased by 15% since the splint came off!"*

---

## Roadmap
- [ ] **Phase 1:** Build the "Quick Log" mobile UI and PostgreSQL schema for time-stamped entries.
- [ ] **Phase 2:** Integrate a Line Chart to visualize pain levels over a 7-day rolling window.
- [ ] **Phase 3:** Develop the JavaScript-based WPM test module.
- [ ] **Phase 4:** Add "Milestone Notifications" (e.g., "60 Days Post-Op: Milestone Reached!").

---