# QA Portfolio

Portfolio of practical Manual QA work.

This repository contains test documentation created while testing my personal portfolio website.

## About the Project

The goal of this project was to practice basic Manual QA skills on a real web application.

I tested my personal portfolio website using functional, UI, responsive, accessibility-related and basic browser DevTools checks.

Website under test:
- Personal portfolio website hosted on GitHub Pages

## What Was Tested

The following areas were checked:

- Navigation between page sections
- Buttons and external links
- Light and dark themes
- Theme persistence after page refresh
- Mobile and narrow-screen layout
- Browser zoom at 80% and 200%
- Keyboard navigation using Tab and Enter
- Direct links to page sections
- Browser Back navigation
- Console errors
- Network requests and HTTP statuses
- Text readability and UI stability

## Test Documentation

### Checklist

[Portfolio Website Checklist](checklists/portfolio-website-checklist.md)

Contains 25 manual checks.

Result:
- Passed: 25
- Failed: 0
- Defects found: 0

### Test Cases

[Portfolio Website Test Cases](test-cases/portfolio-website-test-cases.md)

Contains 20 detailed test cases with:

- ID
- Title
- Preconditions
- Steps
- Expected Result
- Actual Result
- Status

Result:
- Passed: 20
- Failed: 0
- Defects found: 0

## Tools Used

- Browser DevTools
- Console
- Network
- Device Emulation
- Git
- GitHub
- GitHub Pages

## Skills Practiced

- Manual testing
- Functional testing
- UI testing
- Responsive testing
- Test case creation
- Checklist creation
- Expected vs Actual Result comparison
- Keyboard navigation testing
- Basic DevTools usage
- Basic HTTP status analysis

## Test Results

During the completed test runs, no reproducible defects were found.

Console:
- No red JavaScript errors detected

Network:
- No failed HTTP requests detected
- Successful responses included HTTP 200 and 304

## Repository Structure

```text
qa-portfolio/
├── README.md
├── checklists/
│   └── portfolio-website-checklist.md
└── test-cases/
    └── portfolio-website-test-cases.md
