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

## Context
*Gives the reviewer some context about the work and why this change is being made, the WHY you are doing this. This field goes more into the product perspective.*

## Description
*Provide a detailed description of how exactly this task will be accomplished. This can be something technical. What specific steps will be taken to achieve the goal? This should include details on service integration, job logic, implementation, etc.*

## Changes in the codebase
*This is where becomes technical. Here is where you can be more focused on the engineering side of your solution. Include information about the functionality they are adding or modifying, as well as any refactoring or improvement of existing code.*

## Changes outside the codebase
*If you have made changes to external services, need to add additional values to the job settings, or need to add something new to the database, explain it here. This may include updates to third-party services, changes to infrastructure configuration, integration with external APIs, etc.*

## Aditional information
*Provide any additional information that might be useful to the reviewer in evaluating this pull request. This could include performance considerations,design choices, etc.*