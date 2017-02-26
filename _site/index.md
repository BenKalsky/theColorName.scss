# theColorName

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

<ul class="table-of-content">
  <li>IndianRed | #cd5c5c | rgb(205, 92, 92)</li>
  <li>LightCoral | #f08080 | rgb(240, 128, 128)</li>
  <li>Salmon | #fa8072 | rgb(250, 128, 114)</li>
  <li>DarkSalmon | #e9967a | rgb(233, 150, 122)</li>
  <li>LightSalmon | #ffa07a | rgb(255, 160, 122)</li>
  <li>Crimson | #dc143c | rgb(220, 20, 60)</li>
  <li>Red | #ff0000 | rgb(255, 0, 0)</li>
  <li>FireBrick | #b22222 | rgb(178, 34, 34)</li>
  <li>DarkRed | #8b0000 | rgb(139, 0, 0)</li>
  <li>Pink | #ffc0cb | rgb(255, 192, 203)</li>
  <li>LightPink | #ffb6c1 | rgb(255, 182, 193)</li>
  <li>HotPink | #ff69b4 | rgb(255, 105, 180)</li>
  <li>DeepPink | #ff1493 | rgb(255, 20, 147)</li>
  <li>MediumVioletRed | #c71585 | rgb(199, 21, 133)</li>
  <li>PaleVioletRed | #db7093 | rgb(219, 112, 147)</li>
  <li>Coral | #ff7f50 | rgb(255, 127, 80)</li>
  <li>Tomato | #ff6347 | rgb(255, 99, 71)</li>
  <li>OrangeRed | #ff4500 | rgb(255, 69, 0)</li>
  <li>DarkOrange | #ff8c00 | rgb(255, 140, 0)</li>
  <li>Orange | #ffa500 | rgb(255, 165, 0)</li>
  <li>Gold | #ffd700 | rgb(255, 215, 0)</li>
  <li>Yellow | #ffff00 | rgb(255, 255, 0)</li>
  <li>LightYellow | #ffffe0 | rgb(255, 255, 224)</li>
  <li>LemonChiffon | #fffacd | rgb(255, 250, 205)</li>
  <li>LightGoldenRodYellow | #fafad2 | rgb(250, 250, 210)</li>
  <li>PapayaWhip | #ffefd5 | rgb(255, 239, 213)</li>
  <li>Moccasin | #ffe4b5 | rgb(255, 228, 181)</li>
  <li>PeachPuff | #ffdab9 | rgb(255, 218, 185)</li>
  <li>PaleGoldenRod | #eee8aa | rgb(238, 232, 170)</li>
  <li>Khaki | #f0e68c | rgb(240, 230, 140)</li>
  <li>DarkKhaki | #bdb76b | rgb(189, 183, 107)</li>
  <li>Lavender | #e6e6fa | rgb(230, 230, 250)</li>
  <li>Thistle | #d8bfd8 | rgb(216, 191, 216)</li>
  <li>Plum | #dda0dd | rgb(221, 160, 221)</li>
  <li>Violet | #ee82ee | rgb(238, 130, 238)</li>
  <li>Orchid | #da70d6 | rgb(218, 112, 214)</li>
  <li>Fuchsia | #ff00ff | rgb(255, 0, 255)</li>
  <li>Magenta | #ff00ff | rgb(255, 0, 255)</li>
  <li>MediumOrchid | #ba55d3 | rgb(186, 85, 211)</li>
  <li>MediumPurple | #9370db | rgb(147, 112, 219)</li>
  <li>RebeccaPurple | #663399 | rgb(102, 51, 153)</li>
  <li>BlueViolet | #8a2be2 | rgb(138, 43, 226)</li>
  <li>DarkViolet | #9400d3 | rgb(148, 0, 211)</li>
  <li>DarkOrchid | #9932cc | rgb(153, 50, 204)</li>
  <li>DarkMagenta | #8b008b | rgb(139, 0, 139)</li>
  <li>Purple | #800080 | rgb(128, 0, 128)</li>
  <li>Indigo | #4b0082 | rgb(75, 0, 130)</li>
  <li>SlateBlue | #6a5acd | rgb(106, 90, 205)</li>
  <li>DarkSlateBlue | #483d8b | rgb(72, 61, 139)</li>
  <li>MediumSlateBlue | #7b68ee | rgb(123, 104, 238)</li>
  <li>GreenYellow | #adff2f | rgb(173, 255, 47)</li>
  <li>Chartreuse | #7fff00 | rgb(127, 255, 0)</li>
  <li>LawnGreen | #7cfc00 | rgb(124, 252, 0)</li>
  <li>Lime | #00ff00 | rgb(0, 255, 0)</li>
  <li>LimeGreen | #32cd32 | rgb(50, 205, 50)</li>
  <li>PaleGreen | #98fb98 | rgb(152, 251, 152)</li>
  <li>LightGreen | #90ee90 | rgb(144, 238, 144)</li>
  <li>MediumSpringGreen | #00fa9a | rgb(0, 250, 154)</li>
  <li>SpringGreen | #00ff7f | rgb(0, 255, 127)</li>
  <li>MediumSeaGreen | #3cb371 | rgb(60, 179, 113)</li>
  <li>SeaGreen | #2e8b57 | rgb(46, 139, 87)</li>
  <li>ForestGreen | #228b22 | rgb(34, 139, 34)</li>
  <li>Green | #008000 | rgb(0, 128, 0)</li>
  <li>DarkGreen | #006400 | rgb(0, 100, 0)</li>
  <li>YellowGreen | #9acd32 | rgb(154, 205, 50)</li>
  <li>OliveDrab | #6b8e23 | rgb(107, 142, 35)</li>
  <li>Olive | #808000 | rgb(128, 128, 0)</li>
  <li>DarkOliveGreen | #556b2f | rgb(85, 107, 47)</li>
  <li>MediumAquaMarine | #66cdaa | rgb(102, 205, 170)</li>
  <li>DarkSeaGreen | #8fbc8b | rgb(143, 188, 139)</li>
  <li>LightSeaGreen | #20b2aa | rgb(32, 178, 170)</li>
  <li>DarkCyan | #008b8b | rgb(0, 139, 139)</li>
  <li>Teal | #008080 | rgb(0, 128, 128)</li>
  <li>Aqua | #00ffff | rgb(0, 255, 255)</li>
  <li>Cyan | #00ffff | rgb(0, 255, 255)</li>
  <li>LightCyan | #e0ffff | rgb(224, 255, 255)</li>
  <li>PaleTurquoise | #afeeee | rgb(175, 238, 238)</li>
  <li>Aquamarine | #7fffd4 | rgb(127, 255, 212)</li>
  <li>Turquoise | #40e0d0 | rgb(64, 224, 208)</li>
  <li>MediumTurquoise | #48d1cc | rgb(72, 209, 204)</li>
  <li>DarkTurquoise | #00ced1 | rgb(0, 206, 209)</li>
  <li>CadetBlue | #5f9ea0 | rgb(95, 158, 160)</li>
  <li>SteelBlue | #4682b4 | rgb(70, 130, 180)</li>
  <li>LightSteelBlue | #b0c4de | rgb(176, 196, 222)</li>
  <li>PowderBlue | #b0e0e6 | rgb(176, 224, 230)</li>
  <li>LightBlue | #add8e6 | rgb(173, 216, 230)</li>
  <li>SkyBlue | #87ceeb | rgb(135, 206, 235)</li>
  <li>LightSkyBlue | #87cefa | rgb(135, 206, 250)</li>
  <li>DeepSkyBlue | #00bfff | rgb(0, 191, 255)</li>
  <li>DodgerBlue | #1e90ff | rgb(30, 144, 255)</li>
  <li>CornfFlowerBlue | #6495ed | rgb(100, 149, 237)</li>
  <li>RoyalBlue | #4169e1 | rgb(65, 105, 225)</li>
  <li>Blue | #0000ff | rgb(0, 0, 255)</li>
  <li>MediumBlue | #0000cd | rgb(0, 0, 205)</li>
  <li>DarkBlue | #00008b | rgb(0, 0, 139)</li>
  <li>Navy | #000080 | rgb(0, 0, 128)</li>
  <li>MidnightBlue | #191970 | rgb(25, 25, 112)</li>
  <li>Cornsilk | #fff8dc | rgb(255, 248, 220)</li>
  <li>BlanchedAlmond | #ffebcd | rgb(255, 235, 205)</li>
  <li>Bisque | #ffe4c4 | rgb(255, 228, 196)</li>
  <li>NavajoWhite | #ffdead | rgb(255, 222, 173)</li>
  <li>Wheat | #f5deb3 | rgb(245, 222, 179)</li>
  <li>BurlyWood | #deb887 | rgb(222, 184, 135)</li>
  <li>Tan | #d2b48c | rgb(210, 180, 140)</li>
  <li>RosyBrown | #bc8f8f | rgb(188, 143, 143)</li>
  <li>SandyBrown | #f4a460 | rgb(244, 164, 96)</li>
  <li>Goldenrod | #daa520 | rgb(218, 165, 32)</li>
  <li>DarkGoldenRod | #b8860b | rgb(184, 134, 11)</li>
  <li>Peru | #cd853f | rgb(205, 133, 63)</li>
  <li>Chocolate | #d2691e | rgb(210, 105, 30)</li>
  <li>SaddleBrown | #8b4513 | rgb(139, 69, 19)</li>
  <li>Sienna | #a0522d | rgb(160, 82, 45)</li>
  <li>Brown | #a52a2a | rgb(165, 42, 42)</li>
  <li>Maroon | #800000 | rgb(128, 0, 0)</li>
  <li>White | #ffffff | rgb(255, 255, 255)</li>
  <li>Snow | #fffafa | rgb(255, 250, 250)</li>
  <li>HoneyDew | #f0fff0 | rgb(240, 255, 240)</li>
  <li>MintCream | #f5fffa | rgb(245, 255, 250)</li>
  <li>Azure | #f0ffff | rgb(240, 255, 255)</li>
  <li>AliceBlue | #f0f8ff | rgb(240, 248, 255)</li>
  <li>GhostWhite | #f8f8ff | rgb(248, 248, 255)</li>
  <li>WhiteSmoke | #f5f5f5 | rgb(245, 245, 245)</li>
  <li>SeaShell | #fff5ee | rgb(255, 245, 238)</li>
  <li>Beige | #f5f5dc | rgb(245, 245, 220)</li>
  <li>OldLace | #fdf5e6 | rgb(253, 245, 230)</li>
  <li>FloralWhite | #fffaf0 | rgb(255, 250, 240)</li>
  <li>Ivory | #fffff0 | rgb(255, 255, 240)</li>
  <li>AntiqueWhite | #faebd7 | rgb(250, 235, 215)</li>
  <li>Linen | #faf0e6 | rgb(250, 240, 230)</li>
  <li>LavenderBlush | #fff0f5 | rgb(255, 240, 245)</li>
  <li>MistyRose | #ffe4e1 | rgb(255, 228, 225)</li>
  <li>Gainsboro | #dcdcdc | rgb(220, 220, 220)</li>
  <li>LightGray | #d3d3d3 | rgb(211, 211, 211)</li>
  <li>Silver | #c0c0c0 | rgb(192, 192, 192)</li>
  <li>DarkGray | #a9a9a9 | rgb(169, 169, 169)</li>
  <li>Gray | #808080 | rgb(128, 128, 128)</li>
  <li>DimGray | #696969 | rgb(105, 105, 105)</li>
  <li>LightSlateGray | #778899 | rgb(119, 136, 153)</li>
  <li>SlateGray | #708090 | rgb(112, 128, 144)</li>
  <li>DarkSlateGray | #2f4f4f | rgb(47, 79, 79)</li>
  <li>Black | #000000 | rgb(0, 0, 0)</li>
</ul>

This project is just for fun =]

Cheers