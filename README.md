# NodeNatural.Backgrounds.Original - NodeNatural preinstalled background images #

This collection of images was made for
[NodeNatural](https://github.com/alinarezrangel/node-natural), but because
their are licensed under the CC-BY-SA 4.0 (see [LICENSE](LICENSE)) you can
use these files according to the license.

## Authors (creators and contributors) ##

- Alejandro Linarez Rangel (all files)

## Images ##

All images with `background-material-*` are `1024x780px`, the
`background-themed-diamond-*` are `70x70px` and `background-themed-paper.png`
are `50x50px` (but can be displayed as `25x25px`).

The `background-material-*` are inspired by Google Material Design.

All files was created using [Inkscape](https://inkscape.org/en/) and Edited
with [GIMP](https://www.gimp.org/).

## Usage ##

The `background-material-*` are preferibly in all-screen, no-repeat mode:

```css
/* CSS3 */
.background {
	background: url("./background-material-sheets-1.png");
	background-repeat: no-repeat;
	background-position: center;
	background-attachment: fixed;
	background-size: cover;
}
```

While the `background-themed-*` should be in cover-screen, repeat-to-fill
mode:

```css
/* CSS3 */
.background {
	background: url("./background-themed-paper.png");
	background-repeat: repeat;
	background-position: center;
	background-attachment: fixed;
	/*
	* For paper use "25px 25px" but for diamonds use "70px 70px" or "50px 50px"
	*/
	background-size: 25px 25px;
}
```

See the [demo file](demo.html) for a web demo (open with your browser).

## NodeNatural install ##

These images comes preinstalled.

