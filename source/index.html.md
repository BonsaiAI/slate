---
title: Bonsai Documentation


toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/tripit/slate'>Documentation Powered by Slate</a>

includes:

search: true
---

# Bonsai Documentation

Welcome to the sandbox for the future Slate-powered Bonsai documentation site!

<aside class="notice">
This is a temporary landing page.
</aside>

## Draft Sections:

I've set up a draft of the following pages to show off the new format. These are early drafts, and subject to change.

The listed endpoints reflect the site map available at [Coggle](https://coggle.it/diagram/V_RLZO99g4VT4gaT/e87816a3386a4dcf961fcd2df53621233acaf8c1f3c0e2c735189ae0b0d4c90c)


Page | Status | Style
-------------- | -------------- | --------------
[Getting Started][1] | Second Draft | Modular
[Inkling Classic][2] | Zeroth Draft | Modular
[Inkling New][3] | Second Draft | Modular
Mastermind | Absent | N/A
[References][4] | Second Draft | Modular

# FAQ:

## Where did the **Chapter/Section** numbers go?

These are temporarily removed until the site tree settles down, and will likely be replaced.

## Why are we reorganizing the [Inkling Classic][2] page?

This body of work includes overlapping sections with similar names, which is confusing to the reader and breaks Slate functionality. In addition, we're conjoining a notional, concept-based approach with a concrete, lexicon-based approach. The new layout joins the notional explanation with the reference for the actual command and its syntax. In addition, a [Refernces][4] section has the condensed Inkling reference.

## What are Modular pages?

Slate supports the notion of [includes][6], which allow us to put the documentation into a database of sorts and rebuild it from parts. This works by holding the pages in the `includes` folder. A display page is made by adding an `includes` section to the front matter, and then listing the included pages in order.

## What about headers/footers/toc_footers?

These are still being designed. It seems like there's likely to be a full-width header including primary-nav to all sections.

## How do I get back to the beginning?

There's a **Return Home** link in the footer of the table of contents.

[1]: /getting_started.html "Getting Started"
[2]: /inkling_classic.html "Classic Inkling"
[3]: /inkling_everything.html "New Inkling"
[4]: /reference_everything.html "Anaconda CLI instructions"
[5]: /cli_reference.html "CLI Reference"
[6]: https://github.com/lord/slate/wiki/Using-Includes "Using Includes: Slate Documentation"