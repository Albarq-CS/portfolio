# Developer Portfolio Website
## Project Overview
A static personal portfolio with English/Arabic language switching and light/dark themes.

## Problem Statement
Present a developer's background, selected work, technical interests, and professional contact links in one accessible website.

## Key Features
- English and Arabic content with right-to-left switching.
- Persisted theme and language preferences using localStorage.
- Responsive navigation, project sections, and contact links.
- Scroll-based section highlighting and reveal effects.

## Technologies Used
HTML, CSS, vanilla JavaScript, Google Fonts, browser localStorage, and IntersectionObserver. No backend or build pipeline is included.

## Project Structure
| File | Purpose |
| --- | --- |
| `index.html` | Main portfolio implementation |
| `v2index.html` | Alternate existing version retained for comparison |

## Installation and Configuration
No dependencies or secrets are needed:
```sh
python -m http.server 8000
```
Open `http://localhost:8000/`. Alternatively open `index.html` directly. Fonts require network access.

## Usage
Browse the project and background sections; use the language and theme controls. Contact controls link to external professional profiles and email rather than a backend contact form.

## Content Status
The portfolio contains self-authored career and project descriptions. Those descriptions are not independent verification of production experience or a completed AI integration. Keep project status, contribution attribution, and any quantitative claims aligned with their actual evidence.

## Future Improvements
- Add accessible screenshots and verified live project links.
- Review motion reduction, keyboard navigation, contrast, and image performance.
- Replace subjective skill percentages and unverified project claims with concrete examples.
- Consolidate the alternate version only after a separate review.

## Author
[Albarq-CS](https://github.com/Albarq-CS)
