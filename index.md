---
---

*Moḻi-maṇḍala* [moɻimɐɳɖɐlɐ] (lit. ‘language-circle’) is a small group of people interested in the linguistics of the languages of the Indian Subcontinent: a unique landscape home to hundreds of languages from diverse families and interesting historical processes as speakers of so many backgrounds have come into contact. Our main focus is historical linguistics, but we are interested in taking a modern, rigorous approach to the topic in an accessible manner.

# Posts

{% for post in site.posts %}
{% if post.description %}
{% include posts-list-item.html %}
{% endif %}
{% endfor %}