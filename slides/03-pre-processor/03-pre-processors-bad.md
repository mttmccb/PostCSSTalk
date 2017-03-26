### Pre-processors - the bad parts

* It doesn't exist in the browser
* It's an abstraction
* Bad behaviour
  * Includes
  * Extends
  * Nesting (specificity)
  * Scoping / global
* Harder to debug
* Hard to delete code

<aside class="notes">
It was easy to forget you were still writing CSS and CSS is bad enough without another level of abstraction and the end result was still one giant style sheet.

So it does have a lot of good points but it encourage some bad behaviour, which has become better understood. Using extend and nesting things deeply has become a bit of an antipattern.
</aside>
