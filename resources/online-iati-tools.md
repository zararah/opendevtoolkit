---
layout: resource
tagline: ""
tags : [IATI, tools]
title: "Online IATI tools"
unlisted: false
isresource: true
---

*This page is currently a work in progress, pending community contributions + filling in the information below*

We're currently working with[School of Data](http://schoolofdata.org) to create a dynamic tools showroom, to make it as easy as possible to find the aid data tool that you need. 

In the meantime, we've been gathering information on the tools that are out there, focusing on **tools for the data user**; ie. data portals and sites providing useable data, rather than tools to help organisations publish to IATI. You can see what we've got so far on [this spreadsheet](https://docs.google.com/a/okfn.org/spreadsheet/ccc?key=0AiWM2KV46Zt0dG5jOUV3MUFtd0s5ZUV2bXU1LXpmQlE&usp=drive_web#gid=4), where we've split up tools into Global Aid Portals, Country Portals, and Donor Portals, and annotated them with details on what they're most useful for and how easy they are to use. We'll also be looking more at tools to help organisations publish to IATI and make IATI data reusable soon too.

We'll keep the list of tools up here too for reference, but for the most up to date and annotated details on the tools for **using and accessing aid data**, check out [the spreadsheet](https://docs.google.com/a/okfn.org/spreadsheet/ccc?key=0AiWM2KV46Zt0dG5jOUV3MUFtd0s5ZUV2bXU1LXpmQlE&usp=drive_web#gid=4) and [let us know](mailto:zara.rahman@okfn.org) if you have anything to add, or any questions.

**For the most up to date list of tools, with reviews and descriptions, please look at [the spreadsheet](https://docs.google.com/a/okfn.org/spreadsheet/ccc?key=0AiWM2KV46Zt0dG5jOUV3MUFtd0s5ZUV2bXU1LXpmQlE&usp=drive_web#gid=4) rather than the list below**

(For posterity; the original list of tools)


### Contents
<ul>
{% for tool in site.data.tools %}
<li> <a href="#{{ tool.slug }}">{{ tool.name }}</a></li>
{% endfor %}
</ul>

{% for tool in site.data.tools %}
<h4 id="{{ tool.slug }}">{{ tool.name }}</h4>
<dl class="dl-horizontal">
 <dt>URL</dt>
  <dd>
  	<a href="{{ tool.url }}">{{ tool.url }}</a>
  </dd>	
	<dt>Aim of tool</dt>
	<dd>
		{% if tool.aim %}
			{{ tool.aim }}
		{% else %}
			<span class="txt-muted">[to be completed]</span>
		{% endif %}
	</dd>
	<dt>Target audience</dt>
	<dd>
		{% if tool.audience %}
			{{ tool.audience }}
		{% else %}
			<span class="txt-muted">[to be completed]</span>
		{% endif %}
	</dd>
	<dt>Tech used</dt>		
	<dd>
		{% if tool.tech %}
			{{ tool.tech | join:", " }}
		{% else %}
			<span class="txt-muted">[to be completed]</span>
		{% endif %}
	</dd>
	<dt>Data source</dt>
	<dd>
		{% if tool.source %}
			{{ tool.source | join:", " }}
		{% else %}
			<span class="txt-muted">[to be completed]</span>
		{% endif %}
	</dd>
	<dt>Source code</dt> 
	<dd>
		{% if tool.github %}
			<a href="{{ tool.github }}">{{ tool.github }}</a>
		{% else %}
			<span class="txt-muted">[to be completed]</span>
		{% endif %}
	</dd>	
	<dt>Created by</dt>
	<dd>
		{% if tool.creator %}
			{{ tool.creator }}
		{% else %}
			<span class="txt-muted">[to be completed]</span>
		{% endif %}
	</dd>
	<dt>Features wishlist</dt>
	<dd>
		{% if tool.wishlist %}
			{{ tool.wishlist | join:"<br> * " }}
		{% else %}
			<span class="txt-muted">[to be completed]</span>
		{% endif %}
	</dd>
	<dt>Status</dt>
	<dd>
		{% if tool.status %}
			{{ tool.status }}
		{% else %}
			<span class="txt-muted">[to be completed]</span>
		{% endif %}
	</dd>
	<dt>Documentation</dt>
	<dd>
		{% if tool.documentation %}
			<a href="{{ tool.documentation }}">Documentation URL</a>
		{% else %}
			<span class="txt-muted">[to be completed]</span>
		{% endif %}
	</dd>
</dl>
{% endfor %}
