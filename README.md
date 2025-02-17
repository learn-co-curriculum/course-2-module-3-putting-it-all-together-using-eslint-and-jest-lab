**Lab: Putting It All Together Using ESLint and Jest**

**Estimated Completion Time:** 30-60 minutes

**Overview:**
In this lab, you will be working on a JavaScript project that includes several mathematical functions and their corresponding tests. The code has some intentional errors and missing sections in the test file. Your task is to use ESLint to fix the code errors in `index.js` and then complete the missing tests in `index.test.js` to ensure all tests pass.

**Scenario:**
As a junior developer at a software company, you are tasked with maintaining and ensuring the quality of the codebase. You need to debug the code using ESLint and write the necessary tests to verify the functionality of the provided functions. This scenario reflects a common industry situation where maintaining code quality and test coverage is crucial.

**Tools and Resources:**

- Visual Studio Code (or any code editor)
- Node.js
- ESLint
- Jest (for running tests)
- GitHub repository (instructions to fork and clone)

**Instructions:**

1. **Fork and Clone the Repository:**

   - Go to the GitHub repository (https://github.com/learn-co-curriculum/course-2-module-3-putting-it-all-together-using-eslint-and-jest-lab)
   - Fork the repository to your GitHub account.
   - Clone the forked repository to your local machine.
   - Navigate to the project directory and run `npm install` to install the necessary dependencies.

2. **Define Project Needs and Goals**

   - Identify that the project uses JavaScript and the primary goals are code quality and testing.
   - Consider the size and complexity of the project, noting it involves static analysis (ESLint) and testing (Jest).

3. **Fix Code Errors with ESLint:**

   - Open `index.js` in your code editor.
   - Use ESLint to identify and fix any code errors.
     - Run `npx eslint index.js` to check for errors.
     - Fix all identified errors in `index.js`.

4. **Complete the Test File:**

   - Open `test/index.test.js` in your code editor.
   - Review the existing tests and identify the missing sections.
   - Write the missing test cases to ensure all functions in `index.js` are properly tested.
   - Ensure the test cases cover various scenarios and edge cases for comprehensive testing.

5. **Run and Monitor Tests with Jest:**

   - Once you have fixed the errors in `index.js` and completed the test cases in `index.test.js`, run the tests using Jest.
     - Run `npm test` to execute all test cases.
   - Ensure that all tests pass successfully.

6. **Refine and Ensure All Tests Pass**

   - Continue refining the code and tests until all errors are resolved and all tests pass successfully.
   - If necessary, re-run ESLint and Jest to confirm no further issues remain.

**Submission and Grading Criteria:**

- **Submission Format:**

  - Ensure your repository is updated and pushed to GitHub.

- **Feedback and Grading:**
  - Your submission will be reviewed for correctness and completeness.
  - The following criteria will be used for grading:
    - All code errors in `index.js` are fixed.
    - All missing test cases in `index.test.js` are correctly implemented.
    - All tests pass successfully.
