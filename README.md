# [theColorNames](http://thecolorname.xyz)

This library contain a SCSS mixin with all 141 CSS color names:

```scss
@mixin tcn($property, $color) {
  #{$property}: #{$color};
}
```
For example:
```scss
@each $color in $colors {
  .theColorName {
    &.--#{$color} {
      @include tcn(color, $color);
    }
  }
}
```
Will compile to:
```css
.theColorName.--Tomato {
  color: Tomato;
}
```
And the HTML:
```html
<p class="theColorName --Tomato">I'm not a cucumber!</p>
```

### All 141 colors:

NAME | HEX | RGB
--- | --- | ---
IndianRed | #cd5c5c | rgb(205, 92, 92)
LightCoral | #f08080 | rgb(240, 128, 128)
Salmon | #fa8072 | rgb(250, 128, 114)
DarkSalmon | #e9967a | rgb(233, 150, 122)
LightSalmon | #ffa07a | rgb(255, 160, 122)
Crimson | #dc143c | rgb(220, 20, 60)
Red | #ff0000 | rgb(255, 0, 0)
FireBrick | #b22222 | rgb(178, 34, 34)
DarkRed | #8b0000 | rgb(139, 0, 0)
Pink | #ffc0cb | rgb(255, 192, 203)
LightPink | #ffb6c1 | rgb(255, 182, 193)
HotPink | #ff69b4 | rgb(255, 105, 180)
DeepPink | #ff1493 | rgb(255, 20, 147)
MediumVioletRed | #c71585 | rgb(199, 21, 133)
PaleVioletRed | #db7093 | rgb(219, 112, 147)
Coral | #ff7f50 | rgb(255, 127, 80)
Tomato | #ff6347 | rgb(255, 99, 71)
OrangeRed | #ff4500 | rgb(255, 69, 0)
DarkOrange | #ff8c00 | rgb(255, 140, 0)
Orange | #ffa500 | rgb(255, 165, 0)
Gold | #ffd700 | rgb(255, 215, 0)
Yellow | #ffff00 | rgb(255, 255, 0)
LightYellow | #ffffe0 | rgb(255, 255, 224)
LemonChiffon | #fffacd | rgb(255, 250, 205)
LightGoldenRodYellow | #fafad2 | rgb(250, 250, 210)
PapayaWhip | #ffefd5 | rgb(255, 239, 213)
Moccasin | #ffe4b5 | rgb(255, 228, 181)
PeachPuff | #ffdab9 | rgb(255, 218, 185)
PaleGoldenRod | #eee8aa | rgb(238, 232, 170)
Khaki | #f0e68c | rgb(240, 230, 140)
DarkKhaki | #bdb76b | rgb(189, 183, 107)
Lavender | #e6e6fa | rgb(230, 230, 250)
Thistle | #d8bfd8 | rgb(216, 191, 216)
Plum | #dda0dd | rgb(221, 160, 221)
Violet | #ee82ee | rgb(238, 130, 238)
Orchid | #da70d6 | rgb(218, 112, 214)
Fuchsia | #ff00ff | rgb(255, 0, 255)
Magenta | #ff00ff | rgb(255, 0, 255)
MediumOrchid | #ba55d3 | rgb(186, 85, 211)
MediumPurple | #9370db | rgb(147, 112, 219)
RebeccaPurple | #663399 | rgb(102, 51, 153)
BlueViolet | #8a2be2 | rgb(138, 43, 226)
DarkViolet | #9400d3 | rgb(148, 0, 211)
DarkOrchid | #9932cc | rgb(153, 50, 204)
DarkMagenta | #8b008b | rgb(139, 0, 139)
Purple | #800080 | rgb(128, 0, 128)
Indigo | #4b0082 | rgb(75, 0, 130)
SlateBlue | #6a5acd | rgb(106, 90, 205)
DarkSlateBlue | #483d8b | rgb(72, 61, 139)
MediumSlateBlue | #7b68ee | rgb(123, 104, 238)
GreenYellow | #adff2f | rgb(173, 255, 47)
Chartreuse | #7fff00 | rgb(127, 255, 0)
LawnGreen | #7cfc00 | rgb(124, 252, 0)
Lime | #00ff00 | rgb(0, 255, 0)
LimeGreen | #32cd32 | rgb(50, 205, 50)
PaleGreen | #98fb98 | rgb(152, 251, 152)
LightGreen | #90ee90 | rgb(144, 238, 144)
MediumSpringGreen | #00fa9a | rgb(0, 250, 154)
SpringGreen | #00ff7f | rgb(0, 255, 127)
MediumSeaGreen | #3cb371 | rgb(60, 179, 113)
SeaGreen | #2e8b57 | rgb(46, 139, 87)
ForestGreen | #228b22 | rgb(34, 139, 34)
Green | #008000 | rgb(0, 128, 0)
DarkGreen | #006400 | rgb(0, 100, 0)
YellowGreen | #9acd32 | rgb(154, 205, 50)
OliveDrab | #6b8e23 | rgb(107, 142, 35)
Olive | #808000 | rgb(128, 128, 0)
DarkOliveGreen | #556b2f | rgb(85, 107, 47)
MediumAquaMarine | #66cdaa | rgb(102, 205, 170)
DarkSeaGreen | #8fbc8b | rgb(143, 188, 139)
LightSeaGreen | #20b2aa | rgb(32, 178, 170)
DarkCyan | #008b8b | rgb(0, 139, 139)
Teal | #008080 | rgb(0, 128, 128)
Aqua | #00ffff | rgb(0, 255, 255)
Cyan | #00ffff | rgb(0, 255, 255)
LightCyan | #e0ffff | rgb(224, 255, 255)
PaleTurquoise | #afeeee | rgb(175, 238, 238)
Aquamarine | #7fffd4 | rgb(127, 255, 212)
Turquoise | #40e0d0 | rgb(64, 224, 208)
MediumTurquoise | #48d1cc | rgb(72, 209, 204)
DarkTurquoise | #00ced1 | rgb(0, 206, 209)
CadetBlue | #5f9ea0 | rgb(95, 158, 160)
SteelBlue | #4682b4 | rgb(70, 130, 180)
LightSteelBlue | #b0c4de | rgb(176, 196, 222)
PowderBlue | #b0e0e6 | rgb(176, 224, 230)
LightBlue | #add8e6 | rgb(173, 216, 230)
SkyBlue | #87ceeb | rgb(135, 206, 235)
LightSkyBlue | #87cefa | rgb(135, 206, 250)
DeepSkyBlue | #00bfff | rgb(0, 191, 255)
DodgerBlue | #1e90ff | rgb(30, 144, 255)
CornfFlowerBlue | #6495ed | rgb(100, 149, 237)
RoyalBlue | #4169e1 | rgb(65, 105, 225)
Blue | #0000ff | rgb(0, 0, 255)
MediumBlue | #0000cd | rgb(0, 0, 205)
DarkBlue | #00008b | rgb(0, 0, 139)
Navy | #000080 | rgb(0, 0, 128)
MidnightBlue | #191970 | rgb(25, 25, 112)
Cornsilk | #fff8dc | rgb(255, 248, 220)
BlanchedAlmond | #ffebcd | rgb(255, 235, 205)
Bisque | #ffe4c4 | rgb(255, 228, 196)
NavajoWhite | #ffdead | rgb(255, 222, 173)
Wheat | #f5deb3 | rgb(245, 222, 179)
BurlyWood | #deb887 | rgb(222, 184, 135)
Tan | #d2b48c | rgb(210, 180, 140)
RosyBrown | #bc8f8f | rgb(188, 143, 143)
SandyBrown | #f4a460 | rgb(244, 164, 96)
Goldenrod | #daa520 | rgb(218, 165, 32)
DarkGoldenRod | #b8860b | rgb(184, 134, 11)
Peru | #cd853f | rgb(205, 133, 63)
Chocolate | #d2691e | rgb(210, 105, 30)
SaddleBrown | #8b4513 | rgb(139, 69, 19)
Sienna | #a0522d | rgb(160, 82, 45)
Brown | #a52a2a | rgb(165, 42, 42)
Maroon | #800000 | rgb(128, 0, 0)
White | #ffffff | rgb(255, 255, 255)
Snow | #fffafa | rgb(255, 250, 250)
HoneyDew | #f0fff0 | rgb(240, 255, 240)
MintCream | #f5fffa | rgb(245, 255, 250)
Azure | #f0ffff | rgb(240, 255, 255)
AliceBlue | #f0f8ff | rgb(240, 248, 255)
GhostWhite | #f8f8ff | rgb(248, 248, 255)
WhiteSmoke | #f5f5f5 | rgb(245, 245, 245)
SeaShell | #fff5ee | rgb(255, 245, 238)
Beige | #f5f5dc | rgb(245, 245, 220)
OldLace | #fdf5e6 | rgb(253, 245, 230)
FloralWhite | #fffaf0 | rgb(255, 250, 240)
Ivory | #fffff0 | rgb(255, 255, 240)
AntiqueWhite | #faebd7 | rgb(250, 235, 215)
Linen | #faf0e6 | rgb(250, 240, 230)
LavenderBlush | #fff0f5 | rgb(255, 240, 245)
MistyRose | #ffe4e1 | rgb(255, 228, 225)
Gainsboro | #dcdcdc | rgb(220, 220, 220)
LightGray | #d3d3d3 | rgb(211, 211, 211)
Silver | #c0c0c0 | rgb(192, 192, 192)
DarkGray | #a9a9a9 | rgb(169, 169, 169)
Gray | #808080 | rgb(128, 128, 128)
DimGray | #696969 | rgb(105, 105, 105)
LightSlateGray | #778899 | rgb(119, 136, 153)
SlateGray | #708090 | rgb(112, 128, 144)
DarkSlateGray | #2f4f4f | rgb(47, 79, 79)
Black | #000000 | rgb(0, 0, 0)

This project is just for fun =]

Cheers

[![Analytics](https://ga-beacon.appspot.com/UA-92303047-1/theColorName.scss/readme)](https://github.com/igrigorik/ga-beacon)
