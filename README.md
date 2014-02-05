grAB
====

grAB is a light-weight ObjO AB testing platform that can replace html, change css, or redirect based off cookie settings generated by grAB or by the "cam" value passed to the URL.  From here, you can send campaign values from grAB to your tracking service or conversion pixels to decide which parts of the site actually make you money.

Examples:

* [Change CSS](http://brandonam.com/grAB/grAB-example/?cam=a)

Code:

	`grAB.changeCss('campaign','jQuery element', '[array of css]');`

* [Insert HTML from another file](http://brandonam.com/grAB/grAB-example/?cam=b)

Code:

	`grAB.replaceHtml(campaign, jQuery element, file path);`	

* [Simple Redirect](http://brandonam.com/grAB/grAB-example/?cam=c)

Code:

	`grAB.changeUrl(campaign, full url);`