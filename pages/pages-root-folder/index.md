---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header-ml.png
  
widget1:
  title: "Blog"
  url: 'https://mwessley.github.io/CDL_EML_webpage/blog/'
  text: 'These are our news'
widget2:
  title: "Research"
  url: 'https://mwessley.github.io/CDL_EML_webpage/research/'
  text: 'Research'
widget3:
  title: "People"
  url: 'https://mwessley.github.io/CDL_EML_webpage/people/'
  text: 'These are the people in the lab'


callforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html


#  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
#  image: widget-1-302x182.jpg
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
