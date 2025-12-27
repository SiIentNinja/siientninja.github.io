---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

---
# Wait this is the main home pg

{% for i in site.testcollection %}
[{{i.title}}]({{i.url}})

{% endfor %}

{% for i in site.starters %}
[{{i.title}}]({{i.url}})

{% endfor %}