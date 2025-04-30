---
layout: default
heading: My Doggos
---

The main purpose of this website is to document my dogs.
I love them a lot. 
In case they ever get lost, their collars will link them to this website.
So if you're here, thats really unfortunate.
All my dogs are very friendly and this site will document their vaccinations and anything else that is important (like how to get a hold of me).
<div style="text-align: center;">
<span class="mdi--dog"></span>
</div>

{% for doggo in site.doggos %}
- [{{ doggo.name }}]({{ doggo.url }})
{% endfor %}