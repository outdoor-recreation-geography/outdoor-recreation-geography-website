# Web Maps

<h2>Ski Maps</h2>
<ul>
{% for map_app in site.data.ski_map_apps %}

  <li><a href="https://arcgis.com/apps/View/index.html?appid={{map_app.app_id}}" target="_blank">{{ map_app.name }}</a></li>
  <iframe width="500" height="400" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" 
src="https://arcgis.com/apps/View/index.html?appid={{map_app.app_id}}"></iframe>

{% endfor %}
</ul>