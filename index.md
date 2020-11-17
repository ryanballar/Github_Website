# Hello World 
# My projects
I'm working on learning more about Github. 
# My Blog
<ul>
  {% for post in site.posts %}
  {% assign url = "/Github_Website" %}
 
  <li>
    <a href="{{ post.url | prepend: url }}"> {{post.title}}</a>
  </li>
  {% endfor %}
 </ul>
