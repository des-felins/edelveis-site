---
title: "From Cold Starts to Escape Velocity: Three Practical Ways to Accelerate Java Services"
date: 2025-05-10
tags: ["Java", "Performance"]
featureimage: "talks/startup-cover.png"

---

## Summary

Java applications can be incredibly performant in the long run, but their weakest spot is at the startup as they may take seconds to start and minutes to warm up. During that period, they consume more memory and process fewer requests. It gets even worse when you restart the application hundreds of times a day or when you need faster rollout for faster feedback loop.

Luckily, there are not one but three approaches to dealing with this problem:

- GraalVM Native Image

- Coordinated Restore at Checkpoint

- Project Leyden

They all differ in terms of ease-of-use and impact on startup/warmup time reduction. We will explore them one by one unveiling caveats and opportunities they offer so that you can choose a perfect solution for your project.


## Useful Links
### Slides
https://code-with-bellsoft.github.io/java-startup-voxxed-days/1
### Recordings
{{< youtube id="ZEl5n1-98qw" title="Java startup voxxed thessaloniki" >}}
### Upcoming Events
No upcoming events.