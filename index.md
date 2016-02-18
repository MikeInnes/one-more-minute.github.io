---
layout: page
title: home
---

# Mike J Innes

## Some things you should know about me

* My name is Mike
* I know very little about anything (but I'm working on it)
* I'm a semi-effective code monkey, currently monkeying around for Julia Computing
* As a programmer, I spend most of my time writing pieces of text which solve problems
  * Although the problems are often themselves caused by other pieces of text, which were often also written by me

## Some things I've worked on

* Juno, an IDE for the Julia programming language

## Some things you can click on

[GitHub](https://github.com/one-more-minute), [Twitter](https://twitter.com/one_more_minute), [Here](http://one-more-minute.github.io)

## Some things never change

<ul>
{% for post in site.posts %}
<li>
  <a href="{{post.url}}">{{post.title}}</a>
</li>
{% endfor %}
</ul>