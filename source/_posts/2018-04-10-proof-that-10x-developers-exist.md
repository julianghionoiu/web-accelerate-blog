title: Forget about the 10x developer, focus on 3x instead
category: High-Performance Teams
date: 2018-04-10
tags:
- Data-Driven Article
- Skills-Based Hiring
thumbnail: /content/banded_distribution_of_performance.png
lede: "
Controlled data is emerging to show that 10X differences between developers might exist. But the occurrence is low.<br/>
More interesting is the fact the 2x and 3x differences are pretty common within existing teams.
"
featured: true
---

I am going to open up a controversial subject, the 10x developer myth.
This subject has been debated by the industry for decades, so why bring it up again?
Well, I have some interesting data that might change the way you think about developer productivity.

To ensure that we are on the same page as to what a 10x developer is, let’s use this definition from Techpedia [(1)](#1):
> A 10x developer is an individual who is thought to be as productive as 10 others in his or her field. The 10x developer would produce 10 times the outcomes of other colleagues, in a production, engineering or software design environment.

Currently, there is little agreement on how 10x developers look like and whether they are good or bad.
Usually the arguments against the 10x developer fall into three categories:
- Lack of reliable data - The data behind the original articles is being disputed [(2)](#2)
- Speed is bad - Increased speed leads to technical debt and thus slows down the entire team [(3)](#3)
- Superheros are bad - The fact that such developers exist its detrimental to the culture of the company [(4)](#4)

## New data is starting to emerge

At Accelerate we are running our technical assessments as controlled experiments.
We are doing this in order to reliably compare developer productivity. I will go into more details in the next section.

It is not just us, other people have also started measuring productivity.
Steve Fenton recently wrote an article [(5)](#5) where he shares the data he had collected by tracking his team over 12 months. He worked out that:
> Unsurprisingly, the less experienced programmers take a lot longer to deliver features compared to the experienced programmers. About ten times longer, which bears out the concept of a 10x programmer.

## The Accelerate.io approach

How do you measure developer productivity in a controlled way?

Our approach is to simulate multiple development cycles in a controlled environment and ask different developers to go through exactly the same flow.

This eventually took the form of two coding challenges with 5 rounds designed in such a way that we can use time as a proxy for quality:
- Good code helps implement new features faster, it has multiple incremental requirements that put a lot of pressure on the design
- Bad code will translate into time penalties

> With this approach we are describing quality code as code that is able to cope with future requirements.

By translating everything into time, we now have a consistent metric which we can measure.
We are interested in the cumulative time, that is the physical time taken plus time penalties.

To avoid favouring anyone, we used a domain that is well known and we allowed the developers to use their own tools.

This is how a result looks like. You can see the time distribution and the penalties in red:
![Incremental Requirements Coding Challenge](/content/incremental_requirements.png)

## The audience

A total of 120 software developer professionals have currently taken our coding challenges.

The challenges have been used under three circumstances:
1. Developers working for a software company, to form the company benchmark
2. Candidates applying for development roles at the previously mentioned software companies

Every result is anonymised, so no one knows who the other developers are.
Everyone who takes the challenge gets access to a report which shows where they stand and how the other people have performed.

## Results

A representative set of results for a company looks like this:
![Within company distribution](/content/within_company_time_distribution.png)

We are interested in how performance is distributed, so we need to aggregate and normalise the data.
To make it easier to visualise the differences, we are going to use the median as a point of reference and put developers into performance bands.

**Faster than median:**

| Band  | Number of developers  | Percentage |
|:-------------:|:-------------:|:------------:|
|up to 1.5x faster	| 32 | 27% |
|up to 2x faster	| 16 | 13% |
|up to 2.5x faster	| 8	 | 7%  |
|up to 3x faster	| 5	 | 4%  |

**Slower than median:**

| Band  | Number of developers  | Percentage |
|:-------------:|:-------------:|:------------:|
|up to 1.5x slower	| 31 | 26% |
|up to 2x slower	| 16 | 13% |
|up to 2.5x slower	| 10 | 8%  |
|up to 3x slower	| 2	 | 2%  |

From our data set, the performance difference between the fastest and slowest is **8.5x**.
Given that these are extremes, we hypothesise that:
>10x developers are very rare and it involves comparing the best with the worst performers.

A more interesting question is what difference should we expect in the real world.

If we visualise this as a chart, we immediately notice the normal bell curve distribution.
![Distribution of challenge time](/content/banded_distribution_of_performance.png)

Given that around half of the people are situated in the middle bands ( the 1.5x ) we can draw the conclusion that 2x and 3x differences are quite common.
> Actually, I am regularly seeing 2x and 3x differences within the **same company**.

## Implications

Seeing that 2x and 3x differences are quite common, this opens up two strategies for improving the performance of a team:
1. **Raising the bar** by applying objective assessments during the hiring process to identify 2x and 3x developers
2. **Investment in training** targeted at improving the team's development capability. Judging from the data set, a 2x improvement is achievable.

The coding challenge is focused on coding skill, but a developer has to possess a broader set of skills:
- Ability to work with legacy code
- Sharing knowledge withing the team
- Understanding of web architectural patterns
- Deployments and configuration management
- Security and performance monitoring

> Striving for mastery is undoubtedly a good thing. A master developer, who has mastered all the skills, could achieve greater levels of productivity and might even reach 10x.

## Limitations

As with all experiments this is an approximation of the real world and it is limited by its nature.

The main limitations are:
- Code quality is transformed into time by using incremental requirements, this does not cover all possible quality aspects
- Our analysis considered individual productivity, but software development happens in the context of a team
- We only focused on the act of writing code, but a developer is also involved in deployments, QA and architectural decisions

## Getting involved

The experiment is ongoing, so if you or your team is interested in taking the challenge and seeing how you compare (everything is anonymised), please contact me at julian.ghionoiu@accelerate.io.

I promise you will gain unique insights into developer productivity.

&nbsp;

---

#### References
<a name="1">1.</a> https://www.techopedia.com/definition/31673/10x-developer
<a name="2">2.</a> Laurent Bonsavit debunks the myth in his book "[The Leprechauns of Software Development](https://leanpub.com/leprechauns)"
<a name="3">3.</a> "more common way to be a 10x programmer: generate technical debt at a rate that requires ten other developers to clean up the mess." - Brian Craft
<a name="4">4.</a> https://modelviewculture.com/pieces/hacker-mythologies-and-mismanagement
<a name="5">5.</a> https://www.stevefenton.co.uk/2018/03/the-value-of-experience-in-programming/