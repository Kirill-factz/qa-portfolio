# Portfolio Website Test Cases

## Project
Personal Portfolio Website

## Test Type
Manual Functional, UI and Responsive Testing

## Environment
- OS: Windows
- Browser: Desktop browser
- Tools: Browser DevTools
- Test status values: Passed / Failed

---

### TC-001 — Navigate to Skills section

**Preconditions:**
- Portfolio website is open.
- User is at the top of the page.

**Steps:**
1. Locate the "Навыки" link in the top navigation menu.
2. Click the "Навыки" link.

**Expected Result:**
- The page scrolls to the Skills section.
- The "01 / НАВЫКИ" section is visible.

**Actual Result:**
- The page scrolls to the Skills section correctly.

**Status:** Passed

---

### TC-002 — Navigate to Cases section

**Preconditions:**
- Website is open.
- User is at the top of the page.

**Steps:**
1. Move the cursor to the "Кейсы" item in the top menu.
2. Click the "Кейсы" item.

**Expected Result:**
- The page scrolls to the Cases section.
- The Cases section is displayed correctly.

**Actual Result:**
- The page successfully scrolls to the Cases section.
- The section is displayed correctly.

**Status:** Passed

---

### TC-003 — Navigate to Cases section using "Посмотреть кейсы" button

**Preconditions:**
- Website is open.
- User is at the top of the page.

**Steps:**
1. Move the cursor to the "Посмотреть кейсы" button.
2. Click the button.

**Expected Result:**
- The page scrolls to the Cases section.
- The Cases section is displayed correctly.

**Actual Result:**
- The page successfully scrolls to the Cases section.
- The section is displayed correctly.

**Status:** Passed

---

### TC-004 — Switch from dark theme to light theme

**Preconditions:**
- Website is open.
- Dark theme is active.
- User is at the top of the page.

**Steps:**
1. Move the cursor to the theme switch button.
2. Click the theme switch button.

**Expected Result:**
- The website switches to the light theme.
- Text, headings, buttons and interface elements remain readable.
- Interface elements do not blend into the background.

**Actual Result:**
- The website successfully switches to the light theme.
- Text, headings and buttons are displayed correctly and remain readable.

**Status:** Passed

---

### TC-005 — Preserve selected theme after page refresh

**Preconditions:**
- Website is open.
- Light theme is selected.

**Steps:**
1. Press F5 to refresh the page.

**Expected Result:**
- The selected light theme remains active after page refresh.

**Actual Result:**
- The light theme remains active after page refresh.

**Status:** Passed

---

### TC-006 — Open GitHub profile using top button

**Preconditions:**
- Website is open.
- User is at the top of the page.

**Steps:**
1. Move the cursor to the "GitHub" button.
2. Click the button.

**Expected Result:**
- The correct GitHub profile opens.
- The profile page is displayed without errors.

**Actual Result:**
- The correct GitHub profile opens successfully.
- The profile page is displayed correctly.

**Status:** Passed

---

### TC-007 — Open GitHub profile using bottom button

**Preconditions:**
- Website is open.
- User has scrolled to the bottom section of the page.

**Steps:**
1. Move the cursor to the "Открыть профиль GitHub" button.
2. Click the button.

**Expected Result:**
- The correct GitHub profile opens.
- The profile page is displayed without errors.

**Actual Result:**
- The correct GitHub profile opens successfully.
- The profile page is displayed correctly.

**Status:** Passed

---

### TC-008 — Check mobile display

**Preconditions:**
- Website is open in a desktop browser.

**Steps:**
1. Press F12 to open DevTools.
2. Enable mobile device emulation.
3. Select a mobile device or mobile screen size.
4. Review the page from top to bottom.

**Expected Result:**
- The website is displayed correctly in mobile resolution.
- Interface elements do not go outside the screen.
- Text and buttons remain readable.
- Unwanted horizontal scrolling is absent.

**Actual Result:**
- The website is displayed correctly in mobile resolution.
- Interface elements remain inside the screen boundaries.
- Text and buttons are readable.
- Horizontal scrolling is absent.

**Status:** Passed

---

### TC-009 — Check website at 200% zoom

**Preconditions:**
- Website is open in a desktop browser.
- Page zoom is set to 100%.

**Steps:**
1. Press Ctrl + + until page zoom reaches 200%.
2. Review the page from top to bottom.

**Expected Result:**
- Website is displayed correctly at 200% zoom.
- Interface elements remain visible.
- Text and buttons remain readable.
- Unwanted horizontal scrolling is absent.

**Actual Result:**
- Website is displayed correctly at 200% zoom.
- Interface elements remain visible.
- Text and buttons are readable.
- Unwanted horizontal scrolling is absent.

**Status:** Passed

---

### TC-010 — Check website at 80% zoom

**Preconditions:**
- Website is open in a desktop browser.
- Page zoom is set to 100%.

**Steps:**
1. Press Ctrl + - until page zoom reaches 80%.
2. Review the page from top to bottom.

**Expected Result:**
- Website is displayed correctly at 80% zoom.
- Interface elements remain visible.
- Text and buttons remain readable.
- Unwanted horizontal scrolling is absent.

**Actual Result:**
- Website is displayed correctly at 80% zoom.
- Interface elements remain visible.
- Text and buttons are readable.
- Unwanted horizontal scrolling is absent.

**Status:** Passed

---

### TC-011 — Check Console after user actions

**Preconditions:**
- Website is open in a desktop browser.
- DevTools is closed.

**Steps:**
1. Press F12 to open DevTools.
2. Open the Console tab.
3. Click the "Навыки" navigation item.
4. Switch the website theme.
5. Click the "GitHub" button.
6. Return to the website.
7. Review Console messages.

**Expected Result:**
- All actions work correctly.
- No red JavaScript errors appear in Console.

**Actual Result:**
- All actions work correctly.
- No red JavaScript errors are displayed in Console.

**Status:** Passed

---

### TC-012 — Check Network after page refresh

**Preconditions:**
- Website is open in a desktop browser.
- DevTools is closed.

**Steps:**
1. Press F12 to open DevTools.
2. Open the Network tab.
3. Press F5 to refresh the page.
4. Review the HTTP request statuses.

**Expected Result:**
- No failed HTTP requests with 4xx or 5xx statuses are present.
- Main website resources load successfully.

**Actual Result:**
- No failed HTTP requests are present.
- Observed successful statuses include 200 and 304.

**Status:** Passed

---

### TC-013 — Open direct link to Skills section

**Preconditions:**
- Website is open.
- User is at the top of the page.

**Steps:**
1. Click the "Навыки" item in the top navigation menu.
2. Copy the URL from the browser address bar.
3. Open a new browser tab.
4. Paste the copied URL.
5. Press Enter.

**Expected Result:**
- Website opens directly at the Skills section.
- The Skills section is displayed correctly.

**Actual Result:**
- Website opens directly at the Skills section.
- The section is displayed correctly.

**Status:** Passed

---

### TC-014 — Return after opening a case

**Preconditions:**
- Website is open.
- User is in the Cases section.

**Steps:**
1. Click one of the case links, for example "Открыть QA-отчёт".
2. Wait for the case page to open.
3. Click the Back button in the browser.

**Expected Result:**
- User returns to the portfolio website.
- The page returns to the Cases section.
- Website is displayed correctly.

**Actual Result:**
- User successfully returns to the portfolio website.
- The page returns to the Cases section.
- Website is displayed correctly.

**Status:** Passed

---

### TC-015 — Check website in light theme

**Preconditions:**
- Website is open.
- Dark theme is active.
- User is at the top of the page.

**Steps:**
1. Click the theme switch button.
2. Review the page from top to bottom.

**Expected Result:**
- Website is displayed correctly in light theme.
- Text, headings and buttons remain readable.
- Interface elements do not blend into the background.
- Page elements do not disappear after switching theme.
- Light theme remains active while reviewing the page.

**Actual Result:**
- Website is displayed correctly in light theme.
- Text, headings and buttons remain readable.
- Interface elements do not blend into the background.
- Page elements remain visible.
- Light theme remains active.

**Status:** Passed

---

### TC-016 — Check absence of horizontal scrolling in narrow browser window

**Preconditions:**
- Website is open in a desktop browser.

**Steps:**
1. Reduce the browser window width.
2. Review the page from top to bottom.
3. Try to scroll the page horizontally.

**Expected Result:**
- Website remains correctly displayed.
- Unwanted horizontal scrolling is absent.
- Interface elements do not go outside the visible area.

**Actual Result:**
- Website remains correctly displayed.
- Horizontal scrolling is absent.
- Interface elements remain inside the visible area.

**Status:** Passed

---

### TC-017 — Navigate website using Tab key

**Preconditions:**
- Website is open in a browser.

**Steps:**
1. Press Tab several times.
2. Check focus movement through links and buttons.
3. Verify that the active element is visually highlighted.

**Expected Result:**
- Focus moves sequentially through interactive elements.
- The active element is visually highlighted.
- Available navigation elements are not skipped.

**Actual Result:**
- Focus moves correctly through links and buttons.
- The active element is visually highlighted.

**Status:** Passed

---

### TC-018 — Activate navigation link using Enter

**Preconditions:**
- Website is open.
- User is at the top of the page.

**Steps:**
1. Press Tab until focus reaches the "Навыки" navigation item.
2. Press Enter.

**Expected Result:**
- Website navigates to the Skills section.
- The Skills section is displayed correctly.

**Actual Result:**
- Website successfully navigates to the Skills section.
- The section is displayed correctly.

**Status:** Passed

---

### TC-019 — Switch theme using keyboard

**Preconditions:**
- Website is open.
- Dark theme is active.
- User is at the top of the page.

**Steps:**
1. Press Tab until focus reaches the theme switch button.
2. Press Enter.
3. Review the page from top to bottom.

**Expected Result:**
- Website switches to the light theme.
- Text, buttons and headings remain readable.
- Interface elements do not blend into the background.
- Page elements do not disappear.
- Light theme remains active.

**Actual Result:**
- Website successfully switches to the light theme.
- Text, buttons and headings remain readable.
- Interface elements do not blend into the background.
- Page elements remain visible.
- Light theme remains active.

**Status:** Passed

---

### TC-020 — Preserve section after page refresh

**Preconditions:**
- Website is open.
- User is at the top of the page.

**Steps:**
1. Click the "Навыки" navigation item.
2. Wait for the page to scroll to the Skills section.
3. Press F5 to refresh the page.
4. Check the page position after refresh.

**Expected Result:**
- After refresh, the page remains at the Skills section.
- Website is displayed correctly.

**Actual Result:**
- After refresh, the page remains at the Skills section.
- Website is displayed correctly.

**Status:** Passed

---

## Test Summary

- Total test cases: 20
- Passed: 20
- Failed: 0
- Not tested: 0
- Defects found: 0

## Notes

No reproducible defects were discovered during this test run.

Browser DevTools checks showed:
- No red JavaScript errors in Console
- No failed HTTP requests
- Successful HTTP responses included 200 and 304
