---
title: Loan Bank Report
summary: Data visualization project using Tableau to analyze banking loan data.
tags:
  - Data Visualization
date: "2023-01-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
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

# Slides (optional).
# Associate this project with Markdown slides.
# Simply enter your slide deck's filename without extension.
# E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
# Otherwise, set `slides = ""`.
slides: ""
---

[Project details to be added]

<div id="tableauViz" style="width: 100%; height: 600px;"></div>

<!-- Include the Tableau JavaScript API -->
<script src="https://public.tableau.com/javascripts/api/tableau-2.min.js"></script>

<script type="text/javascript">
  var divElement = document.getElementById('tableauViz');
  var vizURL = "https://public.tableau.com/views/Book1_17422518629290/DETAILS?:showVizHome=no&:embed=true";
  var options = {
    width: divElement.offsetWidth,
    height: divElement.offsetHeight,
    hideTabs: true,
    hideToolbar: true
  };
  var viz = new tableau.Viz(divElement, vizURL, options);
</script>
