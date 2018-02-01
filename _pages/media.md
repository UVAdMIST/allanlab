---
title: "dMIST Research Group - Media"
layout: piclay
excerpt: "dMIST Research Group -- Media"
permalink: /media/
---

Jump to: [Presentations](#presentations), [Gallery](#gallery)


# Presentations

### dMIST Presentation Poster
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/pres/dMISTposter.jpg" width="100%">
</figure>

### Coupled Management of Stormwater and Traffic Systems Presentation Poster
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/pres/ImprovingResiliencePoster.jpg" width="100%">
</figure>

<!--#### Timelapse of our STM assembling [(see LION news item)](https://www.physics.leidenuniv.nl/index.php?id=11573&news=867&type=lion&ln=EN):
<iframe width="560" height="315" src="https://www.youtube.com/embed/3iKvUMv1h5A" frameborder="0" allowfullscreen></iframe>-->

# Gallery
(Right-click *'view image'* or *'Open image in new tab'* to see a larger image.)
{% assign number_printed = 0 %}
{% for pic in site.data.pictures_Leiden %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>


