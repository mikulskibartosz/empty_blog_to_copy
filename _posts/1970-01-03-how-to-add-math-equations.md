---
layout: post
title:  "How to put math equations into your articles"
tags: [ 'Tutorial', 'Jekyll' ]
description: "Some description..."
featured: false
hidden: false
excerpt: "Some description..."
---

This project is configured to use MathJax library which displays math equations using JavaScript, and works (or at least should work) in all modern web browsers (including mobile browsers).

To add a math equation, put the following code in the article content:

```js
$$P(A\mid B) = \frac{P(B \mid A) P(A)}{P(B)}$$
```

This produces the following output:

$$P(A\mid B) = \frac{P(B \mid A) P(A)}{P(B)}$$

The math equation code starts and ends with `$$`. Inside the `$$` characters you can use the LaTeX code.