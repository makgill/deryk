---
layout: default
title: Breaking Satoshi Season One Introduction
---

## Introduction

On July 28th, 2010, BitcoinTalk user bytemaster made a post that [questioned Bitcoin's ability to scale](https://bitcointalk.org/index.php?topic=532.15;imode) as a daily payments technology for the world.

>I am convinced that bandwidth, disk space, and computation time necessary to distribute and "finalize" a transaction will be prohibitively expensive for micro-payments.

This was not the first time early Bitcoiners had doubted Bitcoin. As soon as Satoshi Nakamoto announced Bitcoin on the Cryptography Mailing List in 2008, influential list members were wondering out loud whether or not Bitcoin would work at scale. The argument was that the cost of running a Bitcoin node would grow too expensive for most people to run unless bandwidth costs were intentionally restricted, and certain use cases for Bitcoin, particularly micropayments and daily transactions, curtailed.

It was a debate that would come up over and over again before and after Satoshi's mysterious disappearance—what should be prioritized in Bitcoin? Its use as cheap, fast, scarce, non-reputiable, reliable digital cash for the internet? Or the egalitarian 'ideal' that all users must run their own Bitcoin software to secure the network even at the expense of usefulness in regular commerce?—and Satoshi always replied the same way.

>The current system where every user is a network node is not the intended configuration for large scale.  That would be like every Usenet user runs their own NNTP server.  The design supports letting users just be users.  The more burden it is to run a node, the fewer nodes there will be.  Those few nodes will be big server farms.  The rest will be client nodes that only do transactions and don't generate.

In Satoshi's view, Bitcoin could scale and remain cheap, fast to transact, non-reputiable, and secure by professionalizing. Bitcoin in the future would be secured and operated like any other global system: by large companies with substantial capital in the game, not by small hobbyists running computers at home. The Invisible Hand would distribute labor and intelligence in Bitcoin in such a way that both security and usability would be maximized, and most people could simply be users, neither knowing nor caring how the network was secured.

Obviously frustrated by what he saw as a common misunderstanding of Bitcoin, Satoshi ended the thread with bytemaster brusquely.

>If you don't believe me or don't get it, I don't have time to try to convince you, sorry.

This is the theme we see in the early days of Bitcoin, this inability for many to truly get what Satoshi was saying about his creation. Many of the early adopters of Bitcoin who Satoshi met on the Cryptography Mailing List and BitcoinTalk were coming into it with an existing technical bias in their understanding of digital currency and what it should be. Several attempts, sometimes theoretical, sometimes practical, at creating digital currency had already been made. Though all previous attempts at creating a decentralized digital currency had failed, they interpreted Bitcoin as a continuation of these failed projects, and not its own innovation separate from them.

And then there were the philosophical biases of the existing cryptographic and digital cash communities, who insisted on seeing Bitcoin as a sort of agoraphobic, anarchist project designed to overthrow the world governments, despite Satoshi mentioning none of this and insisting that his project was designed to facilitate internet commerce. Although it is fashionable to argue that code is law and ideaology does not matter in Bitcoin, the ideas about man, governance, economic history and human action that one had before coming into Bitcoin affected dramatically what one saw the fundamental purpose of the project to be. This in turn affected the technical positions upon which people built their arguments for Bitcoin's scaling plan.

If you were, for example, an anarcho-socialist, as scared of corporations as you were of government, you would not find Satoshi's plan for 'big server farms' very exciting, and might even be willing to sacrifice the usability of Bitcoin to prevent corporate capture. If you were a radical free-market supporter, you might not be too worried about that because you believe the in natural incentives against corporate corruption that would protect Bitcoin while allowing it to remain usable as intended.

But that is getting ahead of ourselves. For a time some important people did believe him and did 'get it,' and when Satoshi disappeared several months later, the project passed into the control of developer Gavin Andresen, who had been in direct communication with Satoshi and who understood Bitcoin as he did. Writing to developer Mike Hearn in April 2011, Satoshi vaguely explained his exit and his thoughts on Gavin:

> I've moved on to other things.  It's in good hands with Gavin and everyone.

For several years, Bitcoin grew as planned and worked largely as Satoshi intended because the people 'in charge' followed his economic roadmap. A mining industry exploded, users around the world began transacting with it in commerce because it was cheaper and faster than Visa or Mastercard, and businesses emerged to both facilitate that commerce and to sell goods and services in exchange for Bitcoin, often even discounting their products for customers who used Bitcoin. As long as Satoshi's original scaling model was followed, Bitcoin worked as it was supposed to.

We'll cover this all more later in this essay series, as well as look deeper at what Satoshi saw for Bitcoin and its future, but for now, readers only need to know that beneath the obvious success of Bitcoin, the old debate was still there about what Bitcoin was supposed to be and how it would work, and what a world in which Bitcoin were mainstream looked like.

- How should Bitcoin scale? Should Bitcoin even scale? Can it even scale?

- Were micropayments and use in daily commerce an important value proposition, or were security and decentralisation all that mattered? 

- Who secures the network? Capitalists or hobbyists?

New questions developed as well such as:

- Who should make decisions in Bitcoin? Miners and users? Or developers?

- To what extent does Bitcoin mimick gold? How does it differ? How should it differ?

- What role does economics play in Bitcoin? Is code all that matters, or should a deep understanding of human action inform how Bitcoin development moves forward?

- What did Satoshi mean by 'the core design was set in stone?'

- Is Bitcoin just store of value or is it that AND a useful medium of exchange?

Debates over these questions grew increasingly hostile and partisan. Many developers did not agree with Gavin or Satoshi. They either interpreted Satoshi's words in unconventional ways, stretching or often redefining entirely the meaning of words to fit their vision for Bitcoin, or denied the usefulness of Satoshi's thoughts on his creation entirely. With Satoshi gone, it was hard to argue with them. Over time they became more and more influential in Bitcoin and were able to successfully propgandise new Bitcoin users who were not so familiar with the early history. 

Bit by bit, Satoshi's plan for Bitcoin was removed, revised, or reinterpreted. The Bitcoin scaling skeptics, known as the Core Developers won, as did their egalitarian dream for all users running the Bitcoin software, and they successfully kept what were originally temporary Bitcoin processing limits in place permanently in order to keep bandwidth costs low. The consequences for Bitcoin were catastrophic. Transaction fees spiked and confirmation times grew erratic. Bitcoin became less and less usable in commerce. Writing in December 2015, entrepreneur Steve Sokolowski complained about the [increasing unreliability of the Bitcoin network.](https://forums.prohashing.com/viewtopic.php?f=11&t=679)

> It’s now officially impossible to depend upon the bitcoin network anymore to know when or if your payment will be transacted because the congestion is so bad that even minor spikes in volume create dramatic changes in network conditions.

But instead of working to fix this, the Core developers saw this change in the reliability of the network as a sign of network health, and proof their ideas were working. When transaction fees reached an all-time high in late 2017, Core developer Greg Maxwell wrote to the [bitcoin-dev] email list that [he was celebrating.](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2017-December/015455.html)

> Personally, I'm pulling out the champaign that market behaviour is indeed producing activity levels that can pay for security without inflation, and also producing fee paying backlogs needed to stabilize consensus progress as the subsidy declines.

Many followed with similar statements of approval. Bitcoin had been broken, and yet the people responsible for developing Bitcoin were toasting this fact.

Some early Bitcoin users had for years by now tried to prevent this, including people like Gavin Andreesen and Mike Hearn, and to return to Bitcoin's original model. Technical, economic, and historical arguments were made, usually borrowing directly from Satoshi, for how to get fix Bitcoin. Competing camps had formed around the two different views of Bitcoin.

The Satoshi Nakamoto camp lost, but not for the reasons you might think. They didn't lose for any technical, economic or historical reason that they had overlooked. They lost to a campaign of disinformation, censorship, denial of service attacks, blacklisting, and libel by the people who wanted to keep Bitcoin bandwidth costs down and who, as we will later see, may have had motives of their own breaking Bitcoin's ability to be used reliably and cheaply in daily commerce. Gavin and Mike would end up unceremoniously ousted from the Bitcoin community, as would many others, for holding opinions about Bitcoin that Satoshi himself held.

Thousands followed and simply left Bitcoin or created their own projects. The 'altcoin' market is largely a reaction against the failure of Bitcoin to scale as reliable digital cash. Two forks of Bitcoin, Bitcoin Cash and Bitcoin SV. Businesses that previously accepted Bitcoin as a payment option or which had run their entire business on Bitcoin stopped accepting it as a payment option. Years of work spreading adoption was reversed. Those that remained in Bitcoin were useful, unquestioning followers of the Core Developers, who have a virtual monopoly on the roadmap of Bitcoin today, which has for several years now stagnated and left promises unfulfilled.

This is where we are at today. Bitcoin recently celebrated its 11th anniversary and we are not much closer to creating a Bitcoin world. Many Bitcoiners feel the ship has sailed and that Bitcoin's narrow window in which it was able to take over the world was squandered. Time is running out on the mining reward, technical improvements to the existing financial system have allowed faster and cheaper payments to be made available to more people, and there is an increasing threat of hostile regulatory capture or repeated contentious forks that further fracture the ecosystem. 

In February 2010, [Satoshi made a prediction](https://bitcointalk.org/index.php?topic=48.msg329#msg329) about Bitcoin.

> I'm sure that in 20 years there will either be very large transaction volume or no volume.

It feels to many for the first time that his prediction could very well be realized in the negative. Even those who remain optimistic seem tired, and acknowledge in frustration, as Bitcoin.com owner [Roger Ver has many times,](https://bitsonline.com/bitcoin-adoption-lost-years-ver/) that Bitcoin adoption has been set back several years, maybe even decades.

[Breaking Satoshi](/) Season One is an essay series about what happened to Bitcoin that pushed it to this state. The series will explain the various economic, philosophical, psychological and social forces that worked to break Satoshi's Bitcoin and what ideas, understandings and models will help get it back on track. The series will draw from sources like the original forum and email threads with Satoshi, but also archived websites, fiction, poetry, historical works, psychology papers, economics texts, old Tweets, Reddit archives, first-hand accounts, and more.

I have no fixed publishing schedule or order, but I hope to have a definitive history of what happened to Bitcoin completed with the goal of postively influencing whatever direction any fork of Bitcoin takes in the future.

I'll end with a concluding thought: whoever Satoshi is could have done a better job putting checks in place to prevent what happened to Bitcoin!
