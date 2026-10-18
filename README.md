[README.md](https://github.com/user-attachments/files/33626116/README.md)
# Andon Advisor Performance Dashboard

## Repository name

`andon-advisor-performance-dashboard`

## GitHub description

Browser-based weekly advisor performance dashboard generator built with HTML, CSS, and vanilla JavaScript. Turns ASR, ART, and QoS CSV exports into trends, rankings, target comparisons, and coaching insights.

---

# Andon Advisor Performance Dashboard

A lightweight, browser-based tool for turning weekly ASR, ART, and QoS CSV exports into a standalone advisor performance dashboard. It brings team trends, metric targets, advisor rankings, and potential coaching areas into one view.

The generator processes the selected CSV files in the browser and downloads the completed dashboard as a standalone HTML file. It requires no Python service, database, or JavaScript framework.

## Features

- Upload ASR, ART, and QoS CSV exports
- Set reporting week, year, comparison week, and metric targets
- View team-level weekly performance and recent trends
- Compare advisor results against configurable targets
- Classify performance across six metrics
- Review rankings, advisor highlights, and potential coaching areas
- Download the generated dashboard as a standalone HTML file
- Use a responsive layout on desktop and mobile screens

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- Browser File API for reading CSV files
- Browser Blob and download APIs for generating the output HTML

## Getting started

1. Clone or download this repository.
2. Open `andon_dashboard_generator_v2.html` in a modern web browser.
3. Enter the reporting week, previous-week comparison values, and metric targets.
4. Upload the matching ASR, ART, and QoS CSV exports.
5. Select **Generate Dashboard**.
6. Download the generated standalone HTML dashboard.

No build step or package installation is required.

## Input data

The generator expects three CSV exports: ASR, ART, and QoS. The current parser is designed around particular report layouts and column positions; files with different headers or layouts may need parser changes. Use anonymized or synthetic data when trying the project publicly.

## Privacy and responsible use

CSV files are read in the browser by the page. The generated dashboard contains the uploaded performance data. Do not publish real employee, customer, or company-confidential data in this repository, in sample files, or in a generated dashboard. Confirm that you have permission to use and share any data before uploading it to a public service.

## Project impact

The dashboard was created to help managers and leadership review weekly performance for an organization supporting 300+ advisors. Based on reported operational timings, it reduced dashboard preparation from 2–3 hours to 5–8 minutes per manager. Treat any organization-wide time-savings figure as an estimate unless it has been independently measured and validated.

## Limitations

- This is a client-side HTML/CSS/JavaScript application; it does not include a Python backend, database, login, or centralized data storage.
- CSV parsing assumes the report formats expected by the current JavaScript parser.
- The generated HTML is a data-bearing report and should be handled with the same care as its source CSV files.

## Contributing

Suggestions and improvements are welcome. Before submitting changes, describe the expected CSV format and include only synthetic or anonymized examples.

## License

No license has been specified yet. Add a license before inviting others to reuse, modify, or redistribute this project.
