---
layout: default
title: "مدونتي"
---

# مرحبًا بكم في مدونتي 👋

مرحبًا! هذه هي أول تدوينة في مدونتي الجديدة.  
يمكنك تعديل هذا النص وإضافة تدوينات جديدة من خلال ملفات Markdown.

## التدوينات الأخيرة

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>
