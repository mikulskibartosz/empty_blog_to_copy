## The main page of your new blog

You can change it by modifying the index.md file

You can use markdown and html in all your files (this one, blog posts, templates).
If you are not familiar with Markdown, I recommend this tutorial: <a href="https://daringfireball.net/projects/markdown/syntax">https://daringfireball.net/projects/markdown/syntax</a>

## How to use the blog

{% for post in site.posts reversed %}
{% include postlink.html %}
{% endfor %}

## One more thing

After you remove the demo articles, you may want to reverse the order of blog posts in the list.

To do it, open the `index.md` file and remove the `reversed` word from this block of code:

```
{% raw %}
{% for post in site.posts reversed %}
{% include postlink.html %}
{% endfor %}
{% endraw %}
```