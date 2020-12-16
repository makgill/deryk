---
layout: default
title: Bitcoin Humour File
permalink: /bitcoin/humour
---

# Bitcoin Humour File

<p class="notebox">Originally posted on 15 December 2020. Updated frequently. Idea borrowed from <a href="http://milk.com/wall-o-shame/">Milk.com's Wall'o'Shame</a>.</p> 

*"Usury is still immoral and slavery is still moral or immoral in the same conditions as it always was." — Luke Dashjr, Bitcoin Core Developer*


## WTF is this?

This is my attempt to prevent the kind of watered-down academic history of Bitcoin that will no-doubt be written by chronicling content and events that are so shameful they're funny.

{% assign bitcoinhumour = site.bitcoinhumour | sort: 'date' | reverse %}
{% for bitcoinhumour in bitcoinhumour %}

<div class="h-entry note post-stub">
 
 
 <h3 class="post-stub"><a href="{{ bitcoinhumour.url | prepend: site.baseurl }}">
  {{ bitcoinhumour.title }}
      
   </a> ({{ bitcoinhumour.sourcedate }}) </h3>
 
 <p class="p-content"> {{ bitcoinhumour.excerpt }}
 </p>
 
</div>

{% endfor %}  


## Disclaimer and Legal Notice

If you feel that the archived content on this page somehow violates your rights, please let me know which piece of content you want removed and the justification for its removal.
