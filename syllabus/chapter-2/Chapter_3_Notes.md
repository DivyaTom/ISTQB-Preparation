Static Testing Basics
----------------------
Definition
Static testing examines software artifacts without executing the software. It includes manual reviews and automated static analysis tools.

Purpose
Improve quality, detect defects early, and evaluate attributes like readability, completeness, correctness, testability, and consistency.

Applicable Work Products: Can examine almost any readable and structured work product, 

including:
Requirement specifications

Source code

Test plans and test cases

Product backlog items

Project documentation

Models

Not Suitable: Non-interpretable items such as 3rd party executable code (due to legal or technical reasons).

Static Analysis:

Tools check structured artifacts (e.g., code, models) for defects like coding standard violations, security vulnerabilities, maintainability, and more. It often integrates into CI/CD pipelines.

 Value of Static Testing
 -----------------------
Detects defects early in the SDLC, supporting the principle of early testing.

Identifies defects undetectable by dynamic testing (e.g., unreachable code, design flaws).

Enhances shared understanding and communication among stakeholders (testers, developers, business reps).

Can reduce overall project costs by preventing expensive fixes later.

Improves confidence in work products before dynamic testing starts.

Comparison Static Testing vs Dynamic Testing
-------------------------------------------
Aspect	Static Testing	Dynamic Testing
Execution	Does not execute software	Requires executing software
Defect detection	Finds defects directly	Finds defects through failure analysis
Target work products	Both executable and non-executable	Only executable work products
Defect types	Requirements inconsistencies, unreachable code, security issues	Runtime errors, performance issues
Quality attributes measured	Maintainability, readability	Performance, usability

 Feedback and Review Process
   ----------------------------------
Benefits of Early and Frequent Feedback

Prevents costly rework by aligning product with stakeholder needs early.

Ensures changes are understood and implemented early.

Improves clarity and reduces misunderstandings.

Helps focus on high-value features and risk mitigation.

Review Process Activities (Based on ISO/IEC 20246)
---------------------------------------------------

Planning: Define scope, goals, work products, quality attributes to check, exit criteria, standards, effort, schedule.

Review Initiation: Prepare participants, provide access to materials, clarify roles and responsibilities.

Individual Review: Reviewers independently analyze the product using techniques like checklist-based or scenario-based reviews and log anomalies, recommendations, questions.

Communication and Analysis: Review meeting to discuss anomalies, determine which are defects, assign ownership and actions, decide quality level, and whether follow-up review is needed.

Fixing and Reporting: Defects are fixed; reports document outcomes. Once exit criteria are met, the product is accepted.

Roles and Responsibilities
--------------------------------

>>Manager: Decides what to review, allocates resources.

>>Author: Creates and fixes the work product.

>>Moderator (Facilitator): Ensures review meetings run smoothly and fairly.

>>Scribe (Recorder): Records anomalies, decisions, and new findings.

>>Reviewer: Performs the review and identifies anomalies.

>>Review Leader: Organizes and oversees the review process.

Types of Reviews
----------------
>>Informal Review: Unstructured, focuses on finding anomalies without formal documentation.

>>Walkthrough: Author-led session aiming to evaluate quality, educate reviewers, build consensus, motivate improvements, and detect defects. May or may not include prior individual reviews.

>>Formal Reviews: More structured, may include inspections, technical reviews, with defined roles, procedures, and documentation (not covered in detail here but part of the broader spectrum).
