# OxiScan — Smart Oxidative Stress Prediction

OxiScan is a web app that predicts a user's oxidative stress level from a standard blood test report. Built with a Vite + React + TailwindCSS frontend and an Express/Node.js backend (CORS enabled), the system analyzes routine lab values and provides an evidence-based oxidative stress assessment.  
**Live demo:** [OxiScan — Live Demo](https://oxiscan.vercel.app/)

---

## What it does
- Accepts routine blood test values and patient details.
- Runs a prediction pipeline to estimate oxidative stress risk.
- Returns an easy-to-read summary and recommendations.

## Tech stack
- **Frontend:** Vite, React, Tailwind CSS  
- **Backend:** Node.js, Express, CORS  
- **Deployment:** Vercel (frontend) — demo above

## Highlights
- Fast, responsive UI with Tailwind.
- Simple REST API on Express for predictions.
- Designed for quick integration with lab/report upload features.

## Quick start (dev)
1. Clone the repo  
   ```bash
   git clone <your-repo-url>
   cd <repo-folder>
