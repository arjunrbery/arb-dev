---
layout: ''
title: Posts
date: ''
page_sections:
- template: navigation-header
  block: header-1
  logo: "/uploads/2021/08/18/logo-black-simple.png"
  navigation: []
- template: 1-column-text
  block: one-column-1
  slug: responsive
  headline: 16 Fully Responsive Design Blocks
  content: |
    <ul>
	  {% for post in site.posts %}
	    <li>
	      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
	      {{ post.excerpt }}
	    </li>
	  {% endfor %}
	</ul>
- template: simple-footer
  block: footer-1
  content: ''
published: false
---
