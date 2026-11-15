# Project Overview

## Project Name
CarePilot – AI-Powered Hospital Assistance & Triage System

## Objective
Demonstrate how a browser-based information system can organise fictional patient registration, show provisional rule-based categories, display queue information, and provide general educational information.

## Main Modules
1. Dashboard
2. Patient Registration
3. Patient Management
4. Queue Management
5. Rule-based Educational Chatbot
6. Knowledge Base
7. Reports and Analytics
8. Classical AI vs Modern AI Comparison
9. Project Information

## Architecture
The application is a client-side single-page interface:
- HTML defines the page structure and forms.
- CSS defines layout, colours, responsive behaviour, and component styling.
- Vanilla JavaScript handles navigation, rule matching, LocalStorage, rendering, and CSV/report export.
- LocalStorage persists demo data in the browser.

## Data Flow
Demo form input → JavaScript validation and predefined rules → provisional educational output → LocalStorage → dashboard/patient/queue/report views.

## Important Scope Boundary
The app is a non-clinical educational prototype. It is not clinically validated and must not be used for patient care. No live AI model or external AI API is connected in this version.
