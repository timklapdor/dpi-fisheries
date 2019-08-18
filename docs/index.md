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
      <img src="{{ story.slug | relative }}/poster-portrait.jpg" alt="{{ story.title }}">
    </div>
    <div class="text">
        <h3><a href="{{ site.baseurl }}{{ story.url }}">{{ story.title }}</a></h3>
    </div>
  </li>
  {% endfor %}
</ul>
</section>

<section  class="cards" markdown="1">
## Explorable Data
<ul class="x2">
  {% for item in site.explorables %}
  <li class="card">
    <div class="img">
      <img src="{{ site.baseurl }}/assets/fisheries/regions-poster-square.jpg" alt="{{ item.title }}">
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
## Documents

<ul>
  <li class="card">
    <div class="img">
      <img src="{{ site.baseurl }}/assets/fisheries/northern.png" alt="">
    </div>
    <div class="text">
        <h3><a href="{{ site.baseurl }}/assets/docs/Report-Cards-2018-19-Northern.pdf">Northern Report Card</a></h3>
    </div>
  </li>
  <li class="card">
    <div class="img">
      <img src="{{ site.baseurl }}/assets/fisheries/central.png" alt="">
    </div>
    <div class="text">
        <h3><a href="{{ site.baseurl }}/assets/docs/Report-Cards-2018-19-Central.pdf">Central Report Card</a></h3>
    </div>
  </li>
  <li class="card">
    <div class="img">
      <img src="{{ site.baseurl }}/assets/fisheries/southern.png" alt="">
    </div>
    <div class="text">
        <h3><a href="{ site.baseurl }}/assets/docs/Report-Cards-2018-19-Southern.pdf">Southern Report Card</a></h3>
    </div>
  </li>
  <li class="card">
    <div class="img">
      <img src="{{ site.baseurl }}/assets/fisheries/report-cover.jpg" alt="">
    </div>
    <div class="text">
        <h3><a href="{{ site.baseurl }}/assets/docs/Annual-Report-Card-Document.pdf">Annual Report 2018-19</a></h3>
    </div>
  </li>

</ul>

<!--
Filter stories by topic:
<div class="fish-group">
<button>Trout</button><button>Murray Cod</button><button>Golden Perch</button><button>Australian Bass</button>
</div>

<div class="region-group">
<button>North</button><button>Central</button><button>South</button>
</div>
-->
</section>

<section  class="cards" markdown="1">
## Downloads

<ul class="x2">
{% for story in site.stories %}
  <li class="card" style="height: 20vh;">
    <div class="text">
        <h3><a href="{{ site.baseurl }}/zips/{{ story.slug }}.zip">Download {{ story.title }}</a></h3>
    </div>
  </li>
  {% endfor %}
</ul>

</section>
