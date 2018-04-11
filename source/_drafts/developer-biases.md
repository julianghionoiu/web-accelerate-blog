# Developer Cognitive biases

##  The perfect code bias

Because developers take pride in the code they write, they have the desire to produce the perfect code, the code that will stand the test of time and will be able to accommodate all the future requirements.

While this is admirable, this leads to increased delivery times.
1. No one can predict all future requirements so optimising for some requirements might make the code harder to change for others
2. One can polish a piece of code until it is perfect (from their perspective), but every time this happens you get diminishing returns. The opportunity cost incurred by delaying a feature should be compared with the benefits of possibly speeding up the delivery of some of the future features

I have seen one team spending a lot of time on a feature while the business

## The desire to learn the latest techniques and frameworks

Developers have a need to feel that they are up to date, the industry is constantly changing and you have a new buzzword appearing every year. To feel part of the community one has to familiarise oneself with the new techniques and tools.

While this is admirable, it can conflict with the interests of the business.

1. Introducing a technique without mastering it would often lead to detrimental results.

I have seen this happening with people that adopt TDD and push it to their company without having mastered the technique first. This usually leads to a proliferation of unit tests without real business value. They cost to produce and maintain and will make to code harder to change in the future.

Another example I am seeing too often is code written under different paradigms within the same codebase. With functional programming on the rise, you see developers trying to apply functional principles to a object-oriented heavy codebase.
Part of the codebase gets re-written, sometimes with questionable benefits, and most of the time this effort leaves the codebase in an inconsistent state, making it harder for a newcomer to get up to speed and contribute. This impacts the business as resources are being diverted to getting people up to speed on how to work with a code base written with two paradigms.

2. Introducing a new framework out of personal preference, without a cost vs benefit analysis

Say a new shinny testing framework is released and it has a cool feature that you want.
You decide to use it for the new feature that you are working on. Works well for you, but know the codebase has three different ways of writing tests.
This has an impact on the business as the code will be harder to maintain or a dedicated effort has to be made to transition the entire codebase to the new way of writing tests.
