---
title: Bedroom Suite
abstract: Bravo queen bed, mattress and set of Soho bedside tables and tallboy in very good condition.
price: 450
status: Sold
photo: queen-bed.jpg
---
The bedroom suite includes the items below.  Please see the links for details.

{% for post in site.tags.bedroom-suite %}
- [{{ post.title }}]({{ post.url}}) (AUD {{ post.price }})
{% endfor %}

The price for the queen bed includes a good quality mattress that is not included in the new price quoted.
