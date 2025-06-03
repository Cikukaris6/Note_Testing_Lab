# 🧪 Functional Testing Report

## 👤 Student Information  
**Full Name:** Wanjiku Kariuki  
**Cohort:** February Cohort 2025  
**Date:** June 03, 2025  

---

## 🧪 What I Tested

| Test Type        | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| **Unit Test**     | Tested the `saveNote()` function for correct behavior and input validation. |
| **Integration Test** | Verified that saving a note updates the UI and data storage as expected.     |
| **System Test**    | Simulated a full note lifecycle: create → edit → delete.                   |

---

## 🐛 Bugs / Issues Identified

| Type          | Description                                                                                     |
|---------------|-------------------------------------------------------------------------------------------------|
| **Unit**        | Notes can be saved with empty titles or content.                                               |
| **Integration** | After clicking "Save Note", the new note doesn't always appear in the list.                    |
| **System**      | Editing a note sometimes deletes it without repopulating the input fields.                     |
| **UI / UX**     | No confirmation or feedback after saving or deleting a note.                                   |
| **Accessibility** | Form inputs lack labels, making them unreadable by screen readers.                              |

**GitHub Issues Filed:**

- 🔗 [Issue #1: Empty note saving allowed](https://github.com/Cikukaris6/Note_Testing_Lab/issues/1)  
- 🔗 [Issue #2: Save Note doesn’t update UI consistently](https://github.com/Cikukaris6/Note_Testing_Lab/issues/2)  
- 🔗 [Issue #3: Edit function deletes instead of editing note](https://github.com/Cikukaris6/Note_Testing_Lab/issues/3)

---

## 💬 Reflection

**1. What did you learn from testing this app?**  
I learned how to break down features into smaller, testable units and how different types of testing help catch unique issues.

**2. Which part of the app had the most bugs or problems?**  
The edit function was the most inconsistent — it sometimes deleted notes or failed to populate the input fields.

**3. What testing strategy worked best for you?**  
Starting with manual exploratory testing helped me identify visual and functional bugs before writing Jest unit tests.

**4. What was challenging during this lab?**  
Setting up Jest for UI-related behavior was tricky since DOM manipulation required extra setup.
