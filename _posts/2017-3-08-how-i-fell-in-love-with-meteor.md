---
layout: post
title: How I fell in love with MeteorJS... and then out
---

I learned about [Meteor](https://www.meteor.com/) while I was preparing my final project for the web development course I attended last summer. Our assignment was to construct a fully functional full-stack application using any language of our choosing. I wanted to use something new, while most of the class were content using the programming languages and frameworks we had already been taught. I wanted to challenge myself by learning a new framework without any guidance from my instructors. I needed to prove to myself that I could learn new things on my own, and I did.

## Let’s talk about Meteor
Meteor is a full-stack javascript platform for developing web and mobile applications. It includes a key set of technologies for building connected-client reactive applications, a build tool, and a curated set of [Node.js](https://nodejs.org/en/) packages.

Meteor allows you to develop in one language, Javascript, in all environments: application server, web browser, and mobile device. It uses the same code whether you’re developing for web, iOS, Android, or desktop. You can push new features without app store approval or making your users download a new native app.

Meteor’s server sends data, not `HTML`, and the client renders it. It provides full-stack reactivity, allowing your UI to seamlessly reflect the true state of the world with minimal development effort. You can focus on building features instead of wiring disparate components together yourself.

## Continuing to build with Meteor
After completing the web development course, I began building more personal projects for my portfolio using Meteor. I was amazed with how quickly I could get an application up and working with minimal amounts of code. I was able to focus on building features and streamlining the user interface. Deploying my apps was a breeze using meteor.com, Meteor’s own hosting service built specifically for Meteor apps. Meteor has a very convenient setup and effortless deployment method, using a one-line `meteor deploy` command. I had four applications hosted through meteor.com and the hosting was free… until it wasn’t.

## All good things must end… like free hosting
By the beginning of that spring, Meteor announced that they would start charging for their hosting services and calling it "[Meteor Galaxy](https://www.meteor.com/hosting)". Here’s a portion of the announcement a Meteor staff member made about the reasons they were ending the meteor.com free app hosting:
>We know many of you have enjoyed the Meteor.com free hosting service. In a perfect world with infinite resources, we’d invest to keep this separate legacy infrastructure up and running. Unfortunately, delivering free Meteor app hosting has become extremely expensive and technically unsustainable. If there is a cost effective way to deliver free Meteor app hosting in the future, we may explore it but it’s not on our roadmap. For now, we’re 100% focused on making Galaxy the best deployment option for professional Meteor developers.

*You can read the full statement here: [https://forums.meteor.com/t/meteor-com-free-hosting-ends-march-25-2016/19308](https://forums.meteor.com/t/meteor-com-free-hosting-ends-march-25-2016/19308)*


## The Cost of love
I decided to migrate my apps to Meteor Galaxy pay hosting because I thought: “How expensive could it be?”. I really enjoyed building apps with Meteor and I didn’t want to stop. The rate for Meteor Galaxy pay-as-you-go hosting, they stated, “starts at USD $0.04 per container hour”. My first monthly bill was approximately $35, which seems like a lot for apps that no one was using or visiting besides me. I would have shutdown all my deployed applications on Galaxy hosting if I didn’t need them for my portfolio and to land a development job. The next month my bill was $43, I had to quickly find another option to host my apps for free. Where could I find an option that would combine the ease of the one-line deployment command and the cost of FREE?

My quest to find such a mythical creature in my next blog post.
