---
title: "How We Kept Python and Got Our Speed from Rust"
url: "https://www.union.ai/blog-post/how-we-kept-python-and-got-our-speed-from-rust"
date: "2026-06-15"
author: "Yee Hing Tong, Ketan Umare, Nary Yeh, and Samhita Alla"
feed_url: "https://flyte.org/blog"
---
Union.ai explains how it kept Python as the primary language for users while leveraging Rust to optimize performance-critical infrastructure. The piece details Flyte 2.0's architecture, which uses Rust across the SDK, container runtime, data plane, and controller to handle workloads of tens of thousands of short-lived tasks and multi-gigabyte artifacts shuttled across regions, achieving significant speed improvements without sacrificing the Python developer experience.
