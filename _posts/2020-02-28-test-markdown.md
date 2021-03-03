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



# Methodology
For a Wikipedia article, we created the list of factoids for each of its revisions. Let’s say there are $n_i$ revisions in article $a_i$, then for each revision $R_j$, where $j ∈ {1, 2, 3, 4, ...,n_i }$, we create a list of factoids ordered in the way they were present in the revision $R_j$. We call this list as $F_j$. We
focus our analysis on the placement of the factoids in the Wikipedia articles.

We first obtain the vector embeddings of each factoid using Universal Sentence Encoder then we find the similarity between the embedding of two factoids using the Cosine Similarity, which is defined as a metric used to measure how similar two records are irrespective of their size. It gauges the cosine of the point between two vectors anticipated in a multi-dimensional space.

## Dataset
we have taken a random sample of 500 articles out of 5000 most frequently edited English Wikipedia articles collected in April 2020.

## Results

In 458 articles out of 500 (91.6%), we observe average sentence similarity positively correlated with the revisions, whereas 42 articles (8.4%) show a negative correlation. The results show that in the majority of the articles, the average semantic similarity increases with revisions. See the figure below for illustration.

![Crepe](https://github.com/descentis/descentis.github.io/blob/master/assets/img/fig1.png){: .mx-auto.d-block :}

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
