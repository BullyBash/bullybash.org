---
title: Frequently Asked Questions
nav_title: FAQs
permalink: /faqs
layout: default
---
{% assign faqs = site.data.faqs.faqs %}

<div class="grid_container">
 {%- for question in faqs -%}
    <div class="grid_item">
      <h3>{{ question.question }}</h3>
      <p>{{ question.answer }}</p>
    </div>
  {%- endfor -%}
</div>