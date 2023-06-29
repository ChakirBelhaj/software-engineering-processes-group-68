# OWASP - wrong secrets

**Q1)**

> Describe, with your own words, what the project is about. Also, include in such a description the history of the project in terms of age, number of commits in the main branch, and number of collaborators.

**Answer:**

OWASP Wrong Secrets is a vulnerable/p0wnable app that is focused on secrets management. It can be used as a stand-alone game, as part of security trainings, awareness demos, as a test environment for secret detection tools, and bad practice detection tooling. The very first commit to the project was made on 16/8/2020 which means this project is almost 2 years and 10 months old. On the history page is briefly described when the first project version was available which is at 30/11/2021. There are 26 collaborators on the project whereof 3 are bots with the main branch having 3022 commits as of 18/6/2023.

**Q2)**

> What are the practices in terms of commit messages (consider only commits on the main branch).

**Answer:**

Looking at the comments on the commit messages we observe that all merge pull requests are tracked. GitHub supports referencing issues and pull requests using "#" followed by the issue/PR number which this project makes use of. This is consistent throughout the project. Most messages start with a verb describing the kind of action that was performed or change that was made. Some of these words are “fix” “update” “tweak” and “replace”. Messages are kept short and since this project has many collaborators names of the committer are publicly visible. 



**Q3)**

> How are the issues organized?

**Answer:**

The issues on the on the OWASP GitHub page are organized/labeled into different categories such as “Open”, “Closed”, “Bug”, “Enhancement”, “Help Wanted”, “Invalid”, “Question”, “Wontfix” and more. The issues are marked ‘to do’, ‘in progress’ or ‘done’ with 32 issues are yet to be started, 12 are in progress and 74 are currently done.



**Q4)**
>Are there instructions on how to contribute to the project? If yes, explain them.

**Answer:**

OWASP invites users to contribute through 3 different methods. - Filing issues. A user can contribute by identifying missing content or errors in the project. Create an issue and explain what you think is missing or needs improvement, along with suggestions on where it could be added.- Creating a pull request (PR). This is a direct contribution to the project. OWASP mentions before creating a PR, it's recommended to first create an issue to discuss the changes you intend to make. Small modifications like correcting typos may not require an issue. When creating a PR, OWASP asks for the code to meet the following requirements:

1. Code compliance: The code must adhere to the configured Checkstyle and PMD rules.

2. Testing: All new and changed code should have corresponding unit and/or integration tests. New and changed lessons must have integration tests.

3. Status checks: The status checks should pass for your last commit.

-Promote the project. Users can contribute by giving the project a star on GitHub or sharing information about it via social media to help spread the word.



**Q5)**
> What automated checks do exist on a commit pushed to the main branch?

**Answer:**
Depending on what type of commitment is made we observe that different automated checks are performed. A few automated checks that are seen in almost every commit are ‘CodeQL / Analyze’, ‘Dead Link Checker / linkChecker’ and ‘Docker container test / Container test’. Each of these automated checks test different functionalities or characteristics on the pushed commit. For example, ‘CodeQL / Analyze’ runs GitHub's industry-leading semantic code analysis engine against a repository's source code to find security vulnerabilities. It then automatically uploads the results to GitHub so they can be displayed in the repository's security tab1.

**Q6)**
>In the context of pull requests, what automated checks are done (consider checks on commits and comments posted in the pull requests by automated tools and bots)?

**Answer:**
In this project we see that different checks are performed depending on the software version and type of pull request. One of the collaborators of this project is Dependabot, which is a bot mainly used to find and fix vulnerable dependencies in a repository. Observing its activity on the pull request page, Dependabot is concerned with bump pull requests that update the version of a package in a repository. Automated checks that are performed during such a request are tests on java checkstyle and spotbugs,  linkChecker, minikube script and docker container. Various other checks exist throughout the project.

**Q7)**
>How are the release notes organized?*

**Answer:**

**Q8)**
>What is the license of the project? Explain if it’s permissive or restrictive.

**Answer:**

# Edison microservice

**Q1)**

> Describe, with your own words, what the project is about. Also, include in such a description the history of the project in terms of age, number of commits in the main branch, and number of collaborators.

**Answer:**

**Q2)**

> What are the practices in terms of commit messages (consider only commits on the main branch).

**Answer:**

**Q3)**

> How are the issues organized?

**Answer:**

**Q4)**
>Are there instructions on how to contribute to the project? If yes, explain them.

**Answer:**

**Q5)**
> What automated checks do exist on a commit pushed to the main branch?

**Answer:**

**Q6)**
>In the context of pull requests, what automated checks are done (consider checks on commits and comments posted in the pull requests by automated tools and bots)?

**Answer:**

**Q7)**
>How are the release notes organized?*

**Answer:**

**Q8)**
>What is the license of the project? Explain if it’s permissive or restrictive.

**Answer:**
