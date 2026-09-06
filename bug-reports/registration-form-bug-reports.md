# Registration Form Bug Reports

## Project
Registration Form Testing

## Test Type
Manual Functional Testing

## Environment
- OS: Windows
- Browser: Desktop browser
- Testing approach: Manual validation testing

---

## BR-001 — Registration form accepts a one-character full name

**Preconditions:**
- Registration form is open.

**Steps to Reproduce:**
1. Enter one character in the Full Name field.
2. Fill in the remaining required fields with valid data.
3. Click the Register button.

**Expected Result:**
- The form should reject the value in the Full Name field.
- A validation message about insufficient length should be displayed.

**Actual Result:**
- The form accepts a one-character full name.
- Registration proceeds without a validation error.

**Severity:** Medium  
**Priority:** Medium

---

## BR-002 — Registration form accepts a full name longer than the maximum allowed length

**Preconditions:**
- Registration form is open.

**Steps to Reproduce:**
1. Enter a value in the Full Name field that exceeds the maximum allowed length.
2. Fill in the remaining required fields with valid data.
3. Click the Register button.

**Expected Result:**
- The form should reject the Full Name value.
- A validation message about exceeding the maximum allowed length should be displayed.

**Actual Result:**
- The form accepts the Full Name value.
- Registration proceeds without a validation error.

**Severity:** Medium  
**Priority:** Medium

---

## BR-003 — Registration form accepts a negative desired weekly salary

**Preconditions:**
- Registration form is open.

**Steps to Reproduce:**
1. Navigate to the Desired Salary per Week field.
2. Enter a negative value.
3. Fill in the remaining required fields with valid data.
4. Click the Register button.

**Expected Result:**
- The form should reject the negative salary value.
- A validation message should indicate that negative values are not allowed.

**Actual Result:**
- The form accepts the negative salary value.
- Registration completes successfully.

**Severity:** Medium  
**Priority:** Medium

---

## BR-004 — Registration form accepts a future date of birth

**Preconditions:**
- Registration form is open.

**Steps to Reproduce:**
1. Navigate to the Date of Birth field.
2. Enter a date later than the current date.
3. Fill in the remaining required fields with valid data.
4. Click the Register button.

**Expected Result:**
- The form should reject a future date of birth.
- A validation message should be displayed.

**Actual Result:**
- The form accepts a future date of birth.
- Registration completes successfully.

**Severity:** Medium  
**Priority:** Medium

---

## BR-005 — Registration form accepts multiple desired expedition roles

**Preconditions:**
- Registration form is open.

**Steps to Reproduce:**
1. Navigate to the Desired Expedition Role field.
2. Enter more than one role.
3. Fill in the remaining required fields with valid data.
4. Click the Register button.

**Expected Result:**
- The form should not accept more than one role.
- A validation message should be displayed.

**Actual Result:**
- The form accepts multiple roles.
- Registration completes successfully.

**Severity:** Medium  
**Priority:** Low

---

## BR-006 — Registration form accepts an invalid email format

**Preconditions:**
- Registration form is open.

**Steps to Reproduce:**
1. Navigate to the Email field.
2. Enter a value that does not match a valid email format, for example `kirill`.
3. Fill in the remaining required fields with valid data.
4. Click the Register button.

**Expected Result:**
- The form should reject the invalid email.
- A validation message should be displayed.

**Actual Result:**
- The form accepts the invalid email value.
- Registration completes successfully.

**Severity:** Medium  
**Priority:** Medium

---

## BR-007 — Registration form accepts a contact number without the required "+" sign

**Preconditions:**
- Registration form is open.

**Steps to Reproduce:**
1. Navigate to the Contact Number field.
2. Enter a number without the "+" sign, for example `839239239293`.
3. Fill in the remaining required fields with valid data.
4. Click the Register button.

**Expected Result:**
- The form should reject the contact number without the required "+" sign.
- A validation message should be displayed.

**Actual Result:**
- The form accepts the contact number without the "+" sign.
- Registration completes successfully.

**Severity:** Medium  
**Priority:** Medium

---

## BR-008 — Registration form accepts an unsupported file format in the Passport/ID upload field

**Preconditions:**
- Registration form is open.

**Steps to Reproduce:**
1. Navigate to the Passport/ID upload field.
2. Upload a file in an unsupported format, for example `.webm`.
3. Fill in the remaining required fields with valid data.
4. Click the Register button.

**Expected Result:**
- The form should reject the unsupported file format.
- A validation message should be displayed.

**Actual Result:**
- The form accepts the `.webm` file.
- Registration completes successfully.

**Severity:** Medium  
**Priority:** Medium

---

## Summary

- Total bug reports: 8
- Severity Medium: 8
- Priority Medium: 7
- Priority Low: 1
