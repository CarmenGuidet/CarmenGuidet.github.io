---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
title: "Home"
description: "Welcome to my site"
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

widget1:
  title: "Comunicaciones"
  url: 'http://carmenguidet.github.io/conoce/comunicaciones'
  image: "/images/comunicaciones.jpg"
  text: 'Aqui descubriras que es lo que nos perimite comunicarnos a largas distancias.'
widget2:
  title: "Electronica"
  url: 'http://carmenguidet.github.io/conoce/electronica'
  image: widget-1-302x182.jpg
  text: 'Una de las razones por las que nos podemos comunicar es gracias a la electronica.'
widget3:
  title: "Redes"
  url: 'http://carmenguidet.github.io/conoce/redes'
  image: ""
  text: 'Las redes como el Intenet nos permite estar comunicados en todo momento.'


callforaction:
  url1: http://carmenguidet.github.io/experimenta/casa
  text1: Experimenta y crea desde casa 
  style1: alert
  url2: https://tinyletter.com/feeling-responsive
  text2: Para profesorado
  style2: alert

permalink: /index.html

#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true

--- 