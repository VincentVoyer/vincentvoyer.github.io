---
layout: page
title : "Projects"
permalink: /projects/
---

<div class="container-fluid bg-3 text-center">    
  <h3>Some of my Work</h3><br>
  <div class="row">
  {% for post in site.posts %}
	<div class="card col-sm-3">
	  <img class="card-img-top img-responsive" src="{{ post.image }}" style="width:100%" alt="{{ post.title}}">
	  <div class="card-body">
		<h5 class="card-title text-uppercase">{{ post.title}}</h5>
		<p class="card-text resume">{{ post.resume}}</p>
		<a href="{{ post.url }}" class="btn black-button">Read more</a>
	  </div>
	</div>
   {% endfor %} 
  </div>
</div><br>
