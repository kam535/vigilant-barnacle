---
title: "Projects & Publications"
bookmark: true
layout: page
thumbnail: "/assets/img/thumbnail/sample.png"
---
<body class="is-preload">

  <div id="wrapper">

  <div id="main">
    {% for image in site.images %}
        <article class="thumb">
          <a href="{{site.baseurl}}/assets/images/fulls/{{ image.path | split: '/' | last | split: '.' | first }}.jpg" class="image">
            <img src="{{site.baseurl}}/assets/images/thumbs/{{ image.path | split: '/' | last | split: '.' | first }}.jpg" alt="{{ image.title }}" />
          </a>
          <h2>{{ image.title }}</h2>
          <p>{{ image.caption }}</p>
        </article>
      {% endfor %}

  </div>

  <script src="{{ 'assets/js/jquery.min.js' | relative_url }}"></script>
  <script src="{{ 'assets/js/jquery.poptrox.min.js' | relative_url }}"></script>
  <script src="{{ 'assets/js/browser.min.js' | relative_url }}"></script>
  <script src="{{ 'assets/js/breakpoints.min.js' | relative_url }}"></script>
  <script src="{{ 'assets/js/util.js' | relative_url }}"></script>
  <script src="{{ 'assets/js/main.js' | relative_url }}"></script>

  </body>
