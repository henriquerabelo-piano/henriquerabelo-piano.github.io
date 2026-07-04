---
layout: default
title: Home
---
Pianist Henrique Rabelo has performed in recitals and as a soloist with orchestras in various concert halls around the world, in countries such as Brazil, the United States, the United Kingdom, and Austria. The quality of his interpretations has garnered international recognition through numerous awards at music competitions and festivals. His interests encompass a vast repertoire, as well as historical performance practices. Henrique is also a composer whose works have been performed by distinguished artists.

Henrique is a Doctor of Musical Arts Candidate under the guidance of Ksenia Nosikova at the University of Iowa, where he serves as Graduate Teaching Assistant teaching classes, applied piano lessons, organizing concerts and pedagogical activities, and working as a collaborative pianist. His research will focus on the piano works of Brazilian composer Almeida Prado. Henrique earned his Master of Music degree from the University of Wyoming (2023), and his Bachelor of Music degree from UNIRIO (2019), Rio de Janeiro.

## Blog

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
