### Why do I even need a pre-processor

It wasn't (and still isn't unusual) to find a website's running from a single stylesheet covering every page of the site.

For a long time stylesheets were a mess and the solution to updating an existing site was the throw the new rules on the end.

CSS has alway been very limited in term of flexibilty, there are no variables, control flow or way to reduce the amount of duplication you end up writing.

That's why pre-processing tools like Sass emerged you could start to split up your giant stylesheet into partial views, use function to generate some of your rules, nest rules.

This really helped get you towards more maintainable code, until you come to debugging it and realised some of the rules it produced were horrific and difficult to unpick.

It was easy to forget you were still writing CSS and CSS is bad enough without another level of abstraction and the end result was still one giant style sheet.

So it does have a lot of good points but it encourage some bad behaviour, which has become better understood. Using extend and nesting things deeply has become a bit of an antipattern.

So how can we do this better? Sass is a very proprietry language, it will never be native in a browser so Sass will always be part of a build step.

LESS if you hade semicolons.

[Karolina Szczur - Architecture-oriented frontends systems with PostCSS](https://www.youtube.com/watch?v=1vbBLc-fgWk)

* includes
* extends (example)
* nesting (specificity)
* scoping / global
* hard to delete code
