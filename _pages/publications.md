---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

Please find the full list of my papers on [Google Scholar](https://scholar.google.com.au/citations?user=L_dr0dIAAAAJ&hl=en) and [DBLP](https://dblp.org/pid/243/7180.html).

---

{% assign current_year = "" %}
{% for paper in site.data.publications %}
{% if paper.year != current_year %}
## {{ paper.year }}
{% assign current_year = paper.year %}
{% endif %}

<div style="display: flex; gap: 20px; margin-bottom: 30px; align-items: flex-start;">
  <div style="flex: 0 0 200px;">
    <img src="/images/research/{{ paper.image | default: 'placeholder.png' }}" alt="Paper Image" style="width: 100%; object-fit: cover; border: 1px solid #ddd; border-radius: 4px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 8px; font-size: 1.2em;"><a href="{{ paper.url }}">{{ paper.title }}</a></h3>
    <p style="margin-bottom: 8px; font-size: 0.95em; color: #555; line-height: 1.4; text-align: justify;">{{ paper.abstract }}</p>
    <p style="margin-bottom: 5px; font-size: 0.95em;">{{ paper.authors }}</p>
    <p style="margin-bottom: 8px; font-size: 0.95em;"><i>{{ paper.conference }}</i></p>
    <div>{{ paper.badges }}</div>
  </div>
</div>
{% endfor %}

---

_The journal rank (Q4-Q1) and the conference rank (C-A\*) presented above are retrieved from [ScimagoJR](https://www.scimagojr.com/) and [CORE](http://portal.core.edu.au/conf-ranks/) respectively. Please consult the [ScimagoJR website](https://www.scimagojr.com/) and [CORE website](http://www.core.edu.au/conference-portal) for more detailed assessment methods._
