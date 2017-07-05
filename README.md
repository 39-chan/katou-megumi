Custom Animu Homepage
====

![alt tag](https://my.mixtape.moe/jvfnza.jpg "Homepage preview")

Live demo: 
* https://39-chan.github.io/katou-megumi

This repository contains a modified shits of a awesome work by Gokouri-san. Feel free to download and modify. Comments and suggestions appreciated. Please don't expect too much.

Features:
* Switchable on-the-fly boring themes
* Over 69+ random bullshit quotes
* 5 Fucking useless searchboxes
* 4chan weeb links
* Reddit weeb links
* High-res animu fap material links
* Illegal animu download links
* Illegal animu streaming links (with 1 legal tho)
* Very useful sauce links

Customizing, adding mascots and themes
----
 ̶T̶o̶ ̶c̶h̶a̶n̶g̶e̶ ̶c̶u̶r̶r̶e̶n̶t̶ ̶t̶h̶e̶m̶e̶,̶ ̶r̶e̶p̶l̶a̶c̶e̶ ̶i̶t̶s̶ ̶n̶a̶m̶e̶ ̶i̶n̶ [index.html](index.html#L15-17)
Now you don't need to manually replacing the css name if you want to change the theme, just press a buttons / text / whatever you call it, on the bottom right
 
To customize the mascots of all themes, modify the array in [themes/mascots.js](themes/mascots.js):
```javascript
var mascotList = [ "katou-01.png", "katou-02.png", "katou-03.png" "katou-04.png" "katou-05.png" "katou-06.png"];
```

To make a new theme, you can copy an existing one, and change images and [colors-dark.css](themes/colors-dark.css) or [colors-light.css](themes/colors-light.css) as you like.  
Please note that entries in your theme's [mascots.js](themes/mascots.js) should match with contents of [mascots/](themes/mascots/) directory.  

Disclaimer
----
Base codes are written by Gokouri. I only modified some (I actually modified a lot) of his/her codes to suites my need.

All Katou illustrations used in this work are drawn stolen from pixiv. (I'll write the credit later)