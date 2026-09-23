# Rammolai Foundation Website POE Part 1

## Project Title

Rammolai Foundation - Website Development Project (WEDE5020 POE)

## Student Information

- **Name:** Dimpho Masilo
- **Student Number:** ST10500849
- **Module:** WEDE5020 - Web Development (Introduction)

## Project Overview

**Rammolai Foundation** (NPO 262-788 NPO) is a small family-run charity based in Pretoria, South Africa, founded and led by Motlomo, Tshegofatso, and Debra Ramatlo. Guided by the tagline “A small charity has a big impact”, the Foundation supports underprivileged learners across Pretoria through school shoe drives, uniform donations, and sanitary towel and toiletry campaigns. The mission is to give underprivileged children access to the basic school essentials and dignity they need to attend school with confidence. The vision is a Pretoria where no child is held back from school due to a lack of shoes, uniforms, or sanitary products. The target audience includes underprivileged primary and high school learners in Pretoria and Atteridgeville, along with their parents, teachers, corporate sponsors such as Shoprite, and community volunteers.

## Website Goals and Objectives

The website is meant to raise awareness of the Foundation’s work and give it a permanent, professional home online where people can donate money or items, sign up to volunteer, and stay up to date with campaigns without relying solely on Facebook. It also builds credibility with larger donors, such as Shoprite, by transparently showcasing the Foundation’s NPO registration and history of previous drives.

**Key Performance Indicators (KPIs):**

- 25% increase in monthly website visitors within 3 months
- 10% donation conversion rate
- 15 new volunteer or drop-off sign-ups per month
- 35% newsletter sign-up rate monthly

## Key Features and Functionality

| Feature       | Description                                                                                                      |
| ------------- | ---------------------------------------------------------------------------------------------------------------- |
| Structure     | I will use HTML to build a clear, standards-compliant page structure for each of the five core pages.            |
| Styling       | I will add CSS, including media queries, in Part 2 so the layout adapts between mobile, tablet, and desktop.     |
| Interactivity | I will use JavaScript in Part 3 for form validation, image galleries, and simple navigation behaviour.           |
| Domain name   | I will use www.Rammolaifoundation.org.za, registered via Domains.co.za / Afrihost.                               |
| Hosting       | I will use shared hosting suited to a small site, for example Afrihost.                                          |
| Forms         | I will use Formspree to handle contact and volunteer or sponsor enquiry submissions without custom backend code. |
| Payments      | EFT and bank details will be displayed for monetary donations.                                                   |

## Timeline and Milestones

### Organisation Research

- **Owner:** Dimpho Masilo | **Timeline:** 5 Aug 2026 – 5 Aug 2026 | **Status:** Completed
- **Details:** Gathered content from Facebook and related social media channels.

### Project Proposals and Selection

- **Owner:** Dimpho Masilo | **Timeline:** 7 Aug 2026 – 14 Aug 2026 | **Status:** Completed
- **Details:** Drafted two project proposals; finalised selection of the **Rammolai Foundation**.

### Wireframing and Asset Sourcing

- **Owner:** Dimpho Masilo | **Timeline:** 14 Aug 2026 – 15 Aug 2026 | **Status:** Completed
- **Details:** Visualised layouts via wireframes and sourced verified public domain / Foundation assets.

### File Architecture and Information Routing

- **Owner:** Dimpho Masilo | **Timeline:** 15 Aug 2026 – 16 Aug 2026 | **Status:** Completed
- **Details:** Established directory folders (`css`, `js`, `images`) and built out the core sitemap across 5 pages (`index`, `about`, `services`, `enquiry`, `contact`).

### HTML Structuring

- **Owner:** Dimpho Masilo | **Timeline:** 17 Aug 2026 – 17 Aug 2026 | **Status:** Completed
- **Details:** Created base HTML files for all 5 pages using semantic landmarks (`<header>`, `<nav>`, `<main>`, `<footer>`).

### Content Integration and Navigation

- **Owner:** Dimpho Masilo | **Timeline:** 17 Aug 2026 – 18 Aug 2026 | **Status:** Completed
- **Details:** Populated researched content across layout regions and deployed a fully functional navigation menu linked sitewide.

### Optimisation and Code Review

- **Owner:** Dimpho Masilo | **Timeline:** 18 Aug 2026 – 18 Aug 2026 | **Status:** Completed
- **Details:** Cross-browser testing, validation fixes, and documentation comments for readability.

### Documentation and Final Deployment

- **Owner:** Dimpho Masilo | **Timeline:** 19 Aug 2026 – 20 Aug 2026 | **Status:** Completed
- **Details:** Finalised `README.md`, changelog, and repository documentation for Part 1 submission.

## Part 1 Details

Part 1 focuses on project planning, content research, file organisation, and the HTML foundation for the Rammolai Foundation website. CSS styling and JavaScript functionality will follow in Parts 2 and 3.

## Sitemap

| Page     | File            | Purpose                                                               |
| -------- | --------------- | --------------------------------------------------------------------- |
| Homepage | `index.html`    | Hero image, introduction, impact highlights, and call-to-action links |
| About Us | `about.html`    | History, mission, vision, team members, and achievements              |
| Services | `services.html` | Programmes (school shoes, sanitary towel drive) and donation options  |
| Enquiry  | `enquiry.html`  | Form for volunteering, donating, or becoming a sponsor                |
| Contact  | `contact.html`  | Contact details, multiple locations with maps, and a contact form     |

## Folder Structure

```
Website/
├── index.html
├── about.html
├── services.html
├── enquiry.html
├── contact.html
├── README.md
├── css/                 (reserved for Part 2 stylesheets)
├── js/                  (reserved for Part 3 scripts)
└── images/
    ├── logo.jpeg
    ├── Sanitary-drive.jpeg
    ├── Shoe-donation.jpg
    └── Shoprite-award.jpg
```

Related submission materials (proposals and research content) are stored separately under `ST10500849_Part 1/`.

## Changelog

All notable changes to the Rammolai Foundation website project are documented below.

### 2026-09-22

The following changes were made in response to lecturer feedback on Part 1 and Part 2 requirements. The original Part 1 feedback noted that HTML pages and GitHub commit evidence were not clearly visible; the commit history has since been corrected to show multiple, descriptive commits, and this entry documents the Part 2 CSS styling work that follows on from that.

### Added

- External stylesheet (css/style.css) created and linked to all 5 pages (index.html, about.html, services.html, enquiry.html, contact.html).
- Google Fonts (Archivo for headings, Source Sans 3 for body text) linked via <link> tags in every page <head>.
- CSS reset and base styles: consistent box-sizing, margins, font family, and colour scheme applied site-wide.
- Full typography scale using font-family, font-size, font-weight, line-height, and letter-spacing.
- CSS Grid layout for the header (logo, title, and tagline) and Flexbox layout for the navigation menu.
- Colour and decoration styling: brand colour palette (purple, teal, orange) applied via CSS custom properties, borders, and box-shadows.
- Pseudo-classes (:hover, :focus-visible, :active, :required:invalid) added to navigation links, body links, form fields, and buttons for interactive feedback.
- Media queries at 900px (tablet) and 600px (mobile) breakpoints, adjusting layout, typography, navigation, and image sizing responsively.
- Screenshot evidence of the website at desktop, tablet, and mobile screen widths (see Screenshots section below).

### Fixed

- Corrected a stylesheet filename mismatch (styles.css referenced in HTML vs style.css as the actual file name) that was preventing CSS from loading on index.html and about.html.
- Corrected a malformed HTML comment (<! -- ... --> with a stray space) in the Google Fonts comment line.

### 2026-09-17

#### Added

- Empty `css/` and `js/` folders to match the required Part 1 file structure.
- Dedicated **Our Team** section on `about.html` listing Motlomo, Tshegofatso, and Debra Ramatlo.
- Hero image on the homepage welcome section.
- Second location and map on `contact.html` (Kgabo Primary School, Atteridgeville) so the contact page includes more than one location.

#### Changed

- Standardised page titles to “Rammolai Foundation”.
- Simplified HTML comments across all pages.
- Updated README folder structure, headings, and reference formatting.

#### Fixed

- Replaced uppercase `<P>` tags with lowercase `<p>` on all pages.
- Corrected typos and grammar (for example “communtity”, “3 school reached”, “west of pretoria”).
- Removed duplicate reference entries from the README.

### 2026-08-21

#### Added

- Initial project submission files containing 5 core semantic HTML pages.
- Sitewide functional navigation menu linked across all documents.
- Finalised repository documentation, including `README.md` and project timeline.

#### Changed

- Migrated researched content from Facebook/social media into active page body elements.
- Organised resources into `/images` (with `css/` and `js/` prepared for later parts).

#### Fixed

- Debugged HTML layout validation errors caught during multi-browser testing.
- Standardised structural code formatting and added documentation comments for readability.

### 2026-08-17

#### Added

- Initialised core repository file architecture and directory tree.
- Created base sitemap routing layout (`index`, `about`, `enquiry`, `contact`, `services`).
- Sourced and catalogued media assets for site integration.

### 2026-08-14

#### Added

- Initial wireframe mockups for user interface planning.
- Finalised project proposal and selection scope for the **Rammolai Foundation**.

### Screenshots

Screenshots below show the website's responsive behaviour at three screen widths, tested using browser developer tools.

Desktop (~1440px)
[Insert desktop screenshot here]

Tablet (~768px)
[Insert tablet screenshot here]

Mobile (~375px)
[Insert mobile screenshot here]

## References

Afrihost, 2026. Domains. [online] Available at: <https://www.afrihost.com/domains> [Accessed 7 August 2026].

HostAfrica, 2026. How Much Does It Cost to Build a Website in South Africa?. [online] Available at: <https://hostafrica.co.za/blog/websites/website-basics/how-much-does-a-website-cost-in-south-africa/> [Accessed 7 August 2026].

Manna Food Hub, 2026. Uber Eats listing and menu. [online] Available at: <https://www.ubereats.com/za/store/manna-food-hub> [Accessed 7 August 2026].

Rammolai Foundation, 2021. Logo. [Facebook] 11 September. Available at: <https://www.facebook.com/RammolaiFoundation> [Accessed 6 August 2026].

Rammolai Foundation, 2021. Rammolai Foundation Pretoria - Google Map. [online] Available at: <https://share.google/Mcy3tKakYmgYSxWEW> [Accessed 6 August 2026].

Rammolai Foundation, 2022. 30 school shoes donated to Kgabo Primary School. [Facebook] 5 June. Available at: <https://www.facebook.com/RammolaiFoundation> [Accessed 6 August 2026].

Rammolai Foundation, 2022. Dr WF Nkomo High School toiletries and sanitary towel Drive. [Facebook] 23 November. Available at: <https://www.facebook.com/RammolaiFoundation> [Accessed 6 August 2026].

W3Schools, 2026. HTML Tutorial. [online] Available at: <https://www.w3schools.com/html/default.asp> [Accessed 17 August 2026].

Webpartner, 2026. How Much Does a Website Cost Per Month in South Africa?. [online] Available at: <https://www.webpartner.co.za/blog/how-much-does-a-website-cost-per-month-in-south-africa/> [Accessed 7 August 2026].
