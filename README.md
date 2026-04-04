# KodaKodra — Step 2: Multi-Page HTML Brochure

## What This Is
The single page landing from Step 1 expanded into a full multi-page brochure site. Content that previously lived in one scrollable page now has its own dedicated page with room to breathe. Navigation links between all pages.

## What This Demonstrates
- Multi-page site structure with consistent navigation
- Internal linking between pages using relative URLs
- Active state on navbar to reflect current page
- Content architecture — knowing what belongs where
- Consistent layout, branding, and styling across multiple pages
- Informational contact page without a functional form

## Pages
- `index.html` — home/landing with hero and snapshot cards linking to each section
- `about.html` — full background, approach, and tech stack
- `services.html` — expanded service listings with a project approach notes section
- `contact.html` — social and platform links, availability blurb

## Tech Used
- HTML5
- CSS3
- Bootstrap 5
- Font Awesome 6

## Notes
- No JavaScript, no PHP, no database — intentionally static at this stage
- Navbar and footer are duplicated across pages — PHP includes in Step 3 will fix this
- Contact page is informational only — form and PHPMailer added in Step 3
- All subsequent steps build on this same base without retrofitting
