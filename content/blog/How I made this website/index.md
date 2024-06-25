+++
title = "How and why I made this website"
date = 2024-06-07
+++

# How I made this website

{{ img(path="@/blog/How I made this website/repair.png", class="graphik") }} I made this website because I wanted my own personal space on the internet, a place where I can share and store every useful and non-useful piece of personal and non-personal idea, thought, image, link, etc.

I used a *static site generator* called [Zola](https://www.getzola.org/). This is a tiny ~25MB single binary (exe) tool. The structure of the website was coded with a templating language called Tera.

I had already made a website using a custom theme as the base which I modified and tweaked until the entire design and structure was completely different from the base theme. The problem was that the whole codebase was a mess: terrible CSS  code and variable names and lots of redundant and repeated code. Much of the source also had code that I didn't need or had no idea what they did or how they worked. 
So, I decided to make the entire website again from scratch without using any theme as the base. Thanks to the internet, the docs and Copilot AI I was able to rebuild the website. Making the website structure itself took only a few days but styling it took more than a week and it was challenging since I only had a basic idea of CSS but it was fun. The hardest thing was deciding which colours to choose for every element and what made it more dificult was that the colours looked completely different on my laptop screen compared to what it looks on my phone. I finally settled on the current design but still making a few tweaks here and there. I moved all the content from my old blog and generated the entire website, which was almost instant, thanks to Zola's speed.

**Hosting**: The website is hosted in [Cloudflare Pages](https://pages.cloudflare.com/), which is free and also provides a free ".pages.dev" custom domain.

**Banner**: The banner was AI generated with Ideogram.ai and expanded with fusionbrain.

**Graphics**: The favicon and various graphics were taken from [Flaticon](https://www.flaticon.com/), from the icon and sticker packs made by [Darius Dan](https://www.flaticon.com/authors/darius-dan)

 Planned: 
- Fix how it looks on widescreens. 
- Compress and convert all the images to webp.
- Make a mascot for the website.
- Tweak dark mode.
- Implement *markdown shortcodes*.
------------

<!--

1. Colour differences
-->

