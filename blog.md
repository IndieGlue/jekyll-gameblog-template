---
layout: page
title: Dev Blog
permalink: /dev blog/
---

<div class="post-list">
{% for post in site.posts %}
    <div class="post">        
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">
            <div class="crop">
                <img src="{{post.image}}">   
            </div>    
            <div class="text">
                <span class="pst-title">{{ post.title }}</span>
                <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>            
            </div> 
            <div class="desc">
                {{ post.desc }}
            </div>
        </a>  
    </div>
{% endfor %}
</div>