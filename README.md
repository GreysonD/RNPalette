MyColorPalettes
===============

A simple tool for saving and managing your color palettes. Under the hood this is a simple AngularJS app, but no knowledge of Angular is required - just some basic work with JSON.

To manage your palettes open the file js/controllers.js.

The structure of each block is fairly simple:

```
{
	"title": "NAME OF THE PALETTE",
	"data": [
		{
			"name": "OPTIONAL OOLOR NAME - shows up in the tooltip",
			"code": "#HEXVALUE"
		},
		{
			"name": "ADD AS MANY COLORS AS YOU WANT",
			"code": "#HEXVALUE"
		}		
	],
	"tags": [
		"as many tags",
		"as you want"
	]
}
```

You can see an example page on http://fourtonfish.com/my-color-palettes/. You can search through your collection by palette name, tags and the optional color names. On the page above, try  to search for _favorite_, _bright_ or _jet black_.



![My Color Palette.app](/app-scr/app-beta.png)

UPDATE: I am already working on an app, you can preview it at [fourtonfish.com/my-color-palettes/app](http://fourtonfish.com/my-color-palettes/app/)


