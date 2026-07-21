````markdown
# Aswad Khan Portfolio Specification (Final)

## Goal

Create a modern, responsive, single-page portfolio website introducing **Aswad Khan** in under 60 seconds. The website should present personal information in a clean, professional, and visually engaging way while remaining suitable for a school portfolio assignment.

---

# Context

- **Name:** Aswad Khan
- **Class:** 10th Grade
- **School:** Anees Hassan School & College

---

# Content Requirements

## Hero Section

Display:

- Circular avatar with a blue gradient background
- White bold initials:
  - AK
- Large heading:
  - Aswad Khan
- One-line introduction:

> A motivated 10th-grade student who enjoys learning, solving problems, and helping in the family business.

Display two rounded information chips:

- 10th Grade
- Anees Hassan School & College

---

## Education

Section title:

**Education**

Display one information card containing:

### Grade

10th Grade

### School

Anees Hassan School & College

Each label should appear above its value.

---

## Things I'm Proud Of

Section title:

**Things I'm Proud Of**

Display exactly three cards.

Content:

1. Balancing my studies while helping my father in his business.

2. Finding creative solutions to everyday challenges.

3. Managing my time effectively and completing tasks early.

Each card includes:

- Rounded corners
- White background
- Soft shadow
- Blue circular check indicator
- Hover lift animation (desktop only)

---

## Skills

Section title:

**Skills**

Display three large rounded badges.

Skills:

- Business Operations
- Drawing
- Problem Solving

Each badge includes:

- Blue gradient background
- White bold text
- Pill shape
- Hover lift animation

---

## My Dream

Section title:

**My Dream**

Display one quote-style card containing:

> I am working hard to become a future entrepreneur. Helping my father run his business today is teaching me the operations and management skills I need to launch my own company.

The quote card includes:

- White background
- Rounded corners
- Decorative quotation mark
- Soft shadow

---

## Assignment Grading Rubric

Section title:

**Assignment Grading Rubric**

Display a modern responsive table.

Columns:

- Criteria
- Marks

Rows:

| Criteria | Marks |
|----------|------:|
| Specification is complete — Goal, Requirements, Hard Constraints and Out of Scope are included. | 3 |
| Specification reviewed by AI and improved to a score of 9+/10. | 2 |
| Correct Markdown formatting is used throughout the specification. | 2 |
| Working portfolio link submitted. | 2 |
| Reflection section completed. | 1 |
| **Total** | **10** |

Below the table display the note:

> This rubric shows how my portfolio assignment is evaluated.

The rubric card includes:

- Rounded corners
- White background
- Blue gradient table header
- Soft shadow
- Responsive layout

---

## Reflection

Section title:

**My Reflection**

Display three reflection cards.

### Card 1

**What was Markdown?**

Markdown is a simple text formatting language that I used to write my portfolio specification with headings, lists, and structured content.

---

### Card 2

**What was HTML?**

HTML is the language used to build my portfolio website by converting my written specification into a complete web page.

---

### Card 3

**What did AI do?**

AI helped me improve my specification, generate the HTML, and build a clean, modern portfolio while following the project requirements.

Each reflection card includes:

- White background
- Rounded corners
- Blue numbered circle
- Soft shadow
- Hover animation
- Comfortable spacing

---

## Footer

Centered text:

> Built by Aswad Khan · 2026

---

# Design Specification

## Color Palette

### Primary Blue

`#1D4ED8`

### Dark Blue

`#1E3A8A`

### Background

- White
- `#F8FAFC`

### Text

`#1F2937`

### Secondary Text

`#64748B`

### Borders

`#D7E3F7`

---

## Background Design

The background should create a clean and modern appearance using CSS only.

It should include:

- White base
- Soft blue radial gradients
- Light vertical gradient
- No images
- No textures
- No notebook-paper lines
- No repeating horizontal stripes

The background should feel minimal, premium, and professional.

---

## Typography

Use only system fonts.

```
system-ui
-apple-system
Segoe UI
sans-serif
```

No external fonts.

---

## Layout

Maximum content width:

760px

Horizontal padding:

24px

All content centered.

Use generous spacing between sections.

---

## Hero

Centered layout.

Avatar:

- Circular
- Blue gradient
- White initials
- Soft glow shadow

Avatar size:

- Mobile: 100px
- Desktop: 128px

Add a decorative blue gradient underline below the name.

---

## Cards

Use consistent styling across all cards.

Each card includes:

- White background
- Rounded corners
- Thin border
- Soft shadow

Border radius:

22px

Cards include:

- Education
- Proud Of
- Dream
- Rubric
- Reflection

---

## Proud Cards

Each card includes:

- Blue circular check icon
- Hover lift animation
- Stronger shadow on hover

Desktop only.

---

## Skill Badges

Large pill-shaped badges.

Blue gradient background.

White bold text.

Hover effect:

- Lift
- Slight scale

---

## Quote Card

Large quote-style block.

Includes:

- Decorative quotation mark
- White background
- Rounded corners
- Soft shadow
- Comfortable padding

---

## Rubric Table

Display inside a rounded white card.

Header:

- Blue gradient background
- White text

Body:

- Light row dividers
- Centered marks column

Footer row:

- Highlight total marks

Fully responsive on mobile.

---

## Reflection Cards

Display three cards stacked vertically.

Each card contains:

- Blue numbered circle
- Heading
- Paragraph
- Rounded corners
- Soft shadow

Hover:

- Lift slightly
- Stronger shadow

---

## Responsive Design

Single breakpoint:

640px

### Below 640px

- Single-column layout
- Stacked content
- Comfortable spacing

### 640px and above

- Proud cards become a three-column grid
- Skill badges wrap naturally

---

## Animation

Each section fades in while moving upward.

Animation:

- Fade
- 12px upward movement
- 0.5 second ease

Implementation:

- IntersectionObserver

Threshold:

0.15

Root margin:

0px 0px -10% 0px

Animation runs only once.

---

## Accessibility

Include:

- `lang="en"`
- Viewport meta tag
- Description meta tag
- Avatar uses:
  - `role="img"`
  - `aria-label="Aswad Khan"`

Support:

`prefers-reduced-motion`

When enabled:

- Disable animations
- Display all content immediately

---

# Technical Requirements

- Single `index.html`
- CSS inside `<style>`
- JavaScript inside `<script>`
- No external CSS
- No external JavaScript
- No Bootstrap
- No Tailwind CSS
- No jQuery
- No React
- No Vue
- No frameworks
- No CDN
- No external fonts
- No external icons
- No external images

Use semantic HTML elements:

- header
- section
- footer

Required meta tags:

- viewport
- description

Page title:

> Aswad Khan — Portfolio

Include an inline SVG favicon displaying the initials **AK** on a blue background.

---

# Browser Support

Support the latest two versions of:

- Google Chrome
- Microsoft Edge
- Safari
- Mobile Chrome
- Mobile Safari

---

# Out of Scope

Do **not** include:

- Personal photograph
- Phone number
- Email address
- Home address
- Social media links
- Navigation bar
- Login page
- Contact form
- Backend
- Database
- Authentication
- Dark mode
- Print stylesheet
- Analytics
- External assets
- Multi-page navigation

The portfolio must remain a clean, modern, responsive, single-page website built entirely with HTML, CSS, and JavaScript.
````
