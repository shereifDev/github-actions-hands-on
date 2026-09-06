**Exercise 3: Checking Out Source Code**
* **Objective:** Write a workflow that clones the repository into the runner's workspace and lists all files in the root directory.
* **Concepts Used:** `actions/checkout@v4`, `ls -la`.
* **Expected Result:** The logs will display the directory structure of the repository.
* **Note:** Runners start with empty directories. You must explicitly pull your code to interact with it using the latest stable version of the checkout action.
