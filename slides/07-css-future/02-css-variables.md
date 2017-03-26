### CSS Variables

* [CSS Custom Properties for Cascading Variables Module Level 1](https://drafts.csswg.org/css-variables/)
  * Sort of like variables but they cascade
  * You can change them at run time

```css
:root {
  --Accent: green;
}

.NavBar {
  background-color: var(--Accent);
}
```