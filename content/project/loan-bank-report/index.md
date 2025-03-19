---
title: Loan Bank Report
summary: Data visualization project using Tableau to analyze banking loan data.
tags:
  - Data Visualization
date: "2023-01-01T00:00:00Z"
external_link: ""
image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart
links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
slides: ""
---

[Project details to be added]

<!-- CSS to make the container take up the full viewport -->
<style>
  html, body {
    margin: 0;
    padding: 0;
    height: 100%;
  }
  #tableauViz {
    width: 100vw;
    height: 100vh;
  }
</style>

<div id="tableauViz"></div>

<!-- Include the Tableau JavaScript API -->
<script src="https://public.tableau.com/javascripts/api/tableau-2.min.js"></script>

<script type="text/javascript">
  var divElement = document.getElementById('tableauViz');
  var vizURL = "https://public.tableau.com/views/Book1_17422518629290/DETAILS?:showVizHome=no&:embed=true";
  var options = {
    hideTabs: true,
    hideToolbar: true
  };
  var viz = new tableau.Viz(divElement, vizURL, options);
</script>
