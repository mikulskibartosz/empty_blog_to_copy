---
layout: post
title:  "How to add a new blog post"
tags: [ 'Tutorial', 'Jekyll' ]
description: "Step by step instructions regarding adding a new blog post"
featured: false
hidden: false
excerpt: "Step by step instructions regarding adding a new blog post"
---

To add a new blog post, you should:

1. Create a new file in the `_posts` directory. The file name must begin with the publication date in format year-month-day and have the `.md` extension.

2. Copy the following code and put it in the top of the file:

```yaml
---
layout: post
title:  "Your article's title"
tags: [ 'Tag 1', 'Tag 2' ]
description: "Some description that will be visible in search engines"
featured: false
hidden: false
excerpt: "I usually just copy the description here ;)"
---
```

3. Below the code, add the content of your article (you can use HTML and Markdown).

4. Remember that you can always run the blog on your own computer to see the changes but if the publication is in the future, you will not see the blog post!

5. To see future blog posts while running the blog on your computer, use this command: `bundle exec jekyll serve --future`

6. If you have any problems, just look at the source file of this blog post or the Jekyll documentation.