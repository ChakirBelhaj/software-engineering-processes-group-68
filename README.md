
# OWASP - wrong secrets

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

# Edison microservice

**Q1)**

> Describe, with your own words, what the project is about. Also, include in such a description the history of the project in terms of age, number of commits in the main branch, and number of collaborators.

**Answer:**
Edison microservice is a project that contains a collection of libraries that help developers create JVM microservices faster. JVM (Java Virtual Machine) microservices are often smaller independent pieces of a larger application designed to do one thing well. They are written in java and can be run on any platform supporting the JVM. Their first release was on April 11 2017. The project has a total of 53 contributors with 1880 (recorded on 29/06/2023) commits on the main branch. 


**Q2)**

> What are the practices in terms of commit messages (consider only commits on the main branch).

**Answer:**
The initial word of the commit messages are stating the activity that is being done such as: “fix”, “release”, “update”, “Bump”. After it is followed by a small description of the given activity, some messages contains a “#” followed by a number at the end to refer to an issue or pull request within the same repository. Every commit message also shows the person who committed and whether if all the tests that is being runned is successful or not, the tests consists of: CodeQL / Analyze (Java) (push), CodeQL / Analyze (JavaScript) (push), and Build / build (push).  Each commit is also assigned with a distinct identifier called the SHA (Secure Hash algorithm) i.e., Commit ID. 

**Q3)**

> How are the issues organized?

**Answer:**
Each issue is partitioned in two statuses, open and closed, where each status has it’s own tab with the given issues, some issues are also assigned with a label to state the type of the issue such as: “enhancement”, “bug”, “missing docs”. The description of each label resides in a separate label tab. The text format of the stated issue are plain description of the issue. Some issues also comes with a mile stone version number.

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
For each version it states the version number, Commit ID.
A section called “What’s changed” lists the changes in bullet points format. And a section of who contributed, The format of each change (bullet point) is as follow: 
<Bump> <specific dependency that is being updated> <version from old version to new version> <location where the update is taken place> by @dependabot in #<pull request number>
Example: Bump versions.spring_boot from 2.7.1 to 2.7.2 in /gradle by @dependabot in #501
The @dependabot automates the process of keeping dependencies up to date.
Some versions has a section called the “Assets” which refers to resources such as files, which offers the user to download and utilize such resources. 
Additionally, the latest release is labeled with “latest” and some releases has a label “pre-release”.

**Q8)**
>What is the license of the project? Explain if it’s permissive or restrictive.

**Answer:**
This project makes use of the Apache License 2.0 which is a permissive license whose main conditions require preservation of copyright and license notices. Permissive licenses provide more freedom in how users can modify and distribute the software. When conditions are met, this license allows users to freely modify and distribute the software for both private and commercial use. However, this license permits users to use any trademarks associated with the software. A limitation on liability and warranty is also included.


