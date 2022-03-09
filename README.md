<br />
<p align="center">
  <a href="https://github.com/icanseetime/branching-PR-test">
    🤓💻
  </a>

  <h3 align="center" id="top">How to use branching and pull requests</h3>
  <p align="center">
    This is a demo repo to practice using branching and pull requests.
    <br />
    <a href="https://github.com/icanseetime/branching-PR-test"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="http://baxita.github.io/light-pollution">View Demo</a>
    ·
    <a href="https://github.com/icanseetime/branching-PR-test/issues">Report Bug</a>
    ·
    <a href="https://github.com/icanseetime/branching-PR-test/issues">Request Feature</a>
  </p>
</p>

<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#become-a-collaborator">Become a collaborator</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
      <a href="#contribute-to-the-project">Contribute to the project</a>
      <ul>
        <li><a href="#setup">Setup</a></li>
        <li><a href="#pull-request">Pull request</a></li>
      </ul>
    </li>
    <li>
      <a href="#branching">Branching</a>
    </li>
    <li>
      <a href="#additional-resources">Additional resources</a>
    </li>
  </ol>
</details>

---

## Getting started

### Become a collaborator

1. Ask for permission to join the repo by contacting the project maintainer at imgjeits@stud.ntnu.no and ask to be added as a collaborator
2. Accept invitation

### Installation

1. Open your terminal
2. Navigate to a folder on your computer where you would like to store the repo
3. Clone the repo by typing the following
    ```sh
    git clone https://github.com/icanseetime/branching-PR-test.git
    ```
4. Open the local repository in your preferred editor

---

## Contribute to the project

### Setup

1. Go to Github and find an issue that is assigned to you
2. Create a new **feature** branch in your local repository that follows the naming conventions explained in [this table](#branching)
    - ⚠ Make sure that the new branch is branching out from the **develop** branch
3. Publish your branch
4. Move the issue on the Kanban board from _To do_ to _In progress_
5. Work on your issue until you are done and then move to the [pull request](#pull-requests) section

### Pull request

1. Finish commiting all the changes to your branch
    - Make sure you have tested that everything is working before the next step
2. Go to [the Github repo](https://github.com/icanseetime/branching-PR-test) and click the Pull request tab
3. Create a new pull request and make these changes to the setup:
    - Make sure the base branch is **develop**
    - Make sure the compare branch is the **feature** branch you have been working on
    - Check that there is a green check mark and the text "Able to merge"
        - If there are conflicts, you should figure out what the conflicts are, and how to solve them
    - Write a title for the pull request that explains what has been done
        - Optional step: Write a comment if you have something more to say about the work, that can not be summarized in the title
    - Add a reviewer
    - Create the pull request
4. Wait for the reviewer to review your request
5. When the reviewer:
    - approves your PR: continue with step 6
    - requests changes: make the suggested changes, commit them to the branch, update the pull request and request a re-review
6. Merge the pull request
7. Delete branch
8. Move the issue on the Kanban board from _In progress_ to _Done_

---

## Branching

| Type            | Information                                                                                              | Name                                                                                                                                                                                                                                      |
| --------------- | -------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **master/main** | What the users see / production branch. This branch automatically deploys when something is merged.      | Always named **_master_** or **_main_**                                                                                                                                                                                                   |
| release         | 1 branch per new release of the site. Used to test the new release before merging into master to deploy. | Named using [semantic versioning](https://semver.org/), e.g.: **_v1.0.0_**                                                                                                                                                                |
| **develop**     | Where the current work happens.                                                                          | Always named **_develop_**                                                                                                                                                                                                                |
| **feature**     | 1 branch per new feature. (1 issue = 1 feature)                                                          | Should be named **_feature/{ID}-{name}_**, where the _ID_ is the ID of the related issue, and the _name_ is the name of the issue you are working on. E.g.: _feature/1524-shopping-cart_. Issue name can be shortened if it is very long. |
| bugfix          | 1 branch per bug fix. Used when fixing errors (issues with bug tag)                                      | Should be named **_bugfix/{name}_**, where the _name_ is the name of the issue you are working on. E.g.: _bugfix/spelling-errors-in-menu_.                                                                                                |

⚠ _This is a fairly common branching system, but you should always check what system is being used for each project you are working on._

---

## Additional resources

-   [About branches](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)
-   [Create and delete branches](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository)
-   [About pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
-   [Creating a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
-   [Merging a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request)
-   [YouTube video explaining the branch workflow](https://youtu.be/Lj_jAFwofLs)
-   [A successful Git branching model (article)](https://nvie.com/posts/a-successful-git-branching-model/)
-   [Git Handbook from Github](https://docs.github.com/en/get-started/using-git/about-git)
-   [Pro Git (eBook)](https://git-scm.com/book/en/v2)
-   [Google](www.google.com) 😏

---

[Back to top](#top)
