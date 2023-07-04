# OpenSourceRepoTemplate
OpenSourceRepoTemplate

Copy from https://medium.com/code-factory-berlin/github-repository-structure-best-practices-248e6effc405

## Basic Folder Structure

* src Folder: The source code folder! However, in languages that use headers (or if you have a framework for your application) don’t put those files in here.
* test Folder: Unit tests, integration tests… go here.
* .config Folder: It should local configuration related to setup on local machine.
* .build Folder: This folder should contain all scripts related to build process (PowerShell, Docker compose…).
* dep Folder: This is the directory where all your dependencies should be stored.
* doc Folder: The documentation folder
* res Folder: For all static resources in your project. For example, images.
* samples Folder: Providing “Hello World” & Co code that supports the documentation.
* tools Folder: Convenience directory for your use. Should contain scripts to automate tasks in the project, for example, build scripts, rename scripts. Usually contains .sh, .cmd files for example.
    
## Git Special Files

* .gitignore: List of blobs for git to ignore. Affects commands like git add and git clean. You may use gitignore.io to generate a clean and useful gitignore file. [Good startpoint](https://www.toptal.com/developers/gitignore)
* .gitattributes: Let’s you define attributes on files (e.g., to change how files look in a diff).
* .mailmap: Lets you tell git that duplicate names or emails in the history are actually the same person.
* .gitmodules: Let’s you define submodules (subdirectories of your git repository which are checkouts of other git repositories).

## GitHub Special Files & Folders

* README File: README or README.txt or README.md etc. is a file that answer the What, Why and How of the project. GitHub will recognize and automatically surface the README to repository visitors. Here is an awesome list for more professional readme files.
* LICENSE File: LICENSE or LICENSE.txt or LICENSE.md etc. is a file that explains the legal licensing, such as any rights, any restrictions, any regulations, etc. GitHub has developed a tool to help you to choose the right license: [link](https://choosealicense.com/)
* CHANGELOG File: CHANGELOG or CHANGELOG.txt or CHANGELOG.md etc. is a file that describes what's happening in the repo. Version number increases, software updates, bug fixes… are examples of the file’s content.
* CONTRIBUTORS File: CONTRIBUTORS or CONTRIBUTORS.txt or CONTRIBUTORS.md etc. is a file that lists people who have contributed to the repo.
* AUTHORS File: AUTHORS or AUTHORS.txt or AUTHORS.md etc. is a file that lists people who are significant authors of the project, such as the people who are legally related to the work.
* SUPPORT File: SUPPORT or SUPPORT.txt or SUPPORT.md etc. is a file that explains how a reader can get help with the repository. GitHub links this file on the page "New Issue".
* SECURITY File: SECURITY describes your project's security policies, including a list of versions that are currently being maintained with security updates. It also gives instructions on how your users can submit a report of a vulnerability. Fore more details, check the following link.
* CODE_OF_CONDUCT File: CODE_OF_CONDUCT is a file that explains how to engage in a community and how to address any problems among members of your project's community. Here is some examples.
* CONTRIBUTING File: CONTRIBUTING is a file that explains how people should contribute, and that can help verify people are submitting well-formed pull requests and opening useful issues. GitHub links this file on page "New Issue" and the page "New Pull Request". This helps people understand how to contribute.
* ACKNOWLEDGMENTS File: ACKNOWLEDGMENTS or ACKNOWLEDGMENTS.txt or ACKNOWLEDGMENTS.md etc. is a file that describes related work, such as other projects that are dependencies, or libraries, or modules, or have their own copyrights or licenses that you want to include in your project.
* CODEOWNERS File: CODEOWNERS is a file that defines individuals or teams that are responsible for code in a repository. Code owners are automatically requested for review when someone opens a pull request that modifies code that they own. When someone with admin or owner permissions has enabled required reviews, they also can optionally require approval from a code owner before the author can merge a pull request in the repository.
* FUNDING File: funding.yml is a file to raise funding for or support your project.
* ISSUE_TEMPLATE File: When you add an issue template to your repository, project contributors will automatically see the template’s contents in the issue body. Templates customize and standardize the information you’d like included when contributors open issues. To add multiple issue templates to a repository create an ISSUE_TEMPLATE/ directory in your project root. Within that ISSUE_TEMPLATE/ directory you can create as many issue templates as you need, for example ISSUE_TEMPLATE/bugs.md. This list contains multiple templates for issues and pull requests.
* PULL_REQUEST_TEMPLATE File: When you add a PULL_REQUEST_TEMPLATE file to your repository, project contributors will automatically see the template's contents in the pull request body. Templates customize and standardize the information you'd like included when contributors create pull requests. You can create a PULL_REQUEST_TEMPLATE/ subdirectory in any of the supported folders to contain multiple pull request templates.
