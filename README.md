# BSAI_245-lab_3
# A11y Lab (BSAI-245)

An interactive web accessibility practice project built with plain HTML, CSS and JavaScript. It helps you learn keyboard navigation, screen reader support, colour contrast and how to fix common problems against **WCAG 2.1 AA**.

Everything is in a single file (`a11y-lab-BSAI-245.html`). There is nothing to install and no build step.

## Features

### 1. Keyboard and ARIA
- Tabs with arrow keys, Home and End (roving tabindex)
- Accordion using `aria-expanded` and `aria-controls`
- Modal dialog using native `<dialog>`, with focus returned on close
- Form with an error summary, `aria-invalid` and `aria-describedby`
- Live key log to check focus order

### 2. Contrast checker
- Calculates the WCAG contrast ratio from two colours
- Checks AA and AAA for normal text, large text and UI components
- Suggests a passing text colour that keeps a similar hue
- Text size slider and text spacing test

### 3. Fix the page
- Before and After views of a sample shop page
- 8 accessibility issues to find, each with how to spot it and how to fix it
- Progress bar that tracks the issues you have found

### 4. Quiz and report
- 5-question quiz with instant feedback and a score
- Personal notes, saved in your browser
- Report with your name, course, issues found, quiz score and notes, which you can copy or print

## Accessibility built in
- Skip link and visible focus outlines
- Light, dark and high contrast themes
- Respects `prefers-reduced-motion`
- Pass/fail results use a symbol and a word, never colour alone
- Touch-friendly controls at least 44px tall

## How to run
1. Download `a11y-lab-BSAI-245.html`.
2. Open it in any modern browser (Chrome, Firefox, Edge or Safari).

To host it on GitHub Pages, rename the file to `index.html`, then go to **Settings → Pages** and publish from the main branch.

## How to test
- Use the keyboard only: Tab, Shift+Tab, Enter, Space, arrow keys and Esc
- Try a screen reader: NVDA, VoiceOver or TalkBack
- Zoom the browser to 200%
- Run automated tools such as axe DevTools, Lighthouse or WAVE

> Automated tools find only some accessibility problems, so manual testing is always required.

## Tech
HTML5 · CSS3 · Vanilla JavaScript

## WCAG success criteria covered
1.1.1, 1.4.1, 1.4.3, 1.4.4, 1.4.10, 1.4.11, 1.4.12, 2.1.1, 2.1.2, 2.4.3, 2.4.4, 2.4.7, 3.1.1, 3.3.1, 3.3.2, 4.1.2, 4.1.3

## Limitations
This is a learning tool. It cannot replace testing with real assistive technology.

## Author
**Name:** Zargham Zaheer  
**Course:** BSAI-245
