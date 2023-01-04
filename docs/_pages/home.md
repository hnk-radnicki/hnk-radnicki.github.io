---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/aer1_PR1672831128537.jpeg
excerpt: >

feature_row:
  - image_path: /assets/images/vt0.jpg
    alt: "50 Godina Radničkog"
    title: "50 Godina Radničkog"
    excerpt: "Ovdje naručite svoju kopiju knjige"
    url: "/order/"
    btn_class: "btn--primary"
    btn_label: "Saznaj više"

  - image_path: /assets/images/vt1.jpg
    alt: "Sample Post 2"
    title: "Sample Post 2"
    excerpt: "Post 2"
    url: "/aboutn/"
    btn_class: "btn--primary"
    btn_label: "Saznaj više"

  - image_path: /assets/images/vt2.jpg
    alt: "Sample Post 3"
    title: "Sample Post 3"
    excerpt: "Post 3"
    url: "/about/"
    btn_class: "btn--primary"
    btn_label: "Saznaj više"

---

{% include feature_row %}

<!--SofaScore-->
<iframe id="sofa-standings-embed-91537-44800" 
		width="100%"
		height="381"
		src="https://www.sofascore.com/tournament/91537/44800/standings/tables/embed"
		frameborder="0"
		scrolling="no"
		style="height:381px!important">
</iframe>

<script>
(function(el) {
    window.addEventListener("message", (event) => {
        if (event.origin.startsWith("https://www.sofascore")) {
            if (el.id === event.data.id) {
                el.style.height = event.data.height + "px";
            }
        }
    });
})(document.getElementById("sofa-standings-embed-91537-44800"));
</script>

<script type="text/javascript" src="https://www.sofascore.com/bundles/sofascoreweb/js/bin/util/embed.min.js"></script>
<!--SofaScore end-->
