---
layout: post
title: Tracing the Factoids
subtitle: Accepted in The Web Conference - 2021 (Wiki Workshop)
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [Wikipedia]
comments: true
---

We investigate the impact of gradual edits on the re-positioning and organization of the factual information in Wikipedia articles. Literature shows that in a collaborative system, a set of contributors are responsible for seeking, perceiving, and organizing the information. Based on our analysis, we show that in a Wikipedia article, the crowd is capable of placing the factual information to its correct position, eventually reducing the knowledge gaps. We also show that the majority of information rearrangement occurs in the initial stages of the article development and gradually decreases in the later stages.



## Methodology
For a Wikipedia article, we created the list of factoids for each of its revisions. Let’s say there are $n_i$ revisions in article $a_i$, then for each revision $R_j$, where $j ∈ {1, 2, 3, 4, ...,n_i }$, we create a list of factoids ordered in the way they were present in the revision $R_j$. We call this list as $F_j$.
# Dataset

Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
