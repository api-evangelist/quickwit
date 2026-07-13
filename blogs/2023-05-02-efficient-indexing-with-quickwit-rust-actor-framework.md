---
title: "Efficient indexing with Quickwit Rust actor framework"
url: "https://quickwit.io/blog/quickwit-actor-framework"
date: "2023-05-02"
feed_url: "https://quickwit.io/blog/rss.xml"
---
At Quickwit, we are building the most cost-efficient search engine for logs and traces. Such an engine typically ingests massive amounts of data while serving a comparatively low number of search queries. Under this workload, most of your CPU is spent on indexing, making our indexing pipeline a crucial component.
