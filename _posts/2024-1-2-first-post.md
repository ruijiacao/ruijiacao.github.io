---
layout: post
title: An Interesting Application of Vitali Covering 
date: 2024-1-2 
description: 
tags: topology
categories: math
related_posts: false
---

---
A few days ago, I found an interesting problem from the 2018 Miklós Schweitzer competition.

**Problem:**
Let $$S\subset \mathbb{R}$$ be a closed set and $$f:\mathbb{R}^{2n}\to \mathbb{R}$$ be a continuous function. Define a graph $$G$$ as follows: Let $$x$$ be a vertex of $$G$$ iff $$x\in \mathbb{R}^{n}$$ and $$f(x,x)\not\in S$$, then connect the vertices $$x$$ and $$y$$ by an edge in $$G$$ iff $$f(x,y)\in S$$ or $$f(y,x)\in S$$. Show that the chromatic number of $$G$$ is countable. 

The key to this problem is the observation that for any $$x \in V$$ there exists $$\delta_x > 0$$ such that the open ball $$B_{\delta_x}(x) \subseteq V$$ and $$B_{\delta_x}$$ is an independent set in $$G$$.   
