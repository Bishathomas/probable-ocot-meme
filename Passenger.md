# Passenger List 

{% for item in data.titanic.csv %} 

{ {item:Name} was {Item:Age} }

{% endfor %}
