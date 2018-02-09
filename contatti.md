---
layout: page
title: Contatti
sitemap:
priority: 1.0
changefreq: weekly
lastmod: 2014-09-07T16:31:30+05:30
---

# Contatti

Vivai Lariani di Conti Davide

Conti Davide  
Albese con Cassano (CO)  
Telefono: 320 0558323  
e-mail: davideconti79@libero.it  
pec: davideconti79@pec.it  
P.I.: 02730620131  
RUP: 03/1670  

<style>
  #map {
    height: 400px;
    width: 100%;
   }
</style>
<div id="map"></div>
<script>
  function initMap() {
    var albese = {lat: 45.793523, lng:9.1549696 };
    var map = new google.maps.Map(document.getElementById('map'), {
      zoom: 11,
      center: albese
    });
    var marker = new google.maps.Marker({
      position: albese,
      map: map
    });
  }
</script>
<script async defer
src="https://maps.googleapis.com/maps/api/js?key=AIzaSyBtvAsghl9MkyE2RSyB0Zz6jQO49jBBIXw&callback=initMap">
</script>


