# Passenger List 

{% for item in site.data.titanic %} 

{ {item.Name} was {Item.Age} } years old.

{% endfor %}
