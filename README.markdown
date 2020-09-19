# Animated SVG – Event Map

A Pen created on CodePen.io. Original URL: [https://codepen.io/tellaho/pen/PPRjbj](https://codepen.io/tellaho/pen/PPRjbj).

This animated SVG map was produced for Hallowbaloo.com, the website for an annual Halloween event in Honolulu.

The graphic went through several stages from Illustrator -> Sketch -> Sublime Text. Thank goodness I had an awesome graphic designer, Andreina Keller, getting me the original graphic.

I optimized the map down to less than 48kb through several iterations. The first run was to find all unnecessary code supplied by Sketch. The next run meant finding repeated elements in the map and making good use of \<def\> & \<use\>. The last run of optimization was taking the text supplied through my designer's graphic and converting them to \<text\> elements. All of a sudden, the file was tiny—relatively speaking—coming from an original 170kb.

By using some Jade 'include' statements, I was able to import the file inline into the proper template file. Sweet, I had SCSS control of all animation and styling.

See it live at http://hallowbaloo.com/2015/event-map. And check out the event if you're in town! ;)
