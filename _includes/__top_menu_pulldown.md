<li class="dropdown{% if parent_namespace == include.name %} active{% endif %}">
  <a href="{{ page_lang_link }}{{ t[include.name].link }}" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">{{ t[include.name].name }} <span class="caret"></span></a>
  <ul class="dropdown-menu list-unstyled">
    {% include _menudata_list.md namespace=include.name %}
  </ul>
</li>
