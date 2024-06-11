[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15241670&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:
Software engineering is the branch of computer science that deals with the design, development, testing, and maintenance of software applications. Software engineers apply engineering principles and knowledge of programming languages to build software solutions for end users.

What is software engineering, and how does it differ from traditional programming?
Software Engineering is an engineering process that is mainly related to computers and programming and developing different kinds of applications through the use of information technology.

The main difference between software engineering and programming is that software engineering is a process-oriented discipline while programming is a task-oriented activity.

Software engineering is concerned with developing software products that are reliable, efficient and easy to maintain. It applies scientific and mathematical principles to the design, analysis and implementation of software systems. Programming, on the other hand, is mainly concerned with writing code to solve specific problems.

While both software engineering and programming are essential to software application development, they require different skills and knowledge. Software engineers should have a good understanding of computer science concepts and experience with project management and software development methodologies. They must be able to apply these theoretical concepts to real-world problems. Programmers, on the other hand, must be able to code well and have a good understanding of algorithms and data structures.

Software Development Life Cycle (SDLC):

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.

Software Development Life Cycle (SDLC) is the process by which software comes to life. It can vary depending on the framework chosen by the team (more on that later), but whatever path you take, the journey from idea to final software in the user’s hands is what we call SDLC. 


A full SDLC has 7 basic stages: Planning, requirements, design and prototype, software development, testing, deployment, and maintenance. 

In some cases, depending on different variables (project, team, manager, etc.), certain steps can be omitted, split, or combined.

A well-planned SDLC helps teams reduce costs and release software faster by having a set plan to adhere to (even if some frameworks are more chaotic than others, it is still controlled chaos) and providing a clear “bird’s eye view” to help identify inefficiencies and roadblocks. 

There are 7 software development life cycle phases, and they are to be approached sequentially, although in some cases, two might run concurrently (just as development and testing). 

SDLC “works” when your team organizes and executes according to this sequence; how they tackle each individual step will depend upon the framework they chose (more on that later.) For now, let’s outline what happens in each stage/phase.

1. Planning
In this phase, the project leads to defining the project’s purpose and the desired result. 

If the team is developing for a customer instead of to market, the project manager meets with them to discuss the product, its purpose, and the results they want to achieve. The team gathers as much information about the product from the customer.

By the end of the planning phase, the team leads should have a working estimate of how much the project will cost and who will be part of the project. They also set a project deadline and milestones and overall create the basic structure for the project.

By the end of this phase (or, at the very least, the next one), each team member must understand their roles and tasks.

2. Requirements
This second phase of the software development life cycle is often done concurrently with the first. Here, the project lead analyzes the product or client’s goals and decides on the features to aim for as a final goal. Defining and establishing requirements determines what the application will do once launched, the necessary components, and the resources needed to launch it. 

For example, if a team wants to develop software to control a robot that cleans, then the physical robot would be a requirement (component) in the process.

3. Design and Prototype
Once phases 1 and 2 are understood and established, developers can start designing the software. 

The design phase defines how a software application will work. During this phase, teams decide on the programming language, screen layouts, and relevant documentation they will use.

Some of the fundamental aspects developers cover during this phase are:

Architecture: Teams define if they want a specific type of template or if they want to implement any type of industry practice.
User Interface: Teams define the way users will be interacting with the platform. 
Security: Developers must define how they will keep the application secure. This means they need to decide how to protect user data and general app data.
Programming: Define the project’s tech and tool stack. 
Prototyping is also part of this phase. A prototype is a basic idea of how the application looks and works. 

Prototypes allow customers to get a sneak peek of how their application will look; they might even discover that their original idea is not good enough and change it during this phase.

4. Software Development 
During this phase, developers start programming. 

If they work on a small project, one developer takes over the coding tasks, while on large projects, the codebase might be worked on by several developers. 

Before starting to code, teams must have clear predefined guidelines to ensure the code’s quality. In this phase, developers start building the entire system and shaping the project.

Depending on each team’s model, the phase may be conducted in sprints (Agile) or a single block (Waterfall). Teams spend most of their time during this phase ensuring that the application will work efficiently.

5. Testing 
Often, testing happens in parallel with development, as developers write and test the code they’ve produced before moving on to the next coding task.

During this phase, different types of testing occur, such as code quality, unit testing, integration testing, performance testing, and security testing. 

Running testing in parallel with development means that bugs can be fixed within the same sprint or time block, which is more efficient than adding a whole block of coding to be done at the end of the project. It also mitigates the trouble of bug fixes generating new bugs themselves.

6. Deployment
The deployment process starts once the testing phase is over and there are no bugs or errors in the development backlog. 

The team ensures that the software is up-to-date and secure enough for users and pushes it from the development environment to a live environment–usually an app store.

During this phase, the tech support team looks for user feedback and ensures it reaches the dev team.

7. Maintenance
At this point in the SDLC cycle, the application is successfully launched and being used. 

Yet this last phase is still important because bugs or errors missed during testing are bound to appear. Simultaneously, by studying user behavior and feedback, the team can start to think about and plan for upgrades. 

Agile vs. Waterfall Models:

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?

Agile Model
The Agile SDLC methodology strongly emphasizes developer-client communication. The team agrees on an MVP (Minimum Viable Product) with essential features and tries to reach that in as few iterations as possible. 

After every development iteration, the customer can see the results and let the team know if they are satisfied. Therefore, work is done in regularly iterated cycles that are identified as sprints—projects under the Agile model usually last from two to four weeks. This is one of the most popular models for remote teams. 

The Agile model looks like this:
            Requirements 
      Testing           Design 
            Development  
            
The Waterfall Model
The waterfall model was the original SDLC process. This model divides the project into discreet phases, each with its own tasks and objectives. 

What is the difference between Agile and SDLC?
Agile is a type of SDLC model, so it’s not contrasting to SDLC, but it differs significantly from traditional models like Waterfall. Agile is known for its flexibility. It allows changes to be made in the project requirements even at a later stage of development. Traditional SDLC models like Waterfall are more rigid. Additionally in Agile, working software is delivered frequently (weeks rather than months) in increments, which allows stakeholders to receive tangible progress and provide feedback early and often. Traditional SDLC models typically deliver a complete system at once, near the end of the project lifecycle.



In this model, the team must execute of every stage completely, meaning that the output of one phase is the input of the next phase. 

If one phase is not completed, it’s impossible to move forward to the next one. Another characteristic of the Waterfall model is that it’s strictly documented and has predefined features expected to be developed in every phase.

The waterfall model looks like this:
Requirements 
            Design 
                  Implementation 
                                Testing 
                                      Maintenance 

In what scenarios might each be preferred?


Waterfall is a linear project progression, so it’s best suited for projects with a defined end goal. If a project owner has a clear and specific vision of an app, for example, and is confident it will not change throughout the project development, Waterfall methodologies could be a good system to follow.

Meanwhile, Agile leaves a lot of room to adapt and change course as the project develops. It’s better suited for projects where the outcome may be dependent on more research or testing.

The budget for projects using Waterfall methodologies tends to be less flexible because the project is mapped out from the beginning. With Agile, there is more room to change direction as the project develops, so the budget is also subject to change. Similarly, the timeline with Waterfall is set from the start, while it’s more flexible with Agile and dependent on how the project develops.

Waterfall is a better method when a project must meet strict regulations as it requires deliverables for each phase before proceeding to the next one. Alternatively, Agile is better suited for teams that plan on moving fast, experimenting with direction and don't know how the final project will look before they start.


Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.

Requirements engineering is the process of defining, documenting, and maintaining requirements. It involves activities like elicitation, analysis, specification, and verification to ensure software meets stakeholders’ needs. Proper management improves project clarity, reduces errors, and aligns expectations.

Requirements Engineering Process

Feasibility Study
Requirements elicitation
Requirements specification
Requirements for verification and validation
Requirements management

modification and rework. The main steps for this process include:

The requirements should be consistent with all the other requirements i.e. no two requirements should conflict with each other.
The requirements should be complete in every sense.
The requirements should be practically achievable.
Reviews, buddy checks, making test cases, etc. are some of the methods used for this.

Requirements verification and validation (V&V) is the process of checking that the requirements for a software system are complete, consistent, and accurate and that they meet the needs and expectations of the stakeholders. The goal of V&V is to ensure that the software system being developed meets the requirements and that it is developed on time, within budget, and to the required quality.

Verification is checking that the requirements are complete, consistent, and accurate. It involves reviewing the requirements to ensure that they are clear, testable, and free of errors and inconsistencies. This can include reviewing the requirements document, models, and diagrams, and holding meetings and walkthroughs with stakeholders.
Validation is the process of checking that the requirements meet the needs and expectations of the stakeholders. It involves testing the requirements to ensure that they are valid and that the software system being developed will meet the needs of the stakeholders. This can include testing the software system through simulation, testing with prototypes, and testing with the final version of the software.
Verification and Validation is an iterative process that occurs throughout the software development life cycle. It is important to involve stakeholders and the development team in the V&V process to ensure that the requirements are thoroughly reviewed and tested.
It’s important to note that V&V is not a one-time process, but it should be integrated and continue throughout the software development process and even in the maintenance stage.

5. Requirements Management
Requirement management is the process of analyzing, documenting, tracking, prioritizing, and agreeing on the requirement and controlling the communication with relevant stakeholders. This stage takes care of the changing nature of requirements. It should be ensured that the SRS is as modifiable as possible to incorporate changes in requirements specified by the end users at later stages too. Modifying the software as per requirements in a systematic and controlled manner is an extremely important part of the requirements engineering process.

Requirements management is the process of managing the requirements throughout the software development life cycle, including tracking and controlling changes, and ensuring that the requirements are still valid and relevant. The goal of requirements management is to ensure that the software system being developed meets the needs and expectations of the stakeholders and that it is developed on time, within budget, and to the required quality.

Several key activities are involved in requirements management, including:

Tracking and controlling changes: This involves monitoring and controlling changes to the requirements throughout the development process, including identifying the source of the change, assessing the impact of the change, and approving or rejecting the change.
Version control: This involves keeping track of different versions of the requirements document and other related artifacts.
Traceability: This involves linking the requirements to other elements of the development process, such as design, testing, and validation.
Communication: This involves ensuring that the requirements are communicated effectively to all stakeholders and that any changes or issues are addressed promptly.
Monitoring and reporting: This involves monitoring the progress of the development process and reporting on the status of the requirements.
Requirements management is a critical step in the software development life cycle as it helps to ensure that the software system being developed meets the needs and expectations of stakeholders and that it is developed on time, within budget, and to the required quality. It also helps to prevent scope creep and to ensure that the requirements are aligned with the project goals.
Software Design Principles:

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?

Definition: Modularity in Software Design
Modularity in software design refers to the practice of dividing software into separate, independent modules, each responsible for a distinct feature or functionality. This approach promotes better maintainability, scalability, and reusability of code by isolating functional boundaries, making complex systems easier to manage and evolve.

How Does Modular Software Architecture Improve Scalability?
Modular software architecture enhances scalability by breaking down the application into distinct, reusable modules. However, when it comes to improving scalability, modular monolith architecture deserves special attention.

In a modular monolith, the application maintains a single codebase, making it easier to manage and deploy. While it doesn't provide the same level of scalability as a full microservices architecture, it offers a middle-ground solution. By dividing the application into manageable modules within a single codebase, it allows for some level of modularity and flexibility without the added complexity of distributed architecture.

The key advantage of modular monolith architecture is its ability to adapt and expand to meet growing demands
Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

What are the different levels of Testing?
Software must go through different testing stages before it can be considered bug-free and ready for deployment. There are generally four levels of software testing, as mentioned below:

Unit Testing
Integration Testing
System Testing
Acceptance Testing
Let’s have a look at these in detail.

1. Unit/Component Testing
Unit testing is done at the code level, where each component is tested individually to ensure their impartiality and analyze their functionality. Automating unit tests is possible and highly recommended in today’s fast-paced development environment. To make a unit test, you should outline what you expect the code to do and write the code, which will check if it is doing what you expect. You should then run the unit test to verify that everything works as expected. For example, let’s say you have a calculator program that adds two numbers together. You can create a unit test that verifies the numerical values that the calculator program returns are correct. You could also create tests that verify edge cases and errors are handled correctly.

In this simple example, you could use unit testing to verify that the calculator program adds two numbers correctly.

First, outline and document the expectations of the program, such as:

The program should accept two numerical values
It should return the sum of these two values
It should also handle negative numbers correctly
You can then write unit tests that feed these values into the program and verify the correct output. For example, you could have a test that checks the program returns 2 when 1 and 1 are entered. You could have another test that checks the program returns -3 when 1 and -4 are entered. Once all the tests have been written and executed, you can confidently say that the calculator program has been successfully tested and works as expected.

2. Integration Testing
Integration testing enables software testers to test group units integrated into a system or subsystems; it helps identify any bugs or issues arising from coding errors or integrations between modules. It is possible to automate integration testing.

3. System Testing
System testing is performed on an integrated environment comprising the whole application, where all components are assessed against specific business requirements. You can use automation tools for System Testing.

For example, Testsigma, a no-code test automation platform, can complete end-to-end flows for web, mobile, and desktop applications and APIs.

4. Acceptance Testing
Acceptance testing involves testing the system’s Functional and Non-functional aspects, such as performance, security, usability, accessibility, compatibility, and reliability. Depending on the system’s complexity, it can be done manually or through automation tools. In this example, we will demonstrate the process of using Testsigma to automate the acceptance testing of a login page. First, we must create a test scenario that simulates users entering their login credentials and logging in successfully. Testsigma will automatically detect any issues with the page and report them back to us. Using Testsigma for acceptance testing, we can ensure that our login page is working as expected and ready for deployment.

Why Is Testing Crucial in Software Development?

1. Quality Assurance:

Software testing is a fundamental aspect of quality assurance. It helps ensure that a software product meets the specified requirements, functions correctly, and performs reliably. By identifying and fixing defects early in the development process, testing contributes to the creation of robust and dependable software.

2. Risk Mitigation:

Testing is an essential risk mitigation strategy. It identifies potential issues before they reach end-users, reducing the likelihood of software failures and the associated financial and repetitional risks. Early detection and resolution of problems save time and resources in the long run.

3. Customer Satisfaction:

Quality software is the key to customer satisfaction. Software that works as expected, without frequent crashes or bugs, enhances the user experience. Happy customers are more likely to become loyal customers and recommend the product to others.

4. Cost-Effective:

While some may see testing as an added expense, it is, in fact, a cost-effective measure. Identifying and fixing defects in the early stages of development is far less expensive than addressing issues after a product is deployed. The cost of fixing a bug increases exponentially as it progresses through the development lifecycle.

5. Compliance and Standards:

Many industries have regulatory requirements and standards that must be met. Comprehensive testing ensures that software complies with these standards, reducing legal and compliance risks. This is particularly important in fields such as healthcare, finance, and aviation.

Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

What is version control?
Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. As development environments have accelerated, version control systems help software teams work faster and smarter. They are especially useful for DevOps teams since they help them to reduce development time and increase successful deployments.

Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.


Best Version Control Systems
1. GitHub
2. Gitlab
3. Beanstalk
4. HelixCore
5. Apache Subversion
6. AWS CodeCommit
7. Microsoft Team Foundation Server
8. Mercurial
9. Concurrent Versions System (CVS)
10. Bitbucket

1. GitHub
GitHub is a version control system and repository to host Git projects. If you’re wondering what Git is, it is an open-source version control system authored by Linus Torvalds. Yes, the man behind Linux. 

Github is known as the “social media” for software developers. But above all, it helps software teams collaborate and maintain the entire history of code changes.

Strengths:

Provides code review that is available in a private cloud with GitHub Enterprise or on-premise deployment
Uses GitHub Marketplace to look for integrations and tools needed to improve your development process further
Offers a secured environment through signed commits, required status checks, and protected branches to maintain high-standard coding practices
Enhances collaboration through code review tools where members can discuss implementation details before applying code changes
Provides high visibility for all the code parts that are new, edited, or deleted. These are all highlighted to spot changes easily and compare versions of code side by side. 
2. Gitlab
If your project requires continuous integration and continuous deployment (CI/CD), then GitLab is for you. It is a version control software built for the DevOps lifecycle. Meaning, your projects are quite complex, and it involves cloud engineering and the like.

Gitlab provides basic features such as view code, pull requests, and merged resolution.

Strengths:

Improves productivity by cutting down the DevOps cycle time, reducing manual work, and connecting silos and stages
Provides audit management, cycle analytics, issue board and trackers, source code management, unit testing, and continuous delivery
Lowers development risks through frequent deployments that will lead to better predictability, easier troubleshooting, and better code quality
Defies geographical barriers as distributed, and remote teams can work on the latest version of the code and stay current.
3. Beanstalk
For projects that involve outsourcing, Beanstalk is an ideal option. This version control software uses browser and cloud. It allows users to code, commit, review, and deploy using a browser. For ease of use, you can integrate it with any messaging or email platform for efficient collaborations.

It is an enterprise-class secured infrastructure, with high performance, and reliability. This is ideal for startups businesses.

Strengths:

Provides robust encryption, two-factor authentication, and password protection functionalities
Caters to any team size, and can provide a repository and branch-level permissions for teams and individuals
Allows team members are well-informed throughout the deployment because of its release notes feature.
4. HelixCore
HelixCore offers seamless team collaboration and support for both centralized and distributed development workflows. It is available on both cloud and on-premise deployments, making it scalable. 

Strengths: 

Provides workflow freedom where members can work remotely but have total control by setting granular file-level permissions
Supports multi-factor authentication and other security features to secure your intellectual property
Offers a DevOps-ready environment for continuous integration and scalability.
5. Apache Subversion
Apache Subversion (also known as Subversion or SVN)  is an open-source version control system under the Apache license.

Its key features include inventory management, security management, history tracking, user access controls, data recovery, and workflow management. SVN is easy to implement with any programming language. Plus, it offers consistent storage for handling text and binary files.

Strengths:

Creates directories as first-class objects similar to files
Offers easy branching and tagging
Provides effective flow management with automated tracking of merges.
6. AWS CodeCommit
If you are building a project using AWS, then AWS CodeCommit is for you. It can host secure and scalable private Git repositories. You can seamlessly connect with other products from Amazon Web Services (AWS) and host the code in secured AWS environments.

Strengths:

Offers efficient code collaboration with its full support for pull requests; its users can easily comment and review code changes before merging them into branches
Provides robust integrations with Identity Access Management(IAM), other AWS services, and third-party services 
Offers a secure repository for your project documents and source code in the cloud.
7. Microsoft Team Foundation Server
Team Foundation Server is an enterprise-grade tool to help project development. It manages source code, tracks and monitors workflows, and ships software. It works with known programming languages and helps accelerate production through its additional features (Team Build, Team Project Portal, Team Foundation Shared Services, etc.).

Strengths:

Offers a flexible and distributed version control system
Provides a secured and centralized version control for workflows and code management
Enables quick reviewing and merging of code in a Git team project through the pull request method.
8. Mercurial
Mercurial is a free and distributed version control software known for its efficiency. It can cater to projects of different sizes. And developers love its simple and intuitive user interface

Strengths:

Provides a robust backup system, search functionality, project tracking, and management
Offers data import, export, and migration tools
Features robust workflow management, including history tracking, security management, and more.
9. Concurrent Versions System (CVS)
Commercial and open-source developers use CVS. Why? It is one of the oldest version control systems. It is a sophisticated version control software and continues to improve its capabilities.

Strengths:

Maps out components and modules in larger software projects
Caters to multiple developers working simultaneously on a project
Enforces site-specific policies to provide secured operations.
10. Bitbucket
If you are working with projects using Atlassian tools, consider using Bitbucket. It offers code branching, in-line commenting and discussions, and pull requests.

Strengths:

Works with a local server, data center, and on the cloud
Integrates with other Atlassian products such as Jira; it lets you create branches directly from the Jira board
Offers built-in continuous integration and continuous delivery.
Works with a local server, data center, and on the cloud


Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

Responsibilities and Role of Software Project Manager
Without any sound and fury, here is a rundown of all the fundamental, mission-critical tasks that fall within a project manager’s purview:

3.1 Planning Everything from Execution to Delivery
A manager with effective project management skills will always have a plan ready to maximize output 

3.2 Oversee the Software Development Team
A project manager’s job affords them unusual insight into the many moving parts of a team’s task forces. The project manager may collaborate with following members of a team: 

Business analysts
Web designers
Software developers
Content creators
Graphic designers
Sales and advertising teams
Marketing teams


3.3 Delegating Work Effectively
It is crucial to intelligently allocate work to teams when dealing with complex scenarios like large projects or several jobs inside a project. Every project manager must practice and master this form of leadership, and doing so successfully is ultimately the manager’s job as a part of risk management. 

3.4 Monitoring Progress and Tracking Roadblocks
For the most part, a software project manager’s duties concentrate on keeping tabs on ongoing endeavors. 

3.5 Managing the Deployment Deliverables
Delivery of deliverables on schedule and within budget is another key responsibility of the project manager. It’s part of their work to question things like:

Can you tell me about the alterations being made to the company?
Exactly what is the group up to at the moment?
Is there a reason for this action?
What sort of business opportunity or threat exists?
How do you propose we go about doing this?
What are the most well-liked methods for managing projects?
Who exactly performs what?
Where can we find the project’s files and paperwork?
When and where will meetings be held? What are the requirements?
What time frame are we looking at for these activities?
Is there a certain set of skills or experience levels required to work in project management?
Within a company or organization, project managers oversee the preparation and carrying out of specific projects. They should be able to take charge, communicate well, and pay close attention  to detail. 

The project management challenges most commonly faced by a project manager include the following: 

Misalignment between goals and business objectives 
Communication 
Lack of accountability 
Resource allocation 
Scope creep
Project management software
Poor planning and unrealistic deadlines 

Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

Software maintenance is an integral part of the software life cycle that involves modifying and updating software after it has been deployed. The goal of maintenance is to correct faults, improve performance or other attributes, and adapt the software to a changing environment throughout its lifetime.

There are four types of software maintenance:

Corrective Software Maintenance
Adaptive Software Maintenance
Perfective Software Maintenance
Preventive Software Maintenance
Corrective Software Maintenance

Corrective software maintenance is what one would typically associate with the maintenance of any kind. Correct software maintenance addresses the errors and faults within software applications that could impact various parts of your software, including the design, logic, and code. These corrections usually come from bug reports that were created by users or customers – but corrective software maintenance can help to spot them before your customers do, which can help your brand’s reputation.

Adaptive Software Maintenance
Adaptive software maintenance becomes important when the environment of your software changes. This can be brought on by changes to the operating system, hardware, software dependencies, Cloud storage, or even changes within the operating system. Sometimes, adaptive software maintenance reflects organizational policies or rules as well. Updating services, making modifications to vendors, or changing payment processors can all necessitate adaptive software maintenance.

Perfective Software Maintenance
Perfective software maintenance focuses on the evolution of requirements and features that existing in your system. As users interact with your applications, they may notice things that you did not or suggest new features that they would like as part of the software, which could become future projects or enhancements. Perfective software maintenance takes over some of the work, both adding features that can enhance user experience and removing features that are not effective and functional. This can include features that are not used or those that do not help you to meet your end goals.

Preventive Software Maintenance
Preventative Software Maintenance helps to make changes and adaptations to your software so that it can work for a longer period of time. The focus of the type of maintenance is to prevent the deterioration of your software as it continues to adapt and change. These services can include optimizing code and updating documentation as needed.

Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?

Here are five examples of ethical issues and how developers can address them:

addictive design;
corporate ownership of personal data;
algorithmic bias;
weak cyber security and personally identifiable information (PII) protection; and
overemphasis on features.

As software engineering continues to evolve, ethical frameworks must adapt to the changing landscape. Here are some key takeaways for the future:

Continuous Education: Software engineers must stay updated on the latest ethical considerations and industry best practices to ensure responsible software development. Continuous education and training programs can help in raising awareness and promoting ethical decision-making.
Collaboration: Ethical frameworks should encourage collaboration among software engineers, designers, data scientists, and other stakeholders. This interdisciplinary approach can lead to more comprehensive ethical frameworks and ensure that ethical considerations are integrated throughout the software development lifecycle.
Ethical by Design: The concept of "ethical by design" should be a fundamental principle in software engineering. By embedding ethical considerations into the design and development process from the beginning, software engineers can proactively address potential ethical issues and mitigate risks.

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.

https://fullscale.io/blog/top-10-version-control-systems/

https://www.tatvasoft.com/outsourcing/2023/02/role-of-software-project-manager.html

https://www.koombea.com/blog/project-manager-challenges/

https://www.castsoftware.com/glossary/four-types-of-software-maintenance-how-they-help-your-organization-preventive-perfective-adaptive-corrective

https://www.techtarget.com/searchsoftwarequality/tip/5-examples-of-ethical-issues-in-software-development

https://moldstud.com/articles/p-ethical-considerations-in-software-engineering#:~:text=Continuous%20Education%3A%20Software%20engineers%20must,and%20promoting%20ethical%20decision%2Dmaking.
Submit your completed assignment by [due date].
