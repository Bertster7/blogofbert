---
layout: page
title: Blog of Bert
tagline: Rants and Other Nonsense
---
{% include JB/setup %}

## Blog of Bert

In `_config.yml` remember to specify your own data:
    
    title : My Blog =)
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.
    
##Posts

This is where the heading for my post should go

	Indented text like this gets put in a bubble

This is where my posts appear

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

##End of Page
It would make sense to have loads of stuff down here so that the posts aren't at the bottom of the page.


