---
layout: default
title: Bitcoin Humour File
permalink: /bitcoin/humour
---

# Bitcoin Humour File

<p class="notebox">Originally posted on 15 December 2020. Updated frequently.</p> 

*"Usury is still immoral and slavery is still moral or immoral in the same conditions as it always was." — Luke Dashjr, Bitcoin Core Developer*


## WTF is this?

This is my attempt to prevent the kind of watered-down academic history of Bitcoin that will no-doubt be written by chronicling content and events that are so shameful they're funny.

### [It only took 37 seconds for two bitcoin 'celebs' to start fighting on a cruise ship](https://makgill.github.io/bitcoin-shame/coinsbank)

A ridiculous man in a cowboy hat and a debate at a pool party on a hot Barcelona day. What could go wrong?

### [Bitcoin Cash evangelist accused of joyriding stolen armored vehicle in Virginia](https://makgill.github.io/bitcoin-shame/tank)

Of course it was Bitcoin Cash.

### [You will now discover me when pissed off](https://makgill.github.io/bitcoin-shame/abc)

How drunk was Craig Wright when he wrote this?

### [Please send the contact information for your legal council](https://makgill.github.io/bitcoin-shame/please-send-contact)

What happens when Bitcoin's own "Milton" finally decides to burn the building down.



{% assign bitcoinhumour = site.bitcoinhumour | sort: 'date' | reverse %}
{% for bitcoinhumour in bitcoinhumour %}

<div class="h-entry note post-stub">
 
 
 <h2 class="post-stub"><a href="{{ bitcoinhumour.url | prepend: site.baseurl }}">
   {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
      <time class="dt-published" datetime="{{ bitcoinhumour.date | date_to_xmlschema }}" itemprop="datePublished">
        {{ bitcoinhumour.date | date: date_to_rfc822 }}
      </time>
   </a></h5>

{% if bitcoinhumour.reply %}
 <span class="reply-context" style="display:block;background-color: #f5f5f5;text-indent: 1em;">↳ In reply to <a href="{{ bitcoinhumour.reply | relative_url }}" class="u-in-reply-to h-cite">{{ bitcoinhumour.reply }}</a></span>
  {% endif %}
 
 <p class="p-content"> {{ bitcoinhumour.content }}
 </p>
 
   {% if bitcoinhumour.image %}
      <div class="post-image">
        <a href="{{ bitcoinhumour.url | relative_url }}" style="
    text-decoration: none;
">
          <img src="{{ bitcoinhumour.image | relative_url }}" alt="{{ bitcoinhumour.alt }}">
          
  </a>
       </div>  
      {% endif %}
 
</div>

{% endfor %}  
