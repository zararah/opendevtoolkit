---
layout: resource
tagline: ""
tags : [IATI, tools]
title: "Online IATI tools"
unlisted: false
isresource: true
---

*This page is currently a work in progress, pending community contributions + filling in the information below*

We're currently working with the wonderful [School of Data](http://schoolofdata.org) to create a dynamic tools showroom, to make it as easy as possible to find the aid data tool that you need. 

In the meantime, we're working on gathering information and data about all the tools that are already out there, and **we'd love your help.**

To contribute: 

Non-tech option: email [zara.rahman[at]okfn.org](mailto:zara.rahman@okfn.org) stating clearly which tool(s) you're emailing about, and which fields you'd like to fill in. 

Tech option: see this [How to contribute to the tools page readme](https://github.com/zararah/opendevtoolkit/blob/gh-pages/how-to-contribute.md)

**Thank you!**

{% for tool in site.data.tools %}
<h4>{{ tool.name }}</h4>
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
			{{ tool.tech }}
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
	<dt>Github repo</dt> 
	<dd>
		{% if tool.github %}
			<a href="{{ tool.github }}">Github URL</a>
		{% else %}
			<span class="txt-muted">Not applicable- closed source</span>
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
