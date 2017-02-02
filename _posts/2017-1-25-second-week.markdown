---
layout: post
title: 'Ad Specs Page - "All By Grand Design"'
---

[//]: # (Planning/Wireframes)
<h3>The Problem</h3>
It's difficult for Sales and Ad Ops to provide product specs and examples to clients. Doing so requires them to manually aggregate the ad specs and ad examples applicable to the client (typically from past emails, campaigns, etc.), organize them into some presentable format and then email it to them.

<h3>Primary Users & Use Cases</h3>
  <ol>
    <li><strong>Sales:</strong> To easily provide details on and examples of specific placements that a client is considering; a supplement to the media kit that gets more granular, not a replacement for the media kit.</li>
    <li><strong>Ad Ops:</strong> An easy to link site that provides technical details, due dates, and examples for clients. Source of record for specs of our placements.</li>
    <li><strong>Customers / Clients:</strong> Easily accessible; self-service reference documentation </li>
  </ol>

<h3>The Solution</h3>
Design and publish a single page app that includes product descriptions, specs, placement examples, and any other reference information that will help support client engagement efforts from Sales and Ad Ops.

Whether the solution involves one page or multiple pages, clients should be able to easily understand what placement they are providing specs for; Sales and Ad Ops must be able to share links to specific placements to avoid any client confusion about what placement they need to be aware of.

<h3>Planning</h3>

First, I had to do some strategizing on how many links would be created for the page and how they all would fit together. Figuring out if some of these products could be consolidated into fewer links, so that the UI could be more intuitive to the user and take up less screen real estate. Too many links on the nav bar would look cluttered. The more navigation links a page has, the more overwhelming it seems, and the less likely users will figure out what to do:


![product planning](/images/ad-spec-products-2.JPG)


After getting a more concise product copy from the Sales/Ad Ops team, I sketched a wireframe of the layout utilizing a top nav bar. I broke up the products into fitting categories. Each top nav button would take you to a listing of the products in that category, and each listing would have "Details" button that would drop down the specifics with each of the products:

![Ad Specs nav layout](/images/ad-spec-page-layout.JPG)


This is the product detail page I envisioned for each product listing. I thought the user/client would want to see a visual example of the ad first, then all the technical specifications after the visual:

![Product details page](/images/product-details-page.JPG)


After some further thought and conversations with my Creative Director, I revised my pen and paper mockup to have all the specifications and information on top before the visual examples because most of the clients that would use this page already know what the ads/examples would look like. The most important in visual hierarchy for this user case would be the technical specifications, so that they can quickly scan and see all the information they need. The visual examples placed at the end to supplement the information they just read:

<h4>Web mockup:</h4>
![Product page web](/images/product-page-layout-web.JPG)
<h4>Mobile mockup:</h4>
![Product page mobile](/images/product-page-layout-mobile.JPG)
