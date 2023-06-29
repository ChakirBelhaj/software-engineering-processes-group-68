
# OWASP - wrong secrets

## **[Q1]** Intro

> Describe, with your own words, what the project is about. Also, include in such a description the history of the project in terms of age, number of commits in the main branch, and number of collaborators.

**Answer:**

OWASP Wrong Secrets is a vulnerable/p0wnable app that is focused on secrets management. It can be used as a stand-alone game, as part of security trainings, awareness demos, as a test environment for secret detection tools, and bad practice detection tooling. The very first commit to the project was made on 16/8/2020 which means this project is almost 2 years and 10 months old. On the history page is briefly described when the first project version was available which is at 30/11/2021. There are 26 collaborators on the project whereof 3 are bots with the main branch having 3022 commits as of 18/6/2023.

## **[Q2]** Commit Best Practices

> What are the practices in terms of commit messages (consider only commits on the main branch).

**Answer:**

Looking at the comments on the commit messages we observe that all merge pull requests are tracked. GitHub supports referencing issues and pull requests using "#" followed by the issue/PR number which this project makes use of. This is consistent throughout the project. Most messages start with a verb describing the kind of action that was performed or change that was made. Some of these words are “fix” “update” “tweak” and “replace”. Messages are kept short and since this project has many collaborators names of the committer are publicly visible.


## **[Q3]** Issues

> How are the issues organized?

**Answer:**

The issues on the on the OWASP GitHub page are organized/labeled into different categories such as “Open”, “Closed”, “Bug”, “Enhancement”, “Help Wanted”, “Invalid”, “Question”, “Wontfix” and more. The issues are marked ‘to do’, ‘in progress’ or ‘done’ with 32 issues are yet to be started, 12 are in progress and 74 are currently done.



## **[Q4]** Contribute Rules

>Are there instructions on how to contribute to the project? If yes, explain them.

**Answer:**

OWASP invites users to contribute through 3 different methods. - Filing issues. A user can contribute by identifying missing content or errors in the project. Create an issue and explain what you think is missing or needs improvement, along with suggestions on where it could be added.- Creating a pull request (PR). This is a direct contribution to the project. OWASP mentions before creating a PR, it's recommended to first create an issue to discuss the changes you intend to make. Small modifications like correcting typos may not require an issue. When creating a PR, OWASP asks for the code to meet the following requirements:

1. Code compliance: The code must adhere to the configured Checkstyle and PMD rules.

2. Testing: All new and changed code should have corresponding unit and/or integration tests. New and changed lessons must have integration tests.

3. Status checks: The status checks should pass for your last commit.

-Promote the project. Users can contribute by giving the project a star on GitHub or sharing information about it via social media to help spread the word.


## **[Q5]** Automated Checks on Commit

> What automated checks do exist on a commit pushed to the main branch?

**Answer:**
Depending on what type of commitment is made we observe that different automated checks are performed. A few automated checks that are seen in almost every commit are ‘CodeQL / Analyze’, ‘Dead Link Checker / linkChecker’ and ‘Docker container test / Container test’. Each of these automated checks test different functionalities or characteristics on the pushed commit. For example, ‘CodeQL / Analyze’ runs GitHub's industry-leading semantic code analysis engine against a repository's source code to find security vulnerabilities. It then automatically uploads the results to GitHub so they can be displayed in the repository's security tab1.

## **[Q6]** Automated Checks on PULL Request

>In the context of pull requests, what automated checks are done (consider checks on commits and comments posted in the pull requests by automated tools and bots)?

**Answer:**
In this project we see that different checks are performed depending on the software version and type of pull request. One of the collaborators of this project is Dependabot, which is a bot mainly used to find and fix vulnerable dependencies in a repository. Observing its activity on the pull request page, Dependabot is concerned with bump pull requests that update the version of a package in a repository. Automated checks that are performed during such a request are tests on java checkstyle and spotbugs,  linkChecker, minikube script and docker container. Various other checks exist throughout the project.

## **[Q7]** Release Notes

>How are the release notes organized?*

**Answer:**
The release notes are listed on the tags page. The project has a total of 73 tags with each tag being a newly released version. Release notes are organized with changes listed in bullet points. Every bullet point typically represents a specific change or update made in the project. The format includes the action, description, contributor and a reference to the specific pull request or issue. Any user that collaborated on a version is also listed  underneath. Each release note contains an asset with the source code of that version. This consistent format allows users and stakeholders to understand updates and progress made during the project.

## **[Q8]** License

>What is the license of the project? Explain if it’s permissive or restrictive.

**Answer:**
This project makes use of the GNU Affero General Public License v3.0 (AGPLv3) which is a free copyleft license for software and other related work. Copyleft licenses are restrictive and AGPLv3 is considered a strong copyleft license meaning it significantly limits on how the software can be used, modified and distributed. Software that uses AGPLv3-licensed code must be open source and released under the same license. When strict conditions are met, users are allowed to modify and distribute the software for both private and commercial use. However, this license mentions that users have limited liability and warranty. This means that the software authors are not responsible for any damages or losses that arose from the use of the software, and provide no guarantees regarding performance or suitability.

# Edison microservice

## **[Q1]** Intro

> Describe, with your own words, what the project is about. Also, include in such a description the history of the project in terms of age, number of commits in the main branch, and number of collaborators.

**Answer:**
Edison microservice is a project that contains a collection of libraries that help developers create JVM microservices faster. JVM (Java Virtual Machine) microservices are often smaller independent pieces of a larger application designed to do one thing well. They are written in java and can be run on any platform supporting the JVM. Their first release was on April 11 2017. The project has a total of 53 contributors with 1880 (recorded on 29/06/2023) commits on the main branch. 


## **[Q2]** Commit Best Practices

> What are the practices in terms of commit messages (consider only commits on the main branch).

**Answer:**
The initial word of the commit messages are stating the activity that is being done such as: “fix”, “release”, “update”, “Bump”. After it is followed by a small description of the given activity, some messages contains a “#” followed by a number at the end to refer to an issue or pull request within the same repository. Every commit message also shows the person who committed and whether if all the tests that is being runned is successful or not, the tests consists of: CodeQL / Analyze (Java) (push), CodeQL / Analyze (JavaScript) (push), and Build / build (push).  Each commit is also assigned with a distinct identifier called the SHA (Secure Hash algorithm) i.e., Commit ID. 

## **[Q3]** Issues

> How are the issues organized?

**Answer:**
Each issue is partitioned in two statuses, open and closed, where each status has it’s own tab with the given issues, some issues are also assigned with a label to state the type of the issue such as: “enhancement”, “bug”, “missing docs”. The description of each label resides in a separate label tab. The text format of the stated issue are plain description of the issue. Some issues also comes with a mile stone version number.

## **[Q4]** Contribute Rules

>Are there instructions on how to contribute to the project? If yes, explain them.

**Answer:**

OWASP invites users to contribute through 3 different methods.
- Filing issues. A user can contribute by identifying missing content or errors in the project. Create an issue and explain what you think is missing or needs improvement, along with suggestions on where it could be added.
- Creating a pull request (PR). This is a direct contribution to the project. OWASP mentions before creating a PR, it's recommended to first create an issue to discuss the changes you intend to make. Small modifications like correcting typos may not require an issue. When creating a PR, OWASP asks for the code to meet the following requirements:

  1. Code compliance: The code must adhere to the configured Checkstyle and PMD rules.

  2. Testing: All new and changed code should have corresponding unit and/or integration tests. New and changed lessons must have integration tests.

  3. Status checks: The status checks should pass for your last commit.

- Promote the project. Users can contribute by giving the project a star on GitHub or sharing information about it via social media to help spread the word.

## **[Q5]** Automated Checks on Commit
> What automated checks do exist on a commit pushed to the main branch?

**Answer:**
This github repository performs the following automated checks: 
Gradle Build:
The build-main.yml and build_2.7.x.yml configuration file shows that the repository uses GitHub Actions to build the main branch for all versions other than 2.7.x and vice versa, respectively.. When changes are pushed to the main branch or a pull request is opened against the main branch, it triggers a job that sets up Java 17 on an Ubuntu machine, grants execute permissions for gradlew, builds the project with Gradle using the ./gradlew check command. This command triggers a series of tasks within the Gradle build system to ensure the integrity of the codebase. The tasks involve compiling the source code, running unit tests, and performing static code analysis. Thereafter it uploads a JaCoCo report.
CodeQL Analysis (Java):
The codeql-analysis.yml configuration file indicates that the repository uses CodeQL analysis for two languages: Java and JavaScript. The file states that this action does not run for the dependabot[bot] and that the job is done on an Ubuntu machine.
It performs CodeQL initialization and uses Autobuild to automatically build any compiled languages. If Autobuild fails, it's suggested to manually run the build. After these steps, it performs CodeQL Analysis.

## **[Q6]** Automated Checks on Pull Request

>In the context of pull requests, what automated checks are done (consider checks on commits and comments posted in the pull requests by automated tools and bots)?

**Answer:**
The following automated checks are performed:

 Dependency Update Check: The presence of Dependabot in the pull requests indicate an automated check for updating dependencies. This indicates that Dependabot performs checks to ensure the project's dependencies are up-to-date.
Codecov Coverage Analysis: The pull requests we looked at contain a comment from codecov-commenter bot that creates a Codecov Report. The report assesses the impact of the pull request on code coverage. It states that merging the pull request will not affect coverage. However, it advises uploading reports for accurate results, indicating that Codecov performs automated checks to analyze code coverage metrics and provide insights into the extent of testing conducted.
Gradle Build and CodeQL Analysis: These automated tests are performed on each commit, details which can be found in the answer for question: What automated checks do exist on a commit pushed to the main branch?

## **[Q7]** Release Notes

>How are the release notes organized?*

**Answer:**
For each version it states the version number, Commit ID.
A section called “What’s changed” lists the changes in bullet points format. And a section of who contributed, The format of each change (bullet point) is as follow: 
<Bump> <specific dependency that is being updated> <version from old version to new version> <location where the update is taken place> by @dependabot in #<pull request number>
Example: Bump versions.spring_boot from 2.7.1 to 2.7.2 in /gradle by @dependabot in #501
The @dependabot automates the process of keeping dependencies up to date.
Some versions has a section called the “Assets” which refers to resources such as files, which offers the user to download and utilize such resources. 
Additionally, the latest release is labeled with “latest” and some releases has a label “pre-release”.

## **[Q8]** License

>What is the license of the project? Explain if it’s permissive or restrictive.

**Answer:**
This project makes use of the Apache License 2.0 which is a permissive license whose main conditions require preservation of copyright and license notices. Permissive licenses provide more freedom in how users can modify and distribute the software. When conditions are met, this license allows users to freely modify and distribute the software for both private and commercial use. However, this license permits users to use any trademarks associated with the software. A limitation on liability and warranty is also included.


Individual statement of contribution

Muhammad Butt
Our team really stuck to the rules and we all did our part for this project. We talked a lot to make sure everyone had their share of the work. I worked hard on this.

Chakir Belhaj
We followed the project rules and everyone did their part. We made sure to talk things through so the work was split up fairly. I put a lot of effort into this.

Yoad van Praag
Our team went by the book and everyone put in equal effort for this project. We kept in touch regularly to make sure the work was shared out equally. I really gave it my all.

Stephen Kwan
We did things by the rules and everyone pulled their weight on this project. We talked regularly to make sure everyone did their share. I was really committed to this.
