# 🧪 Manual Testing Basics.

This repository contains beginner-friendly notes and concepts about **Manual Testing** in Software Quality Assurance (QA).

---

# 📌 What is Manual Testing?

Manual Testing is the process of testing software manually by a human, without using automation tools.

A tester checks whether the application works correctly by:

* Clicking buttons
* Entering data
* Checking outputs
* Finding bugs/issues

### Example

A tester enters a username and password on a login page and clicks the Login button to verify whether the system behaves as expected.

---

# 🎯 Why Manual Testing?

Manual testing helps to:

* Find bugs
* Check if features work properly
* Ensure good user experience
* Verify requirements

---

# 🔄 SDLC vs STLC.

## SDLC - Software Development Life Cycle

Software development process:

1. Requirement Gathering
2. Design
3. Development
4. Testing
5. Deployment
6. Maintenance

---

## STLC - Software Testing Life Cycle

Software testing process:

1. Requirement Analysis
2. Test Planning
3. Test Case Design
4. Test Environment Setup
5. Test Execution
6. Test Closure

---

# 🧪 Types of Manual Testing

## ✅ Functional Testing

Checks whether application features work correctly.

### Examples

* Login works?
* Add to cart works?
* Search works?

---

## 🎨 UI Testing

Checks the user interface and design.

### Examples

* Button visible?
* Text aligned correctly?
* Colors displayed properly?

---

## 👤 Usability Testing

Checks whether the application is easy to use.

### Examples

* Easy navigation
* User-friendly design

---

## 🔁 Regression Testing

Checks whether old features still work after new changes.

### Example

Developer fixes login bug → tester checks login and related features again.

---

##  Smoke Testing

Basic testing to verify whether the build is stable.

### Examples

* Application opens successfully
* Login works
* Dashboard loads

If smoke testing fails, further testing is usually stopped.

---

## 🛠️ Sanity Testing

Quick testing after a small bug fix.

### Example

Password reset bug fixed → tester checks only password reset functionality.

---

## 🔍 Exploratory Testing

Testing without predefined test cases.

Tester explores the application freely to find defects.

---

## 🎲 Ad-hoc Testing

Random testing without proper planning or documentation.

---

# 📄 Test Case

A **Test Case** is a document that describes what to test and expected outcomes.

| Field           | Description                       |
| --------------- | --------------------------------- |
| Test Case ID    | TC_001                            |
| Test Scenario   | Login                             |
| Test Steps      | Enter valid username and password |
| Expected Result | User logs in successfully         |
| Actual Result   | Passed                            |

---

# 📌 Test Scenario

A high-level functionality to test.

### Example

Verify login functionality.

One test scenario can contain multiple test cases.

---

# 🐞 Bug / Defect

A bug occurs when the actual result does not match the expected result.

### Example

User enters correct credentials but cannot log in.

---

# 🔄 Bug Life Cycle

Typical bug stages:

1. New
2. Assigned
3. Open
4. Fixed
5. Retest
6. Closed

Other possible states:

* Reopened
* Rejected
* Deferred

---

# ⚠️ Severity vs Priority

## Severity

Defines how serious the bug is.

### Example

Application crash = High Severity

---

## Priority

Defines how quickly the bug should be fixed.

### Example

Logo spelling mistake = Low Severity but High Priority

---

# 📋 Test Plan

A document describing:

* What to test
* How to test
* Who will test
* Testing schedule

---

# 🧾 Test Data

Input values used during testing.

### Examples

* Valid username
* Invalid password
* Empty fields

---

# ✅ Positive and Negative Testing

## Positive Testing

Testing with valid inputs.

### Example

Correct username and password.

---

## Negative Testing

Testing with invalid inputs.

### Example

Incorrect password.

---

# 🔁 Retesting

Testing a bug again after it has been fixed.

---

# 🔄 Regression Testing

Testing existing features after modifications to ensure nothing is broken.

---

# 🌐 Real Example — Login Page Testing

### Sample Test Cases

1. Login with valid credentials
2. Login with invalid password
3. Login with empty username
4. Login with empty password
5. Verify password field is hidden
6. Verify forgot password functionality
7. Verify error messages are displayed correctly

---

# 🎤 Common Interview Questions

## What is Manual Testing?

Manual testing is software testing performed manually without automation tools to identify defects.

---

## Difference between Test Case and Test Scenario?

* Test Scenario → High-level functionality
* Test Case → Detailed testing steps

---

## Difference between Severity and Priority?

* Severity → Impact of the bug
* Priority → Urgency to fix the bug

---

## What is Regression Testing?

Testing existing features after changes to ensure nothing breaks.

---

## What is Smoke Testing?

Basic testing performed to verify whether the build is stable enough for further testing.

---

# 🚀 Practice Websites

* [OrangeHRM Demo](https://opensource-demo.orangehrmlive.com/?utm_source=chatgpt.com)
* [Sauce Demo](https://www.saucedemo.com/?utm_source=chatgpt.com)

You can practice:

* Writing test cases
* Finding bugs
* Creating bug reports
* Manual testing workflows

---

# 📚 Technologies / Concepts Covered

* Manual Testing
* SDLC
* STLC
* Functional Testing
* UI Testing
* Regression Testing
* Smoke Testing
* Bug Life Cycle
* Test Cases
* QA Basics

---

# 👩‍💻 Author

Geethmi Sandunika
