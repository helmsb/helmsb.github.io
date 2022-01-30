---
title: Failure IS an Option
layout: post
date: "2019-11-20 12:24:31"
categories: software-best-practices
author_name: Blake Helms
read_time: 7
---

Gene Kranz was a NASA Flight Director who served from the first days of the Mercury missions all the way into the Space Shuttle era. He was immortalized in the cinematic depiction of the real life events of “Apollo 13.” In it, Kranz, played by Ed Harris [^1] utters one of the most memorable lines in the movie, “Failure is NOT an option” and when the stakes are the lives of the 3 men in the badly damaged command module I can certainly not disagree. However, for many of us the stakes are much lower. Most of the software we write is not tied to orbiting space craft, nuclear warheads or medical life support hardware 2 and thus failure IS and SHOULD be an option.

I’ve been in software development professionally for over 15 years. During this time a lot has changed in how we write software. I’m not just talking about the tools and the languages but the methodologies as well. When I began my career we were very much a “Waterfall” based shop. Over time we tweaked that methodology but fundamentally it remained the same. Then, like a great lightning bolt from the sky came “Agile.” It was going to solve all of our problems. Never again would software be late or requirements go unfulfilled. All we had to do works work “Agilely” by doing a very specific set of pre-determined ceremonies and actions and like magic all would be right in the world. Needless to say, that didn’t happen.

In many cases things were worse. The requirements were less defined so our customers were upset. We planned all the work carefully and then worked feverishly all day, most nights and nearly every weekends in order to fulfill the plan that was unrealistic when we devised it.

## What went wrong? Wasn’t “Agile” supposed to save us from all this?

In the previous paragraphs, I capitalized “Agile” to differentiate it from true “agile software development.” “Agile” has gone from an idea, to a buzz word, to a brand. All along the way it has picked up new cruft, like a snowball rolling down a hill. Consultants have come and gone, companies have risen and fallen in the search to package, promote and sell “Agile” to a waiting public. The problem began almost immediately with a misconception and a mangling of the concept. The word “agile” as layed out in the “Agile Manifesto” is an adjective not a noun. This might seem like an unimportant distinction but it’s the cause of decades of strife.

Agile software development doesn’t dictate whether you use Kanban or Scrum or what time you need to have a “Daily Stand-up” or if you should have one at all! Instead it gives you the permission to measure things and determine if it’s effective for you and your team. This is the key point I hope to make in this post.

There is no one size fits all solution. To truly work agilely, you need to develop your practices by measuring them against the principals you want to live by and have an open and honest discussion within your team about whether or not what you’re doing is effective based on the success criteria you’ve decided upon.

Crucially, however, you MUST be willing to admit when an experiment was a failure, learn from it and develop a new experiment based on those findings.

There can be a number of challenges that can hinder this mindset. Let’s discuss a few:

### The Sunk Cost Fallacy

This concept is basically that when evaluating whether or not we should continue a practice we are often biased toward continuing due to the high costs that have already been incurred. It can also serve as a way to “defer” admitting failure by assuming that since the full cost hasn’t yet been realized failure has not yet occurred. Instead you should always base your decisions on the actual data and be willing to accept your loss and work toward a better solution

### Top Down Management

In many cases the culture of the company can create a situation where individual teams don’t have the necessary autonomy to make the decisions on their own and instead are forced to stay within in a strict framework of operation 3.

### Complacency

In some cases you may be succeeding in spite of bad practices. Former President of Pixar, Ed Catmul once said “Success hides problems.” This may be the case in your organization. When things are going well it’s difficult to look introspectively and create experiments. No one wants to rock the boat. You must fight this instinct and always be willing to admit that there are ways that you can improve.

### Apathy

You can only have real change in an organization of the members of that organization care about what they are doing and are looking for ways to improve and grow. This is not only those at the top but also your fellow team-mates. Everyone has to be onboard with improving which means they also have to be onboard with admitting failure.

### Pride

Which brings us to probably the hardest one of all. Sometimes the one person that it is most difficult to admit failure to is yourself. The very though of failing at something makes you sick but failure is how we learn and grow and admitting to that failure is the first step in unleashing that power. You have to stop tying your self worth to the actions you perform. A failure of an experiment doesn’t define you instead it is the first step in helping you improve.

### How do we begin?

First, determine an area that you are looking to measure and improve. Don’t try and solve every problem all at once. Pick something isolated and small. Begin by breaking down the problem using techniques like:

1. The Five Why’s
2. Mind Maps
3. A3 Analysis

*Note: I’ll be going more in-depth into these techniques in future posts.*

Next, determine which metrics you are going to use to measure success or failure. Be realistic. Don’t set unattainable goals but don’t sand bag and set goals that are too easy either. These metrics should also correspond to real indicators that give a sense of whether or not you’ve improved the situation and not simply an easy way to “game the system” (ie. “Don’t juke the stats”). An example of this might be meeting the criteria of “reduce errors by 10%” by simply removing the error logging code.

Once you’ve determined what you want to improve, what metrics are important and how you will measure success or failure you need to determine a time-box to run your experiment then put it into practice.

The final step which the purpose of this post is to review your metrics and determine whether or not you have been successful. If you were, then great, on to the next issue. If not, then you need to have an open and honest discussion with your team and the stakeholders and review what you’ve learned and use these findings to drive the next experiment.

This cycle is sometimes called PDSA (Plan, Do, Study, Act) and it’s probably the most important practice you can add to your organization to drive a culture of agile development. Basically you should never rest on your laurels but instead constantly be experimenting and looking for ways to improve.

Positive change can only happen when you decide to take a hard look at what you’re doing and having the courage to admit failure.

Failure IS an option!

[^1]: A truly masterful performance. How he didn't win an Oscar; I will never understand. 

