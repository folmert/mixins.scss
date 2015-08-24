# mixins.scss
Collection of useful mixins for an easier and more pleasant sass styling.

### How to use

In your base scss file add:

```css
@import "mixins";
```

and then you can extend your existing classes or include mixins by:
```scss
.btn {
  @include button3d($transition-time);
  @extend .flip-vertically;
}
```

