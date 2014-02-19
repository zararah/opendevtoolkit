---
layout: resource
tagline: ""
tags : [IATI, tools]
title: "Online IATI tools"
unlisted: false
isresource: true
---

*This page is currently a work in progress, pending community contributions + filling in the information below*

We're currently working with the wonderful [School of Data](http://schoolofdata.org) to create a dynamic tools showroom, to make it as easy as possible to find the aid data tool that you need. In the meantime, we're working on gathering information and data about all the tools that are already out there, and we'd love your help! 

If you know the answer to any of the missing fields below, please let us know.
Tech option: [submit a pull request directly on github](https://github.com/zararah/opendevtoolkit/blob/gh-pages/resources/online-iati-tools.md)
Non-tech option: email [zara.rahman[at]okfn.org](mailto:zara.rahman@okfn.org)

{% for tool in site.data.tools %}
<h4>{{ tool.name }}</h4>
<dl class="dl-horizontal">
 <dt>URL</dt>
  <dd>
  	<a href="{{ tool.url }}">Website</a>
  </dd>	
	<dt>Aim of tool</dt>
	<dd>{{ tool.aim }}</dd>
	<dt>Target audience</dt>
	<dd>{{ tool.audience }}</dd>  
	<dt>Tech used</dt>		
	<dd>
		{% if tool.tech %}
			{{ tool.tech }}
		{% else %}
			<span class="txt-muted">Unknown</span>
		{% endif %}
	</dd>
	<dt>Data source</dt>
	<dd>{{ tool.source | join:", " }}
		{% if tool.source %}
			{{ tool.source | join:", " }}
		{% else %}
			<span class="txt-muted">Unknown</span>
		{% endif %}
	</dd>
	<dt>Github repo</dt> 
	<dd>{{ tool.github }}</dd>
	<dt>Created by</dt>
	<dd>{{ tool.creator }}</dd>
	<dt>Developer wishlist</dt>
	<dd>{{ tool.wishlist }}</dd>
	<dt>Status</dt>
	<dd>{{ tool.status }}</dd>
	<dt>Documentation</dt>
	<dd>{{ tool.documentation }}</dd>
</dl>
{% endfor %}

