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

*coverage, debugging, defect, error, failure, quality, quality* *assurance, root cause, test analysis, test basis,*
*test case, test completion, test condition, test control, test* *data, test design, test execution, test*
*implementation, test monitoring, test object, test objective,* *test planning, test procedure, test process, test*
*result, testing, testware, traceability, validation, verification*

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
Includes elaborating the test conditions into test cases and other testware.  Test design answers the question “how to test?”.

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

Some test levels  described:

- Component testing (also known as unit testing) focuses on testing components in isolation. It often requires specific support, such as test harnesses or unit test frameworks. Component testing is normally performed by developers in their development environments.

- Component integration testing (also known as unit integration testing) focuses on testing the interfaces and interactions between components. Component integration testing is heavily dependent on the integration strategy like bottom-up, top-down or big-bang.

- System testing focuses on the overall behavior and capabilities of an entire system or product, often including functional testing of end-to-end tasks and the non-functional testing of quality characteristics. For some non-functional quality characteristics, it is preferable to test them on a complete system in a representative test environment (e.g., usability). Using simulations of sub-systems is also possible. System testing may be performed by an independent test team, and is related to specifications for the system.

- System integration testing focuses on testing the interfaces of the system under test and other systems and external services. System integration testing requires suitable test environments preferably similar to the operational environment.

- Acceptance testing focuses on validation and on demonstrating readiness for deployment, which means that the system fulfills the user’s business needs. Ideally, acceptance testing should be performed by the intended users. The main forms of acceptance testing are: user acceptance testing (UAT), operational acceptance testing, contractual acceptance testing and regulatory acceptance testing, alpha testing and beta testing.

#### Test Type

A lot of test types exist and can be applied in projects. In this syllabus, the following four test types are addressed:

**Functional testing** evaluates the functions that a component or system should perform. The functions are “what” the test object should do. The main objective of functional testing is checking the functional completeness, functional correctness and functional appropriateness.

**Non-functional testing** evaluates attributes other than functional characteristics of a component or system. Non-functional testing is the testing of “how well the system behaves”. The followings are  non-functional quality characteristics (ISO/IEC 25010):

- Performance efficiency

- Compatibility

- Usability (also known as interaction capability)

- Reliability

- Security

- Maintainability

- Portability (also known as flexibility)

- Safety

**Black-box testing** is specification-based and derives tests from documentation not related to the internal structure of the test object. The main objective of black-box testing is checking the system's behavior against its specifications.

**White-box testing**  is structure-based and derives tests from the system's implementation or internal structure (e.g., code, architecture, work flows, and data flows). The main objective of white-box testing is to cover the underlying structure by the tests to an acceptable level.

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
