# Day 5 - Bug Life Cycle & Types of Software Testing

## 📖 Introduction

Software testing is not just about finding bugs—it is also about managing them properly and ensuring that the software works correctly before it reaches users.

Today, I learned two important concepts:

- **Bug Life Cycle** – the complete journey of a defect from the moment it is discovered until it is closed.
- **Types of Software Testing** – the different testing techniques used to verify software quality, functionality, security, and performance.

Understanding these concepts is essential for every QA Engineer because testing does not end when a bug is found. The bug must be tracked, fixed, verified, and documented correctly.

---

# 🐞 What is a Bug?

A **bug**, also called a **defect**, is an error, flaw, or fault in a software application that causes the actual result to differ from the expected result.

### Example

Suppose a login page should allow users to log in with the correct username and password.

**Expected Result**
- User enters valid credentials.
- Login is successful.

**Actual Result**
- Even with the correct credentials, the application displays **"Invalid Username or Password."**

This unexpected behavior is considered a **bug**.

---

# 🔄 What is the Bug Life Cycle?

The **Bug Life Cycle** (also known as the **Defect Life Cycle**) is the sequence of stages that a bug goes through after it is discovered.

It helps testers, developers, and project managers monitor the status of every reported bug until it is resolved.

A well-defined Bug Life Cycle ensures:
- Better communication between QA and developers.
- Proper tracking of defects.
- No reported issue is forgotten.
- High-quality software before release.

---

# 📌 Stages of the Bug Life Cycle

## 1. New

A tester discovers a defect while testing the application and reports it in the bug tracking system.

The report usually contains:
- Bug title
- Description
- Steps to reproduce
- Expected result
- Actual result
- Severity
- Priority
- Screenshots (if needed)

---

## 2. Assigned

The project manager or team lead assigns the bug to the appropriate developer who is responsible for fixing it.

---

## 3. Open

The developer reviews the reported issue, reproduces the bug, analyzes its cause, and starts working on the fix.

---

## 4. Fixed

After identifying the root cause, the developer modifies the code and marks the bug as **Fixed**.

The updated application is then sent back to the QA team.

---

## 5. Retest

The tester verifies the same functionality using the same test case to ensure that the bug has been fixed correctly.

If the issue no longer exists, testing continues.

---

## 6. Closed

If the application behaves as expected during retesting, the tester changes the bug status to **Closed**.

This means no further action is required.

---

## 7. Reopened

If the issue still exists after the developer claims it has been fixed, the tester changes the status to **Reopened**.

The bug is sent back to the developer for further investigation.

---

## 8. Deferred

Sometimes a bug is valid but does not need immediate attention.

The team decides to postpone fixing it until a future release.

This status is called **Deferred**.

---

## 9. Rejected

A developer or project manager may reject the bug if:
- It is not actually a defect.
- It is expected behavior.
- It cannot be reproduced.

---

## 10. Duplicate

If the same bug has already been reported earlier, the new report is marked as **Duplicate**.

This avoids unnecessary duplicate work.

---

# 🧪 What is Software Testing?

Software Testing is the process of verifying and validating software to ensure it works according to the specified requirements.

The primary objectives are to:
- Find defects.
- Improve software quality.
- Ensure reliability.
- Verify business requirements.
- Increase customer satisfaction.

Different testing types are used because no single testing method can identify every possible issue.

---

# 📚 Types of Software Testing

## 1. Unit Testing

Unit Testing verifies individual functions, methods, or classes independently.

**Performed by:** Developers

### Example

Testing only the function that calculates the total bill without testing the entire application.

---

## 2. Integration Testing

Integration Testing checks whether multiple modules communicate correctly after being combined.

### Example

Testing whether the Login module successfully connects with the Dashboard module after authentication.

---

## 3. System Testing

System Testing evaluates the complete application as a whole.

It verifies whether all modules work together according to business requirements.

---

## 4. User Acceptance Testing (UAT)

Acceptance Testing is performed by clients or end users.

Its purpose is to confirm that the software satisfies business requirements before deployment.

---

## 5. Smoke Testing

Smoke Testing is a quick test performed after receiving a new software build.

It checks whether the major features are working.

If Smoke Testing fails, the build is rejected.

---

## 6. Sanity Testing

Sanity Testing verifies only the modified functionality after small code changes or bug fixes.

Unlike Smoke Testing, it focuses on a specific area instead of the whole application.

---

## 7. Regression Testing

Regression Testing ensures that recent code changes have not broken existing functionality.

It is performed after:
- Bug fixes
- New features
- Enhancements
- Updates

---

## 8. Retesting

Retesting verifies only the bug that was previously reported.

The tester executes the same test case again to confirm that the issue has been fixed.

---

## 9. Performance Testing

Performance Testing measures how efficiently the application performs under different workloads.

It checks:
- Speed
- Stability
- Scalability
- Response time

---

## 10. Security Testing

Security Testing identifies vulnerabilities in the application.

It ensures:
- User data is protected.
- Unauthorized users cannot access sensitive information.
- The system is resistant to attacks.

---

## 11. Usability Testing

Usability Testing evaluates how easy the application is for users.

It focuses on:
- User interface
- Navigation
- User experience
- Accessibility

---

# 🔍 Retesting vs Regression Testing

| Retesting | Regression Testing |
|------------|--------------------|
| Verifies a specific bug fix. | Verifies the overall application after changes. |
| Focuses only on failed test cases. | Tests both modified and existing features. |
| Performed after fixing a reported defect. | Performed after every significant code change. |
| Ensures the defect has been resolved. | Ensures no new defects were introduced. |

---

# 🎯 Key Takeaways

After today's learning, I now understand:

- What a bug is and how it affects software quality.
- Every stage of the Bug Life Cycle.
- Why bug tracking is important.
- The purpose of different software testing types.
- The difference between Retesting and Regression Testing.
- Why multiple testing techniques are required to build reliable software.

---

# 📝 Conclusion

The Bug Life Cycle provides a structured way to report, monitor, and resolve software defects, ensuring that no issue is overlooked.

The various Types of Software Testing help verify software from different perspectives, including functionality, performance, usability, and security.

Together, these concepts form a strong foundation for every QA Engineer and play a crucial role in delivering high-quality software products.

---



## 🎯 Day 5 Completed ✅
Bug Life Cycle & Types of Software Testing ✅

> *Every bug teaches something. Every test improves quality. Every day is another step toward becoming a skilled QA Engineer.*
## 📅 QA Learning Journey