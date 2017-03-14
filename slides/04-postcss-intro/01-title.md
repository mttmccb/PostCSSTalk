## What is PostCSS, why would I want to use it

PostCSS is one solution, despite the name, it's much like Sass, it's a pre-processor. On it's own it's simply a mechanism to parse CSS, transform it somehow and spit out CSS at the end. It's a little like gulp in this sense.

    PostCSS is a tool for transforming styles with JS plugins. These plugins can lint your CSS, support variables and mixins, transpile future CSS syntax, inline images, and more.

Created by Evil Martians (Andrey Sitnik).

Fork of Rework.

The real power is the in the plugins, you can simply replicate the syntax you were using in Sass. But I'd encourage you not to do that.

Instead start with CSSNext which is a meta-plugin which combines a number of incredibly useful PostCSS plugins to give you probably 80% of what you will need for a typical web project. It's a bit like babel for PostCSS.

It emphasises web standard and the syntax in the plugins mirrors what is in the specs. So the color functions use the spec, unlike Sass. Custom properties are in the spec and implemented in some browsers.