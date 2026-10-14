# Attorneys Arshana Shyamkishore & Associates — Independent website concept

A complete nine-page, static HTML/CSS/JS demo, adapted from the established Abigail Ronald-Louw Attorneys / Wakili wa Tech production layout. No React, no npm build step. Original design layout/components preserved.

## Paths
Home, About, Practice Areas, Our Attorney, Insights, Contact, Privacy, Terms, and custom 404. CSS/JS under assets/.

## Client information and verification
Published email: arshanasnlaw@gmail.com; telephone: 031 464 4940; business WhatsApp: 063 037 9298. Founder Arshana Shyamkishore. Firm location described as Durban/Queensburgh only; exact street address disputed. See RESEARCH-NOTES.md. All four user-supplied attorney photographs used once each in content. All stock photos use unique source IDs. Footer logo truly transparent.

## Contact form
The contact form creates a mailto: draft addressed to arshanasnlaw@gmail.com in the visitor's own email program. Visitor must press Send. It is NOT a server-backed form. Floating WhatsApp links to 063 037 9298.

## SEO, sharing and consent
All nine pages have titles, descriptions, canonical, OG, Twitter image and factual schema; 1200x630 share image: /assets/arshana-social-share.jpg. Intended host is https://arshana-shyamkishore-associates.vercel.app, not deployed/verified. Change host site-wide if the actual Vercel domain differs. All pages carry noindex until client approves public indexing and use of branding/portraits. Robots.txt allows public social crawlers to retrieve metadata while HTML noindex protects against ordinary search indexing. Social preview must be tested after deployment with WhatsApp.

## Run
`python3 -m http.server 8000` from project root. Vercel framework Other, root `.`, output `.`; no build command. Deploy with `npx vercel --yes` for preview; ask permission before production/indexing.

## Needed from client
Confirm exact street address, current office locations, professional qualifications, whether immigration is an active service, photo/logo rights and release authorisation.
