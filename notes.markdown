Method for hiding and showing excerpts based on CSS
---

In the default.html head place a style loop that looks something like:

for site.excerpt div class="excerpt" adjacent child? display:hidden

The idea of the above is that anything in the "excerpt" block is shown but all following adjacent selectors (the rest of the p tags in the post) are hidden. This will take some cranking on:

for site.post div class="excerpt" display:block
