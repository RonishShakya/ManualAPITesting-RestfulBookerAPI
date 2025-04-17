📋 Project Scope
The goal was to thoroughly test the Restful-Booker API through:

Manual testing using Postman

Test Plan and Test Case design

Execution of test cases

Defect detection and reporting

Documentation of results and findings


🧪 Types of Testing Performed
✅ Smoke Testing: Verify the API is reachable and endpoints are responsive

✅ Sanity Testing: Validate major functionalities like booking creation and retrieval

✅ Functional Testing: Check individual API functionalities against expected outcomes

✅ Negative Testing: Send invalid payloads, tokens, or IDs to test error handling

✅ Security Testing: Validate access control using authentication token logic

✅ Boundary Testing: Input extreme values to assess system behavior

✅ Regression Testing: Re-run test cases after bug fixes to ensure stability


🧠 Test Design Techniques Used
Equivalence Partitioning: Divided input data into valid and invalid classes

Boundary Value Analysis (BVA): Tested min/max limits in fields like names and prices

Decision Table Testing: Covered complex logic like booking update rules

State Transition Testing: Simulated state changes like booking lifecycle transitions

Use Case Testing: Based on real-world scenarios like complete booking workflow


🛠️ Approaches Used
Error Guessing: Predicted likely failure points based on experience

Exploratory Testing: Freeform testing to uncover hidden issues

Prioritized Test Cases: Based on functionality criticality and bug frequency


🔧 Tools Used
📬 Postman – for sending HTTP requests and validating responses

📌 JIRA + Zephyr Scale – for managing test cases, execution cycles, and defect tracking

📝 Word and Excel – for writing test plans, execution reports, and manual logs

📸 Snipping Tool – to capture screenshots of response bodies and errors


📊 Artifacts Created
✅ Test Plan – Described testing scope, schedule, approach, and risks

✅ Detailed Test Cases – Covering CRUD operations, filtering, auth token use, and error handling

✅ Defect Report – Including status codes not matching expected values, method not allowed errors, etc.

✅ Test Execution Report – Summarizing test case outcomes and highlighting key bugs


🏁 Conclusion
This project strengthened hands-on experience with REST APIs, focusing on:

REST principles (GET, POST, PUT, PATCH, DELETE)

API authentication (token-based)

Status code handling

Robust test case design
