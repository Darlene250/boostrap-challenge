# Full Stack Conf: Bootstrap Activity Challenge

A responsive, one-page conference website built with **Bootstrap 5 only**, replicating the provided project demo. It uses no custom JavaScript and no other frameworks.

**Course:** Advanced Front-end Web Development, Cohort 1, Team 6

## Team task sheet

[BSE Group Assignments: Task Sheet, Bootstrap Activity Challenge (Team 6)](https://docs.google.com/spreadsheets/d/13gZvkeeiHO9onyuCpNJwWiRnCnyL6P0yjtQGS6kgjUA/edit?usp=sharing)

A PDF copy of the sheet is also in this repository.

## Team and contributions

| Member | Section |
|---|---|
| Darlene Ayinkamiye | Navbar and hero section; Speakers cards and Schedule list |
| Kellen Mutoni | Three-column section (Expert Speakers, About, What you will Learn) |
| Tumba II Kongolo | Register button, registration pop-up form and footer |
| Lincoln Batsinduka | Speakers cards and Schedule list (assigned) |

Individual contributions can be checked in the repository's commit history. The task sheet above records who completed each task.

## Page sections

1. **Navbar:** dark top bar with Home, About, Speakers and Schedule links, plus "Powered By PARAGRAPH".
2. **Hero:** conference title, tagline, and the "Register Now" and "See Speakers" buttons.
3. **Three columns:** Expert Speakers, About Full Stack Conf, and a "What you will Learn" list.
4. **Speakers:** a responsive grid of six speaker cards.
5. **Schedule:** a list of sessions with time badges.
6. **Register:** a modal form with basic info, topic checkboxes and payment info, opened by the register buttons.
7. **Footer:** about text, a sign-up field, links and an "Other Confs" dropdown.

## Built with

- [Bootstrap 5.3.3](https://getbootstrap.com/) (CSS and JS bundle, loaded from the jsDelivr CDN)
- Semantic HTML5

The modal, alerts and dropdown use Bootstrap's built-in `data-bs-*` attributes, so no custom scripts are needed.

## Responsive behavior

The page uses Bootstrap's grid and responsive utilities. It works on mobile, tablet and desktop: the three columns and the speaker cards stack on small screens and sit side by side on medium screens and up.

