# Code Review Guide

## Why code review

It helps developers discover bugs earlier, learn the code base, improve coding performance, share new technologies and techniques with each other, making source code readable by anyone who might be introduced to the project at any given time during development.

For younger developers, the code review process provides an opportunity for younger developers to acquire optimization techniques and boost the performance of their code from other experienced developers. Additionally, it gives a chance to hone their skills and become experts in their craft.

## How to review code

TODO:

## What to look for in Code Review

### Code health

Refer to [Best practices in code writing](#Best-practices-in-code-writing).

### Readable?

In most cases, reviewers should look at every line of code that they have been assigned to review. Sometimes reviewers can choose to scan over large data structures generated code and so on, generally speaking don't scan over any human-written block of code and assume what is inside is okay.

Clarifications are required from the authors when reviewer's reviewing speed is slowing down by code that is too hard to read. Also, if a reviewer don't feel qualified to do some part of the review, needs to make sure there is at least one reviewer is qualified, particularly for complex issues such as privacy, security, concurrency, accessibility, internationalization, etc.

### Compliment & Mentoring

Sometimes it's even more valuable to give good code practises encouragement and appreciation than point out the mistakes. Code review provides developers opportunities to learn new things from others, in long term, developers sharing knowledge with each others is part of improving the code health of a system.

### In Summary

Make sure

- Naming are clear and follow the naming convention.
- Comments are clear, useful and explaining why instead of what.
- TODO

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

Good code is simple and efficient, it can be understood quickly by code readers, and easy to use when other developers come across it in the future. Avoid over-engineering, means the code should not be made more generic than it needs to be, or added unnecessary functions.

### Comments

It is recommended to explain why some code exists, make sure comments are written in clear, useful and understandable English.

An useful comment explains why the code exists rather than what the code is doing (except it is more helpful to understand regular expressions or complex algorithms with comments explaining what they are doing), such as the purpose of a piece of code, how it should be used, and how it behaves when used.

### Reusability and Scalability

Avoid hard coding and developing duplicated code for similar functions, instead developers should analyze the conditions and requirements, refactor the code into reuseable functions ([Complexity](#Complexity) also needs to be considered).

Code can be easily extended and adapted as it won't be discarded when new requirements emerge.

## Reference

[Google-eng-practices](https://google.github.io/eng-practices)

[Best-practices-to-improve-code-quality](https://www.encora.com/insights/best-practices-to-improve-code-quality)
