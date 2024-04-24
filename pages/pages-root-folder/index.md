---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: breaking-chains1-banner.webp
widget1:
  title: "Explore the archives"
  url: '/blog/'
  image: archive_302px.webp
  text: 'Your journey to financial freedom starts here.'
widget2:
  title: "Upcoming seminars"
  url: '/calendar/'
  text: "Sign up for one of our in-person seminars and take control of our own capital."
  image: seminars_302px.webp 
widget3:
  title: "Video archive"
  url: '/videos'
  image: soon_302px.webp
  text: Browse our video archive of live seminars and talks.
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
  url: https://tinyletter.com/feeling-responsive
  text: Keep up to date on all seminars and special events ›
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
