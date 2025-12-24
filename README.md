# Insurance-Pricing-Validation
What is this project?

This project is a simple Python program that checks whether motor insurance prices are correct.

Insurance prices depend on:

the type of product,

the coverage variant,

and the deductible.

Because pricing data can contain mistakes, this program automatically:

calculates the correct price using predefined rules,

compares it with the given price,

fixes the price if it is wrong,

and reports all detected inconsistencies.

How does it work?

Each insurance product has:

a base price,

a variant factor (basic, comfort, premium),

and a deductible factor (100, 200, 500).

The expected price is calculated by applying these factors step by step to the base price.

If the original price does not match the expected one, the program replaces it with the correct value and logs the change.

What does the program return?

Given a set of input prices, the program returns:

a dictionary with corrected prices,

and a list of price inconsistencies, showing what was wrong and how it was fixed.

This makes the pricing logic easy to verify and audit.

Why is this useful?

This type of validation is useful when:

pricing rules must be enforced consistently,

pricing data comes from multiple sources,

or incorrect prices need to be detected automatically.

The project shows how business rules can be translated into clear and maintainable Python code.

Notes

The focus of the project is clarity and correctness.

Business rules are explicit and easy to modify.

The implementation is intentionally simple and easy to follow.
