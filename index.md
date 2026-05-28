---
layout: default
title: Royce AI Solutions Blog
---

# Royce AI Solutions Blog

Welcome to the official blog of Royce AI Solutions - AI Receptionists for Auto Dealerships and Medical Practices.

<div style="display: flex; gap: 20px; flex-wrap: wrap;">

<div style="flex: 1; min-width: 300px;">
<h2>📰 Latest Articles (Max 9)</h2>
<ul>
{% assign articles = site.posts | where_exp: "post", "post.tags contains 'technical-analysis' == false" %}
{% for post in articles limit:9 %}
<li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}</li>
{% endfor %}
</ul>
</div>

<div style="flex: 1; min-width: 300px;">
<h2>📊 Technical Analysis (Max 9)</h2>
<ul>
{% assign tech_posts = site.posts | where_exp: "post", "post.tags contains 'technical-analysis'" | limit:9 %}
{% for post in tech_posts %}
<li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}</li>
{% endfor %}
</ul>
</div>

</div>

---

## About Royce AI Solutions

We build AI receptionists that never miss a call. Serving auto dealerships, medical practices, dental offices, veterinary clinics, real estate agencies, law firms, insurance agencies, financial services, home services, restaurants, hotels, e-commerce businesses, and ANY business needing 24/7 multilingual call answering in Orange County and beyond.

**Ready to capture every call?**
Visit: [royceai.com](https://royceai.com)
