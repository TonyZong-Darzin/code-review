# Workflow for pull requests on Github

#### Working on a feature or issue branch

Create a separate branch for the new feature or issue. Update, add, commit, and push changes in that branch.

## Start a pull request (PR)

Once you finish the work in the dedicated branch, you are ready to make a PR to the target (main) branch.

<img src="./images/PR_review_process.png" width="500px"/>

### 1. Click on `Compare & pull request` or `Create pull request`

#### In your repository

The `Compare & pull request` button will appear in your repository after you push any changes. Check the branch in that message box to ensure it is the one for which you want to create a PR, and then click the button.

<img src="./images/web-page-pull-request.png" width="700px"/>

If you can't find the `Compare & pull request` button show up in your repository you can create PR in [pull requests section](#pull-requests-section).

#### In `Pull requests` tab

Navigate to `Pull requests` tab **in your repository**.

<img src="./images/pull-request-in-navbar.png" width="400px"/>
<br/>

Click `New pull request` button.

<img src="./images/new-pull-rquest-btn.png" width="500px"/>

#### On Github desktop

Click `Create pull request` button.

<img src="./images/desktop-pull-request.png" width="600px"/>

### 2. Select your PR base branch and compare branch

If you navigate through `Compare & pull request` button, it should automatically set the base branch to main and compare branch as the branch that has the most recent changes.

<img src="./images/base-compare.png" width="700px"/>

**base:** the branch where you want to merge your changes into.

**compare:** the topic branch where you made your changes.

### 3. Write your PR title and description

Description accepts [Markdown syntax](https://www.markdownguide.org/basic-syntax/).

The [PR template](./pull-request-template.md) will automatically apply to the description when the PR is created. Fill in the Task title, Solution description, and Checklist (You can do it after [submitting the PR](#4-submit-pr)).

<img src="./images/pull-request-description.png" width="800px"/>

You can also toggle to see a preview of the description.

<img src="./images/pull-request-description-preview.png" width="800px"/>

### 4. Submit PR

Before submitting this PR, ensure that you have reviewed all of your changes, then click on `Create pull request`.

### 5. Request reviewers

Go to `Reviewers` and select users from the list to review your PR. Note that you must have at least one approving review in order to proceed merging the PR.

<img src="./images/select-reviewer.png" width="820px"/>

### 6. Resolve conflicts

Click on `Create pull request` and resolve the conflicts.

<img src="./images/conflict-files.png" width="800px"/>

### 7. Wait for the PR review to be completed

Review required

<img src="./images/wait-reviews.png" width="800px"/>

Changes approved

<img src="./images/review-complete.png" width="795px"/>

[See code review guide](./code-review-guide.md)

### 8. Made changes based on code reviews

<img src="./images/review-not-complete.png" width="800px"/>

TODO:

### 9. Merge PR

Create a merge commit and merge PR.

<img src="./images/mergePR.png" width="700px"/>
