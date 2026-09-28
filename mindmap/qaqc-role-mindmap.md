mindmap
  root((Modern QA/QC Roles - ISTQB Test Process))
    QA vs QC
      Quality Assurance
        Process-oriented
        Preventive
        Implements and improves dev and test processes
        Responsibility of everyone on the project
      Quality Control
        Product-oriented
        Corrective
        Testing is a major form of QC
        Other QC forms: formal methods, simulation, prototyping
      Test results serve both
        QC: used to fix defects
        QA: feedback on how well processes perform
    ISTQB Roles
      Test management role
        Owns test process, test team, leadership
        Mainly planning, monitoring and control, completion
      Testing role
        Engineering or technical side of testing
        Mainly analysis, design, implementation, execution
      Different people may take roles at different times
      Agile: whole-team approach, team shares some management tasks
      Activities are iterative, may overlap, tailored to context
    Test Planning
      Role: test management
      Define test objectives
      Select approach that meets objectives within constraints
      Test plan content
        Context, scope, assumptions, constraints
        Stakeholders and communication
        Risk register
        Test approach: levels, types, techniques, entry and exit criteria, independence, metrics, test data, environment
        Budget and schedule
      Estimation techniques
        Estimation based on ratios
        Extrapolation
        Wideband Delphi
        Three-point estimation
      Test case prioritization: risk-, coverage-, requirements-based
      Testware: test plan, schedule, risk register, entry and exit criteria
    Test Analysis
      Role: testing
      Answers: what to test
      Analyze test basis to identify testable features
      Define and prioritize test conditions with related risks
      Evaluate test basis for defects and testability
      Testware: prioritized test conditions e.g. acceptance criteria, defect reports on test basis
    Test Design
      Role: testing
      Answers: how to test
      Elaborate test conditions into test cases and test charters
      Identify coverage items
      Apply black-box, white-box, experience-based techniques
      Define test data requirements
      Design test environment, identify infrastructure and tools
      Testware: test cases, charters, coverage items, data and environment requirements
    Test Implementation
      Role: testing
      Create or acquire testware e.g. test data
      Organize test cases into test procedures and test suites
      Create manual and automated test scripts
      Arrange tests in a test execution schedule
      Build test environment and verify its setup
      Testware: procedures, scripts, suites, stubs, drivers, simulators, service virtualization
    Test Execution
      Role: testing
      Run tests per execution schedule as test runs
      Manual or automated, incl. continuous testing and pair testing
      Compare actual results with expected results
      Log test results
      Analyze anomalies to identify likely causes
      Report anomalies based on observed failures
      Testware: test logs, defect reports
    Test Monitoring and Control
      Role: test management
      Ongoing throughout all activities
      Monitoring: gather info, compare actual progress vs plan
      Control: take actions needed to meet test objectives
      Evaluate exit criteria or definition of done
      Metrics: progress, defect, risk, coverage, cost
      Testware: test progress reports, control directives, risk information
    Test Completion
      Role: test management
      Occurs at milestones: release, end of iteration, test level done
      Raise change requests or backlog items for unresolved defects
      Archive or hand over reusable testware
      Shut down test environment to an agreed state
      Analyze lessons learned and improvements
      Create and communicate test completion report
    Modern AI-Assisted Testing
      Scope note: not part of CTFL test process
        See ISTQB CT-AI and CT-GenAI syllabi
        Role names below are industry usage, not ISTQB-defined
      AI support per activity
        Planning and control: risk insights, estimation support, report summaries
        Analysis and design: draft test conditions and cases from requirements
        Implementation: generate test data and automation scripts
        Execution: log and anomaly analysis, defect triage, duplicate detection
        Completion: summarize results and lessons learned
      Emerging responsibilities
        Prompt design for testing tasks
        Human review and validation of AI output
        Manage GenAI risks: hallucination, bias, non-determinism, data privacy
        Evaluate, select, integrate AI test tools
      Testing AI-based systems
        Data quality and bias
        Non-determinism and the test oracle problem
        Explainability and transparency
        Techniques: metamorphic testing, adversarial testing
