# Review Process

## Preliminary Questions for the Project

1. What is the specific scope (`*.sol` files) for the security audit?
2. Does the project have comprehensive specifications and code documentation?
3. What is the code coverage percentage?
4. Are there any projects or protocols similar to yours? If so, which ones?
5. Have you previously undergone any audits? Are there plans for further audits or security programs?
6. Threat Model Interview

Based on the responses, we can negotiate the required effort, payment terms, and timeline.

## Security Review Outcomes & Fixes Review

Upon completion of the agreed-upon timeframe, the project will receive a detailed security review report. The project has 7 days to address the identified issues. Each issue should be resolved in a separate commit, with a commit message specifically referencing the issue being addressed. I will then perform a single iteration of a "fixes review" at no additional cost, to verify that the implemented fixes are both correct and secure.

### Important Notes for the Fixes Review

- For any questions or clarifications regarding the vulnerabilities or recommendations in the report, you can contact me through the predetermined channel of communication.
- The review should exclusively focus on the fixes for reported issues; significant refactorings, new features, or architectural changes should not be included.
- If implementing the fixes proves to be overly complex, or if multiple iterations of reviews are required, this constitutes a special case that will be discussed separately.

## Disclaimer

While a smart contract security review aims to identify as many vulnerabilities as possible, it cannot guarantee the complete absence of security risks. The review is a time-bound, resource-constrained, and expertise-driven effort. Therefore, I cannot offer a 100% security guarantee post-review, nor can I assure that the review will uncover all potential issues with your smart contracts.
