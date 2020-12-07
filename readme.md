
This Website is generated using [**Jekyll Static Website Generator**](https://jekyllrb.com/docs/) and [**Minimal Mistakes**](https://mmistakes.github.io/minimal-mistakes/) theme.

## Jekyll Static Site Generator - Installation and Use
Please refer to Documentation:
https://jekyllrb.com/docs/
https://jekyllrb.com/docs/installation/


## Minimal Mistakes
Thanks to [**Minimal Mistakes**](https://mmistakes.github.io/minimal-mistakes/) for the great theme.

## Deviation From the Minimal Mistake theme

### Added new option "wide2" for layouts
Added a ``_sass`` folder with copy of `minimal-mistakes.scss` with following code copied at the end:
```html
/* Manually added for a wider layout (right side) */
.wide2 {
  .page {
    float: left;
    width: 100%;
    @include breakpoint($large) {
      padding-left: 0;
    }

    @include breakpoint($x-large) {
      padding-left: 0;
    }
  }

  .page__related {
    @include breakpoint($large) {
      padding-left: 0;
    }

    @include breakpoint($x-large) {
      padding-left: 0;
    }
  }
}
```

### Changed the overall font size
Added the following code in `\assets\css\main.scss`
(after the  code `@import "minimal-mistakes";`)

```html
html {
  font-size: 16px; // change to whatever //16

  @include breakpoint($medium) {
    font-size: 16px; // change to whatever //18
  }

  @include breakpoint($large) {
    font-size: 18px; // change to whatever //20
  }

  @include breakpoint($x-large) {
    font-size: 20px; // change to whatever //22
  }
}
```

### Changed the theme color
Added the following code in `\assets\css\main.scss`






### Added MathJax in _includes "scripts"



### Changed footer
Removed Powered by Jekyll i
Changed:
<div class="page__footer-copyright">&copy; {{ site.time | date: '%Y' }} {{ site.name | default: site.title }}. {{ site.data.ui-text[site.locale].powered_by | default: "Powered by" }} <a href="https://jekyllrb.com" rel="nofollow">Jekyll</a> &amp; <a href="https://mademistakes.com/work/minimal-mistakes-jekyll-theme/" rel="nofollow">Minimal Mistakes</a>.</div>

<div class="page__footer-copyright">&copy; {{ site.time | date: '%Y' }} {{ site.name | default: site.title }}.</div>
