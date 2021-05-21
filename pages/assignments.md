---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: content
title: course-assignments
---

## Labs
<hr/>
{% for item in site.data.content.labs %}
<ul>
    <li><a href="{{ item.link }}" target="_blank">{{ item.name }}</a> (Due: {{ item.due }})
    {% if item.text != "" %}
    <p>{{ item.text }}</p>
    {% endif %}</li>
</ul>
{% endfor %}

## Homeworks
<hr/>
{% for item in site.data.content.homeworks %}
<ul>
    <li><a href="{{ item.link }}" target="_blank">{{ item.name }}</a> (Due: {{ item.due }})
    {% if item.text != "" %}
    <p>{{ item.text }}</p>
    {% endif %}</li>
</ul>
{% endfor %}

## Projects
<hr/>
{% for item in site.data.content.projects %}
<ul>
    <li><a href="{{ item.link }}" target="_blank">{{ item.name }}</a> (Due: {{ item.due }})
    {% if item.text != "" %}
    <p>{{ item.text }}</p>
    {% endif %}</li>
</ul>
{% endfor %}