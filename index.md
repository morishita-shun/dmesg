## logs

{% assign doclist = site.pages | sort: 'url'  %}
  {% for doc in doclist %}
-     [{{ doc.name }}]({{ site.baseurl }}{{ doc.url }})
  {% endfor %}
