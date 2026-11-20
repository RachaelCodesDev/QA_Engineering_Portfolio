# QA Engineering Portfolio

## About This Portfolio

This portfolio showcases my hands-on projects and practical experience developed through structured Quality Assurance (QA) Engineering training. It highlights my work in manual software testing, API testing with Postman, JavaScript assertions, regression testing, test case development, and defect documentation.

## Portfolio Contents

- Test Cases — Documented software testing scenarios and expected results.
  - [TC-LOGIN-001 — Employee Portal Login](Test_Cases/TC-LOGIN-001.md)
- Defect Reports — Sample bug reports documenting issues and their impact.
  - [BUG-LOGIN-001 — Employee Portal Login Failure](Defect_Reports/BUG-LOGIN-001.md)
- Test Evidence — Screenshots and results supporting executed tests.
  - [EX-307 Retrieve User - 4 Passing Assertions](API_Testing/Test_Results/EX-307_Reproducibility_Test_Results.png)
- API Testing — Postman requests, JavaScript assertions, and regression testing examples.
  - [Authentication Regression Test Report](API_Testing/Test_Results/EX-303_Authentication_Regression_Report.md)
  - [Postman API Testing Collection](API_Testing/Postman_Collections/QA%20Engineering%20-%20API%20Testing%20Collection.postman_collection.json)
  - [EX-307 Retrieve User - Test Evidence](API_Testing/Test_Results/EX-307_Reproducibility_Test_Results.png)
  - [Full Postman Regression Test Report](API_Testing/Test_Results/Full_Postman_Regression_Test_Report.md)
  - [Full Postman Regression Test Evidence](API_Testing/Test_Results/QA_Portfolio_Full_Regression_154_Passed_1_Failed_Final.png)

## Tools & Technologies

- Postman — API request testing and response validation.
- JavaScript — Automated assertions in Postman.
- Python — Programming fundamentals.
- Visual Studio Code — Code editing and QA documentation.
- Markdown — Technical documentation.

## Project Status

In Progress — This portfolio is being developed as part of my hands-on QA Engineering training. Completed examples will be added as they are reviewed and verified.

## Getting Started with Postman
### Import the Postman Collection

1. Open Postman.
2. Click Import.
3. Select `API_Testing/Postman_Collections/QA Engineering - API Testing Collection.postman_collection.json` from the downloaded portfolio files.
4. Complete the import to add the collection to your Postman workspace.

### Configure Postman Variables
Before configuring variables, create a Postman environment named `QA Portfolio - Test Environment` and select it as the active environment. The exported collection does not automatically include this environment.
1. Open Postman, create an environment named QA Portfolio - Test Environment if one does not already exist, and select it as the active environment.
2. Add a new environment variable named `baseUrl` in the Variable column.
3. Set its Value to `https://jsonplaceholder.typicode.com`.
4. Open the imported Postman collection.
5. Select the collection's Variables tab.
6. Set the `userId` variable's Value to `1`.
7. Save the collection.
### Authentication Configuration

Some requests require authentication variables in the Postman environment.

Create the following environment variables as needed:

- `portfolioBearerToken`
- `portfolioBasicUsername`
- `portfolioBasicPassword`
- `portfolioInvalidUsername`
- `portfolioInvalidPassword`

Use appropriate test credentials for the target API. Do not commit real passwords, access tokens, or other secrets to the portfolio repository.
