# Passenger List 

{% for item in site.data.titanic %} 

{{item.Name}} was {{item.Age}} years old. And has {{item.Sibling}} sibling.

{% endfor %}

