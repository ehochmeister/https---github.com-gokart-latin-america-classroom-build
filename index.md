---
layout: page
---

### Courses

<ul>
{% for course in site.data.courses %}
	<li>
		<a href="/courses/{{ course[0] }}/">{{ course[0] }}</a>
	</li>
{% endfor %}
</ul>