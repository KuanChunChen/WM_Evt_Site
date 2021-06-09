---
layout: page
title: About
---

<p class="message">
  Hey there! This page is included evt report which were release in the past.  Feel free to click below link to see the report.
</p>



# Android Evt Report
----------

    {% assign pages_list = site.pages | sort:"url" %}
    {% for node in pages_list %}
      {% if node.title != null %}
        {% if node.layout == "page" %}
          
<p class="message">
  {{ node.url | absolute_url  \n}}<br>
  {{ node.title | absolute_url \n}}<br>
  {{ node.title }}<br>
</p>

        {% endif %}
      {% endif %}
    {% endfor %}


* [Android Evt v6 test]({% if page.title == 'Home' %} active{% endif %}" href="{{ '/' | absolute_url }}")

# Ios Evt Report
----------

* [Ios Evt v1](http://lanyon.getpoole.com)



Thanks for reading!
