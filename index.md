---
title: "Welcome"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0"
  overlay_image: /assets/images/67909951.jpg
  actions:
#    - label: "Github"
#      url: "https://github.com/Zoziologie"
  caption: "Eurasian Dotterel (*Charadrius morinellus*) Crêta de Vella, CH (03.09.2017)"
excerpt: "Explore web apps for birdwatchers!<br>"
intro: 
  - excerpt: 'Wonder what the name means? <br>**Zoziologie** goes back to my childhood, when my brother made fun of my passion for birds ("oiseaux" in French) by calling it "zozio". As I grew older and pursued scientific studies, I tried to combine my passion with birds (zozio) with my scientific background (logos), that gave birth to a new discpline: zoziologie!'
feature_row:
  - image_path: assets/SeeYourObservations/images/sYO_gif_static.png
    alt: "see Your Observation gif"
    image_path_2: assets/SeeYourObservations/images/sYO.gif
    title: "See your observations"
    excerpt: "Visualize all your eBird observations on a map!"
    url: "/see-your-observations/"
    btn_label: " " 
  - image_path: /assets/eBird2LaTeX/images/e2l_gif_static.png
    image_path_2: /assets/eBird2LaTeX/images/e2l.gif
    alt: "eBird2LaTeX gif"
    title: "eBird2LaTeX"
    excerpt: "Generate custom PDF checklists with eBird occurrence data."
    url: "/ebird2latex/"
    btn_label: " " 
feature_row2:
  - image_path: /assets/biolovision2eBird/images/b2e_gif_static.png
    image_path_2: /assets/biolovision2eBird/images/b2e.gif
    alt: "biolovision gif"
    title: "Biolovision2eBird"
    excerpt: "Convert your data from any biolovision website (ornitho, faune-...) to eBird."
    url: "/biolovision2ebird/"
    btn_label: " " 
  - image_path: /assets/Merge2Hotspot/images/m2h_gif_static.png
    image_path_2: /assets/Merge2Hotspot/images/m2h.gif
    alt: "Merg2hotspot gif"
    title: "Merge2Hotspot"
    excerpt: "Find existing hotspots for your personal locations on eBird."
    url: "/merge2hotspot/"
    btn_label: " " 
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/screenshot.PNG
    alt: "BMM web png"
    title: "Quantifying bird migration with weather radars"
    excerpt: 'My current project is to quantify spatio-temporal patterns of bird migration using weather radar data.'
    url: "https://bmm.raphaelnussbaumer.com/"
    btn_label: "d " 
---



{% include feature_row %}

{% include feature_row id="feature_row2" %}

{% include feature_row id="feature_row4" type="center" %}

{% include feature_row id="intro" type="center" %}
