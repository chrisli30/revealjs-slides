# Reveal.js Slides
Check out existing slides at https://chrisli30.github.io/revealjs-slides
## Get Started
1. Install Dependencies, `yarn`
2. Run revealjs program, `yarn start`
   
## Adding Slides
1. Duplicate an existing slide file in `slides/`. Note that the file name has to end with `_slides.md`.
2. Git commit the file into the `main` branch. If you don’t have permission to do so, create a pull request or contact the owner of this repo.
3. Once the changes are committed into main, it will be auto-deployed to ()[https://chrisli30.github.io/revealjs-slides] in 5 minutes.

## Exporting to PDF

To export the current slides to a PDF file, run:
1. `npm install decktape`
2. `node_modules/.bin/decktape <URL> <export_filename>

For example, since the default port for reveal.js is 1948, you can run:
`node_modules/.bin/decktape http://localhost:1948/syllabus/8-XCM/3-Jira_Tutorial/Jira_Tutorial_slides.md#/ my_slides.pdf`
