---
permalink: /
title: "Short Bio"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am a PhD candidate at the Web-Information-Systems group at Delft University of Technology, supervised by Dr. Maria Soledad Pera.

My research centers on the intersection of **recommender systems** and **children**, understanding how children interact with these systems, probing algorithms for their effectiveness for vulnerable children, and assessing the types of risks algorithmic recommendations may pose to children’s well-being. My work further examines how value-laden design and evaluation choices shape recommender systems and influence which outcomes are considered desirable or detrimental for children. My interdisciplinary work combines algorithmic approaches with user-centered methods to capture the complexities of child-recommender system interactions. I advocate for child-aware recommender systems that explicitly account for children’s unique preferences, vulnerabilities, and rights.


## Latest News

{% assign latest_news = site.news | sort: "date" | reverse %}

<ul>
{% for post in latest_news limit:5 %}
  <li>
    <strong>{{ post.date | date: "%b %Y" }}</strong> —
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

[View all news](/news/)