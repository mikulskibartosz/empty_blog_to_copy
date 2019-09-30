---
layout: post
title:  "How to add code, images, and YouTube videos to your articles"
tags: [ 'Tutorial', 'Jekyll' ]
description: "Some description..."
featured: false
hidden: false
excerpt: "Some description..."
---

## Include code into an article

You should put your code either inside: `` `some code here` `` (if that is a one line of code), or use code blocks

````markdown
```python
import pandas as pd

other code
```
````

this will produce the following content:

```python
import pandas as pd

other code
```

## Add images

### Using Markdown

When you put this Markdown in your article:

````markdown
![Golden retriever eats pigs foot](https://upload.wikimedia.org/wikipedia/commons/a/af/Golden_retriever_eating_pigs_foot.jpg "A picture of a dog")
````

you are going to get:

![Golden retriever eats pigs foot](https://upload.wikimedia.org/wikipedia/commons/a/af/Golden_retriever_eating_pigs_foot.jpg "A picture of a dog")

### Using HTML

Of course, you can also use HTML which gives you more control.

```html
<img src="https://upload.wikimedia.org/wikipedia/commons/a/af/Golden_retriever_eating_pigs_foot.jpg" alt="Golden retriever eats pigs foot" style="width:200px; height: 300px;">
```

<img src="https://upload.wikimedia.org/wikipedia/commons/a/af/Golden_retriever_eating_pigs_foot.jpg" alt="Golden retriever eats pigs foot" style="width:200px; height: 300px;">

## Add YouTube video

To add a YouTube video:

1. Open the video you want to add in the browser.

2. Click the share button

3. Select the Embed option and copy the code

4. Put the code as HTML in the content of your blog:

```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/ClIdWYE9wRU?start=10" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```

<iframe width="560" height="315" src="https://www.youtube.com/embed/ClIdWYE9wRU?start=10" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---
