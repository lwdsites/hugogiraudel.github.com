---
title: CSS is easy
layout: post
comments: false
preview: true
---
<section>
<p>I am studying what comes close to "Programming Sciences". My mates are hardware, server or back-end guys. When I tell them I prefer front-end, especially HTML/CSS I always get the same reaction: "CSS is easy".</p>
<p>And I always tell myself the same thing "Yeaaaaah... so that should explain why your CSS is a fucking mess".</p>
</section>
<section id="syntax">
<h2>CSS is easy... syntactically <a href="#syntax">#</a></h2>
<p>Yes. CSS has a very easy syntax based on english words. I don't think it could be much simpler since it can be summed up in 3 words: <strong>selector, property, value</strong>.</p>
<p>A 8-year-old child could do some CSS without even having any explanation on how to do so. Even HTML has a more complicated syntax than CSS since there are some elements which need a closing tag, some don't, some have attributes, some don't, some can't be inside others and so on. CSS is always the same.</p>
{% highlight css %}
selector [, selector2, ...] [:pseudo-class] {
 property: value;
 [property2: value2;
 ...]
}
{% endhighlight %}
</section>
<section id="evolution">
<h2>A constantly evolving language <a href="#evolution">#</a></h2>
<p>The first "problem" (for lack of a better word) with CSS is that it is a constantly evolving language. It was first introduced in 1994 if no mistake so almost 20 years ago. After 3 major versions (CSS1, CSS2 and CSS2.1), CSS is now divided into modules growing at their own speed (Colors Level 3, Selectors Level 4, etc.). It means you cannot simply "learn CSS" then don't get back to it. You can learn the bases, yes but it's not enough.</p>
<p>Things I learnt 2 years ago are irrelevant now, and things I'm learning today might disappear or become bad practices in the future. It is a non-stop evolution -which is cool- but which requires developers to be very careful.</p>
</section>
<section id="browser-dependance">
<h2>Browser dependant <a href="#browser-dependance">#</a></h2>
<p>The thing is, since CSS is a language compiled in the client side (meaning by the browser itself), its interpretation depends on the compiler (once again, the browser).</p>
<p>Yes, HTML and JavaScript as well. But unless you're using new HTML5 elements (which don't provide much more than semantic), your HTML -as long as it is valid- won't differ from one browser to another.</p>
<p>JavaScript is kind of like CSS. The interpretation depends on the JavaScript engine version. For example, Internet Explorer 8 doesn't use the same JS engine as Firefox or Chrome.</p>
<p>Anyway, in order to write consistent CSS, you have to know which browser supports which feature, or partially support them, and how to draw fallback, when to use hacks, and so on. It requires some experience.</p>
</section>
<section id="final-words">
<h2>Final words <a href="#final-words">#</a></h2>
<blockquote class="pull-quote--right">A simple syntax doesn't make an easy language.</blockquote>
<p>CSS isn't easy. Combining a very permissive (somewhat broken) syntax with constantly evolving features and rendering inconsistencies make CSS not that easy. Yes, the syntax is simple, but a simple syntax doesn't make an easy language.</p>
<p>And when you have to deal with performance, modular architecture, and responsive webdesign, it becomes even less easy. But that's a whole 'nother story.</p>
</section>