---
layout: post
title: "Create m x n array initialized with 1"
date: 2014-06-15 09:29:13 +0530
comments: true
categories: 
- Machine Learning
- Array 2D
---

## Initialize Array2D with 1 ##

In python numpy,

{% codeblock lang:python %}
tile(1, (5,2))
{% endcodeblock %}
will give

{% blockquote %}
> array([[1, 1],
>    [1, 1],
>    [1, 1],
>    [1, 1],
>    [1, 1]])
{% endblockquote %}

similarly in F#

{% codeblock lang:fsharp %}
Array2D.init 5 2 (fun i j -> 1)
{% endcodeblock %}

will give
{% blockquote %}
> val it : int [,] = [[1; 1]
>                     [1; 1]
>                     [1; 1]
>                     [1; 1]
>                     [1; 1]]
{% endblockquote %}