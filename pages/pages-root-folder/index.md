---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: 9S8A7805-as-header.jpg
widget1:
  title: "Articles & Resources"
  url: '/blog/'
  image: 9S8A7864-thumb.JPG
  text: 'Here is where we will put articles about different relevant topics'
widget2:
  title: "We welcome your inquiries"
  url: '/contact/'
  image: talmud2.jpg
  text: 'We welcome inquiries from the public regarding all areas of Jewish business law.'
widget3:
  title: "Audio & Video"
  url: '/media/'
  image: Rabbi_Chaim_Mendelson_sm.jpg
  text: 'Audio and Video'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: /donate/
  text: Donate to support the Kollel
  style: alert
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
