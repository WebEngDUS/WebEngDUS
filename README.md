# WebEngDUS

Everything you need to know about how we run the *Web Engineering DUS Meetup*.

## Checklists

Organizing and running the *Web Engineering DUS Meetup* is getting more and more complex.
To make our live easier we follow simple checklists.

[Checkout our Checklists](./CHECKLISTS.md).

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
var a=$('#rsvp-list li'),b=$(a[Math.floor((Math.random()*a.length)+1)-1]);b.siblings().mouseleave().css({border:'none'});b.css({border:'7px dotted red'}).mouseenter();$('html,body').animate({scrollTop:(b.offset().top-300)+'px'},'fast');
```

The original raffle code was written by [@dsiebel](https://github.com/dsiebel) and [provided via a gist](https://gist.github.com/dsiebel/10382712).

## Where I can find you?

The *Web Engineering Düsseldorf* is available at several places:

* [Web Engineering Düsseldorf on Meetup](https://www.meetup.com/Web-Engineering-Duesseldorf/)
* [@WebEngDUS on twitter](https://twitter.com/WebEngDUS)
* [WebEngDUS on GitHub](https://github.com/WebEngDUS)

## Where can I get more information or provide feedback?

If you want to get more information or you have a specific question, feel free to [open an issue in our GitHub issue tracker](https://github.com/WebEngDUS/WebEngDUS/issues/new).
We will be happy to answer it.

If you want to provide us feedback regarding this content, the way we run the meetup or anything else, [opening an issue at our GitHub repository](https://github.com/WebEngDUS/WebEngDUS/issues/new) is also the way to go.

## Where is the original place of this content?

This content is original hosted at [WebEngDUS/WebEngDUS on GitHub.com](https://github.com/WebEngDUS/WebEngDUS).
