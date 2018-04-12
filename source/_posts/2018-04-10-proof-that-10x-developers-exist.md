title: 10X developers do exist - Here is the proof
category: High-Performance Teams
date: 2018-04-10
tags:
- Data-Driven Article
- Skills-Based Hiring
thumbnail: /content/distribution_of_challenge_times.png
lede: "
Controlled data is emerging to show that 10X developers exist and can be spotted.<br/>
More interesting is the fact the 2x and 3x differences are common within existing teams.
"
featured: true
---

I am going to open up a controversial subject, the 10x developer myth.
This subject has been debated by the industry for decades, so why bringing it up?
Well, I have some interesting data to show that might change the way you view things.

To be on the same page, let's use this definition from Techpedia [(1)](#1) about what a 10x developer is:
> A 10x developer is an individual who is thought to be as productive as 10 others in his or her field. The 10x developer would produce 10 times the outcomes of other colleagues, in a production, engineering or software design environment.

On one side you have articles where people share their experience on developer productivity, while on the other side you have people warning against the 10x developer.
Usually the arguments against the 10x developer fall into three categories:
- No reliable data - The data behind the original articles is being disputed [(2)](#2)
- Speed is bad - Increased speed leads to technical debt and thus slows down the entire team [(3)](#3)
- Superheros are bad - The fact that such developers exist its detrimental to the culture of the company [(4)](#4)

## New data is starting to emerge

At Accelerate.io we are running our technical assessments as controlled experiments.
We are doing this in order to reliably compare developer productivity. I will go into more details in the next section.

It is not just us, other people have also started measuring productivity.
Steve Fenton recently wrote an article [(5)](#5) where he shares the data he had collected by tracking his team over 12 months. He worked out that:
> Unsurprisingly, the less experienced programmers take a lot longer to deliver features than the experienced programmers. About ten times longer, which bears out the concept of a 10x programmer. This leads to the cost difference.

## The Accelerate.io "experiment"

How do you create a controlled experiment where you look at developer productivity?

Our take was to try and **simulate a couple of development cycles in a controlled environment** and get different developers to go through exactly the same flow.

This eventually took the form of a coding challenge with 5 rounds designed in such a way that everything translates into time:
- good code helps implement new features faster, it has multiple incremental requirements that put a lot of pressure on the design
- bad code will translate into time penalties

> With this experimental setup we are describing quality code as code that is able to cope with future requirements.

By translating everything into time, we now have a consistent metric which we can measure.

In order to not favour anyone, we used a domain that is well known and we allowed the developers to use their own tools.

This is how a result looks like. You can see the time distribution and the penalties in red:
![Incremental Requirements Coding Challenge](/content/incremental_requirements.png)

## The audience

A total of 65 software developer professionals have currently taken this coding challenge.

The challenge has been used under two circumstances:
1. Developers working for a software company, to form the company benchmark
2. People applying for development roles at the previously mentioned software companies


## Results

Let's look at the extremes:

| Fastest time  | Median time   | Slowest time |
|:-------------:|:-------------:|:------------:|
|1h 34m         | 4h 44m        | 13h 19m      |

We immediately notice the huge difference in performance between the fastest and the slowest.

> Ok, you got me, it is not 10x but it is more like **8.5x**.

Considering the limited scope of the experiment, I would not have expected to see such a difference.

Now, let's look at the performance distribution:
![Distribution of challenge time](/content/distribution_of_challenge_times.png)

You immediately notice that the majority of people take around 4-6 hours to complete the challenge.
If we compare this with the top performers we get a **3x difference**.

It is fair to assume that this is what most of the developers will experience in their day to day lives.
This means that the majority of developers are able to achieve at least a 2x improvement through practice and training.

> I am regularly seeing 2x and 3x differences within the **same company**.

Here is how a usual company benchmark looks like:
![Within company distribution](/content/within_company_time_distribution.png)


## Raw data

If you want to dig deeper, you are invited to have a look at the raw data yourself:
- [Accelerate report](http://report.accelerate.io/CHK/pdemo/?candidate=dvwr01&&rangeFrom=0&rangeTo=300)
- [Data CSV](http://report.accelerate.io/CHK/pdemo/config/results.csv)

## Limitations

As with all experiments this is an approximation of the real world and it is limited by its nature.

The main limitations are:
- code quality is transformed into time by using incremental requirements, this does not cover all possible quality aspects
- we only looked at individual productivity, but software development happens in the context of a team
- we only focused on the act of writing code, but a developer is also involved in deployments, QA and architectural decisions


## Discussions

It looks like 10x developers exist but are rare.
For me, the more interesting find is that there is so much scope for improvement within existing teams.

> Through appropriate training and by recruiting for developers that can deliver, a team could become 2x more productive.


It is surprising that a limited, 4h coding challenge, highlighted such a difference in developer performance.
Imagine if we were to quantify all the other skills a developer might have:
- ability to work with legacy code
- team knowledge sharing
- understanding of web architectural patterns
- deployments and configuration management
- security and performance monitoring

> I can speculate that a master developer could be as much as 30x more productive than a junior member of the team.

## Help us grow the data set

People that take the challenge gain unrestricted access to the report and can see the source code and code casts of all the other participants.

If you are curious about how you or your team will perform, free of charge, give me a shout at julian.ghionoiu@accelerate.io.


&nbsp;

---

#### References
<a name="1">1.</a> https://www.techopedia.com/definition/31673/10x-developer
<a name="2">2.</a> Laurent Bonsavit debunks the myth in his book "[The Leprechauns of Software Development](https://leanpub.com/leprechauns)"
<a name="3">3.</a> "more common way to be a 10x programmer: generate technical debt at a rate that requires ten other developers to clean up the mess." - Brian Craft
<a name="4">4.</a> https://modelviewculture.com/pieces/hacker-mythologies-and-mismanagement
<a name="5">5.</a> https://www.stevefenton.co.uk/2018/03/the-value-of-experience-in-programming/