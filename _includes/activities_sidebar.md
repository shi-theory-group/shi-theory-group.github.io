
## News
<ul class="news-ul">
{% for news in site.data.activities_news %}
<li>
<h3>{{news.title}}</h3>
<p>{{news.description}}</p>
</li>
<hr>
{% endfor %}
</ul>

