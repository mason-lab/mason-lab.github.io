---
title: "Mason Lab: Publications"
layout: default
excerpt: "Mason Lab: Publications"
sitemap: false
permalink: /publications/
---

{% for p in site.data.journalcovers %} {% include journalcover.html %} {% endfor %}

Author affiliations are as follows: __PI in bold__, <b><span style="color:#FDD023">undergrad students in gold, <span style="color:#461D7C">grad students in purple, <span style="color:#06BC40">postdocs in green.</b> 


{% for p in site.data.publications %} {% include publication.html %} {% endfor %}

