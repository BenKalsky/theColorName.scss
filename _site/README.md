# theColorName

This library contain a SCSS mixin with all 142 CSS color names:

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

### All 142 colors:
[![Analytics](https://ga-beacon.appspot.com/UA-92303047-1/theColorName.scss/readme?pixel)](https://github.com/igrigorik/ga-beacon)
