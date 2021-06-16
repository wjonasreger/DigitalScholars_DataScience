---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults


layout: default
---

<!-- landing photo page -->
{% include landing.html image='/assets/img/landing.jpg' %}

<!-- Start of Sections Section -->
<div id="sections" class="offset" style="margin-top:5px;">
  <div class="jumbotron bg-light">
    <!-- title -->
    <div class="col-12 narrow text-center">
      <h1 style="padding-bottom: 20px; text-transform: uppercase;">{{ site.title }} {{ site.semester }} Course Information</h1>
      <div class="heading-underline"></div>
    </div>
    <div class="row text-center">
      <div class="col-md-12">
        <div class="feature">
          <a href="{{ site.data.info.rickroll }}"><i class="{{ site.data.info.online-icon }}" data-fa-transform="shrinks-5 up-4"></i></a>
          <h3>Online Section: {% assign online = site.data.info.sections | where: 'type', 'Online' %}{% if online.size == 2 %}{% for class in online %}{% if class == online.first %}{{ class.name }} & {% else %}{{ class.name }}{% endif %}{% endfor %}{% elsif online.size > 2 %}{% for class in online %}{% if class == online.first %}{{ class.name }}{% elsif class == online.last %} & {{ class.name }}{% else %}, {{ class.name }}{% endif %}{% endfor %}{% else %}{% for class in online %}{{ class.name }}{% endfor %}{% endif %}</h3>
          <p>{% for class in online %}
          <b>{{ class.instructor }}</b><br>
          {{ class.times }}<br>{{ class.location }}<br>{{ class.office }}<br>
          {% endfor %}</p>
        </div>
      </div>
    </div>
  </div>
</div>
<!-- End of Sections Section -->

<div id="announcements" class="offset" style="margin-top:5px; color: white;">
  <div class="fixed-background">
  <div class="dark">
    <!-- title -->
    <div class="col-12 narrow text-center">
      <h3 class="heading" style="padding-bottom: 20px; text-transform: uppercase;">Announcements</h3>
      <div class="heading-underline"></div>
    </div>
    <div class="py-4">
      <div class="row text-center">
        {% include class_cards.html week='2' %}
        {% include class_cards.html week='1' %}
      </div>
    </div>
    <div class="fixed-wrap">
      <div class="fixed" style="background-image: url('{{ site.baseurl }}/assets/img/stat100book.jpg');">
        <div class="layer">
        </div>
      </div>
    </div>
  </div>
  </div>
</div>