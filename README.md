# Tips for Financial Cybersecurity

A simple, static informational webpage that shares practical tips to help people protect their financial information online.

---

## Project Overview

This is a single-page website built with HTML and Tailwind CSS. It displays a list of financial cybersecurity tips in a clean, easy-to-read layout. There is no backend, no database, and no user interaction — it is a pure informational page.

---

## Main Idea

- **Purpose:** Educate people on how to stay safe online when dealing with financial accounts and sensitive data.
- **Problem it solves:** Many people are unaware of basic digital security practices. This page provides simple, actionable steps anyone can follow.

---

## Key Features

- Yellow header banner with page title and subtitle
- 14 financial cybersecurity tips listed clearly
- Clean, readable layout using Tailwind CSS
- Subtle scroll animations using AOS (Animate On Scroll)
- Black footer with copyright notice
- Fully responsive for mobile and desktop

---

## Core Logic

This is a static website — there is no dynamic logic. Here is how it works:

1. User opens `index.html` in a browser
2. The page loads with a styled yellow header
3. Tips are displayed one by one in a vertical list
4. Each tip has a bold title and a short description
5. AOS animations trigger as the user scrolls down
6. A footer appears at the bottom of the page

---

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and content |
| Tailwind CSS (CDN) | Styling and responsive layout |
| AOS v2.3.1 (CDN) | Scroll animations |
| Google Fonts (Inter) | Font import (loaded but overridden by Gill Sans in CSS) |
| Vanilla CSS | Custom font sizes and color overrides |

---

## How to Run the Project Locally

No build tools or installations are required.

**Prerequisites:**
- Any modern web browser (Chrome, Firefox, Edge, Safari)

**Steps:**

```bash
# 1. Clone or download the repository
git clone https://github.com/momin619/commonwealth-website.git

# 2. Navigate into the project folder
cd commonwealth-website

# 3. Open the file in your browser
open index.html
# or simply double-click index.html in your file explorer
```

> **Note:** An internet connection is needed on first load for Tailwind CSS, AOS, and Google Fonts to load from CDN.

---

## Example Workflow / Usage

1. User visits the page (or opens `index.html` locally)
2. The yellow header greets them with the page title
3. They scroll down to read through the 14 cybersecurity tips
4. Each tip fades in smoothly as they scroll
5. They reach the footer at the bottom

No login, no forms, no interaction required.

---

## Folder Structure

```
momin619-commonwealth-website/
└── index.html        # The entire website (single file)
```
