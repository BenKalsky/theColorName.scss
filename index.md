<h1>theColorName</h1>

<p>This library contain a SCSS mixin with all 141 CSS color names:</p>

```scss
@mixin tcn($property, $color) {
  #{$property}: #{$color};
}
```
<p>For example:</p>

```scss
@each $color in $colors {
  .theColorName {
    &.--#{$color} {
      @include tcn(color, $color);
    }
  }
}
```
<p>Will compile to:</p>

```css
.theColorName.--Tomato {
  color: Tomato;
}
```
<p>And the HTML:</p>

```html
<p class="theColorName --Tomato">I'm not a cucumber!</p>
```

<h3>All 141 colors:</h3>

<ul class="table-of-content">
  <li><p><a class="name">IndianRed</a></p><p class="hex">cd5c5c</p><p class="rgb">205, 92, 92</p></li>
  <li><p><a class="name">LightCoral</a></p><p class="hex">f08080</p><p class="rgb">240, 128, 128</p></li>
  <li><p><a class="name">Salmon</a></p><p class="hex">fa8072</p><p class="rgb">250, 128, 114</p></li>
  <li><p><a class="name">DarkSalmon</a></p><p class="hex">e9967a</p><p class="rgb">233, 150, 122</p></li>
  <li><p><a class="name">LightSalmon</a></p><p class="hex">ffa07a</p><p class="rgb">255, 160, 122</p></li>
  <li><p><a class="name">Crimson</a></p><p class="hex">dc143c</p><p class="rgb">220, 20, 60</p></li>
  <li><p><a class="name">Red</a></p><p class="hex">ff0000</p><p class="rgb">255, 0, 0</p></li>
  <li><p><a class="name">FireBrick</a></p><p class="hex">b22222</p><p class="rgb">178, 34, 34</p></li>
  <li><p><a class="name">DarkRed</a></p><p class="hex">8b0000</p><p class="rgb">139, 0, 0</p></li>
  <li><p><a class="name">Pink</a></p><p class="hex">ffc0cb</p><p class="rgb">255, 192, 203</p></li>
  <li><p><a class="name">LightPink</a></p><p class="hex">ffb6c1</p><p class="rgb">255, 182, 193</p></li>
  <li><p><a class="name">HotPink</a></p><p class="hex">ff69b4</p><p class="rgb">255, 105, 180</p></li>
  <li><p><a class="name">DeepPink</a></p><p class="hex">ff1493</p><p class="rgb">255, 20, 147</p></li>
  <li><p><a class="name">MediumVioletRed</a></p><p class="hex">c71585</p><p class="rgb">199, 21, 133</p></li>
  <li><p><a class="name">PaleVioletRed</a></p><p class="hex">db7093</p><p class="rgb">219, 112, 147</p></li>
  <li><p><a class="name">Coral</a></p><p class="hex">ff7f50</p><p class="rgb">255, 127, 80</p></li>
  <li><p><a class="name">Tomato</a></p><p class="hex">ff6347</p><p class="rgb">255, 99, 71</p></li>
  <li><p><a class="name">OrangeRed</a></p><p class="hex">ff4500</p><p class="rgb">255, 69, 0</p></li>
  <li><p><a class="name">DarkOrange</a></p><p class="hex">ff8c00</p><p class="rgb">255, 140, 0</p></li>
  <li><p><a class="name">Orange</a></p><p class="hex">ffa500</p><p class="rgb">255, 165, 0</p></li>
  <li><p><a class="name">Gold</a></p><p class="hex">ffd700</p><p class="rgb">255, 215, 0</p></li>
  <li><p><a class="name">Yellow</a></p><p class="hex">ffff00</p><p class="rgb">255, 255, 0</p></li>
  <li><p><a class="name">LightYellow</a></p><p class="hex">ffffe0</p><p class="rgb">255, 255, 224</p></li>
  <li><p><a class="name">LemonChiffon</a></p><p class="hex">fffacd</p><p class="rgb">255, 250, 205</p></li>
  <li><p><a class="name">LightGoldenRodYellow</a></p><p class="hex">fafad2</p><p class="rgb">250, 250, 210</p></li>
  <li><p><a class="name">PapayaWhip</a></p><p class="hex">ffefd5</p><p class="rgb">255, 239, 213</p></li>
  <li><p><a class="name">Moccasin</a></p><p class="hex">ffe4b5</p><p class="rgb">255, 228, 181</p></li>
  <li><p><a class="name">PeachPuff</a></p><p class="hex">ffdab9</p><p class="rgb">255, 218, 185</p></li>
  <li><p><a class="name">PaleGoldenRod</a></p><p class="hex">eee8aa</p><p class="rgb">238, 232, 170</p></li>
  <li><p><a class="name">Khaki</a></p><p class="hex">f0e68c</p><p class="rgb">240, 230, 140</p></li>
  <li><p><a class="name">DarkKhaki</a></p><p class="hex">bdb76b</p><p class="rgb">189, 183, 107</p></li>
  <li><p><a class="name">Lavender</a></p><p class="hex">e6e6fa</p><p class="rgb">230, 230, 250</p></li>
  <li><p><a class="name">Thistle</a></p><p class="hex">d8bfd8</p><p class="rgb">216, 191, 216</p></li>
  <li><p><a class="name">Plum</a></p><p class="hex">dda0dd</p><p class="rgb">221, 160, 221</p></li>
  <li><p><a class="name">Violet</a></p><p class="hex">ee82ee</p><p class="rgb">238, 130, 238</p></li>
  <li><p><a class="name">Orchid</a></p><p class="hex">da70d6</p><p class="rgb">218, 112, 214</p></li>
  <li><p><a class="name">Fuchsia</a></p><p class="hex">ff00ff</p><p class="rgb">255, 0, 255</p></li>
  <li><p><a class="name">Magenta</a></p><p class="hex">ff00ff</p><p class="rgb">255, 0, 255</p></li>
  <li><p><a class="name">MediumOrchid</a></p><p class="hex">ba55d3</p><p class="rgb">186, 85, 211</p></li>
  <li><p><a class="name">MediumPurple</a></p><p class="hex">9370db</p><p class="rgb">147, 112, 219</p></li>
  <li><p><a class="name">RebeccaPurple</a></p><p class="hex">663399</p><p class="rgb">102, 51, 153</p></li>
  <li><p><a class="name">BlueViolet</a></p><p class="hex">8a2be2</p><p class="rgb">138, 43, 226</p></li>
  <li><p><a class="name">DarkViolet</a></p><p class="hex">9400d3</p><p class="rgb">148, 0, 211</p></li>
  <li><p><a class="name">DarkOrchid</a></p><p class="hex">9932cc</p><p class="rgb">153, 50, 204</p></li>
  <li><p><a class="name">DarkMagenta</a></p><p class="hex">8b008b</p><p class="rgb">139, 0, 139</p></li>
  <li><p><a class="name">Purple</a></p><p class="hex">800080</p><p class="rgb">128, 0, 128</p></li>
  <li><p><a class="name">Indigo</a></p><p class="hex">4b0082</p><p class="rgb">75, 0, 130</p></li>
  <li><p><a class="name">SlateBlue</a></p><p class="hex">6a5acd</p><p class="rgb">106, 90, 205</p></li>
  <li><p><a class="name">DarkSlateBlue</a></p><p class="hex">483d8b</p><p class="rgb">72, 61, 139</p></li>
  <li><p><a class="name">MediumSlateBlue</a></p><p class="hex">7b68ee</p><p class="rgb">123, 104, 238</p></li>
  <li><p><a class="name">GreenYellow</a></p><p class="hex">adff2f</p><p class="rgb">173, 255, 47</p></li>
  <li><p><a class="name">Chartreuse</a></p><p class="hex">7fff00</p><p class="rgb">127, 255, 0</p></li>
  <li><p><a class="name">LawnGreen</a></p><p class="hex">7cfc00</p><p class="rgb">124, 252, 0</p></li>
  <li><p><a class="name">Lime</a></p><p class="hex">00ff00</p><p class="rgb">0, 255, 0</p></li>
  <li><p><a class="name">LimeGreen</a></p><p class="hex">32cd32</p><p class="rgb">50, 205, 50</p></li>
  <li><p><a class="name">PaleGreen</a></p><p class="hex">98fb98</p><p class="rgb">152, 251, 152</p></li>
  <li><p><a class="name">LightGreen</a></p><p class="hex">90ee90</p><p class="rgb">144, 238, 144</p></li>
  <li><p><a class="name">MediumSpringGreen</a></p><p class="hex">00fa9a</p><p class="rgb">0, 250, 154</p></li>
  <li><p><a class="name">SpringGreen</a></p><p class="hex">00ff7f</p><p class="rgb">0, 255, 127</p></li>
  <li><p><a class="name">MediumSeaGreen</a></p><p class="hex">3cb371</p><p class="rgb">60, 179, 113</p></li>
  <li><p><a class="name">SeaGreen</a></p><p class="hex">2e8b57</p><p class="rgb">46, 139, 87</p></li>
  <li><p><a class="name">ForestGreen</a></p><p class="hex">228b22</p><p class="rgb">34, 139, 34</p></li>
  <li><p><a class="name">Green</a></p><p class="hex">008000</p><p class="rgb">0, 128, 0</p></li>
  <li><p><a class="name">DarkGreen</a></p><p class="hex">006400</p><p class="rgb">0, 100, 0</p></li>
  <li><p><a class="name">YellowGreen</a></p><p class="hex">9acd32</p><p class="rgb">154, 205, 50</p></li>
  <li><p><a class="name">OliveDrab</a></p><p class="hex">6b8e23</p><p class="rgb">107, 142, 35</p></li>
  <li><p><a class="name">Olive</a></p><p class="hex">808000</p><p class="rgb">128, 128, 0</p></li>
  <li><p><a class="name">DarkOliveGreen</a></p><p class="hex">556b2f</p><p class="rgb">85, 107, 47</p></li>
  <li><p><a class="name">MediumAquaMarine</a></p><p class="hex">66cdaa</p><p class="rgb">102, 205, 170</p></li>
  <li><p><a class="name">DarkSeaGreen</a></p><p class="hex">8fbc8b</p><p class="rgb">143, 188, 139</p></li>
  <li><p><a class="name">LightSeaGreen</a></p><p class="hex">20b2aa</p><p class="rgb">32, 178, 170</p></li>
  <li><p><a class="name">DarkCyan</a></p><p class="hex">008b8b</p><p class="rgb">0, 139, 139</p></li>
  <li><p><a class="name">Teal</a></p><p class="hex">008080</p><p class="rgb">0, 128, 128</p></li>
  <li><p><a class="name">Aqua</a></p><p class="hex">00ffff</p><p class="rgb">0, 255, 255</p></li>
  <li><p><a class="name">Cyan</a></p><p class="hex">00ffff</p><p class="rgb">0, 255, 255</p></li>
  <li><p><a class="name">LightCyan</a></p><p class="hex">e0ffff</p><p class="rgb">224, 255, 255</p></li>
  <li><p><a class="name">PaleTurquoise</a></p><p class="hex">afeeee</p><p class="rgb">175, 238, 238</p></li>
  <li><p><a class="name">Aquamarine</a></p><p class="hex">7fffd4</p><p class="rgb">127, 255, 212</p></li>
  <li><p><a class="name">Turquoise</a></p><p class="hex">40e0d0</p><p class="rgb">64, 224, 208</p></li>
  <li><p><a class="name">MediumTurquoise</a></p><p class="hex">48d1cc</p><p class="rgb">72, 209, 204</p></li>
  <li><p><a class="name">DarkTurquoise</a></p><p class="hex">00ced1</p><p class="rgb">0, 206, 209</p></li>
  <li><p><a class="name">CadetBlue</a></p><p class="hex">5f9ea0</p><p class="rgb">95, 158, 160</p></li>
  <li><p><a class="name">SteelBlue</a></p><p class="hex">4682b4</p><p class="rgb">70, 130, 180</p></li>
  <li><p><a class="name">LightSteelBlue</a></p><p class="hex">b0c4de</p><p class="rgb">176, 196, 222</p></li>
  <li><p><a class="name">PowderBlue</a></p><p class="hex">b0e0e6</p><p class="rgb">176, 224, 230</p></li>
  <li><p><a class="name">LightBlue</a></p><p class="hex">add8e6</p><p class="rgb">173, 216, 230</p></li>
  <li><p><a class="name">SkyBlue</a></p><p class="hex">87ceeb</p><p class="rgb">135, 206, 235</p></li>
  <li><p><a class="name">LightSkyBlue</a></p><p class="hex">87cefa</p><p class="rgb">135, 206, 250</p></li>
  <li><p><a class="name">DeepSkyBlue</a></p><p class="hex">00bfff</p><p class="rgb">0, 191, 255</p></li>
  <li><p><a class="name">DodgerBlue</a></p><p class="hex">1e90ff</p><p class="rgb">30, 144, 255</p></li>
  <li><p><a class="name">CornfFlowerBlue</a></p><p class="hex">6495ed</p><p class="rgb">100, 149, 237</p></li>
  <li><p><a class="name">RoyalBlue</a></p><p class="hex">4169e1</p><p class="rgb">65, 105, 225</p></li>
  <li><p><a class="name">Blue</a></p><p class="hex">0000ff</p><p class="rgb">0, 0, 255</p></li>
  <li><p><a class="name">MediumBlue</a></p><p class="hex">0000cd</p><p class="rgb">0, 0, 205</p></li>
  <li><p><a class="name">DarkBlue</a></p><p class="hex">00008b</p><p class="rgb">0, 0, 139</p></li>
  <li><p><a class="name">Navy</a></p><p class="hex">000080</p><p class="rgb">0, 0, 128</p></li>
  <li><p><a class="name">MidnightBlue</a></p><p class="hex">191970</p><p class="rgb">25, 25, 112</p></li>
  <li><p><a class="name">Cornsilk</a></p><p class="hex">fff8dc</p><p class="rgb">255, 248, 220</p></li>
  <li><p><a class="name">BlanchedAlmond</a></p><p class="hex">ffebcd</p><p class="rgb">255, 235, 205</p></li>
  <li><p><a class="name">Bisque</a></p><p class="hex">ffe4c4</p><p class="rgb">255, 228, 196</p></li>
  <li><p><a class="name">NavajoWhite</a></p><p class="hex">ffdead</p><p class="rgb">255, 222, 173</p></li>
  <li><p><a class="name">Wheat</a></p><p class="hex">f5deb3</p><p class="rgb">245, 222, 179</p></li>
  <li><p><a class="name">BurlyWood</a></p><p class="hex">deb887</p><p class="rgb">222, 184, 135</p></li>
  <li><p><a class="name">Tan</a></p><p class="hex">d2b48c</p><p class="rgb">210, 180, 140</p></li>
  <li><p><a class="name">RosyBrown</a></p><p class="hex">bc8f8f</p><p class="rgb">188, 143, 143</p></li>
  <li><p><a class="name">SandyBrown</a></p><p class="hex">f4a460</p><p class="rgb">244, 164, 96</p></li>
  <li><p><a class="name">Goldenrod</a></p><p class="hex">daa520</p><p class="rgb">218, 165, 32</p></li>
  <li><p><a class="name">DarkGoldenRod</a></p><p class="hex">b8860b</p><p class="rgb">184, 134, 11</p></li>
  <li><p><a class="name">Peru</a></p><p class="hex">cd853f</p><p class="rgb">205, 133, 63</p></li>
  <li><p><a class="name">Chocolate</a></p><p class="hex">d2691e</p><p class="rgb">210, 105, 30</p></li>
  <li><p><a class="name">SaddleBrown</a></p><p class="hex">8b4513</p><p class="rgb">139, 69, 19</p></li>
  <li><p><a class="name">Sienna</a></p><p class="hex">a0522d</p><p class="rgb">160, 82, 45</p></li>
  <li><p><a class="name">Brown</a></p><p class="hex">a52a2a</p><p class="rgb">165, 42, 42</p></li>
  <li><p><a class="name">Maroon</a></p><p class="hex">800000</p><p class="rgb">128, 0, 0</p></li>
  <li><p><a class="name">White</a></p><p class="hex">ffffff</p><p class="rgb">255, 255, 255</p></li>
  <li><p><a class="name">Snow</a></p><p class="hex">fffafa</p><p class="rgb">255, 250, 250</p></li>
  <li><p><a class="name">HoneyDew</a></p><p class="hex">f0fff0</p><p class="rgb">240, 255, 240</p></li>
  <li><p><a class="name">MintCream</a></p><p class="hex">f5fffa</p><p class="rgb">245, 255, 250</p></li>
  <li><p><a class="name">Azure</a></p><p class="hex">f0ffff</p><p class="rgb">240, 255, 255</p></li>
  <li><p><a class="name">AliceBlue</a></p><p class="hex">f0f8ff</p><p class="rgb">240, 248, 255</p></li>
  <li><p><a class="name">GhostWhite</a></p><p class="hex">f8f8ff</p><p class="rgb">248, 248, 255</p></li>
  <li><p><a class="name">WhiteSmoke</a></p><p class="hex">f5f5f5</p><p class="rgb">245, 245, 245</p></li>
  <li><p><a class="name">SeaShell</a></p><p class="hex">fff5ee</p><p class="rgb">255, 245, 238</p></li>
  <li><p><a class="name">Beige</a></p><p class="hex">f5f5dc</p><p class="rgb">245, 245, 220</p></li>
  <li><p><a class="name">OldLace</a></p><p class="hex">fdf5e6</p><p class="rgb">253, 245, 230</p></li>
  <li><p><a class="name">FloralWhite</a></p><p class="hex">fffaf0</p><p class="rgb">255, 250, 240</p></li>
  <li><p><a class="name">Ivory</a></p><p class="hex">fffff0</p><p class="rgb">255, 255, 240</p></li>
  <li><p><a class="name">AntiqueWhite</a></p><p class="hex">faebd7</p><p class="rgb">250, 235, 215</p></li>
  <li><p><a class="name">Linen</a></p><p class="hex">faf0e6</p><p class="rgb">250, 240, 230</p></li>
  <li><p><a class="name">LavenderBlush</a></p><p class="hex">fff0f5</p><p class="rgb">255, 240, 245</p></li>
  <li><p><a class="name">MistyRose</a></p><p class="hex">ffe4e1</p><p class="rgb">255, 228, 225</p></li>
  <li><p><a class="name">Gainsboro</a></p><p class="hex">dcdcdc</p><p class="rgb">220, 220, 220</p></li>
  <li><p><a class="name">LightGray</a></p><p class="hex">d3d3d3</p><p class="rgb">211, 211, 211</p></li>
  <li><p><a class="name">Silver</a></p><p class="hex">c0c0c0</p><p class="rgb">192, 192, 192</p></li>
  <li><p><a class="name">DarkGray</a></p><p class="hex">a9a9a9</p><p class="rgb">169, 169, 169</p></li>
  <li class="gray"><p><a class="name">Gray</a></p><p class="hex">808080</p><p class="rgb">128, 128, 128</p></li>
  <li><p><a class="name">DimGray</a></p><p class="hex">696969</p><p class="rgb">105, 105, 105</p></li>
  <li><p><a class="name">LightSlateGray</a></p><p class="hex">778899</p><p class="rgb">119, 136, 153</p></li>
  <li><p><a class="name">SlateGray</a></p><p class="hex">708090</p><p class="rgb">112, 128, 144</p></li>
  <li><p><a class="name">DarkSlateGray</a></p><p class="hex">2f4f4f</p><p class="rgb">47, 79, 79</p></li>
  <li><p><a class="name">Black</a></p><p class="hex">000000</p><p class="rgb">0, 0, 0</p></li>
</ul>

<p>This project is just for fun =]</p>

<p>Cheers</p>
