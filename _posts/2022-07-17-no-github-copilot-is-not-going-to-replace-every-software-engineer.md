---
title: No, GitHub Copilot is not going to replace every Software Engineer
layout: post
date: "2022-07-17 14:12:50"
categories: opinion
author_name: Blake Helms
read_time: 6
---
I have seen a lot of articles lately that have the take, ["GitHub Copilot is going to replace all Software Engineers" or "Why become a Software Engineer now that AI can do your job?"]("https://medium.com/data-driven-fiction/dear-developers-thank-you-for-github-copilot-also-youre-fired-c73b65e3565f)  I can understand how the layperson may hear a description of [GitHub Copilot](https://github.com/features/copilot) or see a [demo](https://www.youtube.com/watch?v=edSZh-tpTIk) and think that the AI must be knowledgeable, but to those who understand the job of Software Engineer, we can quickly see the benefits and the limitations of AI written code.

## Why GitHub Copilot can't replace Software Engineers right now
In this section, I'm going to outline the reasons that the idea that GitHub Copilot and similar tools are going to replace all Software Engineers and 

### Understanding the problem you are trying to solve
There is an old joke "You can never replace Software Engineers with AI because it would first require the business stakeholder to be able to articulate what they want." In my career as a Software Engineer, this was always the biggest challenge we faced. It has not been unusual to get only a vague sentence or two to describe complex behavior or worse, ["I'll know it when I see it."](https://en.wikipedia.org/wiki/Duck_test#Elephant_test). Additionally, I have often received requirements counter to previous requirements and must work to try and develop a solution within those constraints. These types of requirements are challenging to communicate to even the most powerful AI currently available.

### The first role of Software Engineers is not to code but to solve problems
[I volunteer teaching High School Programming](https://www.microsoft.com/en-us/teals), and one of my first lessons is that a Software Engineer's job is to solve problems, and sometimes those problems may be best solved by writing NO code at all. I was once hired as a consultant for a company looking to build a pretty expensive software solution. Over the next couple of hours of us discussing the requirements, it became very apparent that we could eliminate the entire project with a few minor changes to their process. While it meant I didn't get to bill for the software project, it was the right thing for them, and I valued providing the BEST solution over the most profitable one.

As it stands, tools like GitHub Copilot don't have that additional context and can't suggest those changes. It's a very skilled hammer and sees every problem as a nail.

### Experience has shown that GitHub Copilot can introduce subtle bugs
I've been using GitHub Copilot since the early betas, and I've been highly impressed with the suggestions that it makes but often will suggest baffling code snippets that include extraneous logic and occasionally ones that compile but are wrong in some subtle way. You have to understand the code it generates to catch some of these bugs on the first pass, and I've watched several people happily accept the suggestion and move on, never noticing that it just broke the logic of the code.

Some examples of things that it might suggest but could be wrong:
1. Properties with the wrong types.
2. Conditionals with the wrong condition logic.
3. Extra properties that aren't needed.
4. Classes and/or methods with the wrong scope.
5. Methods that require external frameworks that you don't use.
6. Outdated syntax.

### GitHub Copilot is only as good as the code the models were trained on
Theodore Sturgeon once observed of contemporary Science Fiction, "[Ninety percent of everything is crap.](https://en.wikipedia.org/wiki/Sturgeon%27s_law)" This has often been applied to other areas, including software. While I think 90% is a high number, there is a lot of bad code in the wild and much of it was used when training the models. That is not to say that it will always output bad code, but sometimes it will. The model has developed connections that will, in many cases suggest the best code, but just as often it will suggest code that can be either bad or at the very least "[smell](https://en.wikipedia.org/wiki/Code_smell)."

It takes a seasoned Software Engineer to spot the difference. If you blindly accept every suggestion, you will almost certainly end up with sub-par code.

## All that said, you should give GitHub Copilot a try
I've spent the bulk of this article highlighting the weaknesses of AI-driven tools like GitHub Copilot, but now I'd like to dive into why I think Software Engineers SHOULD use it.

### It automates a way a lot of mundane, repetitive coding
Programming is not all complex logic and clever tricks. It's a lot of coding, very simple structures, and writing mundane code. GitHub Copilot excels at this. Create a new class and start writing the first property, and will often suggest the rest. It's not perfect as stated above, but it's surprisingly accurate.

### It helps you remember how to do things that you don't do very often
There have been many times that I needed to perform an operation or utilize a method. I can't remember the method's name or exactly how to do something in a language and where I would have previously "Googled" it or copied and pasted from StackOverflow. I was pleasantly surprised it suggested just what I needed to do. It allowed me to stay in the moment and not break flow.

### I find it extremely helpful with determinant "assert statements" in unit tests
One area that I have found GitHub Copilot extremely useful is in writing the "assert statements" in unit tests. As soon as I start writing one, it will suggest additional asserts, and they have frequently been asserts I had not considered. It's like having a very perceptive coding partner.

### Its suggestions can help spur ideas when you get stuck
Sometimes you get stuck writing a particular piece of code and GitHub Copilot can often offer suggestions that either solve a problem or at least help point you in the right direction.

## Final Thoughts
GitHub Copilot is a tool and can be very helpful in increasing your productivity but it's not a panacea. Think of it more like "Cruise Control" in your car which helps by taking over holding your speed on long stretches, but it's not "auto-pilot." You hold the course and it assists. As a Software Engineer, you still need to understand the problem and determine the solution but the tools can help you get to your destination with less effort.

Finally, do I think there will ever be a tool that could replace a programmer? Yes, on a long enough time scale I think it's almost certain. The evidence I've seen points to that being a ways off and may require new approaches to AI and Machine Learning, but who knows, we could be just one breakthrough away. When that time arrives, we will know it, but as of today, good Software Engineers are needed more than ever!
