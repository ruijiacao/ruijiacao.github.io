---
layout: post
title: 2018 Miklos Schweitzer Competition Problem 1 
date: 2024-1-2 
description: 
tags: Miklos Schweitzer 
categories: sample-posts
related_posts: false
header-includes: |
   \BeforeBeginEnvironment{document}{
      \usepackage[most]{tcolorbox}
      \let\example\undefined 
      \let\endexample\undefined 
      \newtcolorbox[auto counter]{problem}{
        colback=white,
        colbacktitle=black,
        arc=0mm,
        title={Example~\thetcbcounter:},
        bottom=-.7\baselineskip,
        colframe=black,
        fonttitle=\bfseries
   }}
urlcolor: blue
extension: latex_macros
---
```problem
Let $$S \subseteq \mathbb{R}$$ be a closed set and $$f\colon \mathbb{R}^{2n} \to \
\mathbb{R}$$ be a continuous function. Let us define a graph $$G$$ as
follows. Let $$x$$ be a vertex of G iff $$x\in \mathbb{R}^n$$ and $$f(x, x)\not\in S$$. We connect the vertices $$x$$ and $$y$$ by an
edge in $$G$$ iff $$f (x, y) \in S$$ or $$f (y, x) \in S$$. Show that the chromatic number of $$G$$ is countable.
```
