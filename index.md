## Skills

## Reading List

{% for book in site.books %}
### {{ book.name }}
<a name='{{ book.link }}'></a>
{{ book.author}}
{% endfor %}

Testing: 
{% include booklink.html ref="hooked" %} 
