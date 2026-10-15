# Mabaso Electrical Services Website

**Module:** WEDE5020 – Web Design and Development
**Assessment:** Portfolio of Evidence (PoE)
**Institution:** The Independent Institute of Education (Pty) Ltd

---

## Student Information

| Field | Detail |
|---|---|
| Name | Mutshidzi Nesengani |
| Student number | ST10518407 |
| Module code | WEDE5020 |
| Campus | Polokwane |
| Submission | Part 1 (Parts 2 and 3 to follow) |

---

## Project Overview

Mabaso Electrical Services is a small electrical contracting business that installs, repairs and maintains electrical systems for homes and small commercial clients. The business currently depends on word of mouth and has no online presence, which makes it hard for new customers to find its services, judge its credibility or request a quote.

This project designs and builds a static, multi-page website for the business using HTML, CSS and JavaScript. The site presents the company's services, background and past work in one place and gives visitors a simple way to make an enquiry. It is built mobile-first because most of the business's customers are likely to browse on a phone.

The project is delivered in three parts as a Portfolio of Evidence:

- **Part 1:** Planning, proposal and the HTML structure of the website.
- **Part 2:** CSS styling and responsive design.
- **Part 3:** To follow in a future submission.

---

## Website Goals and Objectives

**Goal:** Give Mabaso Electrical Services a professional online presence that builds trust and turns visitors into quote requests.

**Objectives**

1. Explain clearly what services the business offers and where it operates.
2. Build credibility through an About page and examples of completed work.
3. Provide a contact page with an enquiry form that validates input before submission.
4. Make the site usable on phones, tablets and desktops.
5. Keep navigation consistent so that any page is reachable in one click from any other page.
6. Use semantic HTML and meaningful alt text so the site is accessible and easy to maintain.

---

## Key Features and Functionality

- **Five linked pages** sharing one header, navigation bar and footer.
- **Shared stylesheet** (`css/styles.css`) so styling stays consistent across pages.
- **Mobile navigation toggle** that collapses the menu on small screens.
- **Services listing** covering the main electrical services offered.
- **Project gallery** showing example work with descriptive captions.
- **Contact form with client-side validation** (required fields, email format, phone format) written in JavaScript.
- **Semantic HTML5 structure** using `header`, `nav`, `main`, `section`, `article` and `footer`.
- **Responsive layout** that adapts to different screen widths (finalised in Part 2).

---

## Timeline and Milestones

| Milestone | Description | Status | Date |
|---|---|---|---|
| Part 1 | Proposal, sitemap, wireframes and HTML structure | Complete | [Date] |
| Part 2 | CSS styling and responsive design | In progress / to follow | [Date] |
| Part 3 | To be confirmed | Not started | [Date] |

---

## Part 1 Details

Part 1 covers the planning and structural build of the website.

**Deliverables**

- Website proposal describing the client, target audience, goals and scope.
- Sitemap showing how the pages connect.
- Five HTML pages with a consistent layout.
- A shared stylesheet with the basic layout and visual identity.
- JavaScript for the mobile navigation toggle and contact form validation.
- This README file.

**Folder structure**

```
mabaso-electrical/
├── index.html
├── about.html
├── services.html
├── projects.html
├── contact.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── images/
└── README.md
```

**Page summary**

| Page | File | Purpose |
|---|---|---|
| Home | `index.html` | Introduces the business and directs visitors to services and contact |
| About | `about.html` | Company background, values and credentials |
| Services | `services.html` | Detailed list of services offered |
| Projects | `projects.html` | Gallery of completed work |
| Contact | `contact.html` | Contact details and validated enquiry form |

---

## Sitemap

```
Home (index.html)
├── About (about.html)
├── Services (services.html)
├── Projects (projects.html)
└── Contact (contact.html)
```

Every page links to all other pages through the main navigation bar, and the Home page links directly to Services and Contact through calls to action.

---

## Changelog

All notable changes to the website are recorded here, newest first.

### [Unreleased]
- Part 2 work (CSS styling and responsive design) to be logged here as it is submitted.

### [1.0.0] – Part 1 – [Date]
**Added**
- Project proposal and sitemap.
- Five HTML pages: Home, About, Services, Projects and Contact.
- Shared stylesheet `css/styles.css`.
- Mobile navigation toggle.
- Client-side validation on the contact form.
- README.md with project documentation.

**Changed**
- None (first release).

**Fixed**
- None (first release).

---

## References

Add every source actually used for code, images, text and ideas. The entries below are in the Harvard style and should be checked against the IIE referencing guide and edited to match what you used.

Mozilla Developer Network (MDN), n.d. *HTML: HyperText Markup Language*. [Online] Available at: https://developer.mozilla.org/en-US/docs/Web/HTML [Accessed 15 October 2026].

Mozilla Developer Network (MDN), n.d. *CSS: Cascading Style Sheets*. [Online] Available at: https://developer.mozilla.org/en-US/docs/Web/CSS [Accessed 15 October 2026].

Mozilla Developer Network (MDN), n.d. *JavaScript*. [Online] Available at: https://developer.mozilla.org/en-US/docs/Web/JavaScript [Accessed 15 October 2026].

WHATWG, n.d. *HTML Living Standard*. [Online] Available at: https://html.spec.whatwg.org/ [Accessed 15 October 2026].

The Independent Institute of Education, 2026. *WEDE5020 Portfolio of Evidence brief*. Unpublished module document.
