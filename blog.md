---
layout: page
title: Dev Blog
permalink: /dev blog/
---

<div class="post-list row">
{% for post in site.posts %}
    <div class="post col-12 col-md-6 col-sm-12">   
        <div class="post-inner">
            <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">
                <div class="crop">
                    <img src="{{post.image}}">   
                </div>    
                <div class="text">
                    <span class="pst-title">{{ post.title }}</span>
                    <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>            
                </div> 
                <span class="line"></span>
                <div class="desc">
                    {{ post.desc }}
                </div>
            </a>  
        </div>
    </div>     
{% endfor %}
</div>