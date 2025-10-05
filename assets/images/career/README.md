# Career Company Logos

This directory contains company logos for the career timeline section of your cover letter website.

## File Naming Convention

Name your logo files using lowercase company names:

- `circle.png` or `circle.jpg`
- `kit.png` or `kit.jpg`
- `[company-name].png` for target companies (e.g., `airtable.png`, `google.png`)

## Logo Specifications

**Recommended specs:**
- **Size:** 200x200px minimum (will display at 60x60px)
- **Format:** PNG (preferred for transparency) or JPG
- **Background:** Transparent PNG works best
- **Style:** Square or circular logos work well

## How to Add Logos to Your Pages

In your company-specific page (e.g., `/airtable/index.html`), find the career cards and uncomment the logo line:

```html
<!-- Before (logo hidden): -->
<!-- <img src="/assets/images/career/circle.png" alt="Circle Logo" class="career-logo"> -->

<!-- After (logo visible): -->
<img src="/assets/images/career/circle.png" alt="Circle Logo" class="career-logo">
```

Update the path to match your logo filename:
```html
<img src="/assets/images/career/airtable.png" alt="Airtable Logo" class="career-logo">
```

## Optional vs Required

Logos are **completely optional**. The career timeline looks great with or without them. Only add logos if:
- You have access to high-quality company logos
- The logos enhance rather than clutter the design
- You want that extra professional polish

## Where Logos Appear

Logos display on the left side of each career card header, next to the job title and company name. They're 60x60px, rounded, and align nicely with the text.
