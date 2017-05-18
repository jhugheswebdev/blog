---
layout: post
title: Learning the Git workflow of a professional company
---

My position at Industry Dive as a Front-end Dev/Design intern, being my first professional experience in the development field, there are many best practices and standards I learned from working at this company.


## Tupac would approve of this git branch
Among the first things I learned was the Git workflow of a professional company; I was used to my personal projects where I was the only one pushing up to a repo. I didn't have to worry much about version control or merge conflicts. I didn't have to think about branching off someone else's branch, or if I should be branching off of master or develop (the answer is develop, always develop). There were a few missteps I had in the beginning with the company branch naming conventions. While I was learning in my web development course, I would name my branches things like: `trying-stuff`, `will-this-work` or `changes-by-tupac`.


## Learning the naming conventions
The first time I tried using my personal naming convention for a git branch and pushing it up, the person QA'ing my code was like "Nah... That's not how you name branches...". Instead of being a cowboy coder, I decided to view the other devs and designers branches to figure out what the naming convention was.  The company uses an issue and project tracking software called [Jira](https://www.atlassian.com/software/jira) to keep all the developers on task and organized.

Example: ![screenshot 2017-05-18 15 22 43](https://cloud.githubusercontent.com/assets/19156146/26222208/26f856ba-3be7-11e7-89ff-b49bd3e7cf1a.png)
Using a Jira ticket number as a prefix and the description of the feature it's working on i.e.: `TECH-1458-adds-contact-form-to-mobile-menu`


## Sometimes You gotta learn the hard way
In the early few weeks, I had issues with committing work on one branch, that should have been on another. These errant commits had me researching heavily on Google about `git revert`, `git rebase` and `git reset` as not to embarrass myself in front of these seasoned development professionals. The bonus of performing all these Git mistakes is that I was researching solutions like crazy and it made me more knowledgeable about how to fix these errors and about Git in general. It felt good to be working with an organization's private git repositories, being granted an SSH key to get access to their repos. I felt pride that I was a professional developer and all my hard work had paid off.

## Other bumps in the Git road
Of course, there were plenty of growing pains in the first couple of weeks, but nothing that I didn't sort out with more experience. Here are the problems I had and how I worked through them.

* In my second week, I pushed up my commit with several hundred other commits that I didn't want to push. I was in the develop branch when I made changes and not my branch. I then git pulled all the changes made in develop, and when I git pushed, it pushed up everyone's changes from the develop branch.  To remedy that error I deleted that pull request and pushed it as a clean commit. The history still showed what I had done, so that was still embarrassing but at least the error was no longer there.

* There were one or two times where I forgot to switch branches before I made changes for different tasks I needed to accomplish.  I would complete the work on the right branch, forget to checkout to a new branch for the second task and work on that same branch. To solve this, I used `git revert` to revert that commit and push up only the correct commits for the branch.

These early mistakes on Git made me more mindful of what site I was working on, what branch and what feature. I'm now very vigilant in making sure I'm working on the right branch, on the correct feature and using the proper naming conventions.
