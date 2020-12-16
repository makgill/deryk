---
layout: default
title: Bitcoin Humour File
permalink: /bitcoin/humour
---

# Bitcoin Humour File

<p class="notebox">Originally posted on 15 December 2020. Updated frequently. Idea borrowed from <a href="http://milk.com/wall-o-shame/">Milk.com's Wall'o'Shame</a>. Support the work <a href="https://makgill.github.io/deryk/support">here.</a></p> 

*"Usury is still immoral and slavery is still moral or immoral in the same conditions as it always was." — [Luke Dashjr](https://makgill.github.io/deryk/bitcoin/humour/lukoos-nest/), Bitcoin Core Developer*


## WTF is this?

This is my attempt to prevent the kind of watered-down academic history of Bitcoin that will no-doubt be written by chronicling content and events that are so shameful, wacky, sad or awesome that they're a little funny (in a dark or light way) to look back on.

## How do I support it?

Share the content, [send me](https://makgill.github.io/deryk/contact) new material to save, or [tip me](https://makgill.github.io/deryk/support) in Bitcoin. Thank you!

{% assign bitcoinhumour = site.bitcoinhumour | sort: 'date' | reverse %}
{% for bitcoinhumour in bitcoinhumour %}

<div class="h-entry note post-stub">
 
 
 <h3 class="post-stub"><a href="{{ bitcoinhumour.url | prepend: site.baseurl }}">
  {{ bitcoinhumour.title }}



   </a>      {%- if bitcoinhumour.sourcedate -%} ({{ bitcoinhumour.sourcedate }}) {%- endif -%} </h3>
  
 <p class="p-content"> {{ bitcoinhumour.excerpt }}
 </p>
 
</div>

{% endfor %}  


## Disclaimer and Legal Notice

If you feel that the archived content on this page somehow violates your rights, please let me know which piece of content you want removed and the justification for its removal.
