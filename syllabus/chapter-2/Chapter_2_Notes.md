 Testing Throughout the Software Development Lifecycle (Chapter_2)
------------------------------------------------------------------

 
1 Testing in the Context of a Software Development Lifecycle 

>> Explain the impact of the chosen software development lifecycle on testing 
>> (K1) Recall good testing practices that apply to all software development lifecycles
>>(K1) Recall the examples of test-first approaches to development 
>> (K2) Summarize how DevOps might have an impact on testing 
>> (K2) Explain shift left 
>>(K2) Explain how retrospectives can be used as a mechanism for process improvement

2 Test Levels and Test Types

>> (K2) Distinguish the different test levels 
>> (K2) Distinguish the different test types 
>> (K2) Distinguish confirmation testing from regression testing

3 Maintenance Testing 

>> (K2) Summarize maintenance testing and its triggers



Testing in the Software Development Lifecycle (SDLC) – Summary
---------------------------------------------------------------
---------------------------------------------------------------
SDLC Models
-----------
Different SDLC models (e.g., waterfall, V-model, spiral, agile) influence how and when testing occurs during development.

Impact on Testing
-----------------
The choice of SDLC affects the scope, timing, documentation, techniques, automation, and tester roles.

>>Sequential Models: Testing often starts after requirements, with dynamic testing later.

>>Iterative/Incremental Models: Each iteration produces a working product; testing is performed at all levels with fast feedback and regression testing.

>>Agile: Emphasizes change, lightweight documentation, extensive test automation, and experience-based manual testing.

Good Testing Practices
---------------------

Test activities correspond to development activities.

Different test levels have distinct objectives to avoid redundancy.

Early involvement of testers supports early defect detection ("shift left").

Test-Driven Development (TDD), Acceptance TDD (ATDD), Behavior-Driven Development (BDD):

Tests are written before code.

Tests guide development and support iterative models.

Automated tests help maintain code quality.

DevOps and Testing:
-------------------

Integrates development, testing, and operations.

Promotes continuous integration (CI) and continuous delivery (CD).

Benefits include fast feedback, increased automation, and reduced regression risk.

Challenges include tool setup and maintenance of automation.

Shift Left Testing:
------------------

?Testing is done earlier in the SDLC (e.g., during requirements review, coding).

?Improves quality and reduces later costs.

?Requires stakeholder buy-in.

Retrospectives:
---------------

Regular review meetings to improve testing and development processes.

Enhance team learning, process quality, and collaboration.

Test Levels
------------

>>>Component Testing: Testing individual units/components, usually by developers.

>>>Component Integration Testing: Testing interactions between components.

>>>System Testing: Testing the complete system's functionality and non-functional aspects.

>>>System Integration Testing: Testing interfaces between systems.

>>>Acceptance Testing: Validates readiness for deployment, often by users.

Test Types
----------

>>>Functional Testing: Verifies system functions meet requirements.

>>>Non-Functional Testing: Tests quality attributes like performance, security, usability.

>>>Black-box Testing: Based on specifications without internal structure knowledge.

>>>White-box Testing: Based on internal code structure.

Confirmation and Regression Testing:
------------------------------------

!Confirmation testing ensures defects are fixed.

!Regression testing ensures changes don’t break existing functionality.

!Regression testing benefits from automation.

Maintenance Testing:
-----------------------

!Testing changes after deployment (e.g., fixes, upgrades).

!Includes impact analysis and regression testing.

!Important for system updates, migrations, and retirement.

