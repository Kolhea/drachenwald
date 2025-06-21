---
title: The Landed Nobility of Drachenwald
exerpt: Lands held in fief to the Crown of Drachenwald
---
<p class="centered-text">
<a href="{{ site.baseurl }}{% link royals/index.html %}" class="btn btn--primary">King & Queen</a>
{% comment %}
<a href="{{ site.baseurl }}{% link royals/heirs.html %}" class="btn btn--primary">The Heirs</a>
{% endcomment %}
<a href="#" class="btn btn--inverse">Landed Nobility</a>
<a href="{{ site.baseurl }}{% link royals/drachenwald-succession.md %}" class="btn btn--primary">Drachenwald Succession</a>
</p>

{% assign royalty= site.data.regnum-officers | where: "office", "royalty" %}

Across Drachenwald, certain lands are secured by local nobility who hold regions in fief to the Crown.

## Nordmark (Sweden)

<img src="{{ site.baseurl }}{% link images/heraldry/nm_vapen_liten.gif %}" width="40" alt="Arms of Nordmark">{: .align-left}  

Their Highnesses of The [Principality of Nordmark](https://nordmark.org/)

{% assign v = royalty  | where: "group", "Nordmark" %}
{% include territorial-contacts.md listing=v %}

### Styringheim (Island of Gotland, Sweden)

<img src="{{ site.baseurl }}{% link images/heraldry/styringheim_logo.gif %}" width="40" alt="Arms of Styringheim">{: .align-left}  

Their Excellencies of the [Barony of Styringheim](https://www.styringheim.se/)  

{% assign v = royalty | where: "group", "Nordmark-Styringheim" %}
{% include territorial-contacts.md listing=v %}

### Gotvik (Gothenburg, Sweden)  

<img src="{{ site.baseurl }}{% link images/heraldry/gotviktrans.gif %}" width="40" alt="Arms of Gotvik">{: .align-left}  

Their Excellencies of the [Barony of Gotvik](https://gotvik.se/)
 
{% assign v = royalty | where: "group", "Nordmark-Gotvik" %}
{% include territorial-contacts.md listing=v %}

## Insulae Draconis (United Kingdom, Ireland, Iceland)  

<img src="{{ site.baseurl }}{% link images/heraldry/iddevice.svg %}" width="40" alt="Arms of Insulae Draconis">{: .align-left}  

Their Highnesses of the [Principality of Insulae Draconis](https://insulaedraconis.org/)

{% assign v = royalty | where: "group", "Insulae Draconis" %}
{% include territorial-contacts.md listing=v %}

### Eplaheimr (Central, west and south Ireland)


Their Excellencies of the [Barony of Eplaheimr](https://eplaheimr.org/)

{% assign v = royalty | where: "group", "Insulae Draconis-Eplaheimr" %}
{% include territorial-contacts.md listing=v %}

## Knight's Crossing (Germany)  

<img src="{{ site.baseurl }}{% link images/heraldry/knightscrossing_m.gif %}" width="40" alt="Arms of Knight's Crossing">{: .align-left}  

Their Excellencies of the [Barony of Knight's Crossing](https://www.knightscrossing.org/)
 
{% assign v = royalty | where: "group", "Knights Crossing" %}
{% include territorial-contacts.md listing=v %}

## Aarnimetsä (Finland)

<img src="{{ site.baseurl }}{% link images/heraldry/arnimetsa.gif %}" width="40" alt="Arms of Aarnimetsä">{: .align-left}  

Their Excellencies of the [Barony of Aarnimetsä](https://www.aarnimetsa.org/)
 
{% assign v = royalty | where: "group", "Aarnimetsä" %}
{% include territorial-contacts.md listing=v %}
