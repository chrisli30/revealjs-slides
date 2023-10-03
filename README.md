# Reveal.js Slides

## Get Started
1. Install Dependencies, `yarn`
2. Run revealjs program, `yarn start`
   
   
## Exporting to PDF

To export the current slides to a PDF file, run:
1. `npm install decktape`
2. `node_modules/.bin/decktape <URL> <export_filename>

For example, since the default port for reveal.js is 1948, you can run:
`node_modules/.bin/decktape http://localhost:1948/syllabus/8-XCM/3-Jira_Tutorial/Jira_Tutorial_slides.md#/ my_slides.pdf`
