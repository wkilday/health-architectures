---
layout: default
---

# Microsoft Health Architectures 
Health Architectures is a collection of reference architectures and, when appropriate, implementations. They illustrate end-to-end best practices for using the Azure API for FHIR and related technologies.  As you look through this site, you will see some typical 'hello world' examples as well as more complex solutions. We conduct peer reviews to bring you the best practices for using the Microsoft Health technologies. 

<br>

Site title = {{ site.title }} 

repository name = {{ site.github.repository_name }} 

relative url = {{ relative_url }}

base url = {{ baseurl }}

<a href="{{ "/" | absolute_url }}">{{ site.title | default: site.github.repository_name }}</a>


<h2>Latest Posts</h2>

<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.excerpt }}</a></h3> 
          {{ post.title }}
    </li>
  {% endfor %}
</ul>




[Blogs](./_posts/blog.html)

[Exporting Data to HIVE, HDFS or Azure DataBricks](./_posts/2020-07-24-exportingDataToHive)




We invite you to ask questions, make suggestions and share use cases which we might consider for future reference architectures or implementations.