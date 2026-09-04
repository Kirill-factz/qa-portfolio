# Portfolio Website Testing Checklist

## Project
Personal Portfolio Website

## Test Type
Manual Functional and UI Testing

## Environment
- OS: Windows
- Browser: Desktop browser
- Tools: Browser DevTools
- Testing methods:
  - Functional testing
  - UI testing
  - Responsive testing
  - Basic accessibility checks
  - Network and Console checks

## Checklist

| ID | Check | Expected Result | Status |
|----|-------|-----------------|--------|
| CH-001 | Click the "Навыки" navigation link | Page scrolls to the Skills section | Passed |
| CH-002 | Click the "Кейсы" navigation link | Page scrolls to the Cases section | Passed |
| CH-003 | Click the "Обо мне" navigation link | Page scrolls to the About section | Passed |
| CH-004 | Click the "Контакты" navigation link | Page scrolls to the Contacts section | Passed |
| CH-005 | Click the "Посмотреть кейсы" button | Page scrolls to the Cases section | Passed |
| CH-006 | Click the GitHub link in the top section | Correct GitHub profile opens | Passed |
| CH-007 | Click the GitHub link in the bottom section | Correct GitHub profile opens | Passed |
| CH-008 | Switch between light and dark themes | Theme changes correctly | Passed |
| CH-009 | Refresh the page after changing the theme | Selected theme remains active | Passed |
| CH-010 | Open the website on mobile screen size | Content is displayed correctly | Passed |
| CH-011 | Navigate through interactive elements using Tab | Focus moves through interactive elements | Passed |
| CH-012 | Activate navigation links using Enter | Selected link works correctly | Passed |
| CH-013 | Switch the theme using keyboard | Theme changes using keyboard input | Passed |
| CH-014 | Reduce browser window to a very narrow width | Layout remains usable and stable | Passed |
| CH-015 | Check for horizontal scrolling on narrow screen | No unwanted horizontal scrolling appears | Passed |
| CH-016 | Set browser zoom to 200% | Text and controls remain visible and usable | Passed |
| CH-017 | Set browser zoom to 80% | Layout remains stable | Passed |
| CH-018 | Refresh the page while positioned in the Cases section | Browser returns to the same section | Passed |
| CH-019 | Open a direct link to the Skills section | Correct section opens | Passed |
| CH-020 | Open GitHub link in a new browser tab | Correct GitHub profile opens in new tab | Passed |
| CH-021 | Open case links and return using browser Back button | Website returns correctly | Passed |
| CH-022 | Check visible text for spelling errors | No visible spelling errors found | Passed |
| CH-023 | Review all page sections in light theme | Text, buttons and borders remain readable | Passed |
| CH-024 | Check Browser DevTools Console after user actions | No JavaScript errors appear | Passed |
| CH-025 | Check Browser DevTools Network after page reload | Requests complete without HTTP errors | Passed |

## Test Summary

- Total checks: 25
- Passed: 25
- Failed: 0
- Not tested: 0
- Defects found: 0

## Notes

During this test run, no reproducible defects were discovered.

Successful HTTP responses included status codes:
- 200
- 304

No critical Console or Network errors were observed.
