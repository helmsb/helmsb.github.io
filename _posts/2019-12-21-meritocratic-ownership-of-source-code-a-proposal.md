---
title: "Meritocratic Ownership of Source Code: A Proposal"
layout: post
date: "2019-11-20 12:24:31"
categories: software-best-practices
author_name: Blake Helms
author_avatar: blake-avatar
author_url: "/author/blake"
show_avatar: false
read_time: 3
feature_image: post-assets/feature-wilt-chamberlin-granny-shot
square_related: recommend-laptop
---

Recently, a coworker and I were discussing “Inner-sourcing.” Inner-sourcing is when a company utilizes open source principles and practices within the company. One thing we were lamenting was that even as our company works to implement Inner-sourcing, repos are still tied to teams and thus their bandwidth is a limiting factor.

This got me thinking, how could we setup a git repo which was not owned by any one person or team but still had the appropriate gates to prevent bad code from entering? That’s when I had the idea for a new ownership model, “Meritocratic Ownership.”

In this model, credit (for a lack of better terms, we’ll call it ‘Karma’) is awarded to individuals as they contribute. Over time, as their “Karma” increases they have more sway over a repo that has been configured with the “Meritocratic Ownership” model. However, the real power, is pooling Karma to create or accept change as a group. In the next section I will outline at a high-level how I envision this working.

## How does a repo become “meritocratic?”

This model does not replace any of the previous ownership models. This would be something that the original repo owner would have to choose to do. However, once it’s been turned on, it could only be turned off by a community vote.

## What is Karma and how do I accrue it?

Karma, is a credit that is earned when you perform actions that promote the healthy growth of a repo or the community at large.I see three different types of Karma:

**Repo Karma** – This is the highest form. It is awarded as you submit pull requests that are accepted, write tests, improve documentation or other things necessary for a healthy repo.

**Community Karma** – This is awarded as a percentage of your repo Karma. The more you contribute to open source projects, the more Karma you earn and this can be used to give an individual gravitas with newer repos since they have proven their merit. However, this Karma is not as valuable as repo Karma.

**Awarded Karma** – This is a limited supply that can be distributed from one individual to another as a “thank-you” for work. It essentially acts as an incentive to enlist help.

## How is Karma used?

When something happens on a repo that needs approval it is presented to the community. Each action requires a certain amount of consensus in order to be acted upon. For example, accepting a pull request may require 200 Karma for a particular repo. If 4 people who each have 50 Karma review and approve it, the pull request is accepted. Alternatively one person who has sufficient Karma can accept it. This can also be challenged by other contributors in order to keep balance.Another important point is the amount of Karma required for a particular action is based on a formula that is designed to ensure the largest amount of community involvement, similar to Bitcoin.

## Other benefits

While I originally envisioned it for use internally, it would be great for community open source projects as well as reviving once-dead projects. While you can always fork a dead project and revive it that way it is also diluting recognition and raising the barrier to entry.

## Concluding thoughts

This proposal is by no means perfect and I highly encourage you to leave a comment with suggestions or tweet at me @helmsb.
