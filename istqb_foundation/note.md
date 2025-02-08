# Certified Tester Foundation Level

## Intro

### Learning Objectives

• K1: Remember

• K2: Understand

• K3: Apply

### Chapters

• Chapter 1: Fundamentals of Testing (180 minutes)

• Chapter 2: Testing Throughout the Software Development Lifecycle (130 minutes)

• Chapter 3: Static Testing (80 minutes)

• Chapter 4: Test Analysis and Design (390 minutes)

• Chapter 5: Managing the Test Activities (335 minutes)

• Chapter 6: Test Tools (20 minutes)

## 1. Fundamentals of Testing

### Keywords

_coverage, debugging, defect, error, failure, quality, quality_ _assurance, root cause, test analysis, test basis,_
_test case, test completion, test condition, test control, test_ _data, test design, test execution, test_
_implementation, test monitoring, test object, test objective,_ _test planning, test procedure, test process, test_
_result, testing, testware, traceability, validation, verification_

### What is Testing?

Software testing is a way to assess the quality of the
software and to reduce the risk of software failure in operation.

#### Testing and Debugging

The two are very similar activities. however Testing can show failures that are caused by defects in the
software. Debugging is the development activity that finds, analyzes, and fixes such defects.

### Why is Testing Necessary?

Other than that sometimes it is required to meet contractual or legal requirements or industry-specific standards, testing of components and systems, and their associated documentation, can help reduce the risk of failures occurring during operation.

#### Quality Assurance and Testing

Those are two very diffierent thing, the concept of quality management ties them together.

- Quality management includes all activities that direct and control an organization with regard to quality.
- QA focuses on the overall process of ensuring that a product or service meets its design specifications the user’s needs. It´s a continuous process that begins during the planning stages of a product or service and continues through the development, testing, and deployment of the product or service.

#### Errors, Defects, and Failures

"A person can make an error (mistake), which produces a defect (fault, bug) in the code, in software or a system, or in a document. If the execution of the defect in code happens, the system may fail to do what it should do (or something it shouldn’t), which causes a failure"

- The Error is a human mistake. An Error appears not only due to the logical mistake in the code made by the developer. Anyone in the team can make mistakes during the different phases of software development.
- A Defect is a variance between expected and actual results. An Error that the tester finds is known as Defect. A Defect in a software product reflects its inability or inefficiency to comply with the specified requirements and criteria and, subsequently, prevent the software application from performing the desired and expected work.
- Failure is a consequence of a Defect. It is the observable incorrect behavior of the system. Failure occurs when the software fails to perform in the real environment.

### Testing principles

- **Testing shows the presence, not the absence of defects.**
  Testing can show that defects are present in the test object, but cannot prove that there are no defects. Testing reduces the probability of defects remaining undiscovered in the test object, but even if no defects are found, testing cannot prove test object correctness.

- **Exhaustive testing is impossible.**
  Testing everything is not feasible except in trivial cases. Rather than attempting to test exhaustively, test techniques, test case prioritization, and risk-based testing, should be used to focus test efforts.

- **Early testing saves time and money.**
  Defects that are removed early in the process will not cause
  subsequent defects in derived work products. The cost of quality will be reduced since fewer failures will occur later in the SDLC. To find defects early, both static testing and dynamic testing should be started as early as possible.

- **Defects cluster together.**
  A small number of system components usually contain most of the defects discovered or are responsible for most of the operational failures. This phenomenon is an illustration of the Pareto principle. Predicted defect clusters, and actual defect clusters observed during testing or in operation, are an important input for risk-based testing.

- **Tests wear out.**
  If the same tests are repeated many times, they become increasingly ineffective in
  detecting new defects. To overcome this effect, existing tests and test data may need to be modified, and new tests may need to be written. However, in some cases, repeating the same tests can have a beneficial outcome, e.g., in automated regression testing.

- **Testing is context dependent.**
  There is no single universally applicable approach to testing. Testing is done differently in different contexts.

- **Absence-of-defects fallacy.**
  It is a fallacy (i.e., a misconception) to expect that software verification will ensure the success of a system. Thoroughly testing all the specified requirements and fixing all the defects found could still produce a system that does not fulfill the users’ needs and expectations, that
  does not help in achieving the customer’s business goals, and that is inferior compared to other competing systems. In addition to verification, validation should also be carried out.

### Test Activities, Testware and Test Roles

Testing is context dependent, but, at a high level, there are common sets of test activities without which
testing is less likely to achieve test objectives. These sets of test activities form a test process

#### Test Activities and Tasks

- **Test planning**
  Consists of defining the test objectives and then selecting an approach that best achieves
  the objectives within the constraints imposed by the overall context.

- **Test monitoring and test control.**
  Test monitoring involves the ongoing checking of all test activities and
  the comparison of actual progress against the plan. Test control involves taking the actions necessary to
  meet the test objectives.

- **Test analysis**
  Includes analyzing the test basis to identify testable features. Test analysis answers the question “what to test?” in terms of measurable coverage criteria.

- **Test design**
  Includes elaborating the test conditions into test cases and other testware. Test design answers the question “how to test?”.

- **Test implementation**
  Includes creating or acquiring the testware necessary for test execution

- **Test execution**
  Includes running the tests in accordance with the test execution schedule and comparing the test result with the expected results. Anomalies are analyzed to identify their likely causes. This analysis allows us to report the anomalies based on the failures observed

- **Test completion**
  Usually occurs at project milestones. For any unresolved defects, change requests or product backlog items are created. The test activities are analyzed to identify lessons learned and improvements for future iterations, releases, or projects. A test completion report is created and communicated to the stakeholders.

#### Test Process in Context

Test activities are an integral part of the development processes and are not performed in isolation. Therefore, the way the testing is carried out will depend on a number of contextual factors like:

- Stakeholders
- Team members
- Business domain (criticality of the test object, identified risks, market needs, specific legal
  regulations, etc.)
- Technical factors
- Project constraints
- Software development
  etc...

#### Testware

Testware is created as output work products from the test activities described in section 1.4.1. There is a
significant variation in how different organizations produce, shape, name, organize and manage their work products.

- Test planning work products include: test plan, test schedule, risk register, entry criteria and exit criteria.
- Test monitoring and test control work products include: test progress reports , documentation of control directives and information about risks.
- Test analysis work products include: (prioritized) test conditions, and defect reports regarding defects in the test basis (if not fixed directly).
- Test design work products include: (prioritized) test cases, test charters, coverage items, test data requirements and test environment requirements.
- Test implementation work products include: test procedures, manual and automated test scripts, test suites, test data, test execution schedule, and test environment items.
- Test execution work products include: test logs, and defect reports.
- Test completion work products include: test completion report, action items for improvement of subsequent projects or iterations, documented lessons learned, and change requests.

#### Roles in Testing

In this syllabus, two principal roles in testing are covered: a test management role and a testing role.

- The test management role takes overall responsibility for the test process, test team and leadership of the test activities. It is mainly focused on the activities of test planning, test monitoring, test control and test completion.

- The testing role takes overall responsibility for the engineering (technical) aspect of testing. It is is mainly focused on the activities of test analysis, test design, test implementation and test execution.

### Essential Skills and Good Practices

#### Generic Skills

- Testing knowledge

- Thoroughness, carefulness, curiosity, attention to details, being methodical

- Good communication skills, active listening, being a team player

- Analytical thinking, critical thinking, creativity

- Technical knowledge

- Domain knowledge

#### Whole Team Approach

One of the important skills for a tester is the ability to work effectively in a team context and to contribute positively to the team goals.
In the whole team approach any team member with the necessary knowledge and skills can perform any task, and everyone is responsible for quality. It improves team dynamics, enhances communication and collaboration within the team, and creates synergy by allowing the various skill sets within the team to be leveraged for the benefit of the project.

#### Independence of Testing

A certain degree of independence makes the tester more effective at finding defects due to differences between the author’s and the tester’s cognitive biases, however this is not a replacement for familiarity, e.g., developers can efficiently find many defects in their own code.

The main benefit of independence of testing is that independent testers are likely to recognize different kinds of failures and defects compared to developers because of their different backgrounds, technical perspectives, and biases.

However, there are also some drawbacks. Independent testers may be isolated from the development team, which may lead to a lack of collaboration, communication problems, or an adversarial relationship with the development team.

## Testing Throughout the Software Development Lifecycle

acceptance testing, black-box testing, component integration testing, component testing, confirmation

testing, functional testing, integration testing, maintenance testing, non-functional testing, regression testing, shift left, system integration testing, system testing, test level, test object, test type, white-box testing

### Testing in the Context of a Software Development Lifecycle

An SDLC model is an abstract, high-level representation of the software development process. It defines how different development phases and types of activities performed within this process relate to each other, both logically and chronologically Examples:

- sequential development models (e.g., waterfall model, V-model)
- iterative development models (e.g., spiral model,prototyping)
- and incremental development models (e.g., Unified Process)

#### Impact of the Software Development Lifecycle on Testing

Testing must be adapted to the SDLC to succeed. The choice of the SDLC impacts on the:

- Scope and timing of test activities (e.g., test levels and test types)

- Level of detail of test documentation

- Choice of test techniques and test approach

- Extent of test automation

- Role and responsibilities of a tester

In sequential development models, in the initial phases testers typically participate in requirement reviews, test analysis, and test design.

In some iterative development models and incremental development models, it is assumed that each iteration delivers a working prototype or product increment. This implies that in each iteration both static testing and dynamic testing may be performed at all test levels.

Agile software development assumes that change may occur throughout the project. Therefore, lightweight work product documentation and extensive test automation to make regression testing easier are favored in agile projects.

#### Software Development Lifecycle and Good Testing Practices

Good testing practices, independent of the chosen SDLC model, include the following:

- For every software development activity, there is a corresponding test activity, so that all development activities are subject to quality control

- Different test levels have specific and different test objectives, which allows

for testing to be appropriately comprehensive while avoiding redundancy

- Test analysis and design for a given test level begins during the corresponding development phase of the SDLC, so that testing can adhere to the principle of early testing

- Testers are involved in reviewing work products as soon as drafts of these work products are available, so that this earlier testing and defect detection can support shift left

#### Testing as a Driver for Software Development

TDD, ATDD and BDD are similar development approaches, where tests are defined as a means of directing development. Each of these approaches implements the principle of early testing and follows shift left , since the tests are defined before the code is written.

- Test-Driven Development (TDD):
  Directs the coding through test cases. Tests are written first, then the code is written to satisfy the tests, and then the tests and code are refactored.

- Acceptance Test-Driven Development (ATDD)
  Derives tests from acceptance criteria as part of the system design process. Tests are written before the part of the application is developed to satisfy the tests

- Behavior-Driven Development (BDD)
  Expresses the desired behavior of an application with test cases written in a simple form of natural language, which is easy to understand by stakeholders,usually using the Given/When/Then format. Test cases should then automatically be translated into executable tests.

#### DevOps

DevOps is an organizational approach aiming to create synergy by getting development (including

testing) and operations to work together to achieve a set of common goals. DevOps promotes team autonomy, fast feedback, integrated toolchains, and technical practices like continuous integration (CI) and continuous delivery (CD). This enables the teams to build, test and release high-quality code faster through a DevOps delivery pipeline.

Benefits of DevOps from the testing perspective:

- Fast feedback on the code quality, and whether changes adversely affect existing code

- CI promotes shift left in testing by encouraging developers to submit high quality code accompanied by component tests and static analysis

- Automated processes are promoted like CI/CD that facilitates establishing stable test environments

- The visibility on non-functional quality characteristics increases

- Automation through a delivery pipeline reduces the need for repetitive manual testing

- The risk of regression is minimized due to the scale and range of automated regression tests

DevOps is not without its risks and challenges, these include:

- The DevOps delivery pipeline must be defined and established

- CI / CD tools must be introduced and maintained

- Test automation requires additional resources and may be difficult to establish and maintain

Although DevOps comes with a high level of automated testing, manual testing ,that, especially from the user's perspective, will still be needed.

#### Shift Left

The principle of early testing is sometimes referred to as shift left because it is an approach where testing is performed earlier in the SDLC. Shift left basically suggests that testing should be done earlier (e.g., not waiting for code to be implemented or for components to be integrated), but it does not mean that testing later in the SDLC should be neglected.

Good practices that illustrate how to achieve a “shift left” in testing:

- Reviewing the specification from the perspective of testers. These review activities on

specifications often find potential defects, such as ambiguities, incompleteness, and inconsistencies

- Writing test cases before the code is written and have the code run in a test harness during code implementation

- Using CI and even better CD as it comes with fast feedback and automated component tests to accompany source code when it is submitted to the code repository

- Completing static analysis of source code prior to dynamic testing, or as part of an automated process

- Performing non-functional testing starting at the component test level, where possible. This is a form of shift left as these non-functional test types tend to be performed later in the SDLC when a complete system and a representative test environment are available

Shift left might result in extra training, effort and/or costs earlier in the process but is expected to save efforts and/or costs later in the process.

#### Retrospectives and Process Improvement

Retrospectives are often held at the end of a project or an iteration, at a release milestone, or can be held when needed. Here participants discuss:

- What was successful, and should be retained?
- What was not successful and could be improved?
- How to incorporate the improvements and retain the successes in the future?

The results should be recorded and are normally part of the test completion report. Retrospectives are critical for the successful implementation of continuous improvement, and it is important that any recommended improvements are followed up. Some benefits are: Increased test effectiveness / efficiency, Increased quality of testware, Team bonding and learning, Improved quality of the test basis, Better cooperation between development and testing.

### Test Levels and Test Types

Test levels are groups of test activities that are organized and managed together. Each test level is an instance of the test process, performed in relation to software at a given phase of development, from individual components to complete systems or, where applicable, systems of systems.

Test types are groups of test activities related to specific quality characteristics and most of those test activities can be performed at every test level.

#### Test Levels

Test levels are distinguished by the following non-exhaustive list of attributes, to avoid overlapping of test activities:

- Test object

- Test objectives

- Test basis

- Defects and failures

- Approach and responsibilities

Some test levels described:

- Component testing (also known as unit testing) focuses on testing components in isolation. It often requires specific support, such as test harnesses or unit test frameworks. Component testing is normally performed by developers in their development environments.

- Component integration testing (also known as unit integration testing) focuses on testing the interfaces and interactions between components. Component integration testing is heavily dependent on the integration strategy like bottom-up, top-down or big-bang.

- System testing focuses on the overall behavior and capabilities of an entire system or product, often including functional testing of end-to-end tasks and the non-functional testing of quality characteristics. For some non-functional quality characteristics, it is preferable to test them on a complete system in a representative test environment (e.g., usability). Using simulations of sub-systems is also possible. System testing may be performed by an independent test team, and is related to specifications for the system.

- System integration testing focuses on testing the interfaces of the system under test and other systems and external services. System integration testing requires suitable test environments preferably similar to the operational environment.

- Acceptance testing focuses on validation and on demonstrating readiness for deployment, which means that the system fulfills the user’s business needs. Ideally, acceptance testing should be performed by the intended users. The main forms of acceptance testing are: user acceptance testing (UAT), operational acceptance testing, contractual acceptance testing and regulatory acceptance testing, alpha testing and beta testing.

#### Test Type

A lot of test types exist and can be applied in projects. In this syllabus, the following four test types are addressed:

**Functional testing** evaluates the functions that a component or system should perform. The functions are “what” the test object should do. The main objective of functional testing is checking the functional completeness, functional correctness and functional appropriateness.

**Non-functional testing** evaluates attributes other than functional characteristics of a component or system. Non-functional testing is the testing of “how well the system behaves”. The followings are non-functional quality characteristics (ISO/IEC 25010):

- Performance efficiency

- Compatibility

- Usability (also known as interaction capability)

- Reliability

- Security

- Maintainability

- Portability (also known as flexibility)

- Safety

**Black-box testing** is specification-based and derives tests from documentation not related to the internal structure of the test object. The main objective of black-box testing is checking the system's behavior against its specifications.

**White-box testing** is structure-based and derives tests from the system's implementation or internal structure (e.g., code, architecture, work flows, and data flows). The main objective of white-box testing is to cover the underlying structure by the tests to an acceptable level.

All the four above mentioned test types can be applied to all test levels, although the focus will be different at each level.

#### Confirmation Testing and Regression Testing

Changes are typically made to a component or system to either enhance it by adding a new feature or to fix it by removing a defect. Testing should then also include confirmation testing and regression testing.

**Confirmation testing** confirms that an original defect has been successfully fixed. Depending on the risk, one can test the fixed version of the software in several ways, including:

- executing all tests that previously have failed due to the defect, or, also by

- adding new tests to cover any changes that were needed to fix the defect

**Regression testing** confirms that no adverse consequences have been caused by a change, including a fix that has already been confirmation tested. These adverse consequences could affect the same component where the change was made, other components in the same system, or even other connected systems.

Regression test suites are run many times and generally the number of regression test cases will increase with each iteration or release, so regression testing is a strong candidate for automation. Where CI is used, such as in DevOps, it is good practice to also include automated regression tests.

Confirmation testing and/or regression testing for the test object are needed on all test levels if defects are fixed and/or changes are made on these test levels.

### Maintenance testing

There are different categories of maintenance, it can be corrective, adaptive to changes in the environment or improve performance or maintainability, so maintenance can involve planned releases/deployments and unplanned releases/deployments (hot fixes).

The scope of maintenance testing typically depends on:

- The degree of risk of the change

- The size of the existing system

- The size of the change

The triggers for maintenance and maintenance testing can be classified as follows:

- Modifications, such as planned enhancements (i.e., release-based), corrective changes or hot fixes.

- Upgrades or migrations of the operational environment, such as from one platform to another, or tests of data conversion when data from another application is migrated into the system being maintained.

- Retirement, such as when an application reaches the end of its life.

## Static testing

anomaly, dynamic testing, formal review, informal review, inspection, review, static analysis, static testing, technical review, walkthrough

### Static Testing Basics

In contrast to dynamic testing, in static testing the software under test does not need to be executed. Code, process specification, system architecture specification or other work products are evaluated through manual examination (e.g., reviews) or with the help of a tool (e.g., static analysis).

Static analysis can identify problems prior to dynamic testing while often requiring less effort and tools. Static analysis is often incorporated into CI frameworks. While largely used to detect specific code defects, static analysis is also used to evaluate maintainability and security. Spelling checkers and readability tools are examples of static analysis tools.

#### Work Products Examinable by Static Testing

Almost any work product can be examined using static testing. Examples include requirement specification documents, source code, test plans, test cases,product backlog items, test charters, project documentation, contracts and models.

Any work product that can be read and understood can be the subject of a review. However, for static analysis, work products need a structure against which they can be checked (e.g., models, code or text with a formal syntax).

Work products that are not appropriate for static testing include those that are difficult to interpret by human beings and that should not be analyzed by tools (e.g., 3rd party executable code due to legal reasons).

#### Value of Static Testing

Static testing can detect defects in the earliest phases of the SDLC, fulfilling the principle of early testing. It can also identify defects which cannot be detected by dynamic testing (e.g. unreachable code, design patterns not implemented as desired, defects in non-executable work products).

Certain code defects can be detected using static analysis more efficiently than in dynamic testing, usually resulting in both fewer code defects and a lower overall development effort.

#### Differences between Static Testing and Dynamic Testing

Static testing and dynamic testing practices complement each other. They have similar objectives, such as supporting the detection of defects in work products, but there are also some differences, like:

- There are some defect types that can only be found by either static or dynamic testing.

- Static testing finds defects directly, while dynamic testing causes failures from which the associated defects are determined through subsequent analysis

- Static testing may more easily detect defects that lay on paths through the code that are rarely executed or hard to reach using dynamic testing

- Static testing can be applied to non-executable work products, while dynamic testing can only be applied to executable work products

- Static testing can be used to measure quality characteristics that are not dependent on executing code (e.g., maintainability), while dynamic testing can be used to measure quality

Typical defects that are easier and/or cheaper to find through static testing include:

- Defects in requirements (e.g., inconsistencies, duplications)

- Design defects (e.g., inefficient database structures, poor modularization)

- Certain types of coding defects (e.g. unreachable or duplicated code, excessive code complexity)

- Deviations from standards (e.g., lack of adherence to naming conventions in coding standards)

- Incorrect interface specifications (e.g., mismatched number, type or order of parameters)

- Specific types of security vulnerabilities (e.g., buffer overflows)

- Gaps or inaccuracies in test basis coverage (e.g., missing tests for an acceptance criterion)

### Feedback and Early Review Process

#### Benefits of Early and Frequent Stakeholder Feedback

Early and frequent feedback allows for the early communication of potential quality problems. If there is little stakeholder involvement during the SDLC, the product being developed might not meet the stakeholder’s original or current vision.

Frequent stakeholder feedback throughout the SDLC can prevent misunderstandings about requirements and ensure that changes to requirements are understood and implemented earlier. This helps the development team to improve their understanding of what they are building.

#### Review Process Activities

The ISO/IEC 20246 standard defines a generic review process that provides a structured but flexible framework. The activities in the review process are:

- Planning. During the planning phase, the scope of the review, which comprises the purpose, the work product to be reviewed, quality characteristics to be evaluated, areas to focus on, etc... , shall be defined.

- Review initiation. During review initiation, the goal is to make sure that everyone and everything involved is prepared to start the review.

- Individual review. Every reviewer performs an individual review to assess the quality of the work product under review, and to identify anomalies, recommendations, and questions by applying one or more review techniques (e.g., checklist-based reviewing, scenario-based reviewing).

- Communication and analysis. Since the anomalies identified during a review are not necessarily defects, all these anomalies need to be analyzed and discussed. For every anomaly, the decision should be made on its status, ownership and required actions.

- Fixing and reporting. For every defect, a defect report should be created so that corrective actions can be followed up. Once the exit criteria are reached, the work product can be accepted. The review results are reported.

#### Roles and Responsibilities in Reviews

Reviews involve various stakeholders, who may take on several roles. The principal roles and their responsibilities are:

- Manager – decides what is to be reviewed and provides resources, such as staff and time for the review

- Author – creates and fixes the work product under review

- Moderator (also known as the facilitator) – ensures the effective running of review meetings, including mediation, time management, and a safe review environment in which everyone can speak freely

- Scribe (also known as recorder) – collates anomalies from reviewers and records review information, such as decisions and new anomalies found during the review meeting

- Reviewer – performs reviews. A reviewer may be someone working on the project, a subject matter expert, or any other stakeholder

- Review leader – takes overall responsibility for the review such as deciding who will be involved, and organizing when and where the review will take place

#### Review Types

There exist many review types ranging from informal reviews to formal reviews. The required level of formality depends on factors such as the SDLC being followed, the maturity of the development process, the criticality and complexity of the work product being reviewed, legal or regulatory requirements, and the need for an audit trail.

Selecting the right review type is key to achieving the required review objectives. The selection is not only based on the objectives, but also on factors such as the project needs, available resources, work product type and risks, business domain, and company culture. Some review types are:

- Informal review. Informal reviews do not follow a defined process and do not require a formal documented output. The main objective is detecting anomalies.

- Walkthrough. A walkthrough, which is led by the author, can serve many objectives, such as evaluating quality and building confidence in the work product, educating reviewers, gaining consensus, generating new ideas, motivating and enabling authors to improve and detecting anomalies.

- Technical Review. A technical review is performed by technically qualified reviewers and led by a moderator. The objectives of a technical review are to gain consensus and make decisions regarding a technical problem, but also to detect anomalies, evaluate quality and build confidence in the work product, generate new ideas, and to motivate and enable authors to improve.

- Inspection. As inspections are the most formal type of review, they follow the complete generic process. The main objective is to find the maximum number of anomalies. Other objectives are to evaluate quality, build confidence in the work product, and to motivate and enable authors to improve. Metrics are collected and used to improve the SDLC, including the inspection process. In inspections, the author cannot act as the review leader or scribe.

#### Success Factors for Reviews

- Defining clear objectives and measurable exit criteria. Evaluation of participants should never be an objective

- Choosing the appropriate review type to achieve the given objectives, and to suit the type of work product, the review participants, the project needs and context

- Performing reviews on small chunks, so that reviewers do not lose concentration during an individual review and/or the review meeting

- Providing feedback from reviews to stakeholders and authors so they can improve the product and their activities

- Providing adequate time to participants to prepare for the review

- Support from management for the review process

- Making reviews part of the organization’s culture, to promote learning and process improvement

- Providing adequate training for all participants so they know how to fulfil their role

- Facilitating meetings
