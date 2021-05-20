---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
{% include landing_small.html title='About Us' %}

<div id="about" class="offset" style="margin-top: 5px;">
  <div class="bg-light py-4">
    <div class="container py-4">
      <div class="row text-center">
        {% include staff_cards.html role='Lead Instructor' seniority='1' %}
        {% include staff_cards.html role='Assistant Instructor' seniority='1' %}
        {% include staff_cards.html role='Advisor' seniority='1' %}
      </div>
    </div>
  </div>
</div>
