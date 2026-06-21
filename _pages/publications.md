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
<div class="pub-list" markdown="1">
{% for paper in site.data.publications %}
{% if paper.year != current_year %}
## {{ paper.year }}
{: .pub-year }
{% assign current_year = paper.year %}
{% endif %}

<div class="pub-card">
  <div class="pub-card__media">
    <img src="/images/research/{{ paper.image | default: 'placeholder.png' }}" alt="{{ paper.title }}">
  </div>
  <div class="pub-card__body">
    <h3 class="pub-card__title"><a href="{{ paper.url }}">{{ paper.title }}</a></h3>
    <div class="pub-card__badges">{{ paper.badges }}</div>
    <p class="pub-card__authors">{{ paper.authors }}</p>
    <p class="pub-card__venue">{{ paper.conference }}</p>
    <p class="pub-card__abstract">{{ paper.abstract }}</p>
  </div>
</div>
{% endfor %}
</div>

---

_The journal rank (Q4-Q1) and the conference rank (C-A\*) presented above are retrieved from [ScimagoJR](https://www.scimagojr.com/) and [CORE](http://portal.core.edu.au/conf-ranks/) respectively. Please consult the [ScimagoJR website](https://www.scimagojr.com/) and [CORE website](http://www.core.edu.au/conference-portal) for more detailed assessment methods._
