# CONTRIBUTING Guidelines
A CONTRIBUTING file is a plain text file that provides a guide on what and how to contribute to a project. Create it in the top level directory of your project.

## Goal
The goal of your CONTRIBUTING file is to help contributors submit well formed pull requests and to open useful issues. Learn more at [setting guidelines for repository contributors](https://help.github.com/en/github/building-a-strong-community/setting-guidelines-for-repository-contributors).

It supports the contributor on the following tasks.

1. Environment details: How to set up your development environment. We recommend including this in the README so provide a link to the file here.
2. How to submit changes: Provide Pull Request protocol, include expected norms on response for the code owners on submission.
3. How to report a bug: Detail how an issue should be created by filling out the `bug report issue` and include what information is expected.
4. How to raise a new feature request: Detail how an issue should be created by filling out the `feature request issue` and include what information is expected.
---

## CONTRIBUTING template
Use this as a sample guide for your CONTRIBUTING file. Change as you need.

```
:tada: Thanks for taking the time to contribute. :tada:

### Purpose

Use this document to learn how to contribute to `repo name`.

### Project Documentation

The `README` in the root of the repository should link to
project documentation. If you can't find the documentation you're
looking for, please file a `GitHub issue` with details of what you would like to see documented.

### I don't want to read the whole thing,I just have a question!
We use our `GitHub team` discussions to give helpful answers on any questions about this project. Please don't add an issue to ask a question.

### What should I know before I get started
For details on prerequisites and how to get started on with this project please go to the `README` file

### Bug report

Bugs are tracked as Github issues using the `bug template issue`. Use this template to create a bug report, include as many details as possible as the information it asks for helps us resolve issues faster.

Note: If you find a Closed issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

### Feature requests

Feature requests or suggested enhancements are tracked as GitHub issues using `feature request issue`. Use this template to capture the following information.
- Use a clear and descriptive title for the issue to identify the request.
- Provide a step-by-step description of the suggested enhancement with as much details as possible.
- Describe the current behavior and explain which behavior you expected to see instead and why.
- Explain why this enhancement would be useful.

### First code contribution

A good place to start when considering how to contribute to this project is to review the issues labelled `good first issue` and `help-wanted`. As a first time contributor choose `good first issue` as this should require limited code changes. For a more in-depth contribution select a `help-wanted` issue.

### Pull requests

Please adhere to the following steps to open a pull request for your proposed changes. *Note that examples of how to contribute to a project are using the command line interface. There is also the option of using GitHub Desktop to manage your work, learn more [here](https://help.github.com/en/desktop/contributing-to-projects).*

- Clone the repo. If you cloned the repo a while ago, get the latest changes from master. *For example:*
    ```
    bash
    $ git clone git@github.com/adriancollins/hexa-writing-style-guide
    ```
Or, update you local copy
    ```
    bash
    $ git pull origin master
    ```
- Create a new branch to contain your feature, change, or fix. Branch name should be short and reflect the work you are doing. *For example:*
    ```
    bash
    $ cd writing-style-guide
    $ git checkout -b my-code-changes
    ```
- Make changes, including necessary changes to READme.md and test locally
- Commit your changes. *For example:*
    ```
    bash
    $ git add README.md
    $ git commit
    $ git push origin my-code-changes
    ```
- Push changes to GitHub.
- Create a pull request, providing a title and details on the changes you have made. Link to an issue by adding # issue no.
- Two developers must approve your pull request before you can merge it to master. Expect review responses within 24hrs.
- Merge the pull request on approval. Consider squashing all commits for this pull request squash to retain a clean and readable git history.
- Choose to close the pull request without merging if the change is not longer required.

Read more details on [contributing using pull requests](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests).
```
