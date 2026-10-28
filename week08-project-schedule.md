# Project Schedule: RCHN Patient Intake and Scheduling System
**Consultant:** [Osazee John Alohan]
**Role:** Associate Consultant, Project Manager, NovaTech Consulting
**Engagement:** Regional Care Health Network (RCHN)
**Date:** [10/27/26]
---
## Work Breakdown Structure

### Grouping 1: [Remote Health Care Network]
- [Define the product vision and establish the core project team governance.]
- [Gather comprehensive requirements for the health and data modules.]
- [Finalize the project charter and obtain all stakeholder approvals.]
### Grouping 2: [Project Planning and Backlog Preperations]
- [Choose the main product backlog based on the five main user stories.]
- [Map out all the sprint schedules, release goals and use story acceptance criteria.]
- [Estimate all the story points and find the team's starting pace.]
### Grouping 3: [System Development and Configurations]
- [Build a secure user registration and access control]
- [Make a real-time patient-doctor messaging interface.]
- [Build the core patient scheduling workflow and standardize intake forms]

### Grouping 4: [Clinic Deployment and Project Closures]
- [Implement end to end user acceptance testing with the clinic staff]
- [Deliver comprehensive user training sessions to clinic staff.]
- [Hand over any documentation and sign off on all closures.]



[Continue this pattern for each course WBS grouping. Your WBS must include at least four major groupings with at least two lower-level work components each.]

### WBS Rationale
[My WBS represents the Week 5 Project Scope by showing what it would take to build the core patient scheduling workflow. As I have shown in my 3rd Work Packages phase.
The application maintenance and the operational support were excluded because my WBS is strictly covering the project's lifecycle up to the final deployment of Phase 4.
All the maintenance does not fall on the temporary scope of this project.]
---
## Task Dependencies
[List each dependency you identified. Repeat this line for each one.]
- [Finalize the project charter and obtain stakeholder approval (1.3)] → [Choose the main product backlog based on the 5 user stories], [Dependency type: Finish-to-Start]

- - [Build a secure user registration and access control (3.1)] → [Implement end to end user acceptance testing], [Dependency type: Finish-to-Start]
 
  - - [Implement end to end user accepteance testing] → [Deliver comprehensive user training sessions to clinic staff.], [Dependency type: Finish-to-Start]

### Dependency Logic
[One dependency I would choose is my Task 3.1 to Task 4.1. If the predecessor activity "Build a secure user registration and role-base access control" slips by 2 weeks, then it will damage the project's timeline. 
The user acceptance testing might be affected by it because it directly relies on a fully built and secure environment. To minimize the schedule damage, we could overlap the work. 
Instead of waiting around for the security feature to be 100% done, the team can start checking other things out early. This will keep the project moving forward.]
---
## Activity Schedule
| ID | Activity | Duration (working days) | Predecessors | Start week |
|---|---|---:|---|---:|
| A | [Finalize the project charter | [5] | None | [1] |
| B | [Draft product backlog] | [5] | [A] | [2] |
| C | [Build user registration and login] | [10] | [B] | [3] |
| D | [Execute user acceptance testing] | [5] | [C] | [5] |

### Scheduling Assumptions
[I estimated the durations and start weeks by giving out basic tasks for 5 days each. I gave the programming task 10 days because coding usually take more time and effort. 
A thing that can go wrong is if the clinic doctors and nurses don't have time to test the software, then the whole project will run late.]
---
