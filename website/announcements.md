---  
layout: page  
title: Announcements  
---  
  
Stay updated with the latest news and updates from the Agents Working Group.  
  
{% for post in site.posts %}  
  <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>  
  <p>{{ post.date | date: "%B %-d, %Y" }}</p>  
  {{ post.excerpt }}  
{% endfor %}  
