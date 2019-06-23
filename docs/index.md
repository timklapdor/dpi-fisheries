---
layout: page
---
<section class="cards" markdown="1">
The list of resources below has been developed by the team form [26fifty](https://26fifty.com.au) for the New South Wales Department of Primary Industries. The *Stories* have been created using Google's [AMP Story]() format and the *Explorable* Census Map is an interactive SVG.   
</section>

<section class="cards" markdown="1">
## Featured Stories

<ul >
{% for story in site.stories %}
  <li class="card">
    <div class="img">
      <img src="assets/fisheries/bookend-forestry.png" alt="">
    </div>
    <div class="text">
        <h3><a href="{{ story.url }}">{{ story.title }}</a></h3>
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
    <img src="assets/fisheries/bookend-forestry.png" alt="">
  </div>
  <div class="text">
      <h3><a href="{{ item.url }}">{{ item.title }}</a></h3>
  </div>
</li>

## Add in Angleraccess Website - https://www.angleraccessdev.dpi.nsw.gov.au/

## Fish stocking map https://www.dpi.nsw.gov.au/fishing/recreational/resources/stocking
{% endfor %}
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
