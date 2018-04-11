# Quality vs Speed fallacy

The general belief is that you cannot have fast software delivery without degrading code quality.
What if this is not true, but it is just hard to achieve both?

This perceived tradeoff happens when an individual has reached it's peak productivity. If they try to go faster, they start cutting corners and this degrades code quality. If they want to improve the code quality they need to spend more time.
This is a capability plateau and not insurmountable law. If the developer focuses on improving their development techniqu in respect to both delivery speed and code quality, they will be able to eventually break through the plateau and achieve a new level of productivity which will translate into a greater speed of delivery and code quality.

This has been happening through the journey of a developer.

Let's take a junior developer, he starts by taking a long time to solve simple problems. The code produced is often partially correct and off sub-standard quality.

By practicing, the junior developer picks up speed and is able to find the solutions faster, at the same time the quality of the code starts to gradually increase by using better language constructs. Because by now, the junior only worked with small problems, there was no need to think about supporting multiple requirements so the quality of the code can be considered suboptimal.
The junior developer starts coding very fast, but with little emphasis on code quality and correctness. We will call him a hacker. He is proud of the fact that he is able to come up with clever, fast solutions.

After spending more time working on the same codebase and having to face his past decisions (lack of tests, poor software design), the hacker realises that writing software is not just about the immediate solution, but also about the long term maintenance. This makes him learn about software design and testing strategies. As with any new techniques, the initial journey is slower but he can see that the software now produces is nicer, it can accommodate future requirements and it is has tests to prove that the software if working as expected.

By this point, one starts to adopt a craftsperson mentality and will dedicate himself to producing well crafted code. Speed is not a concern because he believes that quality is much more important than short term delivery. This belief if also amplified by all the books, workshops and meetups about software quality. This makes the person think that the only way is to produce software of even better quality, the perfect code. This is a dead end as this quickly leads to diminishing returns. (see the The perfect code bias)

Another avenue to pursue is the delivery speed. One will realise that the business is driven by delivery dates and features. In order to add more business value you can either deliver more features in a given time or deliver the same set of features faster. This is when a craftsman will start pursuing delivery speed but without degrading quality. They realise that quality is an investment and this investment should be made with great care as it bears a cost and a risk.

To increase delivery speed and maintain code quality, two main directions stand out:

1. Minimising the risks associated with design decisions

- Incremental/Evolutionary Design
- Domain Driven Design
- Simple code - Transformation Priority Premise

2. Becoming faster at changing existing code

- Refactoring
- Mastering the tools, IDE, language

When code quality is used as a tool, rather than a goal, it allows a developer to move fast and sustain the pace indefinitely.


Coming back to the original issue of quality vs speed, the question is not what is the right tradeoff, but why can't you move faster?
What is slowing you down?

## Why do we need software ?

Achieve a business goal, offer a service.
Software is written to support a business in it's current endeavours.
Writing software is not a goal it is a means to an end.

## What is quality ?

In order to define quality we should first look at the effect it has on the business.
Let's run through a thought exercise.

Say we have two companies A and B of the same size working in parallel to deliver the same service with the same functionality.
Both companies manage to achieve this at the same time. Unfortunately, users are complaining about the service provided by company B. Which now has to divert resources to fix them.

Now, say the market needs a new feature, feature 2. Company A manages to deliver this feature slightly faster than company B.
For feature 3, Company A takes only half the time it takes Company B to deliver the same feature.

A better quality code produces the following outcomes:
- ability to accommodate future requirements faster
- less time spent on solving problems/issues
- faster on-boarding of new team members

As you might notice, all the previous three items refer to time, but this is not present time, it is future time. We can measure quality as time saved in the future.
Because the future is uncertain, this makes it difficult to quantify quality.

## What is the delivery speed ?

Some requirements are known and needed as soon as possible. There is no uncertainty.
The speed at which the team is able to deliver these requirements is the delivery speed.
