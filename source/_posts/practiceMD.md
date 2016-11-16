---
title: PracticeMD
date: 2016-11-14 18:03:37
categories:
- MD
---

## Block Quote 
{% blockquote %}
content 這邊插入文章的引言，包含作者、來源和標題。
{% endblockquote %}

{% blockquote David Levithan, Wide Awake %}
Do not just seek happiness for yourself. Seek happiness for all. Through kindness. Through mercy.
{% endblockquote %}

{% blockquote Seth Godin http://sethgodin.typepad.com/seths_blog/2009/07/welcome-to-island-marketing.html Welcome to Island Marketing %}
Every interaction is both precious and an opportunity to delight.
{% endblockquote %}

## Code Block
{% codeblock lang:js %}
alert("hello");
{% endcodeblock %}

{% codeblock lang:objc %}
[rectangle setX: 10 y: 10 width: 20 height: 20];
{% endcodeblock %}

{% codeblock _.compact http://underscorejs.org/#compact Underscore.js %}
_.compact([0, 1, false, 2, '', 3]);
=> [1, 2, 3]
{% endcodeblock %}

## jsFiddle
{% jsfiddle shorttag [tabs] [skin] 100% 240 %}

## iframe
{% iframe https://docs.google.com/presentation/d/111WmrqoAQ4DHHupcxy7yrzJ1wq_tRBy54ynqE4eroFc/embed?start=false&loop=false&delayms=3000 100% 400 %}

## Image 
{% img [class names] http://sui.com.tw/wp-content/uploads/2014/11/s4.jpg 600 [height] [title text [alt text]] %}

## Link 
{% link text url [external] [title] %}

## Youtube
{% youtube IMbZfruSE84 %}

