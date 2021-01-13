#DIY CSS Framework

### Overview

I build this basic CSS framework for the sake of learning CSS and making utility first classes. It is basically a Bootstrap like framework. You use row class and then you can position up to 12 columns inside a row.

### Focus of exercise

- learning to build my own CSS framework
- responsive design

### How it works?

To make a 12 column layout you have to first position a row, and inside you should position up to 12 columns.

```html
<div class="row">
  <div class="col">example</div>
  <div class="col">example2</div>
</div>
```

This makes us two same sized columns.

### Grid breakpoints

Breakpoints that I used are the same as in bootstrap, and you also have appropriate classes for \
different sized screens.

-Such as:\

- lg = min-width 1200px
- md = min-width 992px
- sm = max-width 768px

## References

[Bootstrap documentation](https://getbootstrap.com/docs/4.0/getting-started/introduction/)
[Tailwind CSS documentation](https://tailwindcss.com/docs)
