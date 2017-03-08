# blend-layer

This is blending of image and color.

![blending palette](./palette.png)

It's very simple.
This is supplied from CSS.

For example, Just use below property.
```css
background-image: url(image.jpg);
background-color: #8f1313;
```

But, Black and white don't apply blend.
These is just seen only original color.

So, I set black to #333. This is bright a little more than #000(black).
```css
.black {
  background-color: #333;
}
```

And, White don't apply blend too.
So, I'm changed blend-mode of below.
```css
background-blend-mode: luminosity;
```
If you change blend-mode to luminosity, You'll see better.

If you feel laking about white, Try to change brightness.
```css
-webkit-filter: brightness(1.10);
```

Did you feel better?
