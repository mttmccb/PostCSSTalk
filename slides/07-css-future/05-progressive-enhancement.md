### Progressive Enhancement

* Feature queries aka the [@supports rule](https://www.w3.org/TR/css3-conditional/#at-supports)
* [Progressive Enhancement & CSS](https://bitsofco.de/3-new-css-features-to-learn-in-2017/)

```css
@supports ( display: flexbox ) {
  body, #navigation, #content { display: flexbox; }
  #navigation { background: blue; color: white; }
  #article { background: white; color: black; }
}
```