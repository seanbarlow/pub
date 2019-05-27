# All things

I have decided to try giving blogging a try. I will cover a range of topics from OpenShift to Big Data. The common theme throughout will be everything will be deployed to or done on [Microsoft Azure](http://www.azure.com)

<p>
    Posts
</p>

<ul>
    {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
</ul>