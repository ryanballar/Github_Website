# Hello World 
# My projects
I'm working on learning more about Github. 
# My Blog
<ul>
  {% for post in site.posts %}
  {% include base.html %}
  <li>
    <a href="{{ base }}{{ post.url }}"> {{post.title}}</a>
  </li>
  {% endfor %}
 </ul>
