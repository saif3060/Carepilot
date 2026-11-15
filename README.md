# CarePilot – AI-Powered Hospital Assistance & Triage System

CarePilot is a standalone, browser-based educational prototype that demonstrates patient registration, provisional rule-based priority categorisation, queue management, department suggestions, a rule-based chatbot, a knowledge base, and basic reports.

> **Important:** CarePilot is a college/learning demonstration only. It is not a medical device, is not clinically validated, and must not be used for real patient care, diagnosis, treatment, or emergency decision-making. Priority labels are illustrative only. Real health concerns must be assessed by qualified healthcare professionals. For emergencies, contact local emergency services immediately.

## Features

- **Dashboard:** summary cards, priority distribution, department-wise counts, recent registrations, and activity.
- **Patient registration:** captures basic demo details and reported symptoms, duration, and severity.
- **Rule-based demonstration:** applies predefined keyword and condition rules to produce an explainable provisional category.
- **Priority categories:** High, Medium, Low (Demo), and Needs Human Review.
- **Patient management:** view, search, filter, edit, and delete demo records.
- **Queue management:** view the demonstration queue and update record status.
- **Educational chatbot:** responds using predefined rule-based patterns; it does not connect to a live AI model.
- **Knowledge base:** browse and search the included educational information.
- **Reports and analytics:** view counts/charts and export demo records as CSV or a summary.
- **Local browser storage:** demo records persist in the browser using `localStorage`.

## Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Browser LocalStorage

There is no backend server, external database, machine-learning model, or external API required for the core application.

## Run Locally

### Option 1: Open directly

1. Download or clone this repository.
2. Open the project folder.
3. Double-click `index.html` or open it in a modern browser.

### Option 2: Use VS Code

1. Open the project folder in Visual Studio Code.
2. Open `index.html`.
3. Run it with the Live Server extension, or open the file directly in your browser.

No `npm install`, build command, environment variables, or API key is required.

## GitHub Setup

### Create a repository on GitHub

1. Sign in to GitHub and select **New repository**.
2. Enter a repository name, for example `CarePilot-Hospital-Assistance`.
3. Add a short description: `A standalone educational hospital assistance and rule-based triage prototype`.
4. Choose Public or Private according to your preference.
5. Create the repository.

### Upload using the GitHub website

1. Open your new repository.
2. Select **Add file → Upload files**.
3. Upload `index.html`, `README.md`, `LICENSE`, and `.gitignore` from this project folder.
4. Commit the changes.

### Or upload using Git

```bash
git init
git add .
git commit -m "Initial commit: add CarePilot hospital assistance prototype"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/CarePilot-Hospital-Assistance.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username and update the repository URL if you chose a different name.

## Project Structure

```text
CarePilot-Hospital-Assistance/
├── index.html
├── README.md
├── LICENSE
├── .gitignore
└── docs/
    └── PROJECT_OVERVIEW.md
```

The original application is intentionally kept in one `index.html` file. Its CSS and JavaScript are embedded in that file, so the project can be run without a build setup.

## How It Works

1. A user enters fictional/demo patient details in the registration form.
2. JavaScript checks the submitted information against predefined demonstration rules.
3. The interface displays an explainable provisional category and related informational guidance.
4. The record is stored in browser LocalStorage.
5. Dashboard, patient management, queue, and report views read the stored demo records.

## AI Implementation – Be Accurate When Presenting This Project

The current implementation uses **classical, rule-based logic** (predefined conditions and keyword matching). The chatbot uses predefined response patterns. The project does **not** currently run a trained machine-learning model, generative AI model, or external AI API.

The “Modern AI” section is a conceptual comparison for learning purposes, not an implemented feature. Do not describe the prototype as connected to a live AI service.

## Data and Privacy Notes

- The app stores records in the current browser's LocalStorage.
- Data is not synchronised to a server or shared between browsers/devices.
- Use fictional sample data only. Do not enter real patient or sensitive personal information.
- Clearing browser site data may remove locally stored records.

## Limitations

- The rules are illustrative and have not been medically validated.
- Keyword matching may misinterpret or miss the meaning of a description.
- The application cannot diagnose, prescribe, or guarantee that a priority category is safe.
- The prototype has no authentication, backend, role-based access control, or secure clinical database.
- The chatbot is not a substitute for a qualified healthcare professional.

## Future Scope

- Add a secure backend and authentication.
- Add role-based access for reception staff and authorised clinicians.
- Add a properly governed database and audit logging.
- Improve accessibility and multilingual support.
- Evaluate any future clinical decision-support features through appropriate expert, regulatory, privacy, and safety review before real-world use.

## Contribution

For a college team project, add your actual team members, roles, institution, and project guide details here. Only list contributions that each member genuinely completed.

## License

This project is provided under the MIT License. See [LICENSE](LICENSE).
