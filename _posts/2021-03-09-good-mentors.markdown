---
layout: post
title:  "Mentors, and how to find them"
date:   2021-03-09 20:00:03
categories: tech
published: true
---

I find that the importance of finding, and having good mentors if you want to advance in your tech career is highly underrated. You can code all you want, but if you do not have someone who points out best practices and suggests better ways of implementing something, your progress will be stalled and learning will be slower. Sometimes when you are new to a tech stack you might also not know what to search for in order to develop the feature you want/bug you are coming across, so it helps if someone points you in the right direction.

<em>How does one go about finding good mentors, however?</em>

The best way to do this is to get into a good tech/developer team. At all of the companies I've worked at, for example, I've noticed that there's at least one person in the team who is an excellent engineer and communicator. My strategy thus has been to learn as much as possible from this person. This is a form of implicit mentorship that comes with working at a good team. You can ask thoughtful questions, get feedback and potentially, in the first few months, ramp up on your knowledge of the product you are developing with the help of this person. These engineers are usually not present very prominently on the web (through writing or speaking publicly), so getting access to them at work is a great opportunity for mentorship that is not accesible to you otherwise.

Pull/merge requests for your code are also great avenues where you can utilize the knowledge of the rest of the team. Let's take a small but concrete example.

A month or so ago, I had to refactor some code to improve on 3 different types of options for different components of the application which had some similarities between them. I converted the Python dictionaries into Pydantic models and modularized them. However, I had used inheritance to group the common functionality between the 3 options. When I made a merge request for this change, I got a suggestion for using composition instead of inheritance, which totally made sense ! The option types were not necessarily parent-children relationships (i.e. there wasn't an is-a relationship), but included components of other option types (i.e. there was a has-a relationship). However, this wasn't something I had thought of and therefore getting that feedback really helped the code quality, as well as clarifying a real use case of an important concept. 

It's not always easy to find good mentors at work for everyone. For example, what if you aren't employed currently, or are still looking for that ideal job, or are trying to transition to a particular area/domain in your tech career?


In that case, I recently read about a technique that could be implemented. It's called "Pick Up What They Put Down", which you can read in detail [here](https://www.swyx.io/puwtpd/). It basically suggests that you get involved with something recent that someone in the tech community made/developed and try to make meaningful contributions towards it, i.e. write about it, or create tutorials for it, or try to fix bugs for it. Then, by blogging/tweeting about it or by virtue of working on it over time, you receive mentorship from the creator or the tech community. This technique is something I personally haven't tried yet, but I can see how it can be very useful provided the right amount of effort goes into it.

At the end of the day, people learn best from people. This is why I think finding good mentors is not only an option, but a requirement, as they play a crucial role in the growth of your skills/tech career.

