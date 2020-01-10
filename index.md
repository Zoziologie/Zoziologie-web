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
excerpt: "Learn more about bird using web apps!<br>"
intro: 
  - excerpt: '<img src="/assets/images/logo.png" style="width: 100px;" id="img-exp"><span id="exp" style="display:none;"><br><b>Do you wonder why the website has such a strange name?</b> <br> *Zoziologie* goes back to my childhood, when my brother made fun of my passion for birds ("oiseaux" in French) by calling it "zozio". As I grew older and pursued scientific studies, I tried to combine my passion with birds (zozio) with my scientific background (logos), that gave birth to a new discpline: zoziologie!</span>'
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
    title: "eBird 2 LaTeX"
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
    title: "Merge 2 Hotspot"
    excerpt: "Find existing hotspots for your personal locations on eBird."
    url: "/merge2hotspot/"
    btn_label: " " 
feature_row22:
  - image_path: /assets/GlobalRareeBird/images/grb_static.png
    image_path_2: /assets/GlobalRareeBird/images/grb.gif
    alt: "globalrareebird gif"
    title: "Global Rare eBird"
    excerpt: "See all rare birds from eBird."
    url: "/globalrareebird/"
    btn_label: " " 
  - image_path: /assets/QueryMapBiolovision/images/qmb_static.png
    image_path_2: /assets/QueryMapBiolovision/images/qmb.gif
    alt: "QueryMapBiolovision gif"
    title: "Query Map Biolovision"
    excerpt: "Search custum area on any biolovision websites."
    url: "/querymapbiolovision/"
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
    image_path_2: https://bmm.raphaelnussbaumer.com/2016/BMM-web.gif
    alt: "BMM web png"
    title: "Quantifying bird migration with weather radars"
    excerpt: 'In my work, I study the spatio-temporal patterns of nocturnal bird migration using weather radar data.'
    url: "https://bmm.raphaelnussbaumer.com/"
    btn_label: " " 
---

<img src="/assets/images/scroll-down.svg" id="scroll-down">

{% include feature_row %}

{% include feature_row id="feature_row2" %}

{% include feature_row id="feature_row22" %}

{% include feature_row id="feature_row4" type="center" %}

{% include feature_row id="intro" type="center" %}

<script>
  $("#scroll-down").click(function() {
    $('html,body').animate({
        scrollTop: $("#main").offset().top},
        'slow');
});
  $("#img-exp").hover(
    function() {
      $("#exp").show()
    },
    function () {
      $("#exp").hide();
    }
  );
</script>