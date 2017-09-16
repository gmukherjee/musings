---
layout: post
title: BMT Big Merge Tracker
subtitle: Conducts clustering
---
What is COSCI?
======

COSCI (COnvex Screening for Cluster Information) is a non-parametric method for ranking and screening non-informative features in large scale cluster analysis problems. Unlike the non-parametric density estimation based screening techniques, COSCI is very
scalable, and can successfully handle datasets with more than one million observations. COSCI discards non-informative features by first computing a clustering score for the clustering tree constructed for each feature, and then thresholds the resulting values.

Perfect Screening Property
---------

COSCI produces a score for each feature, which reflects its relative importance for clustering, and then screens out the features with lower scores. It enjoys a perfect screening property in the sense that under mild regularity conditions on the densities of the features, COSCI screens out all the non-informative features with high probability.

How to use this repository?
----------

This repository holds the scripts that reproduce the analysis in the paper [1]. Send me an email if anything does not work as expected.

References
=======
[1.] [Feature Screening in Large Scale Cluster Analysis](http://www.sciencedirect.com/science/article/pii/S0047259X17300271)    
Banerjee, T., Mukherjee, G. and Radchenko P.  *Journal of Multivariate Analysis, Volume 161, 2017, Pages 191-212, ISSN 0047-259X*

[2.] [Convex clustering via ℓ1 fusion penalization](http://onlinelibrary.wiley.com/doi/10.1111/rssb.12226/abstract)   
Radchenko P., Mukherjee G.   *J. R. Stat. Soc. Ser. B Stat. Methodol. (2017)*


You can write regular [markdown](http://markdowntutorial.com/) here and Jekyll will automatically convert it to a nice webpage.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](http://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

## Here is a secondary heading

Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


How about a yummy crepe?

![Crepe](http://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

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
