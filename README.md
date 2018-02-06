# WebEngDUS

Everything you need to know about how we run the *Web Engineering DUS Meetup*.

## Checklists

Organizing and running the *Web Engineering DUS Meetup* is getting more and more complex.
To make our live easier we follow simple checklists.

[Checkout our Checklists](./CHECKLISTS.md).

## Meetup templates

A template for a new event at Meetup.com is described in [MEETUP.md](./MEETUP.md).

## Assets (Logo, Presentation, etc.)

All our assets can be found in the [*Assets*-Folder](./Assets). This includes:

- our colour scheme
- our logo in various formats and variants
- the design of our beach flag
- a Keynote template
- a DINA4 template

All assets were created by [Fabian Huettenhoff](https://twitter.com/zuqbu). A **big** Thank you for this!

## Code of Conduct

[Checkout the Code of Conduct for our events](./CODE_OF_CONDUCT.md).

## Raffle

From time to time we do a raffle.
The winnings will be (in most of the times) provided by various sponsors.
Winnings we had in the past were

* power banks (e.g. to recharge your phone)
* programing language mascots (e.g. [ElePHPant](https://secure.php.net/elephpant.php))
* conference tickets

To select a winner, we assume that everyone signed up in the meetup event page.
We open the event page, open the developer console of the browser and use one of the following javascript snippets to select a winner:

"going" only
```js
// only "going"
var a=document.querySelectorAll('.attendees-list li'),b=a[Math.floor((Math.random()*a.length)+1)-1];a.forEach(function(e){e.style='';});b.style='border: 7px dotted red;';b.scrollIntoView({behavior:'smooth'});
```

The raffle script code was written by [@SHyx0rmZ](https://github.com/SHyx0rmZ).

## Where I can find you?

The *Web Engineering Düsseldorf* is available at several places:

* [Web Engineering Düsseldorf on Meetup](https://www.meetup.com/Web-Engineering-Duesseldorf/)
* [@WebEngDUS on twitter](https://twitter.com/WebEngDUS)
* [WebEngDUS on GitHub](https://github.com/WebEngDUS)
* [WebEngDUS on Speaker Deck](https://speakerdeck.com/webengdus)

## Where can I get more information or provide feedback?

If you want to get more information or you have a specific question, feel free to [open an issue in our GitHub issue tracker](https://github.com/WebEngDUS/WebEngDUS/issues/new).
We will be happy to answer it.

If you want to provide us feedback regarding this content, the way we run the meetup or anything else, [opening an issue at our GitHub repository](https://github.com/WebEngDUS/WebEngDUS/issues/new) is also the way to go.

## Where is the original place of this content?

This content is original hosted at [WebEngDUS/WebEngDUS on GitHub.com](https://github.com/WebEngDUS/WebEngDUS).
