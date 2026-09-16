---
layout: default
title: Publications
permalink: /publications/
---

# Publications

<p class="pub-note"> For citation counts and the most complete list see <a href="https://scholar.google.com/citations?user=m_OH6V8AAAAJ">Google Scholar</a> and <a href="https://orcid.org/0000-0002-1163-6368">ORCID</a>.</p>

{% assign by_year = site.data.publications | group_by: "year" | sort: "name" | reverse %}
{% for group in by_year %}
<h2 class="pub-year">{{ group.name }}</h2>
{% for p in group.items %}
<p class="pub">
  <span class="authors">{{ p.authors }}</span> ({{ p.year }}).
  <span class="title">{{ p.title }}</span>
  <span class="venue">{{ p.venue }}</span>{% if p.detail %}, {{ p.detail }}{% endif %}.
  <span class="links">{% if p.doi %}<a href="https://doi.org/{{ p.doi }}">doi</a>{% endif %}{% if p.eprint %}<a href="https://eprints.gla.ac.uk/{{ p.eprint }}/">Enlighten</a>{% endif %}</span>
</p>
{% endfor %}
{% endfor %}
