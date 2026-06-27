---
title: "Use Cache to Stop re-running work in your pipelines"
url: "https://www.union.ai/blog-post/use-cache-to-stop-re-running-work-in-your-pipelines"
date: "2026-06-17"
author: "Sage Elliott"
feed_url: "https://flyte.org/blog"
---
This practical guide introduces task caching in Flyte 2, demonstrating how to prevent redundant pipeline executions. Developers can use the flyte.Cache object with an @env.task decorator to automatically skip re-running tasks when inputs remain unchanged, helping with common scenarios like failed training runs and hyperparameter tuning iterations.
