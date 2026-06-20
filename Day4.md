# Software Testing Life Cycle (STLC)

The **Software Testing Life Cycle (STLC)** is a step-by-step process followed by the QA team to ensure that software is thoroughly tested before it is released. It helps testers organize testing activities, identify defects early, and verify that the application meets both business and user requirements. STLC is an important part of the **Software Development Life Cycle (SDLC)** because it focuses on delivering a high-quality and reliable product.

### Why STLC is Important

* Provides a structured and organized testing process.
* Helps detect defects at an early stage.
* Ensures all software requirements are properly tested.
* Improves the overall quality and reliability of the application.
* Makes it easier to monitor testing progress and report results.

---

# Phases of STLC

## 1. Requirement Analysis

This is the initial phase of STLC where the testing team studies the project requirements to understand what needs to be tested.

**Activities:**

* Review requirement documents and specifications.
* Discuss requirements with stakeholders when clarification is needed.
* Identify incomplete, unclear, or conflicting requirements.
* Analyze functional and non-functional requirements such as performance, security, and usability.
* Identify possible testing risks.

---

## 2. Test Planning

In this phase, the testing team creates a detailed plan describing how testing will be carried out.

**Activities:**

* Define the testing scope and objectives.
* Decide the testing approach (manual, automation, or both).
* Select testing tools, environments, and required resources.
* Set entry and exit criteria.
* Estimate testing effort, budget, and schedule.
* Assign responsibilities to team members.
* Prioritize testing based on project risks.
* Review and approve the final test plan.

---

## 3. Test Case Development

During this phase, testers prepare test cases and test data based on the project requirements.

**Activities:**

* Design detailed test cases.
* Create suitable test scenarios.
* Prepare test data for execution.
* Define the expected result for each test case.
* Review and update test cases if necessary.
* Maintain the Requirement Traceability Matrix (RTM) to ensure all requirements are covered.

---

## 4. Test Environment Setup

Before testing begins, a suitable environment is prepared to simulate the real working conditions of the application.

**Activities:**

* Install and configure required software and testing tools.
* Set up servers, browsers, operating systems, databases, and devices.
* Provide necessary user accounts and permissions.
* Verify that the environment is ready for testing.
* Integrate with CI/CD pipelines and automation tools when required.

---

## 5. Test Execution

In this stage, testers execute the prepared test cases and record the results.

**Activities:**

* Execute manual or automated test cases.
* Compare actual results with expected results.
* Report defects with severity and priority.
* Retest resolved defects.
* Perform regression testing whenever changes are made.
* Record and analyze testing outcomes.
* Generate execution reports.

---

## 6. Test Closure

This is the final phase of STLC where all testing activities are completed and documented.

**Activities:**

* Prepare the Test Summary Report.
* Confirm that all critical defects have been resolved or properly documented.
* Clean up the testing environment.
* Archive test cases, test data, and reports for future reference.
* Conduct a review to identify lessons learned and improvement opportunities.
* Share the final testing results with stakeholders.

---

# Difference Between SDLC and STLC

## 📖 Overview

Although **Software Development Life Cycle (SDLC)** and **Software Testing Life Cycle (STLC)** are closely related, they serve different purposes. SDLC focuses on developing software, while STLC focuses on testing the software to ensure its quality before release.

---

## 📊 SDLC vs STLC

| Aspect | SDLC (Software Development Life Cycle) | STLC (Software Testing Life Cycle) |
|--------|-----------------------------------------|------------------------------------|
| **Definition** | A structured process that covers the complete development of software, from gathering requirements to maintenance. | A structured process that defines all testing activities, from requirement analysis to test closure. |
| **Primary Focus** | Developing and delivering software. | Verifying and validating software quality. |
| **Main Phases** | Requirement Gathering, Design, Development, Testing, Deployment, Maintenance | Requirement Analysis, Test Planning, Test Case Development, Test Environment Setup, Test Execution, Test Closure |
| **Performed By** | Business Analysts, Developers, Project Managers, and QA Team | Primarily the QA or Testing Team |
| **Deliverables** | Software application, design documents, user manuals, deployment package | Test plan, test cases, defect reports, test summary report, test closure report |
| **Objective** | Build software that meets business and user requirements. | Ensure the software is reliable, meets requirements, and is free from critical defects. |
| **Relationship** | Covers the entire software development process. | A subset of SDLC that focuses only on testing activities. |

---

## 🔑 Key Differences

- **SDLC** focuses on developing software, whereas **STLC** focuses on testing the software.
- **SDLC** begins with requirement gathering and ends with software maintenance, while **STLC** starts with requirement analysis and ends with test closure.
- **Developers and project teams** are mainly responsible for SDLC, whereas the **QA team** is mainly responsible for STLC.
- **STLC** is a part of **SDLC** and helps ensure the software developed during SDLC meets quality standards before release.

---
## 📝 Conclusion

The **Software Development Life Cycle (SDLC)** and the **Software Testing Life Cycle (STLC)** work together to deliver high-quality software. While **SDLC** focuses on planning, designing, developing, deploying, and maintaining the software, **STLC** ensures that the software is thoroughly tested at every stage to identify defects and verify that it meets user and business requirements. By following both lifecycles, development and testing teams can build reliable, high-quality applications, reduce defects, and deliver software that performs as expected.

## 🎯 Day 4 Completed ✅

**Part of QA Engineer Learning Journey.**
