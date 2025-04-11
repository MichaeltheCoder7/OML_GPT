# OML_GPT

[![Build Status](https://app.travis-ci.com/melaasar/cs130-template.svg?branch=master)](https://app.travis-ci.com/github/melaasar/cs130-template)
[![Release](https://img.shields.io/github/v/release/melaasar/cs130-template?label=release)](https://github.com/melaasar/cs130-template/releases/latest)

### Description
Our project creates a integration of OpenAI's ChatGPT with a formal knowledge base using Ontological Modeling Language (OML) vocabulary and SPARQL querying. This appliaction creates a complex system that translates natural language queries into structured SPARQL queries, allowing users to interact with complex data effortlessly. Here's an overview of the entire project:

### Usage
The usage of our integrated ChatGPT and formal knowledge base designed to be intuitive and friendly for users, meet the needs of a broad audience regardless of their technical background. Users begin by accessing our web-based application, where they are greeted by a chat-like interface which like ChatGPT. Here, they can input their questions or queries in natural language, just as having a conversation with someone in real life. At the backend, powered by ChatGPT, interprets these queries and translates them into SPARQL queries using the defined OML. These queries are then executed against the formal knowledge base. The results are converted back into natural language and presented to the user in the same chat interface, making the process of querying complex data sets as simple as having a reality chat. This system is ideal for those who want to get answers in complex data without having SPARQL technology. It provides services between advanced data query and user-friendly interaction.

### Feature
#### Backend
1. **Advanced Natural Language processing：** The coreof our backend lies the integration of ChatGPT's sophisticated language models. This model expertise in processing and interpreting user queries presented in natural language. This feature allows our system to understand and analyze user inputs as if they were conversing with a human. This can ensure that user queries are processed efficiently and accurately.
2. **Automatic SPARQL Query Generation：** An important functionality of our backend is it can transform user queries, phrased in everyday language, into precise SPARQL queries. In the process, we exploit nuances to improve the accuracy and relevance of queries. By doing this, we ensure that the retrieved data is closely integrated with the user's question, increasing the effectiveness of the query.
3. **Interaction with Knowledge Base:** As we carefully design the system, our system can interact efficiently with different knowledge bases, executing SPARQL queries and retrieving the data most relevant to user requests. This interaction is not only fast, but also able to handle the adaptation problem of different knowledge bases. This makes our query function more widely used.
4. **Intuitive Data Translation:** A standout feature of our backend is its ability to convert complex query results into clear and concise natural language responses. This is particularly important because it makes the application accessible to users who do not have technical expertise in SPARQL. By providing simple and easy-to-understand functionality, our system makes tools accessible to a variety of users with varying levels of technical knowledge.
#### Fronted 
1. **Intuitive Chat Interface:** Our frontend boasts a highly interactive chat interface, designed to allow users to input queries in a familiar, user-friendly format. This feature allows users to input their queries in a format that is both familiar and user-friendly which may reduce the learning curve and enhancing user engagement.
2. **Real-Time Interaction:** Our application provide delivering as fast as possible responses to user queries, ensuring an uninterrupted and dynamic user experience. This real-time interaction is key to keeping users engaged and satisfied, providing them with immediate feedback and answers to their inquiries.
3. **Backend Integration:** Our frontend is expertly efficiently communicatesd with the backend system, ensuring precise and efficient communication. This integration guarantees that user queries are processed accurately and the responses are delivered quickly. This maintain the reliability of the user experience.
4. **User-Friendly Navigation:** The design of our application is centered on simplicity and ease of use, which make each user of all technical backgrounds can use directly. We've ensured that navigating through the application is intuitive and straightforward.
5. **Robust Security Measures:** Security is one of the most important feature in our application. We implement strong security protocols to protect user data and interactions with the backend. This feature ensures that user information is protected and that all interactions are secure in the application.
6. **Comprehensive User Guide and Help Section:** To help users easily get started with our application, we provide an extensive user guide and help section. This feature contains tutorials designed to guide users through the application's various features, ensuring they can effectively utilize all its features. At the same time, they can also provide timely feedback when encountering problems.
7. **Optimized Performance:** Performance is key in our application design. We've optimized the frontend to ensure rapid loading times and smooth interactions. This optimization ensures a smooth and fast user experience.

### Contributing 
Contributions to OML_GPT are welcome! We want to get your contributing, such as:
1. Reporting a bug
2. submitting a fix
3. Proposing new features
4. Discussing the current code
#### We develop wit Github
We use Github to host code, track issue and pull request. Pull requests are the best way to propose the change to the code. We welcome your pull request.
1. Fork the repo and create your branch from master.
2. If you add code that should be tested, adding tests.
3. If you chang APIs, update the documentation to mention us.

### Contact
Zeyu Tan ztan56@outlook.com\
Minkai Yang minkaiyang@g.ucla.edu\
Lam Hoang Lamhoang1213@g.ucla.edu\
Yunhao Du dudulu19980209@gmail.com\
Jiaxi Wang jwang008@g.ucla.edu\
Ziwei Ren zren57@g.ucla.edu\

### Epic

[//]: # (An [epic]&#40;https://dev.to/jorenrui/a-look-into-how-i-manage-my-personal-projects-my-git-github-workflow-1e7h#epic-issue&#41; is an issue with the label `epic`. It represents a large story that can be broken into stories, which can be addressed over multiple sprints. An epic issue references its story issues as a task list in its description. A Github action has been added to automatically check/uncheck the story task items when they get closed/reopened.)
1. **Parse Query Results**\
Result Interpretation and Transformation
2. **Submit Query**\
Natural Language Query Submission
3. **Generate SPARQL Query**\
Natural Language to SPARQL Conversion
4. **API Development**\
Natural Language Query Processing
5. **Documentation and Training**\
Comprehensive Documentation and Training
6. **Deployment and Monitoring**\
Production Deployment and Monitoring
7. **Search and Query Functionality**\
Semantic Search Enhancement
8. **Database Query Performance Optimization**\
Database Query Performance Enhancement
9. **Query History**\
User Query History
### Story

[//]: # (A [story]&#40;https://www.atlassian.com/agile/project-management/epics-stories-themes&#41; is an issue with the label `story`. It may represent a new feature or an enhancement to an existing feature. A story issue can be broken into sub-tasks, which are added as a task list in the description of the story issue. These sub task items can be checked manually by the developer to indicate completion.)
1. **Parse Query Results**\
As a backend service, my goal is to transform the results from SPARQL queries into a structured format that ChatGPT can interpret, enabling it to convert these results into comprehensible natural language.
2. **Submit Query**\
As a user, I want to use the natural language to ask questions since I can phrase the questions in the most familiar way.
3. **Generate SPARQL Query**\
As a backend service, I hope to get the SPARQL Query which is converted from the natural language, so I can get the data from the SPARQL directly.
4. **API Development**\
As a backend developer, I want to design and implement APIs that can translate natural language queries into SPARQL queries, so that the system can understand and process user requests efficiently.
5. **Documentation and Training**\
As a technical writer, I want to create detailed documentation and training materials for the system, so that future developers and users can easily understand and use the application.
6. **Deployment and Monitoring**\
As a DevOps engineer, I want to deploy the application in a production environment with effective monitoring and logging, so that we can ensure its continuous operation and quickly address any issues that arise.
7. **Search and Query Functionality**\
As a user, I want to perform semantic searches using natural language queries and get contextually relevant results.
8. **Database Query Performance Optimization**\
As a database administrator, I want to optimize database indexing strategy to reduce query execution times for complex queries.
9. **Query History**\
As a user, I want to view recent searches.
### Sprint 
#### Sprint 1: Project Initialization and System Design
* Objective: Set the foundation for the project.
* Tasks(Completed):
  * Define the project goal.
  * Determine role arrangements and tasks for each role.
  * Set up frontend and backend development environment.
  * Design the frontend interface and user flow.
  * Design the backend architecture, including ChatGPT integration and SPARQL query generator.

#### Sprint 2: Frontend and Backend Development
* Objective: Begin frontend and backend development.
* Tasks(Completed):
    * Implement basic components and pages.
    * Implement page navigation logic.
    * Enhance the UI design.
    * Set up the server, knowledge base, and database.
    * Implement API for the backend.
    * Implement SPARQL query generation and result generation.
    * Implement user register and login.
    * Setup CI/CD.

#### Sprint 3: Debugging & Optimization 
* Objective:Focus on debugging, optimizing, and refining the existing system
* Tasks(Completed):
  * Review and prioritize existing issues and bugs reported during testing and user feedback.
  * Debug and Resolve Issues
  * Optimization Strategies, Code Review and Refactoring
  * Optimize frontend design.
  * Start frontend and backend testing.
  * Connect frontend to backend API.

#### Sprint 4: Testing, Finalization and Deployment
* Objective: Test and refine the system.
* Tasks(Completed):
  * Continue to implement and perform unit tests for tasks module
  * Continue to implement and perform unit tests for process_query
  * Gather feedback from initial user testing.
  * Finalize all development tasks.
  * Conduct system testing.
  * Prepare deployment environment with CI/CD.



[//]: # (### Bug)

[//]: # (A bug is an issue with the label `bug`. It represents a problem with the existing code that needs to be fixed.)

[//]: # (### Question)

[//]: # (A question is an issue with the label `question`. It represents a question raised by anyone that may get converted into other types of issues.)

[//]: # (## Labels)

[//]: # (In addition to the [standard labels]&#40;https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/managing-labels#about-default-labels&#41; above, you can add new labels to issues to classify them into different classes like `documentation`, `frontend`, etc, or to add metadata like `duplicate`, `invalid` etc.)

[//]: # (## Milestones)

[//]: # (A [milestone]&#40;https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/tracking-the-progress-of-your-work-with-milestones&#41; groups issues that are expected to be delivered at some point in time. It also allows ordering &#40;prioritizing&#41; these issues and tracking their progress &#40;percentage of issues completed so far&#41;. In the scrum context, a milestone can be used as a sprint. So, you can create your sprints and give them names like Sprint1, Sprint2, etc., and set their due dates respectively.)

[//]: # (## Projects)

[//]: # (A [project]&#40;https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/tracking-the-progress-of-your-work-with-project-boards&#41; is a kanban-style board that can aggregate a set of issues for any purpose. In the scrum context, we can create one project called `Scrum Board` and choose its template as `Automated kanban with reviews`. &#40;This will create a set of initial notes that you can delete&#41;.)

## Branches

The `master` branch is the main branch used for releases. Other branches can be created. For example, a branch called `gh-pages` is often used to create a website for the repository (for more information check this [link](https://pages.github.com/)). Other branches can be created to address the issues of the repository, one branch per issue (called an `issue` branch). Such branches can then be used to create pull requests, where they get peer-reviewed and eventually merged into the `master` branch. For more information on branches, check this [link](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/about-branches).

## Pull Requests

A [pull request](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/about-pull-requests) is a request to merge commits from one branch to another branch. This is typically used to merge commits from an `issue` branch into the `master` branch. A pull request is how the process of peer review is carried out. Reviewers can comment on the code changes to show approval or request changes (which will need to be addressed by additional commits to the `issue` branch). When a CI pipeline is configured for a repository (see below), it will run on any `issue` branch that is part of a pull request. When the peer review process has concluded, the new commits can merged into the `master` branch. The recommended merge option is `Squash and merge`, (i.e., squash all commits into a single commit) since it makes the repository's history simple and linear.

## Tags

Tags can be used to mark release points in a repository's commit history. Typically, after some work goal has been achieved, with a set of commits, a tag (typically a version number like 1.0.0, 1.0.1, etc.) is [pushed to the respository](https://stackoverflow.com/questions/18216991/create-a-tag-in-a-github-repository) to mark this point. This results in the tag showing up in the repository's [tags page](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/viewing-your-repositorys-releases-and-tags).

## Workflows

### Creating issues

An issue can be created from the `issues` tab of a repository. An issue type (bug, story, epic, question) is first chosen then its corresponding template can be sufficiently filled.

### Triaging issues

The Product Owner goes frequently to the `Scrum Board` project and clicks on the `Add Cards` link to triage new issues in the repository to the board's `To do` column, which acts here as the `Product Backlog`. Product Owner can also added unbaked ideas to the `To do` column as notes, which are placeholders that can later be converted into issues. Issues and notes can then be ordered in the `To do` column to show their priority.

### Planning sprints

The Scrum Master creates a new milestone and gives it a suitable name (e.g., Sprint1) and a due date. Then, in the `Scrum Board`, issues from the top of the `To do` column (assuming they have been ordered based on priority) can be assigned to that milestone and to the developers who will work on them.

### Working on issues

Developers go to the `Scrum Board` where they can filter it for the issues assigned to them in a given milestone. They can pick ones to work on by moving them to the `In progress` column (this is important since this is not automated).

### Reviewing progress

In the daily standup, the `Scrum Master` can review progress by going to the `Scrum Board` and filtering it by the current milestone (sprint). Developers can then reference issues in the various columns when they answer the usual standup questions, e.g., issues they work on (`In progress`), finished (`Done`), or yet to work on (`To do`).

### Working with issue branches

Before developers can work on an issue, they should check out and pull the `master` branch to ensure that they have all the latest commits locally. Then, they should create a new local `issue` branch and name it `issue-[number]` (replacing `[number]` with the issue number). Several `issue` branches can be created concurrently, one for each issue, but it is important to make them independent from each other by checking out the `master` branch before creating each of them. This allows them to be pushed and merged independently from each other (and with the least conflicts).

Each `issue` branch can accumulate commits to address the issue. When ready, it can then be pushed to a corresponding remote branch that can then be used to create a pull request into the `master` branch. The pull request template needs to be filled at this point. Once created, a pull request can be reviewed by a peer reviewer who may request changes. These changes can be made using new commits in the local `issue` branch that can subsequently be pushed to the corresponding remote `issue` branch. When all peer reviews have concluded, the pull request can then be `squash merged` into the `master` branch ([read more here](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/about-pull-request-merges#squash-and-merge-your-pull-request-commits)), and the `issue` branch [can be deleted](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/managing-the-automatic-deletion-of-branches). If the pull request description includes the words `fixes #[number]` (where `[number]` is an issue number), the issue with that number will [automatically be closed](https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword).

> It is recommended to not push commits to the master branch directly but to always go through a peer review process using an `issue` branch.

### Using a CI/CD pipeline

Every repository needs to have a way to build its artifacts headlessly. It is a good idea to run tests as part of such a build. Instructions on how to build the components in a repository need to be documented in the repository's README.md.

A repository can also be set up to build continuously whenever a commit is pushed to the `master` branch by setting up a CI script (e.g., [Travis CI](https://www.travis-ci.com/)) in its root folder. Such script will configure the build environment (as a virtual machine) and invoke the build script on the `master` branch. If the script fails for some reason, the committer will be notified to fix it. It is a good practice to add a build [badge](https://shields.io/category/version) to the README.md file to visibly indicate the status of the last CI build (Travis CI provides such badges). 

The CI script will also be run when a new pull request is created or when more commits are pushed to its linked `issue` branch. Such a build assures peer reviewers that the new commits when accepted will not break the build. In fact, a successful CI build can be a prerequisite for peer reviewers to look at the changes.

When a tag is pushed to the `master` branch, the CI script will additionally deliver and/or deploy the built artifact(s). The script can also be configured to create a Github release based on the tag.
