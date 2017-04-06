---
talk_id: css-and-the-first-meaningful-paint
title: "CSS and the first meaningful paint"
---

<p>
To render a webpage browsers needs to go through the complex dance of networking, parsing and painting before any content can be displayed to your user. Over the years, we've developed mechanisms and hacks to aid the browser at each stage of this process, but these have always come at some cost or trade-off.
</p>
<p>
How can we utilize modern web platform features to load our CSS as fast as possible? Should we still be inlining our critical content into the document or instead, how can HTTP/2 server push and Service Workers help us?
</p>
<p>
In this talk we will take a journey exploring the current, past, and future best-practices for loading CSS in the browser and how we can achieve a first meaningful paint within 1000ms. Ultimately creating a faster, more resilient experience for our users.
</p>
