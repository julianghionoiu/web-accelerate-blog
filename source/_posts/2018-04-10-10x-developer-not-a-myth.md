title: The experiment that proves 10x developers exist
category: High-Performance Teams
date: 2018-04-10
tags:
- Data-Driven Article
- Skills-Based Hiring
thumbnail: https://s3.amazonaws.com/ptsteadman-images/helloworld.jpg
lede: "
TODO How would you design an experimental setup to

The 10x developer exists and I have data to prove it.
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

In order to not favour anyone, we had to use a domain that is well known and allow the developers to use their own tools.

**TODO: Image with 5 incremental requirements**

## The audience

People that currently work in software companies (benchmark)
People that are applying for experienced software developer roles.


## Results


**TODO: Image with time distribution**

**TODO: Diff between slower and faster**

**TODO: Diff within companies**


## Raw data

**TODO: Link to article**
**TODO: Link to data CSV**

## Limitations

As with all experiments this is an approximation of the real world and it is limited by its nature.

The main points are:
- we only look at individual productivity, but software development happens within the team
- we only focused on the act of writing code, but developing software also involves deployments and architecture
- the participants are allowed to take breaks (pause and resume) and this effect has not been quantified


## Summary


## Next steps


#### References
<a name="1">1.</a> https://www.techopedia.com/definition/31673/10x-developer
<a name="2">2.</a> Laurent Bonsavit debunks the myth in his book "The Leprechauns of Software Development"
<a name="3">3.</a> "more common way to be a 10x programmer: generate technical debt at a rate that requires ten other developers to clean up the mess." - Brian Craft
<a name="4">4.</a> https://modelviewculture.com/pieces/hacker-mythologies-and-mismanagement
<a name="5">5.</a> https://www.stevefenton.co.uk/2018/03/the-value-of-experience-in-programming/