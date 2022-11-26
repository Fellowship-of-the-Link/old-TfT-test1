# Changed 'version control' sections

_a post in [[Pete's Project Journal]]_

Hi Mathew and Bill!

I had problems with the "version control" sections as they were, so I've made some wholesale changes, on 2022-11-26 (PST).

First to note, it seems there were perhaps two purposes the "version control" sections served:

1. Let readers know that they were looking at draft/non-working "version 0" versions of the page they were on.
2. A place to keep notes about this version, or what was needed to increment to the next version.

Second, two language notes:

1. In a recent meeting, I think we discussed changing "version" in the context of the project plan to "phase".
2. The particular phrase "version control", drives me nuts as a software developer, unless it has the computer science meaning, viz., [Version control - Wikipedia](https://en.wikipedia.org/wiki/Version_control).

So, now to describe the changes.

1. I added a bottom "notice" section to the navbar of the web version, which currently says, "Currently at Phase 0 (see [[Project plan]]). Please explore, but bear in mind: nothing works yet." This is implemented in the `this-wiki-themes/basso/_navbar.html`. Hopefully this lets readers know they're looking at Phase 0 of the project website.
2. I renamed and move the old "version control" sections, from the top of the page (where they were interruptive (perhaps because they weren't in a proper YAML section)) to the bottom, where they are under a horizontal rule (`---`) and have the section title `## Revision Comments`, which I like better than "version control" as a title for the place to keep page revision notes.

I do all this in the hope that it's incrementally useful and incrementally better, but not in the presumption that it's final; just another step better.  I'm looking forward to talking later this week!