---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_sphere.jpg
widget1:
  title: "Blog"
  url: 'http://antworteffekt.github.io/blog/'
  image: widget-1-302x182.jpg
  text: 'Periodically updated with fresh news, thoughts and activities.'
widget2:
  title: "Projects"
  url: 'http://antworteffekt.github.io/projects/'
  text: 'Some things I have been busy with.'
  image: stuff-3.pdf
widget3:
  title: "About me"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: 'Information on me.'

permalink: /index.html
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
