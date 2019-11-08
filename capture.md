# _Capture_

The **_first_ step** in creating
a **system** of for personal effectiveness
is to help people ***capture***
_everything_ on their mind. <br />
Emptying one's mind (_specifically working memory_)
of everything that is occupying space and processing power
is _essential_ for gaining focus
on the _one_ most important priority.
This step is often referred to as a "brain dump".

<div align="center">
    <a href="https://github.com/dwyl/product-roadmap/issues/12">
        <img src="https://user-images.githubusercontent.com/194400/68108635-3497be00-fee0-11e9-83f0-6a56ecc99623.jpg" width="500">
    </a>
</div>
<!-- this diagram is borrowed from https://anniemueller.com/brain-dump-noun-1
we definitely need a better one. If you want to help with this,
please open an issue: github.com/dwyl/product-roadmap/issues/new -->


> A brain dump is the act of writing down everything
that is on your mind so that you don't forget it
and to clear your brain to **focus** on **one thing**
instead of being distracted by many things.
https://anniemueller.com/brain-dump-noun-1

## Free Text Input

The first feature we need to build
is a way of capturing all thoughts
on one's mind.
Thankfully this is just a matter
of capturing free text (_using a **`textarea`** element_)
and safely storing it as **`text`** in Postgres.

Figma wireframe: https://www.figma.com/proto/WrpkKGJNYZbeCzMRDVtvQLbC/dwyl-app

![capture-plaintext](https://user-images.githubusercontent.com/194400/68241788-3c05b700-0007-11ea-941b-0fd58962ad03.png)

We can/will evolve this text input
to have autocompletion and natural language processing
(_to detect the kinds of items being typed_).
First we need to have an ultra-basic MVP working.


Please see: https://github.com/dwyl/product-roadmap/issues/12
for detail and acceptance criteria.


## Existing (_Incomplete_) Tech-based Approaches

There are several tools that can be used for an _initial_ brain dump.
They each have their strengths and weaknesses.

+ Basic notes app on phone/PC - good for initial capture, useless for follow up.
+ Google Docs - quite good for collaborative capture, useless for next steps.
+ Evernote - powerful yet incomplete, over-complicated and expensive.
+ Trello - trello is great for capturing and OK for categorising
but _useless_ for completion.


Our MVP _could_ be achieved
simply by using one of these
_existing_ Apps
and then focussing on the _next_ step
in the workflow.
However we feel there is still
a _lot_ of work to do in the **Capture** stage
and the UX is an _integral_ part of the "on-boarding" for our App,
so we feel that _building_ it from scratch is _essential_.

### Can't We Just Use Sticky Notes?

Capturing a brain dump
on paper or sticky notes
_can_ feel like a good step in the moment.

![colorful-sticky-notes](https://user-images.githubusercontent.com/194400/68108210-1ed5c900-fedf-11e9-829b-27f84889e311.jpg)

But unless those notes
are _immediately_ transferred
to a system and categorised,
most of the information is lost.
We've all been there
in the brain-storming / idea generating
session where everyone shares their thoughts.
Everyone feels great for a few moments,
like _real progress_ has been made,
but in reality walls full of _unorganised_ sticky notes
is where ideas and information go to _die_.
(_sorry if that feels overly dramatic,
  but we have felt the frustration
  of both **losing** the **individual** sticky notes
  and the **entire session**
  due to a lack of a systematic process for storing the information_)

A further downside of sticky notes
is that while they are OK for colocated teams,
they are ***useless*** for **_remote_ collaboration**.

People often _attempt_ to resolve
this by taking a photo of the board full of sticky notes,
naively thinking that they have "captured"
the information.
While the photo is better than nothing
it creates a false sense of security
because most of the time
the single word on the sticky note
does not capture the whole idea.
