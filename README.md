# AccessFlow

AccessFlow is a small interactive web accessibility toolkit built as an HCI lab project. The idea behind it is to make accessibility easier to understand by letting users explore common interface problems, test different settings, and compare a broken interface with an improved version.

Instead of only listing accessibility guidelines, AccessFlow provides hands-on examples of how those guidelines apply to real interface elements.

## What it includes

### 1. Keyboard and ARIA
Explore keyboard navigation, tabs, accordion controls, menus, modal dialogs, and form validation. This section also includes a keyboard event log to help observe focus movement and key interactions.

### 2. Contrast and zoom
Choose text and background colors to calculate their contrast ratio against WCAG thresholds. You can also experiment with text magnification, page reflow, text spacing, and simulated color-vision differences.

### 3. Accessibility fixes
Compare a sample coffee shop interface before and after accessibility improvements. The examples cover common problems such as missing image descriptions, poor contrast, inaccessible controls, unclear links, and form errors. The issue tracker lets you record which problems you identify.

### 4. Accessibility audit
Review accessibility criteria, record pass or fail results, add notes, and generate a summary report. The report can be copied as text or printed.

## Built with

- HTML
- CSS
- JavaScript
- ARIA attributes and keyboard interaction patterns
- WCAG 2.1 accessibility guidelines

## Running it locally

Download or clone the repository and open `index.html` in a modern web browser. The project does not require a package manager or a build process.

## A note on testing

AccessFlow is intended for learning and experimentation. Its contrast calculations and interface demonstrations are useful starting points, but they do not guarantee that a website meets every accessibility requirement. Real projects should also be tested with assistive technologies, keyboard-only navigation, and manual accessibility checks.

## Project purpose

This project explores how accessibility principles can be applied during interface design and evaluation. It focuses on making common barriers visible and showing practical ways to improve the experience for different users.
