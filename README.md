## Welcome to GitHub Pages

<ul class="languages">
{% for lang in site.data.languages %}
{% assign language = lang[1] %}
<li><a href="{{site.baseurl}}{{lang[0]}}">{{language.icon}} {{ language.label }} ({{ language.code }})</a></li>
{% endfor %}
</ul>
