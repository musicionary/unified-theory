+++
title = "Decentralized Brain"
description = ""
author = "Chip Carnes"
date = 2021-02-28T18:29:38-06:00
tags = []
categories = []
draft = false
+++

Recently, I've dipped my toes in the ocean of the Web3 world [see what I did there Ocean Protocol??](https://oceanprotocol.com/).  During this time, this inspired me to think about my current knowledge tools, and the sort of tools that would be lovely to work with in a Web3 ecosystem.  I'm sure that many of these ideas already exist, but here's how I've imagined stringing them together.

## Information Hashing
- Information/content should be cryptographically hashed.
- When that contentt is updated, the hash should change.
- Previous hashes should still persist and could though of or represent the concept of "older" information.
- Content and its respective edits should have some concept of information "nearness" that is calculatable (i.e. If a word is changed, the resulting hash should be nearer, than say a paragraph that is changed.)
- There should be a way to visually represent the nearness of two hashes. Additionally, this doesn't have to be explicitly tied to a specific entity.  If I write a sentence on this site, and you write the same exact sentence elsewhere, the hashes should be the same.
- Correspondingly, if I write a sentence, and you write basically the same sentence but with just one word's worth of difference, this "informational map" should represent my resulting hash and your content's resulting hash as near, even though they have separate origins.


## Decentralized storage

If I'm involved in knowledge work, here's what would make that process better.  Work that I produce should live outside of my brain, for the usefulness it may provide to others.  Others may propose updates to that work asynchronously, and I should be notified of proposed changes. 

- Whether I chose to integrate those changes for myself should not prevent the changes from persisting for others.
- However, that "graph" of knowledge (with edits, or maybe just tangentially related information) should grow on its own, without my approval necessarily; it's only the incorporation/merging of information that may need to be approved by me (for myself).
- Provenance of information would need to be identified/preserved by hashes. Therefore, any edits from myself or others can have persistent attribution.
	
## Knowledge as Neurons

Content that I access with greater frequency should be surfaced first, before content which is access less frequently.  Additionally, this shouldn't be limited to information that I've produced for myself.  Let's say I've written a note for myself to remember the definition of the Overton Window, for example.  I've also discovered another source of a definition, and let's set that I like it better (i.e. I search for/access it more frequently).

Therefore, when I query for the Overton Window, the "neuron" that I've used with greater frequency should have the option of being given priority in being surfaced first.

- This doesn't eliminate the "weaker" neuron.  They can always be accessed directly by their hash.
- Or, given the above idea, about hashed "nearness", there could be some UI that displays for me the various neurons that are related, and how near they are to each other, and which are _weighted_ more or less strongly.
	
## Knowledge Dimensionality

I had this idea that, in a way, knowledge can be thought of as having dimensions.  I can describe the length and width, about the knowledge, so to speak.  This is what we are most familiar with, I believe, in our daily lives in how we interact with information.  We see what the information _is_ and maybe attributes about it's _source_.  But we don't have a great way, even in the modern internet, of having an interface that displays a third dimension about the information. That third dimension could be a number of things:

- The provenance of that information. 
	- i.e An online newspaper article is saying Thing A, but really Thing A comes from another person talking about Thing A in the context of Thing B).
 - Arguments and counterarguments.  The world is sufficiently complicated that even with generally objective concepts, there's seemingly some degree of arguability about it.  It would be useful to represent points and counterpoints of information in some visual/dimensional way that people could interact with.
 - More benignly, dimensionality could just be different perspectives or facets about the same information.  
	 - If, having played in a performance of Brahms' 2nd symphony in the viola section, I might describe the experience of that work in wholly a different way than someone in the bassoon section.  These experiences can be thought of different facets, both about the symphony, and therefore present a third dimension, so to speak, about the _concept_ of that symphony.  Again, it would be interesting to have a visual way to interface with that kind of dimensionality.