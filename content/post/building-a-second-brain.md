+++
title = "Building a Second Brain"
description = "Ingesting, creating, and networking what you read."
author = "Chip Carnes"
date = 2020-05-31T13:39:31-05:00
tags = []
categories = []
draft = false
+++

In early winter of this year, just a little before we were it the throes of the COVID-19 pandemic, 
I was in my daily perusing of Hacker News. I came across a post on [Superorganizers](https://superorganizers.substack.com/p/how-to-build-a-learning-machine###) about personal information storage and retrieval.
Little did I know, I was about to head down a months-long endeavor of crafting a system
of tools for reading, note-taking, and linking ideas together.  

Whether I did this because of quarantine, or whether it would have happened regardless is hard to say, but it been 
a great way to pass the time. To me it felt like the process that woodworkers go through when they build a bunch of
tools, just to be able to build the things they actually want to build.

My intent in writing this is to lay out the system of tools that I've become relatively satisfied with, so that you're
able to implement something similar without it having to take you a **global pandemic's worth of weekends with 
nothing else to do**, just to stitch the tools together.

> _The obvious caveat: all software referenced make change by the time you read this. YMMV_

## What to do with what you read

Odds are, you've probably seen something on the interwebs that says something to the effect of "Super rich and smart
white man is super rich and smart because they read an insane amount". And maybe if you're like me you've thought, _"I guess I can be super smart too, if I only read as much as those people."_

And for many years, I've read few dozen books each year.  Some of which have been duds, others of which have been life-changing.
Looking over my Goodreads list though (let's be friends on Goodreads; it's the only "social media" I care about), most of the
books I've read I only vaguely remember.

> Maybe (maybe?) could I give you a elevator pitch summary on each book.  But even with the life-changing books, I couldn't tell you
> what parts or ideas had an impact on me.

Such is true, if not more, with articles I read online.

_If only there were a way to frequently encounter ideas I've read in the past..._ 

Enter [Readwise](https://readwise.io)

### Spaced repetition - a recipe

1. Highlight things you read
2. Sign up for Readwise.  
    - There's a trial period; then you must pay a paltry amount **TO BUILD A SECOND BRAIN**
3. Write notes based on the highlights delivered to your inbox each day.
4. Repeat ad infinitum.  Now you have a second brain (mostly).

The details:

If you have a moment, go read that article from Superorganizers.  This was the impetus and blueprint for my journey.

The general idea is that you want to be saving things that you find impactful, insightful, or generally memorable.
Facts, witticisms, beautiful wordcraft, whatever. The intention is to highlight anything that you think you might want
to come back to in the future.

I mostly highlight via Kindle ebooks. This is one of many sources that Readwise can ingest from.

![Readwise Sources](/images/Readwise.png/)

_omg look at all the options_

"But I prefer reading physical books".  Great! The Readwise mobile app will let you take pictures of book pages, and
then you can functionally add highlights from that.  You can also manually input "highlights". Check their docs for
more details.

Ideally each day, you would read through the highlights that Readwise sends you and then write a **short** note about 
the highlights that make the neurons in your brain giggle (not a scientific definition).

## Taking Notes

Strangely in 2020, there seems to be an plethora of note taking apps that are being developed. 
Some are feature-rich, some are bare bones. 

I recommend visiting [Zettelkasten](https://zettelkasten.de/) and it's Forum for suggestions. That website is a bit
of a rabbit hole, but there's some amazing ideas and thought-organization patterns coming from that community.

I think a good note taking app should be open source, or at least have a cloud storage option that is yours
(Dropbox, Google Drive, etc) so that if the app is shuttered some day, you'll still have your notes. 

I also think the app should support, or primarily use Markdown.  When you're writing, do you like finding and clicking
buttons (or even keyboard shortcuts) just to format your text?? 

Neither do I. 

Use Markdown. Leave your hands on the keyboard. It'll change your life.

Additionally, a critical feature for note taking is the ability to link notes/ideas together.  Markdown has great 
support for internal links.

### Linking notes

One aspect of linking notes that I find particularly useful is the ability to see any other notes reference the same link.
This is known as backlinking, and recently I've discovered a couple of applications that feature backlinking.  One
is [Roam Research](https://roamresearch.com) and the other is [Obsidian](https://obsidian.md).  

Of the two I prefer Obsidian because the source of your notes lives either on your computer or in the cloud (i.e. Dropbox).

{{< youtube cFYaWC_86W0 >}}  

### Connecting Ideas
Here's the summary of my workflow up to this point.

1. I read stuff and highlight.
2. Readwise gathers my highlights and emails me a selection of them.
3. I read through my Readwise highlights and if any of them stand out to me, I write a new note (even if I've written
about the highlight previously).
4. I'll add links in that note for certain words or phrases.  This could be things like [[note-taking]] or [[class-warfare]]
or [[emergence theory]]
5. Then, I'll click that link to view any backlinks, and I'll read through other notes I've written that reference that
concept.

The last step provides new material to connect ideas for the note that I'm actively writing. Also, this can lead me down
a rabbit hole of reading through various notes and updating them with links to other things.  This is the best part of
the process, because this is where you are creating a network of ideas.  Intuitively you might connect things like
note-taking and productivity.  But maybe you'll also find yourself connecting productivity and pop-tarts.

For me, the point of this isn't to connect only logical concepts.  It's to connect **anything** that could possible relate,
regardless of how distant they may seem.

> An idea is a connection. Yours is the kind of mind that is always looking for connections, and so you are intrigued when seemingly disparate phenomena can be linked by an obscure connection. An idea is a new perspective on familiar challenges.  
>
> You revel in taking the world we all know and turning it around so we can view it from a strange but strangely enlightening angle. You love all these ideas because they are profound, because they are novel, because they are clarifying, because they are contrary, and because they are bizarre.[[1](https://www.gallup.com/cliftonstrengths/en/252260/ideation-theme.aspx)]

In short, connecting ideas like this is closer to the tangled up way that concepts are stored in your brain.  

Also, if mind maps are your thing, check out this _faaaaancy_ graph view of connected notes.

![Obsidian Graph View](/images/obsidian_graph.png/)

## Bonus: Handwriting Notes
I'm a kinesthetic learner, and if I really need to remember something I'm gonna write it down by hand. Obviously,
this is pretty sucky for integrating this low-tech note creation with a second-brain type note taking app. Ideally,
I want to be able to write a note, and then it easily be added to all my other notes, linked, and searchable from my
computer.

### The iPad
I really think the iPad + Apple Pencil has been a game changer for me. I found the app [Nebo](https://nebo.app) which is
amazing at handwriting recognition, and handwriting-to-text conversion.  

With this, I can write notes on the iPad and then export them to Dropbox, in the same folder/directory as all my other notes.
This means that I write a note, convert it to text, export it, and then I can find it on my computer without any extra work.

Additionally, if I can write the Markdown link syntax `[[example-link]]` in the handwritten note.  And once it's in the
cloud with my other notes, I can then use Obsidian to explore all the backlinks.

![Falcor](https://media.giphy.com/media/cOB8cDnKM6eyY/giphy.gif)