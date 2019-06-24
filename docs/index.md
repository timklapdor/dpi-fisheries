---
layout: page
---
<section class="cards" markdown="1">
  The list of resources below has been developed by the team from [26fifty](https://26fifty.com.au) for the New South Wales Department of Primary Industries. The *Stories* have been created using Google's [AMP Story]() format and the *Explorable* Census Map is an interactive SVG.   
</section>

<section class="cards" markdown="1">
## Featured Stories

<ul >
{% for story in site.stories %}
  <li class="card">
    <div class="img">
      <img src="{{ story.slug | relative }}/poster-square.jpg" alt="">
    </div>
    <div class="text">
        <h3><a href="{{ site.baseurl }}{{ story.url }}">{{ story.title | capitalize }}</a></h3>
    </div>
  </li>
  {% endfor %}
</ul>
</section>

<section  class="cards" markdown="1">
## Explorable Data
<ul>
  {% for item in site.explorables %}
  <li class="card">
    <div class="img">
      <img src="{{ site.baseurl }}/assets/fisheries/regions-poster-square.jpg" alt="">
    </div>
    <div class="text">
        <h3><a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a></h3>
    </div>
  </li>
  {% endfor %}

  <li class="card">
    <div class="img">
      <img src="{{ site.baseurl }}/assets/fisheries/angler-poster-square.jpg" alt="">
    </div>
    <div class="text">
        <h3><a href="https://www.angleraccessdev.dpi.nsw.gov.au/">Angler Access</a></h3>
    </div>
  </li>


  <li class="card">
    <div class="img">
      <img src="{{ site.baseurl }}/assets/fisheries/stocking-poster-square.jpg" alt="">
    </div>
    <div class="text">
        <h3><a href="https://www.dpi.nsw.gov.au/fishing/recreational/resources/stocking">NSW Stocking Map</a></h3>
    </div>
  </li>
</ul>

<!-- <iframe src="monitoring-overview/index.html" style="min-height:600px;min-width:48%;"></iframe>
<iframe src="report-cards/index.html" style="min-height:600px;min-width:48%;"></iframe> -->
</section>


<section  class="cards" markdown="1">
## Stories

Filter stories by topic:
<div class="fish-group">
<button>Trout</button><button>Murray Cod</button><button>Golden Perch</button><button>Australian Bass</button>
</div>

<div class="region-group">
<button>North</button><button>Central</button><button>South</button>
</div>
</section>
