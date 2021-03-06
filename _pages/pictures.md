---
title: "Borglab - Pictures"
layout: piclay
excerpt: "Borglab -- Pictures"
permalink: /pictures/
---

# Pictures
Jump to: [Adversarial T-shirt](#adversarial-t-shirt), [MSU Campus](#beautiful-campus-of-msu-!-go-green-!), [Group Logos](#group-logos)

## Adversarial T-shirt
#### K. Xu, G. Zhang, S. Liu, Q. Fan, M. Sun, H. Chen, P.-Y. Chen, Y. Wang, X. Lin, [Adversarial T-shirt! Evading Person Detectors in A Physical World](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500647.pdf), ECCV’20
<iframe width="560" height="315" src="https://www.youtube.com/embed/8GCN7xQkaa0" frameborder="0" allowfullscreen></iframe>

## Beautiful Campus of MSU! Go Green!

(Right-click *'view image'* to see a larger image.)
{% assign number_printed = 0 %}
{% for pic in site.data.pictures_Leiden %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/campus/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
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

#### Cute Dr. Squirrel on compus!
<iframe width="560" height="315" src="https://www.youtube.com/embed/scQs0zwvrfk" frameborder="0" allowfullscreen></iframe>

## Group Logos
#### group logo
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/logo.png" width="60%">
</figure>

#### group logo - black
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/logo_black.png" width="60%">
</figure>

#### group logo - white
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/logo_white.png" width="60%">
</figure>

#### group T-shirt
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/group_tshirt.png" width="60%">
</figure>

#### group sign
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/group_sign.png" width="60%">
</figure>

#### group icon
<figure>
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/group_icon.png" width="60%">
</figure>