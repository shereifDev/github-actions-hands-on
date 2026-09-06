**Exercise 2: Branch Filtering & Target Restriction**
* **Objective:** Configure a workflow to trigger only when code is pushed to branches that start with `feature/`.
* **Concepts Used:** `on: push: branches`, wildcard character `*`.
* **Expected Result:** Pushing to main does nothing, but pushing to `feature/login` triggers the workflow.
* **Note:** Restricting workflows to specific branches saves CI/CD minutes and prevents unnecessary builds.
