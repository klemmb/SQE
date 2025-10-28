# Test Management Templates | buro-talk
TEST PLAN TEMPLATE
------------------

​

*   Author
    
*   Date
    
*   Document Version
    
*   Classsification
    
*   Prepared for
    

Document Release
----------------

​

*   Function
    
*   Role
    
*   Name
    
*   Date
    
*   Signature
    
*   Author
    
*   Reviewer
    
*   Approval
    

​

DRAFT DOCUMENT FOR REVIEW
-------------------------

This document is in draft form, and is currently being used for iterative improvement, issue capture and feedback from internal customers, and as such may contain errors or omissions.

The content is subject to change as a result of scope discussions.

Until the document is formally released, no part of this document constitutes an agreed deliverable and is for reference or discussion only.

​

EXECUTIVE SUMMARY
-----------------

{This section should only be completed after all subsequent sections, of the Test Plan, have been drafted.  The Executive Summary should provide a one to two page summary of the Test Plan, including main objectives, scope, key dates and resource requirements.  Also make it clear why testing must be done as defined, and in particular the way in which risk is being managed.

The Executive Summary should provide Senior Management with sufficient information about the Test Plan without the need to read the entire document.  Make sure that the Executive Summary avoids all unnecessary jargon and is free from abbreviations.}

​

REVISION HISTORY & CHANGE CONTROL
---------------------------------

​

*   Date
    
*   Version
    
*   Author
    
*   Description
    

​

TABLE OF CONTENTS
-----------------

​

INTRODUCTION
------------

{This is a general note about the template which is to be deleted from any published document.  All sections of this document which are showing in italic text are provided as either guidance notes or examples of possible content.  All italic text must either be deleted, updated or replaced with appropriate non-italic text before a document is issued for review.}

​

PROJECT BACKGROUND
------------------

{Provide the reader with some context for the project. What is the project trying to deliver?}

​

DOCUMENT PURPOSE
----------------

{This document has been produced as part of the planning activity for the project.  It has been created to provide the audience with an understanding of the scope and approach to testing for the project.

The  Test Plan also defines the basic testing deliverables to be developed and delivered during the project as well as the testing processes to be employed, the quality principles to be applied and the corresponding responsibilities to be fulfilled.}

DOCUMENT SCOPE
--------------

AUDIENCE
--------

{The Test Plan is to be provided to the Project Sponsor, Senior User, the Senior Supplier, the Project Manager, Subject Matter Experts, Engineering Leaders and Senior Test Analysts.  It may also be provided to individuals outside of this audience where there may be implications for other projects and initiatives.}

KEY DATES
---------

INPUTS TO TESTING
-----------------

The identification of appropriate Inputs to Testing for the project will be fundamental to the effectiveness and efficiency of the testing lifecycle, and therefore the quality of the project’s deliverables.  The various inputs identified will be used at different levels within the testing lifecycle during the project.

Table XX, below, defines pre-existing items that will be used as inputs to testing for this project:

{The entries in the table may include such items as User Guides, Business Processes and Procedures, current Production Systems, Test Scripts and access to knowledgeable individuals.}

*   Ref
    
*   Item Title
    
*   Item Summary
    
*   Item Owner
    

Table XX – Pre-existing Inputs to Testing

Table XX, below, defines the deliverables being delivered by the project that will be used as inputs to testing:

{The full set of deliverables to be delivered by the project should have been agreed prior to creation of this Test Plan and a list of these should be available from the Project Manager.}

*   Ref
    
*   Item Title
    
*   Item Summary
    
*   Item Owner
    

​

Table XX – Project Deliverables as Inputs to Testing

TEST OBJECTIVES
---------------

The Testing Objectives defined for the Project have been created to support the Project Objectives and the related Test Strategy.  Table XX, below, defines the Project Testing Objectives that have therefore been identified for this project.

The objectives of Testing are:   {Example: replace the following with project related information}

System Integration Testing
--------------------------

*   To verify that internal system elements can work together (Sometimes referred to as ‘Integration in the Small’)
    
*   Establish and verify Hardware integration sequence
    
*   Establish and verify Software integration sequence
    
*   Hardware/software integration sequence
    
*   Sub-system integration sequence
    
*   To ensure data formats and communication elements function as expected
    
*   To verify that the system under test  can work together with other with other external systems (Sometime referred to as ‘Integration in the Large’)
    

Data Migration Testing
----------------------

*   To verify ensure that process and operations to extract, clean, re-format and load data from an existing system’s database to a new system’s database can be conducted correctly when the changeover takes place;
    
*   To check the completeness of migrated data
    
*   To verify that old and new data can co-exist on the new system
    
*   To establish time needed for  the Data Migration processes
    
*   To test the back out and recovery scenarios for data Data Migration
    
*   Check the Security of the Data Data Migration process
    
*   To validate the security of migrated data
    

Operational Acceptance Testing
------------------------------

*   To verify that the Back Up and Recovery process works as specified
    
*   To verify that a change can be safely backed out of a production environment
    
*   To ensure a shutdown and resumption can be safely managed
    
*   To ensure that there is the correct operational support personnel,  documentation and training
    
*   To prove that alerts are raised in the event of a component failure, error condition or if a threshold is breached.
    
*   To prove that the implementation into the production environment will be successful and not adversely affect the existing production services.
    
*   To check any redundancy features work correctly
    
*   To prove that all components of a service are capable of being supported to the required internal or external standards.
    

User Acceptance Testing
-----------------------

*   To verify the operation and usability of the system changes being delivered, in accordance with the agreed Business Requirements Specifications;
    
*   To verify the operation and usability of the system changes being delivered, in accordance with the agreed Business Processes;
    
*   To confirm that the new or amended IT system(s) provides business users with an effective and efficient solution;
    
*   To verify that business operations are not compromised or adversely impacted by the changes being delivered;
    
*   To reduce the risk of critical (system failure), severe or important defects from progressing into production.
    
*   To verify the operation and usability of the system changes being delivered, in accordance with the agreed Business Requirements Specifications;
    
*   To verify the operation and usability of the system changes being delivered, in accordance with the agreed Business Processes;
    

Operational Acceptance Testing
------------------------------

*   To verify that the Back Up and Recovery process works as specified
    
*   To verify that a change can be safely backed out of a production environment
    
*   To ensure a shutdown and resumption can be safely managed
    
*   To ensure that there is the correct operational support personnel,  documentation and training
    
*   To prove that alerts are raised in the event of a component failure, error condition or if a threshold is breached.
    
*   To prove that the implementation into the production environment will be successful and not adversely affect the existing production services.
    
*   To check any redundancy features work correctly
    
*   To prove that all components of a service are capable of being supported to the required internal or external standards.
    

​

Project Testing
---------------

​

*   Check that the system works as a whole and validate the main functional areas before UAT
    
*   Checks the principle requirements of the system have been met
    
*   Identify and remove defects that would impact subsequent testing
    

​

SCOPE OF TESTING
----------------

{It is important that the expectations for Test Coverage, and therefore the Scope of Testing, are clearly communicated, understood and agreed before  Test Level Planning is undertaken.  As well as identifying what will be tested in Test Plan it also defines what will not be tested, establishing clear expectations for this testing level.}

​

Table XX, below, defines attributes within the Scope of Testing for the project:

​

{Define what will be specifically tested during the project, covering both new and pre-existing attributes, such as specific IT systems, sub-systems or modules, system interfaces and business processes.  It may be appropriate to include System Architecture Diagrams or high level Process Flow Diagrams, in which case these should be referred to within Tables 6a and 6b, and included as Appendices at the end of the Test Plan.}

​

*   Type
    
*   Attribute Description
    
*   Reason For Inclusion
    

Table XX – Attributes within Scope of Testing

​

Table XX, below, defines attributes which are Out of Scope of Testing for the project:

​

*   Type
    
*   Attribute Description
    
*   Reason For Exclusion
    

Table XX – Attributes Out of Scope of Testing

​

TEST APPROACH
-------------

{The Test Approach for the project should be created in line with the relevant Test Strategy for the area of development concerned. The levels of testing for the project should be clearly defined, together with any assumptions, external dependencies, constraints, pre-requisites and risks.}

​

User Acceptance Testing will be managed and coordinated by the {insert appropriate text} Test Team.  A group of End Users to be involved in defining and running User Acceptance Tests will be identified and confirmed.

A meeting with these End Users will be arranged to explain and confirm the purpose of the project and their involvement in the testing process.

​

The {insert appropriate text} Test Team will undertake the majority of Test Preparation activities, with input from the End Users in regard to the Test Scenarios to be tested.  The types of tests to be considered when defining the set of Test Scenarios will include:

​

*   Business Requirements Testing
    
*   Business Process Testing
    
*   Usability Testing
    
*   Ad-hoc Testing
    
*   Regression Testing (in regard to UAT only)
    

The End Users will confirm and approve a final set of Test Scenarios for User Acceptance Testing.

​

The {insert appropriate text} Test Team will create corresponding Test Scripts and Test Data for the Test Scenarios in Quality Center in advance of Test Execution, ensuring that Test Coverage is complete.  The required Test Coverage is determined by the attribute Business Criticality and Assessed Risk defined for each Test Requirement (Test Condition).

​

Additionally, a Test Execution Schedule will be produced defining when tests will be executed and by which End Users.

Test Execution activities will be carried out by the End Users using printed or exported Test Scripts from XXX, e.g. in MS Excel format.  Test Execution is planned to have two test cycles allowing for a fix release to be delivered prior to the second test cycle.  Support and coordination of UAT Execution will be provided by the {insert appropriate text} Test Team.

Typical activities in the User Acceptance Test Level include but not be limited to:

*   Environment Check
    
*   Static Data and starting conditions check
    
*   Smoke Test
    
*   Cycle 1
    
*   Cycle 2 Defect fix and regression}
    

The Testing processes and guidelines will be followed during both Test Preparation and Test Execution.

The {insert appropriate text} Test Team will update XXX with the results obtained during User Acceptance Test Execution.

All defects found by End Users will be reported to the nominated {insert appropriate text} Test Team UAT Coordinator.  These will then be recorded and managed to resolution within XXX, the Test Management tool being used for Defect Management during the project, following the Defect Management process.

Any retesting or regression testing required will be scoped to a manageable level.

The End Users will approve successful completion of Test Scripts.

RISKS
-----

​

ASSUMPTIONS
-----------

A number of assumptions have been made during the definition of this Test Plan, as identified in Table XX, below.  Each assumption will be validated during the project testing lifecycle.  Appropriate action will be taken as required to address any invalid assumptions.

*   Reference (i.e. AS01)
    
*   Assumption Description
    
*   Reason for Assumption
    
*   Test Level to Validate
    

Table XX – Assumptions

DEPENDENCIES
------------

A number of external dependencies and project interfaces have been identified during the definition of this Test Plan, as identified in Table XX, below.

{Dependencies can be either inbound or outbound, i.e. items or activities required to enable the Project Testing to be fulfilled and items or activities that require the Project Testing to run to plan.

External dependencies may include availability of resources and test environments being used for other projects, delivery of software from third party suppliers and the availability of business users during testing activities.}

*   Ref
    
*   Dependency/Interface Description
    
*   Project or Activity
    
*   “In” or “Out”?
    

Table XX – External Dependencies

​

CONSTRAINTS
-----------

To ensure that the Test Plan is achievable, any constraints that have been identified during definition of the Test Plan are included within Table XX, below.

{Constraints are barriers or limitations which are definite, and can be categorised by Type such as Resource, Technical, Cost or Time.}

*   Ref
    
*   Constraint Type
    
*   Constraint Description
    

Table XX – Constraints

PREREQUISITES
-------------

A number of non-project related prerequisites have been identified during the definition of this Test Plan, as identified in Table 8.5, below.  These prerequisites must be addressed to ensure that the Project Testing can be delivered as planned.

{Test Plan Prerequisites are items or activities within the control of the Test Team.  This may include recruitment, definition of processes and availability of test tools.}

*   Ref
    
*   Prerequisite Type
    
*   Prerequisite Description
    

Table XX – Prerequisites

​

RISKS
-----

Several key risks have been identified which will have an impact on the ability to undertake Project Testing as defined within this Test Plan.  These have been captured in Table XX, below, and will he escalated to the Project Manager for inclusion within the project’s Risks and Issues Register.

*   Ref
    
*   Summary Description
    
*   Impact
    
*   Probability
    
*   Risk Value
    
*   Risk Response
    
*   Risk Trigger
    

{Avoid, Accept, Reduce (Mitigate), Transfer;What transforms the risk to an issue?}

Table XX – Risks

TEST METHOD
-----------

*   Test Objective:
    
    *   {What defects is the test trying to uncover; what attribute is the test trying to confirm? What is the test coverage (technical/requirements)}
        
*   Test Setup
    
    *   {How is the test environment, data, automation etc. set-up to be able to conduct the test?}
        
*   Test Procedure
    
    *   {What is the process to execute the test? Scripted, exploratory, rational for execution, measurement and results.}
        
*   Test Results
    
    *   {In what format are the test results produced and reported.}
        

RESPONSIBILITIES AND INVOLVEMENT
--------------------------------

{Example – This Level of Testing will be planned and managed by the Test  Manager and undertaken by the Test Team with clarification and support  provided by Subject Matter Experts (SME) and Business Analysts (BA) where needed.}

​

GOVERNANCE
----------

{Example – Testing will be formally planned, reviewed and approved in accordance with the Testing processes and procedures.  The Test Plan will be produced in accordance with the approved Product Description and associated Test Plan Template.

​

Testing will be subject to progress reporting, providing information on the progress of testing against the agreed plan and identifying issues and risks that may impact subsequent levels of testing.  Because the software being developed shall  be under version control ...}

​

SUSPENSION AND RESUMPTION CRITERIA
----------------------------------

ENTRY CRITERIA
--------------

​
-

EXIT CRITERIA
-------------

{Example – System Test Execution cannot complete until the following have been satisfied:

*   All System Test Scripts have been executed, subject to any agreed deferrals.
    
*   All test defects identified have been resolved, subject to any agreed deferrals.
    
*   Appropriate System Test Results and Test Evidence have been captured.
    

{Example – Unit and Link Test Execution cannot complete until the following have been satisfied:

*   All Unit and Link Test Scripts have been executed, subject to any agreed deferrals.
    
*   All test defects identified have been resolved, subject to any agreed deferrals.
    
*   Appropriate Unit and Link Test Results and Test Evidence have been captured.
    

The Unit and Link Test Exit Criteria will be confirmed and potentially updated within the Unit and Link Test Plan.}

​

QUALITY GATES
-------------

{Example: There are key points during the project testing lifecycle when quality needs to be checked (this will typically be hand over of responsibility or progression to a different phase or test level.  For this project, Quality Gates will be implemented as shown in the table below. }

Table XX, below, defines the Quality Gates to be implemented during the project testing lifecycle. {Example: replace with information relevant to the project}

*   Quality Gate
    
*   Quality Gate Purpose {To ensure that all System Test Execution and System Test Preparation activities have been successfully completed}
    
*   Subsequent Activity {User Acceptance Test Execution}
    

Table XX – Quality Gates

​

Quality Gates will be formally managed, with each being recorded within a Quality Gate Assessment Form and supported by a process for addressing and managing completion of any outstanding items.

​

TEST  ENVIRONMENT REQUIREMENTS
------------------------------

TEST ENVIRONMENT ARCHITECTURE
-----------------------------

{This section of the document should provide an overview of the potential test environment architecture to support the project and should define the number of test environments required.  For each Test Environment required identify the test environment components, such as individual applications, application interfaces, database requirements, client requirements and data requirements.  It may be appropriate to refer to an architecture diagram, in which case this should be referred to and included as an Appendix at the end of the Test Plan.}

TEST ENVIRONMENT ACCESS
-----------------------

{This section of the document should define the controls to be placed on access to each of the test environments.  At this level of planning test environment access requirements should be generic in their definition.  For example, Analyst Programmers should only have “read only” access to all test environments and Database Administrators should have access to apply releases and updates only.}

TEST DATA REQUIREMENTS
----------------------

{This section of the document should provide early visibility of any test data requirements for the test environments.  This could include converted, migrated or historic data as well as any static or dynamic reference data.  In some instances this may include identification of the requirement for data files and messages.  The subsequent Test Level Plans should include more detailed test data requirements.}

TEST ENVIRONMENT AVAILABILITY
-----------------------------

{This section of the document should provide an early indication of when test environments need to be available to the project, providing guidance for provision of supporting services and to assist in scheduling usage of test environments.  It may be useful to include a diagram or table to illustrate a schedule.  This will also help to justify the number of test environments specified.}

TEST ENVIRONMENT SUPPORT REQUIREMENTS
-------------------------------------

{This section of the document should provide early notification to those providing supporting services for the test environments.  This should include requirements for backups and restores, including frequency.  Again, these should be refined and confirmed within the Test Level Plans.}

​

The Test Environment in which User Acceptance Testing will be conducted will be subject to formal Configuration and Release Management controls.

​

The following Test Environment Requirements have been identified for User Acceptance Testing:

*   Test Environment Components – {Provide an inventory of what IT systems, modules and interfaces each Test Environment must include.  Where possible, also define specific Test Environments by name.}
    
*   Dates Required – {Provide dates between which the Test Environment(s) must be available to the project}
    
*   Test Data Required – {If known, provide information on test data requirements, such cuts of data from production systems on a particular day}
    
*   Security and Access – {If known, provide information on controls for access to the Test Environments}
    
*   Additional – {Provide any additional information, such as requirements for backing up and restoring Test Environments, scheduling batch runs or manipulating system dates}
    

Releases will be applied to the Test Environment(s) upon request by the Test Lead or UAT Coordinator to the Environment Manager.

​

ROLES AND RESPONSIBILITIES
--------------------------

The table below, defines the roles and responsibilities to support delivery of testing in accordance with the Test  Plan.

{Include any additional background about selection of resources which may be applicable.The table should be completed as far as practicable at this time.  Discussion should be held with all individuals to be named prior to inclusion within the document.  Add and delete Roles and Responsibilities as required.  Individuals can be assigned to multiple Roles.}

*   Role
    
    *   {Test Manager
        
    *   Senior Test Analyst
        
    *   Test Analyst
        
    *   Test Incident Manager
        
    *   Configuration Manager
        
    *   Release Manager
        
    *   Database Administrator
        
    *   Analyst Programmer
        
    *   Service Test Manager
        
    *   Business Analyst
        
    *   Business User}
        
*   Responsibility
    
*   Team
    
*   Name(s)
    

Table XX – Roles and Responsibilities

BUDGET AND TOLERANCE

A budget of {enter number in words} man days effort at a notional cost of {enter day rate value, as provided by XXX} has been agreed for project testing activities with the Project Manager.  This does not include costs incurred by other teams in support of the project testing activities.

Table XX defines the tolerances to be applied to delivery against the Test Plan.

*   Type
    
*   Description
    
*   Tolerance
    
*   Time {Testing must complete within estimated days effort +/= 20 working days.}
    
*   Cost
    
*   Scope
    

Table XX – Budget and Tolerance

​

MONITORING AND CONTROL
----------------------

Testing Progress Reports will be provided to the Project Manager by the {Test Manager/Senior Test Analyst} on a {weekly/fortnightly} basis and copied to other testing resources assigned to the project.  Regular update meetings to review the Testing Progress Reports will be agreed with the Project Manager.

​

Testing activities will be monitored by the {Test Manager/Senior Test Analyst} during the project to ensure progress is maintained within agreed tolerances.  Any significant risks or issues identified will be immediately raised with the Project Manager and managed within the project’s Risks and Issues Register.

​

Testing progress reports will be provided to the Project Manager and other testing resources assigned to the project during the individual levels of testing.  These will provide appropriate metrics from testing, including comparisons of progress against plan, test coverage and analysis of defects raised.

​

TESTING DELIVERABLES
--------------------

Table XX, below defines the products to be produced during the project’s testing lifecycle.

Amend as necessary

*   Id
    
*   Product Name
    

Table XX – Testing Deliverables

​

STAFF AND TRAINING NEEDS
------------------------

{Define any staff or training needs or requirements to be fulfilled to enable delivery of testing in accordance with the Test Plan.  For example, this may include training on the functionality of a particular software application.  Do not include requirements which would be considered as standard, such as training on the use of ...., unless agreed with the Project Manager as an allowable project cost.}

TEST SCHEDULE
-------------

The Test Schedule in Figure 17, below, diagrammatically represents the delivery of products defined within the Test Plan.  These will be expanded upon in the subsequent Test Level Plans.

{Below is an example Test Schedule created in MS Excel.  It may be more appropriate to use MS Project, however the diagram must be legible when the Test Plan is printed.}

Figure 17 – Project Testing Schedule
