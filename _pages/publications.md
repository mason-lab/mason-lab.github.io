---
title: "Mason Lab: Publications"
layout: default
excerpt: "Mason Lab: Publications"
sitemap: false
permalink: /publications/
---

Author affiliations are as follows: __PI in bold__, <span style="color:#FDD023">undergrad students in green</style>, <span style="color:#461D7C">grad students in green</style>, <span style="color:#06BC40">postdocs in purple</style>. 

{% for p in site.data.journalcovers %} {% include journalcover.html %} {% endfor %}

{% for p in site.data.publications %} {% include publication.html %} {% endfor %}

