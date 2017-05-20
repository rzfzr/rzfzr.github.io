## Finished Projects
## Things I am currently working on:

Neway

Ludom Dare 38

AntiOctagon

Jogos do Rio

Kinect Simulator

UENP

Virtual Manipulative

Passaros.com
  website
  app
  
Clicnet.com

Bandeirantes Online

Balls

SMA
![GitHub Logo](/images/sma1.webp)

![GitHub Logo](/images/sma2.webp)

![GitHub Logo](/images/sma3.webp)

{% for image in site.static_files %}
    {% if image.path contains 'images' %}
        <img src="{{ site.baseurl }}{{ image.path }}" alt="image" />
    {% endif %}
{% endfor %}

