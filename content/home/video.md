+++
# Gallery section using the Blank widget and Gallery element (shortcode).
widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 5  # Order that this section will appear.


[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"
  height = "calc(100vh - 70px)"
  
title = "Animation"
subtitle = ""

[design.background]

  # Background image.
  image = "oxide.jpg"  # Name of image in `static/img/`.
  image_darken = 0.3  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  image_position = "center"  # Options include `left`, `center` (default), or `right`.
  image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
+++

{{< video library="1" src="zebra_video.mp4" controls="yes" autoplay="autoplay" loop="loop" preload="auto" >}}
