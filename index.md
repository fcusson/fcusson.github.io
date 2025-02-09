---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<div class="home-intro">
    <h1>Hello I'm Felix Cusson</h1>
    <p class="tagline">Team Lead | Senior Data Developer | Open Source Contributor | Dungeon Master</p>
    <p>
        I specialize in **data analytics and enablement**, leading a team that builds scalable, **AWS Serverless solutions** for managing enterprise data.  
    I also contribute to **open-source projects**, primarily in **Python**, including maintainin
    [Spotcast](https://github.com/fondberg/spotcast), a Home Assistant integration enabling Spotify playback on Chromecast device.
    When I'm not coding, I’m a **Dungeon Master**, running immersive campaigns across multiple worlds.
    </p>
    <a href="/about.html" class="btn">Learn More</a>
</div>

<hr>

<h2>Fetured Projects</h2>
<div class="Fetured-projects">
  {% for project in site.projects limit:3 %}
    <div class="project">
      <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
      <p>{{ project.excerpt }}</p>
    </div>
  {% endfor %}
</div>
<p><a href="/projects.html">View all projects →</a></p>

<hr>
