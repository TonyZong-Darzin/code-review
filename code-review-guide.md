# Code Review Guide

## Why code review

It assists developers in discovering bugs earlier, learning the code base, improving coding performance, sharing new technologies and techniques with one another, and making source code readable by anyone who may be introduced to the project at any time during development.

For junior developer, the code review process allows them to learn optimisation techniques and improve the performance of their code from more experienced developers. It also gives them a chance to hone their skills and become experts in their field.

## How to review code

TODO:

## What to look for in Code Review

### Code health

Refer to [Best practices in code writing](#Best-practices-in-code-writing).

### Readable?

In most circumstances, reviewers should examine each line of code that has been allocated to them. Reviewers may choose to scan over large data structures, generated code, and so on; but, do not scan over any human-written block of code and presume that what is inside is fine.

When the reviewer's reviewing pace is slowed by difficult-to-read code, the authors must provide clarification. Also, if a reviewer does not feel qualified to conduct any aspect of the review, make sure there is at least one qualified reviewer, especially for complicated topics like privacy, security, concurrency, accessibility, internationalisation.

### Compliment & Mentoring

It is sometimes more helpful to encourage and appreciate good coding practises than to point out errors. Code review gives developers the opportunity to learn new things from others; in the long run, developers sharing information with one another is part of enhancing a system's code health.

### In Summary

Make sure

- Naming are clear and follow the naming convention.
- Comments are clear, useful and explaining why instead of what.
- TODO:

## Best practices in code writing

### Clarity

Follow consistent code style and naming conventions applicable to the language.

- [How to write clean code](./Clean_Code.pdf)

Some style guides:

- [C# Style Guide](https://google.github.io/styleguide/csharp-style.html)
- [HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html)
- [JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)
- [TypeScript Style Guide](https://google.github.io/styleguide/tsguide.html)

### Complexity

Good code is simple and efficient, easy to understand by code readers, and easy to use when other developers encounter it in the future. Avoid over-engineering, which involves not making the code more generic than necessary, or adding unneeded functions.

### Comments

It is recommended to write comments for code in clear, useful and understandable English.

An useful comment explains why the code exists rather than what the code is doing (Unless it's a regular expression or a complex algorithm, in which case comments clarifying what they do are useful), such as the purpose of a piece of code, how it should be used, and how it behaves when used.

### Reusability and Scalability

Avoid hard coding and developing duplicated code for similar functions, instead developers should analyze the conditions and requirements, refactor the code into reuseable functions ([Complexity](#Complexity) also needs to be considered).

Code can be easily extended and adapted as it won't be discarded when new requirements emerge.

## Reference

[Google-eng-practices](https://google.github.io/eng-practices)

[Best-practices-to-improve-code-quality](https://www.encora.com/insights/best-practices-to-improve-code-quality)
