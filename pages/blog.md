---
layout: full-width
title: Blog
permalink: /blog/
---
  
  <span style="font-size: xx-large; padding-top:30px">
    Music Articles
  </span> 
  <ul class="content-listing ">
    {% for post in site.categories.music %}      
      <li class="listing">
        <hr class="slender">
        <a href="{{ post.url | prepend: site.baseurl }}"><h3 class="contrast">{{ post.title }}</h3></a>
        <br><span class="smaller">{{ post.date | date: "%B %-d, %Y" }}</span>  <br/>
        <div>{{ post.excerpt }}</div> 
      </li>
    {% endfor %}
  </ul>  

  <!--<div style="font-size:1.75em; margin-bottom:0.5cm">
  !-- <br />
  !-- <font> Contents </font>
  !-- <li><a href="#aims">Key aims</a></li>
  !-- </div> -->

  <!--<br /> this gives you a break in page --> 

  <!--<a href="https://www.remnote.io/a/test-folder/60927fe2b57ae300456f2152"><font style="font-size:1.15em"><b>Paper notes</b></font></a> -->

  <!-- I'm making notes on papers I come across that are related to MLPM in some way. **Nothing beats reading the original paper so please do that if you can** - these notes can hopefully complement that. -->
  

  <!---
bundle exec jekyll serve -w --baseurl=""
git add . && git commit -m "[...]" && git push origin master && rake
-->
   


