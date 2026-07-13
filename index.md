---
layout: default
title: Royce AI Solutions — AI Tutor & Blog
---

# Royce AI Solutions

AI Receptionists for Auto Dealerships & Medical Practices — and now, AI Tutoring.

<div style="
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white; padding: 30px; border-radius: 12px; margin: 30px 0;
  text-align: center;
">
  <h2 style="color: white; margin: 0 0 10px;">🧠 RoyceAI Tutor — Now Available!</h2>
  <p style="font-size: 1.1em; margin: 0 0 15px;">
    Personalized 1-on-1 AI tutoring for your child. Math, Science, English, Korean, and more.
    Homework help. Quiz prep. Reading practice. 24/7 availability.
  </p>
  <a href="https://t.me/royceai_bot" style="
    display: inline-block; background: white; color: #764ba2;
    padding: 12px 32px; border-radius: 8px; font-weight: bold;
    text-decoration: none; font-size: 1.1em;
  ">Start Free Trial →</a>
  <p style="margin: 10px 0 0; font-size: 0.85em; opacity: 0.9;">
    Serving Irvine. K-12 subjects including Korean, Math, Science & English.
  </p>
</div>

<div style="
  background: #ff6b6b; color: white; padding: 25px; border-radius: 12px; margin: 20px 0;
  text-align: center;
">
  <h2 style="color: white; margin: 0 0 10px;">🍽️ Think You Know Food?</h2>
  <p style="font-size: 1em; margin: 0 0 15px;">
    Take our 10-question Cuisine Quiz. Determine your grade level.
    <strong>Warning:</strong> Most adults score below 5th grade.
  </p>
  <a href="cuisine-game" style="
    display: inline-block; background: white; color: #ff6b6b;
    padding: 12px 32px; border-radius: 8px; font-weight: bold;
    text-decoration: none; font-size: 1.1em;
  ">Take the Quiz →</a>
</div>

---

## Latest Articles

<div style="display: flex; gap: 20px; flex-wrap: wrap;">

<div style="flex: 1; min-width: 300px;">
<h2>📰 Industry Blog</h2>
<ul>
{% assign count = 0 %}
{% for post in site.posts %}
  {% unless post.tags contains "technical-analysis" %}
    {% assign count = count | plus: 1 %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}</li>
    {% if count >= 9 %}{% break %}{% endif %}
  {% endunless %}
{% endfor %}
</ul>
</div>

<div style="flex: 1; min-width: 300px;">
<h2>📊 Technical Analysis</h2>
<ul>
{% assign count = 0 %}
{% for post in site.posts %}
  {% if post.tags contains "technical-analysis" %}
    {% assign count = count | plus: 1 %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> - {{ date | date: "%B %d, %Y" }}</li>
    {% if count >= 9 %}{% break %}{% endif %}
  {% endif %}
{% endfor %}
</ul>
</div>

</div>

---

## About Royce AI Solutions

We build AI receptionists that never miss a call — and now, AI tutors that never get tired. Serving auto dealerships, medical practices, dental offices, veterinary clinics, real estate agencies, law firms, insurance agencies, financial services, home services, restaurants, hotels, e-commerce businesses, tutoring centers, and ANY business needing 24/7 multilingual AI in Orange County and beyond.

**Ready for AI?**
Visit: [royceai.com](https://royceai.com) | [Start Tutoring →](https://t.me/royceai_bot)
