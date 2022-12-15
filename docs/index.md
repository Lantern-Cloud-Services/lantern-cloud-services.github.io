---
layout: default
---

[Link to another page](./example.markdown).

# Meet the team

### Bender

<img src="./media/bender.jpg" width="300"/>

> Bender is our glorious leader, presedent and CEO, responsible for the day to day operations here at Lantern Cloud Services.
> 
> Without him all is lost.

### JasonCooOneMtc

<img src="./media/234422_bender_256x256.png" width="300"/>

> JasonCooOneMtc is our glorious leaders right hand machine, mostly responsible for keeping the meat bag in line.

### jdvcDev 

<img src="./media/jcook_photo.jpg" width="300"/>

> jdvDev is the lowly resident meat bag.  We keep him around to interface with the other meat bags.

## Header 1 - Index of Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>