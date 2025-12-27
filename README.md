TaskGlitch – Task Analytics Dashboard

TaskGlitch is a lightweight task management and analytics dashboard built as part of a technical assignment.
The project focuses on fixing functional bugs, improving stability, and deploying a production-ready React application.

Live Demo

🔗 Live App:
https://khajahussain-taskglitch.vercel.app

🔗 GitHub Repository:
https://github.com/Khshaikh-19/task-glitch

Tech Stack

Frontend: React + TypeScript

UI Library: Material UI (MUI)

Build Tool: Vite

State Management: React hooks

Deployment: Vercel

Version Control: Git & GitHub

What Was Done (Bug Fixes)

The following issues were identified and fixed during the assignment:

1. Duplicate API / state updates

Cause: React StrictMode triggering double renders in development

Fix: Adjusted logic to prevent duplicate fetch/state updates

2. Snackbar undo behavior

Issue: Snackbar closing unexpectedly and undo not resetting state properly

Fix:

Handled clickaway close reason

Ensured undo action restores state correctly

3. Unstable task sorting

Issue: Tasks reshuffled randomly due to non-deterministic sorting

Fix:

Added a deterministic tie-breaker using createdAt

Ensured consistent sorting based on ROI, priority, and creation time

All fixes were committed with clear commit messages and separate commits (no single giant commit).

Project Setup (Local)

# Clone the repository
git clone https://github.com/Khshaikh-19/task-glitch.git

# Move into the project directory
cd task-glitch

# Install dependencies
npm install

# Start development server
npm run dev

Deployment

The application is deployed on Vercel and connected directly to the main branch.
Every push to main triggers an automatic redeployment.


