# Ski Maps

{% for map_app in site.data.ski_map_apps %}

## {{map_app.name}}

<iframe width="100%" height="500" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" 
src="https://www.arcgis.com/apps/instant/media/index.html?appid={{map_app.app_id}}"></iframe>


<a href="https://www.arcgis.com/apps/instant/media/index.html?appid={{map_app.app_id}}" target="_blank">Open in New Tab</a>

{% endfor %}