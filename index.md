---
title: "aryoda's wiki site"
output: html_document
---


You can find here a list of all my non-trival publications related to the R programming language
(i. e. source code, packages, training slides).



### Published R packages

[tryCatchLog](https://github.com/aryoda/tryCatchLog) - An R package to improve error handling compared to the standard tryCatch function



### Published R training material

[Error handling with R and tryCatchLog](https://github.com/aryoda/R_trainings) - training slides are in preparation (please wait a few more weeks)



### Recommended external sources

[www.r-bloggers.com](http://www.r-bloggers.com/) - R news and tutorials contributed by over 600 R bloggers




### My blog posts here

<p>
{% for post in site.posts %}
    <strong>{{ post.date | date: "%B %e, %Y" }}</strong> - <a href="{{ post.url }}">{{ post.title }}</a> ({{ post.category }}) <br>
{% endfor %}
</p>

