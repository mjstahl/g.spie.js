g.spie.js
=========

Spie chart for g.Raphael JS.

g.spie.js is a modification of g.pie.js.  The radius parameter expects
an array of radius' as opposed to a single value.

For more information about Spie charts refer to the following URLs:
https://en.wikipedia.org/wiki/Pie_chart#Spie_chart
http://addictedtor.free.fr/graphiques/RGraphGallery.php?graph=106

Usage
=====
```javascript
r = Raphael("holder-div-id");
r.spiechart(100, [90,50,75], [55,20,25], {
    colors: [#55B550, #DFC962, #DD6164]
}); 
```
