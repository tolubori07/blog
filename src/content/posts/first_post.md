---
title: "I do not understand Astro"
slug: "I-do-not-understand-Astro"
description: "A reflection on why I am not using Astro to its fullest potential"
pubDate: "Dec 18 2023"
heroImage: "/blog-placeholder-4.jpg"
Author: "Jaabir Adeniji-Bello"
tags: ['Programming', 'javascript', 'Astro', 'Web dev']
---

<article class="content text-xl sm:px-0 sm:mx-0">
<p>In order to understand what I mean when i say i don't understand Astro, It's important to understand what exactly Astro is.</p>
<h1 class="text-4xl font-bold">What is Astro?</h1>
<p> Astro is a static site generator(SSG) that focuses mostly on shipping less Javascript to improve website performance. By default, Astro ships 0 Javascript, yes, 0 Javascript to the browser, just plain 'ol static HTML. But of course developers like making fancy stuff like carousels, toggling between light and dark mode, shopping carts etc 🙄 which require some Javascript. To deal with this Astro uses a technique called <mark>Partial Hydration</mark> to ship Javascript to components that require Javascript only while keeping the rest of the page static. This architecture has been dubbed as <mark>Astro Islands</mark>.What I particularly like about Astro is that it does all of this SSG stuff while still maintaining the same modern developer feel that most people get from Javascript frameworks like React, Vue and Svelte to provide a static HTML site. </p>
<p>Astro describes itself as a "web framework for content-driven websites". It claims to "optimize your website like no other web framework can."</p> <img src="/Astroperformance.png" class="w-4/5 mb-12"> 
<h3 class="text-2xl font-bold underline">Some really cool astro features</h3>
<ul class="text-left list-disc">
<li>Bring your own framework(BYOF): Astro allows developers to use their own prefered framework (given that it's just going to turn it into static HTML again 🤣) whether it's react, preact, vue, alpine or do you prefer to bring in your own UI library like bootstrap or tailwind? Astro supports plugins for various UI libraries</li>
<li>100% static HTML</li>
<li>SEO enabled</li>
<li> Partial hydration(Islands)</li>
</ul>
<p> While I started to play around with Astro, I was most excited to see its Island architecture in effect, but I never succeeded. Astro has this developer toolbar at the bottom of the page while it's still in productiona that allows you to see where there's an island, regardless of where I put javascript i never found any Islands. This led me to some questions...</p>
<h2 class="text-2xl font-bold"> Is using Islands architecture a bad thing?</h2>
<p>I'm quite sure it is because Astro is trying to make you use Javascript less so using the architecture does sound like a bad thing, but then again, that's its main selling point. My main issue with Astro is that its features are so good that they make it bad. For example, i'm also aware of someone else who has fallen into the trap of using a different framework in Astro. This gave them so much freedom to neglect Astro's main purpose:<mark>"web framework for content-driven websites"</mark>. This caused their content to eventually become a small portion of the page among all the interactive components.</p>
<h2>Where do I go from now?</h2>
<p>In times like these, it's best to ask the developers themselves, what they intended by creating the framework. The best way to do this is to read the documentation, read blog posts from the developers and even ask other programmers that may be well versed in the framework/programming language.
</br>
Thank you for reading.</p>
</article>
