# Implementation of Linting in Github Workflow 

In this we'll see how we can apply vaccum lint to find errors and bugs in the files/folders. THis will also lists only the changed json files we have in the files/folders.

**Example :** IN this the bash script lists all the types of files that hav been changed, but it will only lists the json changed files in the step.

This workflow will triggered at three conditions that are mention below:

1. **Opened:** When a pull request is created, it enters the "opened" state. This means that the pull request is new and has not yet been reviewed or edited by any team members.

2. **Reopened:** If a pull request is closed and then reopened, it enters the "reopened" state. This can happen if there were issues with the original pull request that needed to be addressed or if additional changes were made to the code after the pull request was closed.

3. **Edited:** If changes are made to a pull request after it has been opened, it enters the "edited" state. This means that the pull request has been modified in some way, such as adding new commits or making changes to existing code.