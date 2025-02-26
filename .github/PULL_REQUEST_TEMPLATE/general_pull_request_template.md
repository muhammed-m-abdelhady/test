<!--
  Please include:
  - JIRA ticket ID(s) (e.g., JIRA-1234)
  - A brief description of your changes
  - How these changes solve the problem

  Note: Manual testing steps are not required.
-->

## JIRA Ticket(s)
[JIRA-XXXX](https://your-jira-instance/browse/JIRA-XXXX)

## Checklist
<!-- 
  to make the checkbox checked add x between the [].
  Leave the sections that has not been affected empty.
-->
**1. Change Classification:**

* [ ] **Breaking Change:** This change introduces incompatibilities with existing functionality or APIs.
    * **If checked:**
        * [ ] Migration scripts (if applicable) have been created and tested.
        * [ ] A plan for communicating the breaking change to users has been created.
* [ ] **Non-Breaking Change:** This change is backward-compatible.

**2. Rollback/Recovery:**

* [ ] **Difficult/Impossible Rollback:** This change cannot be easily reverted.
* [ ] **Easy Rollback:** This change can be reverted without significant issues.

**3. Data Impact:**

* [ ] **Significant Data Migration/Modification:** This change affects a large amount of data or requires complex migrations.
    * **If checked:**
        * [ ] Data migration scripts have been written and thoroughly tested.
        * [ ] Data integrity has been verified after migration.
* [ ] **Minimal Data Impact:** This change has minimal effect on existing data.

**4. Dependency Changes:**

* [ ] **Introduces New Dependencies:** This change adds new external libraries or services.
    * **If checked:**
        * [ ] Dependency licensing has been reviewed.

**5. Configuration Changes:**

* [ ] **Configuration Changes:** This change has effect on configurations.

## Description of Changes
_A concise summary of what has been changed_

## How It Solves the Problem  
_Explain briefly how these changes address the issue_

## Additional Information
_Any extra context or notes can be added here like files to check_
