---
layout: page
menu: false
date: "2025-09-21 01:53:59"
title: Frontend
description: Sinds 2006 ben ik onderweg op mijn muzikale ontdekkingsreis op de piano – van A t/m D-examen – en tegenwoordig invalpianist bij Popkoor Wiezz in Wierden..
permalink: /frontend/
---

# ... naar implementatie.

Mijn focus binnen frontend-ontwikkeling ligt vooral op **Vue.js** als framework.  
Ik vind Vue sterk omdat het overzichtelijk blijft, ook in grotere projecten, en het combineert goed met herbruikbare componenten.  

Daarnaast gebruik ik **Bootstrap** om snel een stevige basis voor de vormgeving neer te zetten.  
Samen zorgen Vue en Bootstrap voor een efficiënte workflow waarin ik zowel flexibiliteit als consistentie behoud.  

Her en der werk ik ook aan **Laravel-projecten**, waarbij ik steeds handiger word met **PHP**.  
Binnen Laravel gebruik ik regelmatig **Twill** als CMS, wat een krachtige en gebruiksvriendelijke manier biedt om content te beheren.  
Deze combinatie maakt dat ik zowel de frontend als de backend beter begrijp en kan verbinden.  

---

## Frontend gerelateerde posts

<ul>
  {% for post in site.posts %}
    {% if post.tags contains "frontend" %}
      <li>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        <small>— {{ post.date | date: "%d-%m-%Y" }}</small>
      </li>
    {% endif %}
  {% endfor %}
</ul>







