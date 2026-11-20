# Full Postman Regression Test Execution Report

## Test Objective

The objective of this regression test was to execute the complete Postman API testing collection and evaluate the results of its automated JavaScript assertions. The execution was intended to identify unexpected API behavior, verify previously implemented test coverage, and document any failures requiring further investigation.

## Test Environment

- **Testing Tool:** Postman
- **Collection:** QA Engineering - API Testing Collection
- **Environment:** QA Portfolio - Test Environment
- **Execution Method:** Postman Collection Runner
- **Iterations:** 1
- **Requests Executed:** 47
- **Validation Method:** Automated JavaScript assertions

## Test Execution Results

The complete Postman API testing collection was executed using the Collection Runner.

- **Total Requests:** 47
- **Total Iterations:** 1
- **Assertions Passed:** 154
- **Assertions Failed:** 1
- **Known Failure:** EX-313 - Invalid JSON Test

The EX-313 test expected an HTTP 400 Bad Request response when malformed JSON was submitted. The actual API response was HTTP 500 Internal Server Error.

The discrepancy was retained in the regression results for further investigation.

## Test Execution Summary

| Metric | Result |
|---|---|
| Requests Executed | 47 |
| Collection Runner Iterations | 1 |
| Total Assertions | 155 |
| Assertions Passed | 154 |
| Assertions Failed | 1 |
| Overall Execution Status | Completed with Known Failure |

The regression execution completed with one failing assertion. The collection cannot be classified as fully passing until the EX-313 discrepancy is investigated and resolved.

## Defect Investigation — EX-313

**Test:** EX-313 - Invalid JSON Test

**Test Scenario:** Submit malformed JSON to the JSONPlaceholder API.

**Expected Result:** HTTP 400 Bad Request.

**Actual Result:** HTTP 500 Internal Server Error.

**Assertion Result:** FAILED.

**Investigation Status:** Open — further investigation required.

The observed response did not match the expected HTTP status code. The failing assertion was preserved rather than modified solely to produce a passing test.

The root cause has not been confirmed. Further investigation is required to determine whether the discrepancy reflects API behavior, test expectations, or another factor.

## Test Evidence

The Postman Collection Runner screenshot documents the final regression execution, including 154 passing assertions and 1 failing assertion.

[View Full Postman Regression Test Evidence](QA_Portfolio_Full_Regression_154_Passed_1_Failed_Final.png)

## Test Conclusion

The full Postman regression execution completed with 47 requests and 155 automated assertions.

Of those assertions, 154 passed and 1 failed.

**Overall Status: COMPLETED WITH KNOWN FAILURE**

The EX-313 Invalid JSON Test remains unresolved because the API returned HTTP 500 instead of the expected HTTP 400.

The regression results and supporting evidence have been preserved for further investigation. The collection should not be classified as fully passing until the discrepancy is resolved and regression testing is repeated.



