# Polynomial Class Mutation Testing

Above is a simple class for evaluating polynomials, along with a sparse test suite that provides 94% coverage.

## Set up the Environment

1. Ensure you have access to the `Polynomial` class, your unit tests, and the `pytest` testing framework.

## Define Mutation Operators

1. Identify and define specific mutation operators that you will apply to the `Polynomial` class. 
2. Each mutation operator should be well-documented. 
   
   Example operators may include:
   - Changing coefficients
   - Modifying arithmetic operations
   - Introducing redundant code
   - Other potential mutations

## Implement Mutation Operators

1. Implement the mutation operators as methods in a separate Python module or script.
2. These methods should modify the `Polynomial` class source code according to the defined mutation operators.
3. Ensure that you provide clear examples of how these operators should be applied.

## Apply Mutations

1. Apply the defined mutation operators to the `Polynomial` class to create mutant versions of the class.
2. Create multiple mutants, each representing a different mutation.

## Run Tests on Mutants

1. Run your unit tests on each mutant version of the `Polynomial` class.
2. Determine whether the mutants survive (i.e., the test cases fail to detect the mutation) or are killed (i.e., the test cases correctly identify the mutation).

## Analyze Results

1. Analyze the results of the mutation testing to identify which mutants survived and which were killed.
2. Classify the mutations into different categories based on their impact (e.g., harmless, equivalent, serious).

## Improve the Test Suite

1. Based on the results of mutation testing, revise your test suite to better detect mutants.
2. You may need to add new test cases or modify existing ones to enhance the test coverage.

## Write a Report

1. Write a comprehensive report summarizing the mutation testing process. The report should include:
   - **Introduction**
   - **List of defined mutation operators**
   - **Description of applied mutations and their impact**
   - **Summary of mutant survival and killing**
   - **Analysis of the test suite's effectiveness**
   - **Recommendations for improving the test suite**
   - **Conclusion**

2. The report should be a `README.md` file in the root of the folder in which you performed your analysis.

3. Zip or tarball the entire folder and submit.
