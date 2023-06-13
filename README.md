# WebEngDUS

Everything you need to know about how we run the *Web Engineering DUS Meetup*.

## Location Sponsor / Location and Company Briefing

The *Web Engineering DUS Meetup* depends on the support of local companies.
Local companies can sponsor the meetup by providing us with a location, technical equipment, and some food and drinks during the meetup.

For consistent communication and expectation management, we provide everything you, as a company, need to know about sponsoring and hosting a WebEngDUS meetup event:

* [Informationen für Locations für das Hosting eines Web Engineering DUS Meetup (Deutsch)](https://docs.google.com/document/d/1A77agjCXp-sFt3FNSkVCz-dZoEfBDR1tpbkyV1jFGLo/edit#heading=h.ghdyyw6l3nfw)

## Getting involved

If you would like to get involved, please check out our [Contribution Guide](./CONTRIBUTING.md).

## Checklists

Organizing and running the *Web Engineering DUS Meetup* regularly is effort, can be complex, and sometimes stressful.
To make our lives easier, we follow a simple and structured checklist:

[Check out our Checklist for running the WebEngDUS](./CHECKLISTS.md).

## Template to set up a new event at Meetup.com

Look at our last event in our [Web Engineering Düsseldorf Meetup group](https://www.meetup.com/de-DE/web-engineering-duesseldorf/events/).
Feel free to copy the description text there and use it.

The template is constantly evolving.

## Assets (Logo, Presentation, etc.)

All our assets can be found in the [*Assets*-Folder](./Assets). This includes:

- our colour scheme
- our logo in various formats and variants
- the design of our beach flag
- a Keynote template
- a DINA4 template

### Font

The font _Gotham HTF_ was used.

### Credit

All assets were created by [Fabian Huettenhoff](https://twitter.com/zuqbu). A **big** Thank you for this!

## Code of Conduct

[Checkout the Code of Conduct for our events](./CODE_OF_CONDUCT.md).

## Raffle

From time to time, we do a raffle.
The raffle price will be (most of the time) provided by various sponsors.
Prices we had in the past:

* power banks (e.g. to recharge your phone)
* programing language mascots (e.g. [ElePHPant](https://www.php.net/elephpant.php))
* conference tickets

To select a winner, we assume that everyone signed up via the meetup event page.
We open the event page, open the developer console of the browser and use the following javascript snippet to select a winner:

"going" only
```js
// only "going"
var a=document.querySelectorAll('.attendees-list li.attendee-item'), b=a[Math.floor((Math.random()*a.length)+1)-1];
a.forEach(function(e){e.style='';});
b.style='border: 7px dotted red;';
b.scrollIntoView({behavior:'smooth'});
```

The raffle script code was written by [@SHyx0rmZ](https://github.com/SHyx0rmZ).

## Social Media

The *Web Engineering Düsseldorf* is available at:

* [Web Engineering Düsseldorf @ Meetup.com](https://www.meetup.com/Web-Engineering-Duesseldorf/)
* [@WebEngDUS on twitter](https://twitter.com/WebEngDUS)
* [WebEngDUS on GitHub](https://github.com/WebEngDUS)
* [Web Engineering Düsseldorf @ LinkedIn](https://www.linkedin.com/company/web-engineering-d%C3%BCsseldorf/)
* [WebEngDUS on Speaker Deck](https://speakerdeck.com/webengdus)

## Organizers and contact

Have a question or feedback for us?

* [Open an issue in our GitHub issue tracker](https://github.com/WebEngDUS/WebEngDUS/issues/new)
* Speak to us at one of the local events
* Write us an email or contact us on social media

If you want more information or have a specific question, feel free to [open an issue in our GitHub issue tracker](https://github.com/WebEngDUS/WebEngDUS/issues/new).
We will be happy to answer it.

If you want to provide us feedback regarding this content, the way we run the meetup, or anything else, [opening an issue at our GitHub repository](https://github.com/WebEngDUS/WebEngDUS/issues/new) is also the way to go.

The meetup is organized by

| Andy Grunwald                                                   | Dominik Siebel                                                    |
| --------------------------------------------------------------- | ----------------------------------------------------------------- |
| <img src="https://avatars.githubusercontent.com/u/320064?v=4" height="150" alt="Andy Grunwald" title="Andy Grunwald">  | <img src="https://avatars.githubusercontent.com/u/145283?v=4" height="150" alt="Dominik Siebel" title="Dominik Siebel"> |
| [GitHub](https://github.com/andygrunwald)                       | [GitHub](https://github.com/dsiebel)                              |
| [LinkedIn](https://www.linkedin.com/in/andy-grunwald-09aa265a/) | [LinkedIn](https://www.linkedin.com/in/dominik-siebel-1960a067/)  |
| [twitter](https://twitter.com/andygrunwald)                     | [twitter](https://twitter.com/milchjieper)                        |


## Where is the original place of this content?

This content is originally hosted at [WebEngDUS/WebEngDUS on GitHub.com](https://github.com/WebEngDUS/WebEngDUS).
