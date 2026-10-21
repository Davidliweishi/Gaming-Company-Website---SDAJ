# Group-1---Web-Project---SDAJ

# SDAJ – Game Studio Website

A multi-page website for **SDAJ**, a made-up game development company based in Melbourne, Australia, whose tagline is *"Timeless Classics, Forged in Darkness..."*. We built it as a group project for a web development unit at Swinburne University of Technology in 2025.

The site is plain HTML and CSS, with no frameworks and no JavaScript.

## Pages

| Page | File | What it does |
|------|------|--------------|
| Home | `index.html` | Introduces the studio, with navigation and contact links |
| Careers | `jobs.html` | Job openings table, employee benefits, and the hiring process |
| Apply | `apply.html` | Job application form with HTML5 validation (job reference number, date of birth, postcode, email and phone patterns, plus skills checkboxes) |
| About | `about.html` | Team profiles, roles, a team photo, and a table of team details |

## Features
- Semantic HTML5 structure across every page
- Shared external stylesheets (`styles/layout.css`, `styles/colours.css`) for a consistent dark fantasy theme
- Client-side form validation using only HTML attributes (`pattern`, `required`, `maxlength`)
- Accessible markup: alt text on images and ARIA attributes

## Project Structure
├── index.html
├── about.html
├── apply.html
├── jobs.html
├── styles/         # current stylesheets
├── outdated-css/   # earlier stylesheet versions
└── images/

## Running It
No build step is needed. Clone the repo and open `index.html` in a browser.

> Note: the application form posts to a Swinburne test endpoint (`mercury.swin.edu.au`), so submitting it only works as a demo.

## Team
| Name | Role | Contribution |
|------|------|--------------|
| Ari Stein | Project Manager | Jobs page, code validation |
| Jack Rosewarne | Developer | About page, Jira |
| Silang Song | Developer | Apply page, organising meetings |
| David Wei | Developer | Home page, submission |

Project management: Jira · Version control: Git/GitHub
