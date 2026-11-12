# Chief of Staff Dashboard setup

Set up your own **Chief of Staff Email & Teams Dashboard** in Microsoft 365 Copilot Cowork.

**Open the setup page: https://brentwhichel.github.io/cos-dashboard-setup/**

Enter your priorities, people and accounts once. The page turns them into the exact Cowork prompts that build a private dashboard in your own Microsoft 365: every email and Teams message that needs you, screened against your Chief of Staff constitution, researched, and drafted in your voice. Nothing is sent until you press Send.

## What the page gives you

- Nine personalized setup steps, each with a Copy button: your constitution, the private feed, the dashboard app, email screening, customer email, instant alerts for key people, the Teams sweep, a catch-up test, and an audit plus weekly tuning.
- A setup pack (.zip) with every prompt and a checklist, and the dashboard app's source files, already set up with your email, time zone and folder.
- Prompts to add a priority person or a customer account later.

## What you need

- Microsoft 365 Copilot with Cowork, including automations (event triggers and scheduled tasks) and App Builder.
- Your own Outlook, Teams and OneDrive.
- About 45 minutes, plus 15 minutes after the first week.

## Privacy

The page runs entirely in your browser. Nothing you type is sent anywhere: your answers stay in your browser and in the files you choose to download. All names in the built-in example are fictional.

## How this repository publishes

`docs/index.html` is the whole page. The workflow in `.github/workflows/publish.yml` deploys `docs/` to GitHub Pages whenever it changes, or when the repository owner posts an update to the **Publish channel (automated)** issue.
