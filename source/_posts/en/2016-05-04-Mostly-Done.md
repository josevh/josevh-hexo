---
title:  Mostly done
excerpt: Site build updates.
lang: en
date: 2016-05-04 06:00:00 -0700
tags:
---
Styling this blog is coming along nicely.

So far I've enjoyed the flexibility that Jekyll provides.
For my relatively simple design, it's proved easy to work with.

Having worked with frameworks like Laravel, I can appreciate the level of control Laravel gives.
On the other hand, it's fun to get creative and to adapt to a new environment.
For a small-scale project like this portfolio page it's perfect.
It's a lot nicer to work with than Wordpress, at least for implementing the design.
The downside however, is that there is no app from which to post.

For this design I used some inspiration from [Bill Lovett's portfolio](http://ilovett.com/).
I liked his design's focus on text rather than color and images.
Still learning design, I took it upon me to emulate what I liked best from his design and incorporated it into mine.

I'm liking Jekyll, it's just flexible enough for a low-effort project.

I'll include a few screenshots in case I update it later and want to look back on this.


<a class="thumbnail center-block" href="#" data-toggle="modal" data-target="#carousel-modal" >
  <img src="jekyll-screenshot-thumb.png" alt="homepage" />
</a>

<style>
  .carousel-control.left, .carousel-control.right { background-image: none}
  .glyphicon {color: #000;}
</style>

<div id="carousel-modal" class="modal fade" tabindex="-1" role="dialog"><!--
  --><div class="modal-dialog modal-lg"><!--
    --><div class="modal-content"><!--
      --><div class="modal-header"><!--
        --><button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true" style="font-family: sans-serif">&times;</span></button><!--
        --><h4 class="modal-title">Jekyll Design</h4><!--
      --></div><!--
      --><div class="modal-body"><!--
        --><div id="carousel-post" class="carousel slide" data-ride="carousel"><!--
          
          --><ol class="carousel-indicators"><!--
            --><li data-target="#carousel-post" data-slide-to="0" class="active"></li><!--
            --><li data-target="#carousel-post" data-slide-to="1"></li><!--
            --><li data-target="#carousel-post" data-slide-to="2"></li><!--
          --></ol><!--
        
          --><div class="carousel-inner" role="listbox"><!--
            --><div class="item active"><!--
              --><img src="jekyll-screenshot.png" alt="homepage" /><!--
            --></div><!--
            --><div class="item"><!--
              --><img src="jekyll-blog-screenshot.png" alt="blog" /><!--
            --></div><!--
          	--><div class="item"><!--
              --><img src="jekyll-post-screenshot.png" alt="post" /><!--
            --></div><!--
        	  --><div class="item"><!--
              --><img src="jekyll-projects-screenshot.png" alt="projects" /><!--
            --></div><!--
        	  --><div class="item"><!--
              --><img src="jekyll-experience-screenshot.png" alt="experience" /><!--
            --></div><!--
        	  --><div class="item"><!--
              --><img src="jekyll-skills-screenshot.png" alt="skills" /><!--
            --></div><!--
        	  --><div class="item"><!--
              --><img src="jekyll-contact-screenshot.png" alt="contact" /><!--
            --></div><!--
          --></div><!--
          --><a class="left carousel-control" href="#carousel-post" role="button" data-slide="prev"><!--
            --><span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span><!--
            --><span class="sr-only">Previous</span><!--
          --></a><!--
          --><a class="right carousel-control" href="#carousel-post" role="button" data-slide="next"><!--
            --><span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span><!--
            --><span class="sr-only">Next</span><!--
          --></a><!--
        --></div><!--
      --></div><!--
    --></div><!--
  --></div><!--
--></div>