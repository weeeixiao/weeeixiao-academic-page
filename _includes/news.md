<h1 id="news"></h1>

<h2 style="margin: 60px 0px 10px;">News</h2>

<ul>
<!-- current news -->
{% for news in site.data.news.current %}
<li>
<strong>[{{ news.date }}]</strong> {{ news.content }}
</li>
{% endfor %}

<!-- old news -->
<!-- <li> <a href="javascript:toggle_vis('newsmore')">Show more</a> </li>
<div id="newsmore" style="display:none">
{% for news in site.data.news.old %} 
<li><strong>[{{ news.date }}]</strong> {{ news.content }}</li>
{% endfor %}
</div> -->

</ul>
