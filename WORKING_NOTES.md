# Working Notes — Nicole Kus Personal Landing Page

> This is an internal working document for developer and AI assistant reference. It is not meant for a public audience and should be updated at the end of each work session.

## How to Use This File (For AI Assistants)

1. Read this entire file before suggesting changes or writing code.
2. Read `README.md` for the public-facing project summary.
3. Follow the project structure and conventions already in place.
4. Do not change the folder structure unless there is a clear reason.
5. Refactor conservatively since this project was AI-assisted.
6. Ask before making major structural or design changes.
7. Do not suggest linking or embedding the resume on the site.

## Current State

**Last Updated:** 2026-03-10

This project is in a strong finished state for the BAIS:3300 assignment. The landing page has been built in Replit, includes all core sections, and is ready to be pushed to GitHub and reviewed on Azure. The site reflects the PRD and STANDARDS files and presents a clean, professional personal landing page.

### What Is Working

- [x] GitHub repository created
- [x] Azure Static Web App connected
- [x] Custom domain configured
- [x] Replit connected to GitHub repo
- [x] `PRD.md` created
- [x] `STANDARDS.md` created
- [x] Hero section completed
- [x] About section completed
- [x] Skills section completed
- [x] Projects section completed
- [x] Contact section completed
- [x] Headshot added to `images/`
- [x] Site preview working in Replit

### What Is Partially Built

- [ ] README.md may still need final review after being added
- [ ] WORKING_NOTES.md may need another update after final push
- [ ] Final Azure check should be completed after pushing changes

### What Is Not Started

- [ ] Any future enhancements beyond assignment requirements
- [ ] Additional project case study pages
- [ ] Expanded animations or advanced interactivity

## Current Task

**What I was working on when I last stopped:**  
I finished reviewing the landing page design and content in Replit and moved on to the final documentation files required for submission. I was working on creating `README.md` and `WORKING_NOTES.md` so the repository includes all required project documentation.

**The very next step is:**  
Push the final files from Replit to GitHub and confirm the deployed site works correctly on Azure.

## Architecture and Tech Stack

| Technology | Version | Why It Was Chosen |
|---|---|---|
| HTML5 | Current | Used to build the structure of the landing page |
| CSS3 | Current | Used for styling, spacing, layout, and responsiveness |
| JavaScript | Minimal / vanilla | Included for future enhancements, but kept light for a simple static site |
| Markdown | Current | Used for project documentation files like PRD, STANDARDS, README, and working notes |
| GitHub | Current | Used for version control and repository hosting |
| Replit | Current | Used for AI-assisted planning, editing, and implementation |
| Azure Static Web Apps | Current | Used to deploy and host the site online |

## Project Structure Notes

```text
nwkus-landing-page/
├── index.html
├── PRD.md
├── STANDARDS.md
├── README.md
├── WORKING_NOTES.md
├── css/
│   └── stylesheet.css
├── js/
│   └── scripts.js
└── images/
    └── headshot.jpg

index.html is the main landing page file.

css/stylesheet.css contains all styling.

js/scripts.js is currently minimal and reserved for future enhancements.

images/headshot.jpg stores the local profile image used on the site.

PRD.md and STANDARDS.md should stay in the root because they are part of the assignment workflow.

The resume file was used as reference material during development but should not be linked on the site.

Data / Database

This project does not use a database or persistent data source. It is a static front-end site.

Conventions
Naming Conventions

Main page file is index.html

Main stylesheet is css/stylesheet.css

JavaScript file is js/scripts.js

Images are stored in the images/ folder

Code Style Rules

Semantic HTML structure

External CSS only

Static single-page layout

Resume should not be linked or embedded on the site

Git Commit Style

Keep commit messages short and descriptive

Example: Add README and working notes

Decisions and Tradeoffs

Decision made: Kept the site as a simple static single-page landing page because that matches the assignment scope and is easier to deploy.

Decision made: Used a clean professional layout instead of something overly styled or flashy because the audience is recruiters and hiring managers.

Decision made: Grouped skills into technical tools and analytics/finance skills to make the page easier to scan.

Decision made: Featured three strong academic/analytics projects to show a mix of Excel, Python, SQL, and Power BI.

What Was Tried and Rejected

Rejected: Linking or embedding the resume on the landing page, because the project instructions and PRD specifically avoided that.

Rejected: Overcomplicating the site with extra features before the core sections were complete.

Rejected: Manual coding from scratch as the main workflow, since the assignment specifically used Replit Plan mode for AI-assisted implementation.

Known Issues and Workarounds

Mobile spacing may still need small refinements depending on device size.

Some project descriptions could be improved later with more measurable outcomes.

No workaround is currently needed because the site is functioning well for assignment purposes.

Browser / Environment Compatibility

Expected to work in Chrome, Safari, and Firefox

Built as a responsive front-end site for desktop and mobile

Previewed in Replit and intended to deploy through Azure Static Web Apps

Open Questions

Should any final wording changes be made before submission?

Does the deployed Azure version match the final Replit version exactly after push?

Session Log
2026-03-10

Created the PRD for the personal landing page

Created and customized STANDARDS.md

Set up GitHub repository and Azure Static Web App

Connected the project to Replit

Added headshot and project files

Used Replit Plan mode to generate the landing page

Reviewed and refined the generated page content and layout

Created documentation files for README.md and WORKING_NOTES.md

Left incomplete: final GitHub push and final Azure check

Next step when resuming: push final code, verify deployment, and capture screenshots for submission

Useful References

BAIS:3300 assignment instructions

Replit AI Plan mode workflow

GitHub repository for version control

Azure Static Web Apps deployment workflow

ChatGPT was used to help generate the PRD, STANDARDS, README, and revision guidance