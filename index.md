## Giuseppe Palestra
I am a researcher in Social Robotics and Assistive Techologies.

## Research Interests
My research activity focuses on: 
- Multimodal Human Behavior Analysis
- Facial Expression Recognition

## Where I was born
I was born in Italy, in the wordeful region of [Apulia](https://en.wikipedia.org/wiki/Apulia).

## Blog
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

### Updated
<em>{{ site.time | date_to_long_string }}</em>
