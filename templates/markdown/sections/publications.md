{% extends "section.md" %}

{% block body %}

<a href="https://scholar.google.com/citations?user={{ goog_id }}" class="btn btn-primary" style="padding: 0.3em;">
  <i class="ai ai-google-scholar"></i> Google Scholar
</a>

<table class="table table-hover">
{{ content.details }}
</table>

{% endblock body %}
