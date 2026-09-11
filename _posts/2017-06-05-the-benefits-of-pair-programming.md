---
title:  "The Benefits of Pair Programming"
#excerpt: "Words go here"
#categories: 
#  - tests
tags:
  - programming
  - software development
  - collaboration
---

During my college internship, I was one of two programmers who worked on the proof of concept for a game called [_Hug The Line_](https://github.com/beandrake/Hug-The-Line). We experimented a good deal to figure out which software development methodology would be the most effective for our specific project, and in the end we decided to use an agile methodology loosely based on [Extreme Programming](https://en.wikipedia.org/wiki/Extreme_programming).

One of the most interesting aspects of Extreme Programming we adopted was pair programming. This meant that almost all of our code was written as a team; while only one of us would typing at any given time, we were usually both engaged in dialogue about what to do next or how to do it.

To some this might seem like a waste of resources. Why use two programmers to accomplish a single task? Couldn't they get twice as much done separately? In theory that's certainly possible, but based on my experience I think that pair programming offers some key advantages.

![image-center]({{ "/assets/images/Swiss_cheese_model.png" | relative_url }}){: .align-center}
{: style="text-align:center"}
<sup>A visual representation of the Swiss Cheese Model, with three slices of cheese with different holes, with lines passing through holes in the cheese or being blocked where there is no hole.</sup>

To understand why, let's look at the [Swiss Cheese Model of Accident Causation](https://en.wikipedia.org/wiki/Swiss_cheese_model). This model conceptualizes systems as multiple slices of Swiss cheese, where each hole is a possible point of failure; if a single linear hazard can pass through every layer without being blocked, an incident occurs. By aligning multiple systems with differing points of failure, the likelihood of a failure falling through the entire stack of cheese is reduced.

Leveraging this model, we can think of every programmer as a slice of cheese. Because we are human and capable of making mistakes, each slice will have holes. And by collaborating with a different slice of cheese, we can mitigate the possibility of errors. If I make a mistake, my programming partner has a good chance of catching it. These mistakes can range from the simple (using the wrong variable in an equation) to the major (programming unnecessary systems due to a misunderstanding). While these errors could certainly be discovered during code reviews, why wait that long? Pair programming nips these issues in the bud, minimizing the time spent exacerbating problems and subsequently correcting them.

And this same phenomenon also applies to problem solving. Having two programmers focused on the same challenges frequently resulted in better solutions because each of us would have different ideas about the best way to solve problems, and generally one person's idea was better. The more complex or high level the process, the more likely that we would disagree, at which point we would have brief, productive arguments to determine how best to proceed.

These arguments were always incredibly fruitful. I would even go so far as to say that having respectful arguments feels like an integral part of pair programming. But how do you keep things constructive as opposed to antagonistic? Looking back, I think there are a few reasons why our arguments were always so productive:

1. **We both genuinely respected and cared for each other.**

   Making a point was never more important than the other person's feelings; kindness and tact were always maintained.

2. **We were both of similar skill levels.**

   Because of this, neither of us was inclined to defer to the other's judgment due to seniority. Similarly, neither of us was ever tempted to think that our experience made our own judgment superior.

3. **Our goal was always to find the best solution, never to "win" the argument.**

   If someone wins, someone else loses; this dynamic has no place on a collaborative team. Both of us wanted not only what was best for the project, but what was best for each other. Often neither of us started the argument with the best solution; rather, we would discover it together over the course of our debate.

4. **We listened as much as we talked.**

   It's really a corollary of the above, but if you're not truly listening to someone else's ideas, you rob yourself of the opportunity to learn anything. No matter how right I thought I was, when my partner talked, I _wanted_ her to convince me — and she often did.

5. **We both had very different perspectives.**

   This is where I think the core value of arguments — and pair programming — comes from. The more identical your cheese slices, the more redundant they are. Both of us had wildly different backgrounds and perspectives, resulting in a great deal of accident coverage as well as a wider breadth of creative solutions.

Pair programming worked great for us on _Hug The Line_. If the chance ever presents itself, I'd love to do it again.