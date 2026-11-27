# Acceptance Criteria
<!--
Acceptance criteria tell you when a user story is DONE. Each one must be testable: pass or fail.
Write 2–3 criteria for every user story using this format:

Given [a situation], when [the user does something], then [this should happen].

Tips:
- Number them under their story: AC1.1 and AC1.2 belong to US1.
- Describe what the user SEES, not how the code works.
- Include at least one "what if it goes wrong" case per story (empty input, no results).
- Avoid vague words like "fast," "nice," or "easy." Could a classmate test it and agree it passed?

Example:
## US1: View today's menu
- AC1.1: Given I open the App page, when it loads, then I see each dish with its name, photo and price.
- AC1.2: Given no dishes are added yet, when I open the menu, then I see "No dishes today yet."

AC - Acceptance Criteria
-->

### Feature: Office Selection & Search 
US1: As a student, I want to browse, search, and filter available campus offices, so that I can quickly find the specific office I need to visit. 

- AC1.1: Given I am on the main dashboard, when the page loads, then I see a list of campus offices (such as Registrar, Cashier, Clinic, Guidance, Admissions, and Student Affairs). 

- AC1.2: Given I click on a specific office from the list, when it is selected, then the application displays that office's dedicated queue details. 

### Feature: Live Queue Status Display 
US2: As a student, I want to view the current queue status of a selected office, so that I know how many people are ahead of me and how long I will have to wait. 

- AC2.1: Given I have selected a campus office, when its queue status loads, then I can clearly see the number currently being served. 

- AC2.2: Given I am viewing an office's queue status, then the interface displays the total number of people currently waiting in line. 


### Feature: Virtual Queue Number Generation 
US3: As a student, I want to request and receive a virtual queue number after submitting my required details, so that I can hold my spot in line without physically standing in a crowd. 

- AC3.1: Given I select an office and click the button to get a queue number, when the request modal opens, then I am prompted to enter required information. 

- AC3.2: Given I submit the queue request form with valid, complete information, when I confirm, then the system generates and displays a unique virtual queue number and updates the waiting count. 

