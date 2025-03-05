---  
layout: page  
title: Announcements  
---  
  
Stay updated with the latest news and updates from the Agents Working Group.  

This is lazily mirrored from the content at [Github Discussions: Announcements](https://github.com/The-AI-Alliance/agents-wg/discussions/categories/announcements)
  
{% for post in site.posts %}  
  <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>  
  <p>{{ post.date | date: "%B %-d, %Y" }}</p>  
  {{ post.excerpt }}  
{% endfor %}  
