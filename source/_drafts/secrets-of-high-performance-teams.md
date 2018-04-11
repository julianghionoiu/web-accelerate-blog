# Secrets of high-performance teams

How do some teams perform incredibly well under the uncertainty of real-life development?
The answer is not that they write perfect code.

You cannot predict all the possible future requirements, so you cannot produce, today, the perfect code that will cope with the future of tomorrow. Focusing on optimising a handful of future requirements might be risky.

In order to achieve a high performance, teams focus on activities with a high return on investment regardless of the requirement that is yet to come.

*A good test suite*

If done right, a good test suite enables the team to move fast by ensuring that the new requirements are being added as expected, while the past features are still passing. This focuses the team on the task at hand and allows for the code to be refactored as needed.

Attributes of a good test suite:
- focused on describing the business value
- provides good coverage
- has fewer tests

This not only ensures a level of correctness, but will also allow the code to be changed to accommodate future requirements.

Having a good test suite is a balancing act, too few tests will lead to defects deployed to production, while too many tests with slow you down.

An pitfall here is to add too many tests at the wrong level of abstraction. Each additional test will provide diminishing returns and will make changing that piece of code more difficult.

*Simple code*

By simple code, I am referring to code that:
- makes very little assumptions about the future
- uses abstractions that are part of the business domain
- has fewer abstractions
- can be easily understood by a new member of the team

Because code quality is about the ability to accommodate future requirements, a simple code that makes no assumptions about the future, will provide the best return on investment.
This is because it copes equally well with any requirement, allowing itself to be read, understood and changed.

There are techniques that will help a developer create simple code. To name a few:
- Incremental/Evolutionary Design
- TDD As If You Meant It
- Transformation Priority Premise

*Refactoring skills*

A team that is comfortable with refactoring has less pressure to get everything right the first time. This makes the team go faster as it can deploy and experiment with different solutions.

Another reason to invest in refactoring techniques is the ability to quickly improve the quality of the code base, allowing the team to re-establish the fast delivery pace.

As the code evolves to support more requirements, the quality of the code base might go down.
If not kept in check it will slow down the delivery of the subsequent features.
If the quality issues are not addressed for a longer period of time, it will lead to a spiral of long delivery cycles and reduced code quality.

A team that has mastered refactoring techniques, can quickly refactor the code base to a state where delivery speed is restored.

*Know your tools*

There are tools a developer uses everyday. Such as IDE, Language, command line, frameworks.
Getting better at using the day to day tools will have an immediate impact on productivity.