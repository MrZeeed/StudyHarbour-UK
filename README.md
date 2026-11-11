# StudyHarbour UK

A responsive, single-page student-support website with a navy, cream and red design and an original inline SVG illustration.

## Run locally

Download or clone this repository and open `index.html`. Everything needed by the page is inline: there are no packages, external fonts, image downloads or build steps.

For an HTTP preview with Python installed, run `python3 -m http.server 8000 --bind 127.0.0.1` from the project folder and open `http://127.0.0.1:8000`. Stop with Ctrl+C.

## What works

- Home, About Us, Student Support, FAQs and Contact anchors.
- A mobile menu with Escape, outside-click and breakpoint dismissal.
- Five support checklists opened from cards in accessible dialogs.
- Native expandable FAQs.
- Direct links for the checklists: `#applications`, `#courses`, `#accommodation`, `#student-life` and `#careers`.
- Browser Back/Forward and reload for those topic links.
- Reduced-motion styles and keyboard focus indicators.

## Content and contact configuration

The community invitation and contact details have not been supplied. Join buttons intentionally show an availability dialog. There is no registration form or enquiry submission service.

Edit the static text and the `topics` object inside `index.html` to update content. If adding real contact or community links, use details supplied by the owner and update the related FAQ and availability wording together. Do not invent partnerships, testimonials, statistics or contact information.

Colours are CSS variables near the top of the file. The illustration and logo are inline SVG, so they remain available offline.

## Check changes

1. Open each navigation link and each support card.
2. Reload a direct topic URL, then use Back, Forward and the dialog close button.
3. At a phone width, open the menu and close it with Escape, an outside click and a menu action. Confirm its expanded state resets after resizing.
4. Use Tab to reach controls and check the visible focus indicator.
5. Check the Join buttons and FAQs still accurately describe availability.

The site gives general starting points. Keep course-specific requirements and personal immigration advice tied to official sources and the relevant provider's instructions.

## Repository contents

`index.html` contains the complete HTML, CSS, SVG and JavaScript. `README.md` explains setup and maintenance. Hosting is a separate configuration decision; no deployment workflow is included here.
