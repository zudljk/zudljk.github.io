<ul>
    {% for item in site.data.contacts %}
    <li>
        <a href="{{ item.link }}">
            <img class="socialicon" src="{{item.icon}}"/>
            {{ item.name }}
        </a>
    </li>
    {% endfor %}
</ul>