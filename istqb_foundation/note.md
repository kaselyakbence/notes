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
