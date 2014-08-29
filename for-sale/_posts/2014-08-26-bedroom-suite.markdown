---
title: Bedroom Suite
abstract: Bravo queen bed, mattress and set of Soho bedside tables and tallboy in very good condition.
price: 450
status: Available
photo: bedroom-suite.jpg
---
The bedroom suite includes the items below.  Please see the links for details.

The price for the queen bed includes a good quality mattress that is not included in the new price quoted.

{% for post in site.tags.bedroom-suite %}
  - [{{ post.title }}]({{ post.url}}) (AUD {{ post.price }} on its own; {{ post.price-new }} new.)
{% endfor %}
