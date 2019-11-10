# Product Roadmap

![roadmap-1152x672-flip](https://user-images.githubusercontent.com/194400/27068309-5b379538-5007-11e7-99fb-20f09369c672.jpg)


## _Why_?

Having a _clear_ **Product Roadmap** is ***essential***
to help ***everyone*** _focus_
on our collective **goal**.

### _Public_?

From a "commercial" perspective making our
Product Roadmap `public` _can_ be viewed as
"_**giving away** all our **secrets**_" by those who follow
_traditional_ (_competition-focussed_) _capitalism_.

We don't think we are "_competing_" with anyone,
rather we are trying to _serve_ the people
using our app and listen to their feedback.
If there are other people/teams/companies
trying to solve the same challenge as us
and they are _not_ open-sourcing their code
and/or guarding the user-feedback,
they are _stuck_ in a _fixed_ mindset.
We believe that _radical_ transparency and openness
both in _what_ we do and _how_ we do it
is _essential_ for succeeding in our _mission_.

Only time will tell if making our product roadmap
Public on GitHub is a good or bad idea, we think it's
worth the _experiment_ just to discover the outcome.

## _What_?

<!--
In "Phase One" of dwyl we are building
a software application to solve a _specific_ set
of ***7 Universal Human Needs***:

1. **Communication**
2. **_Personal_ Effectiveness** through **Task and Time Management**
3. **Teamwork**
4. [***Self-Actualisation***](https://en.wikipedia.org/wiki/Self-actualization)

Later, once we have an _excellent_ UX for our core app,
we will strategically expand our app
to cover other areas including:
4. **Life-long Learning**
5. **Nutrition, Health and Fitness**
6. **Personal Finance Management**

> _**Note**: we don't expect a **single** app to magically "**solve**"
all of these problems, and we are **not** going
to "tackle" all the problems at **once**;
we may end up only having time/resources to solve **one**
of these challenges.
This list is intended as a guide not a "gospel"._
-->

Our immediate plan is to build a **_single_ app**
that satisfies _several_ human needs
while focussing on the theme of "***personal effectiveness***".

The @dwyl App will be a "_hybrid_"
containing several features
that together help the individual
achieve _all_ of their personal goals
through a systematic workflow.

The @dwyl App Will have the following basic workflow:
***Capture, Categorise Complete***.

1. ***Capture*** - capture everything that is on your mind in a "brain dump".
2. ***Categorise*** - split out blocks of text
  into distinct items and _categorise_ them. <br />
  **a)** What type of info/item is it?
  e.g: Todo Item, Reading list item, shopping list,
  random thought, bucket list? <br />
  **b)** Do you have an _existing_ category/tag for the item
  or is it **`new`**? <br />
  **c)** Contextualise the item in terms of time/space:
  a shopping list item context could be "grocery store"
  whereas a reading list item could be "daily commute"<br />
  **d)** **Add** any additional ***detail*** you can think of at the time.
  e.g: acceptance criteria, deadline, dependencies <br />
  **e)** If the item is a task that has sub-tasks, create and link them.
3. ***Complete*** - do the work to _complete_ the item/task.<br />
  **a)** Re-read the original description
  and determine if you have everything you need to start the task.
  If not, write down what is missing. <br />
  **b)** ***Delegate*** if necessary/possible <br />
  **c)** ***Track progress*** of the task. <br />
  **d)** ***Confirm*** it was completed to expected standard. <br />
  **e)** ***Review*** & ***Reflect*** - confirm the task was completed
  and all the original criteria were met by the assignee.
  Leave a brief feedback comment with any thoughts.
  Check the item off as "Done" if appropriate.

For the first step (***Capture***),
we will build an ultra-simple interface
to allow people to
input **`palintext`**
and save it to a backend as **`text`**.
For details, please see:
[`brain-dump.md`](https://github.com/dwyl/product-roadmap/blob/master/checklists.md)

Once the text input is working,
we will iterate and improve it
in several interesting and innovative ways
in response to feedback from people _using_ the MVP. <br />
We will add additional methods
to help people "capture" information.
e.g:
+ Linking to external sources of information.
+ Photo/image uploads
  + Optical Character Recognition (OCR)
  + Image/object recognition
+ Voice/audio recording
  + Speech transcription and indexing

These are complex features
that have formed the basis for entire companies.
So in order to make progress with them,
we will need to _significantly_ leverage
the Open Source work of many brilliant people.
But we are getting ahead of ourselves;
we need to _first_ focus
on creating "MVP" versions
of each step in the workflow.

For the _second_ step, ***Categorise***,
we will need a tagging system that allows people
to apply textual labels to items.
The UX for this is still "TBD".
We will need to sketch it out ahead of sprint planning.
See: https://github.com/dwyl/product-roadmap/issues/15


And finally for the _third_ step, ***Complete***,
we will build a simple checklist system.
See: [`checklists.md`](https://github.com/dwyl/product-roadmap/blob/master/checklists.md)





### USP: What is _different_ about the @dwyl App?

A valid/relevant **question** is: what makes the @dwyl App unique?
i.e. What is our
["unique selling point"](https://en.wikipedia.org/wiki/Unique_selling_proposition)?<br />
The **answer** is: _initially_ it may _appear_ that our App
does not have much different
from existing apps that _partially_ solve the personal effectiveness challenge.
The _major_ differences will become apparent in due course:
1. **People Not _Profits_** - We are playing an
["***infinite game***"](https://github.com/dwyl/start-here/issues/190)
where our _mission_ is to
"_Empower people to maximise effectiveness, creativity and happiness_."
See:
[What is dwyl's mission?](https://github.com/dwyl/start-here/blob/master/mission.md#what-is-dwyls-mission)
We will not _rest_ until we have created a system/app
that is _universally accessible_ to every human being
that allows _everyone_ a fair opportunity to live their best life.
We will _cooperate_ with _many_ people/organisations
to build a comprehensive solution that _anyone_ can use.
2. ***Open Source*** - All of our code will _always_ be ***Open Source***.
That means anyone can modify/extend/improve it.
And if people feel we are not doing a good enough job
of stewarding the App/community, they can _tell_ us!
Of the _many_ "productivity" apps out there,
almost _none_ are Open Source.
This means that your usage is locked-in to their system for better or worse.
Your data is bound by their "terms and conditions"
(_including being visible to 3<sup>rd</sup> party "analytics" providers
i.e. Google_)
and you are a _hostage_ to their whims.
If they decide to have a UI re-write
that
[_completely_ changes](https://github.com/dwyl/product-roadmap/issues/14)
how you interact with the App,
you have _no control_ and are _forced_ to use the "new version";
their way or the highway.
We are going to _eliminate forced updates_
by implementing a UX/UI innovation we call Progressive UI.
3. **Progressive UX/UI** - the UX/UI for _each_ person using the app,
will be _personalised_ to the individual
based on the features they (_most_) _use_.
If the person does not _use_ a particular function, they won't _see_ it.
> Note: This is might not feel relevant during "MVP",
but it will be an _amazing_ feature once our app has _lots_ of functionality.
4. **Best-in-Class Engineering Practices** -
Focus on high quality software product
with best-in-class engineering practices.
We are building a robust and reliable app
with a focus end-to-end testing to ensure a consistent UX
on as many devices as possible.
There shouldn't be any surprises or inconsistent UX (_bugs_),
and if there are, they can be reported and fixed _fast_.


#### Familiar UX?

In some cases the features and UX we are building
may appear _familiar_
because several other people/teams/companies
have _attempted_ to solve this challenge before.
If you are well-versed in _existing_ software/apps
or curious about UI/Design in general,
you _might_ find certain features familiar.
You may think:
"_note-taking similar to Evernote_",
"_collaborative editing like Google Docs_"
or "_offline reading like Pocket_".
In _most_ cases the app(s)
that _already_ has/have a certain feature(s)
(_e.g. nested note-taking, collaborative editing
  or offline distraction-free reading_)
did not _invent_ the feature,
they merely have a memorable _implementation_ of it.
Our intention is _never_ to "copy"
the feature/UX of another App,
but we will draw inspiration from _many_ sources.



## _Who_?

Who is this product roadmap intended for?

+ _Everyone_ ***using*** the dwyl application.
+ _Everyone_ ***contributing*** to
the various project(s) that make up the dwyl app.

(_provided the **contribution guidelines/workflow** is **respected/followed** to **avoid chaos**_).

#### _Who NOT_?

Who should *not* be reading this product roadmap?

Anyone who:
+ believes the World (_or themself_) "_cannot be improved_.
+ thinks the challenges listed above are "_already solved_"
by "XYZ Company" ...
+ is not _obsessed_ by working on solving a
_problem_ that benefits all of humanity.
+ does **not _want_ to _learn_** the skills required
to build something great.
+ is not prepared to
["_**work hard every waking hour**_"](https://youtu.be/NU7W7qe2R0A)

## When?

We started a laying the groundwork for
building the dwyl app _while_ ago ... <br />
The app is undergoing constant/ongoing improvement,
we don't expect the app to be "_finished_" because
there are _so many_ useful features we want to build.

_**Get involved today** and **help us prioritize**
which **features** get built **next**_!

## How?

If you want to get involved in helping us with the App,
there are 4 ways to help:

1. **Use** the **_Beta_ App**!
`[insert app link here!]`
2. Give us ***feedback*** on the **_existing_ UX**
`[insert feedback link here!]`
3. **Read** the
[issues](https://github.com/dwyl/time/issues?q=label%3A%22help+wanted%22+is%3Aissue+is%3Aopen)
and help us answer questions if you can.
4. Write some **`code`**!
See: https://github.com/dwyl/technology-stack


### Tech & Features Roadmap


This list _will_ evolve over time. <br />
We will insert links to specific features
and check them off this list as we go.

#### MVP Basic Workflow

+ [ ] Mobile First UI/UX to **Capture** **`plaintext`**
+ [ ] Save **`plaintext`** data to Phoenix backend
+ [ ] Simple UX to **Categorise** (Transform)
the **`plaintext`** into actionable items. <br />
UI/UX **`help wanted`**: https://github.com/dwyl/product-roadmap/issues/15
+ [ ] Start working on task (_start timer for item_)
see: https://github.com/nelsonic/time-mvp-phoenix#create-schemas
+ [ ] Check a task off as done.

After the MVP workflow is complete,
we will hold a sprint demo to showcase the state of the App.
The sprint demo will be recorded on our Zoom call.
Following the sprint demo call
we will do a backlog grooming session to discuss the features/ideas list:

#### Offline Support

+ [ ] Create Progressive Web App using Elm.
see:
+ [ ] Save data on device if offline.

#### Image Capture

+ [ ] Capture (_upload_) images from mobile.
+ [ ] Categorise (_tag_) the images for findability.

#### Authentication

+ [ ] Create accounts to allow people to own their content/items.
+ [ ] Authenticate with GitHub OAuth
  + [ ] Associate person record with GitHub username + token.
+ [ ] Associate **`items`** with **`person`**



<!--
## Brain Dump of Features

The following list needs to be _organised_:

+ [ ] Security First - ensuring the security of both the people
using the Application(s) and the (_personal_) Data in the system
is a ["hygiene factor"](https://en.wikipedia.org/wiki/Two-factor_theory)
and needs to be addressed _first_ on any checklist.
  + https://github.com/dwyl/learn-security
  + https://github.com/dwyl/ISO-27001-2013-information-technology-security

+ [ ] **Offline _First_** - the network might
feel reliable in major Cities, but go outside
in the "wild" it's _consistently unreliable_;
everything we build needs to work offline first
and be _frugal_ with bandwidth.

+ [ ] Mobile First - hopefully this is fairly obvious by now.
  + [ ] Progressive Web App
    + https://github.com/dwyl/learn-progressive-web-apps
  + [ ] iOS Native App for iDevices (Non-PWA)

  + [ ] Apple Watch UI - while apple watch is _definately **not**_
  the platform we want to "_win_" the "_wearable tech_"
    + https://github.com/dwyl/learn-apple-watch-development

+ [ ] Distributed by `default`
  + Blockchain helps us decentralize, verify and secure the database:
  https://github.com/dwyl/learn-blockchain
  + WebRTC allows peer-to-peer (_decentralised_) communication:
  https://github.com/dwyl/learn-WebRTC

+ [ ] API: REST and RealTime (WebSockets)

+ [ ] Sharing

+ [ ] Permissions

+ [ ] Teams

+ [ ] Repeatable Checklists

+ [ ] Estimate time required for each task

+ [ ] Delegate task with checklist

+ [ ] Track time against a task

+ [ ] End Task

+ [ ] Get "Sign-off" (_Confirmation_) / Feedback on Completed Task
-->

## Further Reading

+ "How we built a product vision and roadmap":
https://wildbit.com/blog/2016/05/11/how-we-built-a-product-vision-and-roadmap
(_a really good read! also image credit!_)


<hr />


### Why Do So _Few_ Companies Make Their "Road Map" Public?


_**Most companies**/organisations are
**deliberately** "**guarded**" with
their Product Roadmap for a **number** of **reasons**
that all boil down to_
["***FUD***"](https://en.wikipedia.org/wiki/Fear,_uncertainty_and_doubt):

+ _**Fear** that a "**competitor**" will "**steal**" their **ideas**_
(_and get to "**market**" **faster**
thus "capturing" the "**users**" and market share_)

> _**Note**: In **some cases** this **fear**
is **justified** e.g: where an innovation
is easy to replicate and difficult to differentiate.<br />
However we **hypothesize** that
being **open** and **transparent**
with our roadmap will foster
a more **collaborative culture**_.

+ _**Fear** that members of their **own team** will leave
and "**steal**" their **secrets**; <br />
this does
[happen](http://mashable.com/2017/05/20/uber-vs-google-waymo-self-driving-car-wars-get-nasty)
but only because the knowledge is **not** shared openly_.

+ _**Uncertainty** about the **future** of their **product/industry**._ <br />
_Committing to a long-range map implies a fixed/inflexible destination._

+ _**Doubt** in their **own ability** to **deliver** the plan_.
