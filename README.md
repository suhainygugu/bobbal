# Dashboard DFS40303 ISMS

An interactive English-language dashboard for a polytechnic lecturer teaching Semester 4 diploma students.

## Run locally

The dashboard is a self-contained static website with no dependencies or build step.

```sh
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000 in a browser.

## Features

- Colourful, responsive dashboard and focused sidebar navigation.
- Editable 120-minute practical lesson, activity ordering and duration warnings.
- Information security case study, task instructions and evidence links.
- Twelve fictional students across three groups, with competency tracking and feedback.
- Editable weighted rubric, incomplete-assessment handling and calculated scores.
- Follow-up notes, mastery chart, printable reports and CSV export.
- Local browser storage and confirmed demo reset.

All initial records are labelled **Demo Data**. Edits are stored only in the current browser and device. Document links record references; they do not upload files. The prototype has no application backend or cloud data storage.

## Using the dashboard

Use **Practical lesson planner** to edit lesson details and tasks, **Student competencies** to update statuses and open student rating panels, and **Assessment rubric** to edit criterion descriptors and weights. Export CSV or print reports to keep a copy of your records.

## Source

`dist/index.html` contains the HTML, styling and interactive JavaScript. Serve the `dist` directory using any static website host.
