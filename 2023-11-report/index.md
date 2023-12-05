# Zürich 23.11 ZHF Hackathon and UX Workshop report

On the last weekend of November 2023, the Zürich Friends of Nix hosted a multi-event around the [Zero Hydra Failures release preparations for NixOS 23.11](https://discourse.nixos.org/t/lets-have-a-great-23-11-release-cycle/33765).
It featured a two-day hackathon and a UX workshop, that all took place at [Eastern Switzerland University of Applied Sciences](https://www.ost.ch/) (OST) right next to Lake Zürich.

# Background and preparations

The Nix ecosystem is growing, and so is the community building it.
This can also be felt in the now regular Zürich ZHF hackathon, which has seen more and more participants over time.
The event is designed to encourage people to learn to know each other, hack on everything Nix, and together shape the future of open source.

The third iteration again incorporated participant feedback from last time, and also experience from in-person [workshops at NixCon 2023](https://discourse.nixos.org/t/nixcon-governance-workshop/32705):
- More time for hacking and mingling
- Shorter workshop sessions
- A variety of brief talks for overview and inspiration
- Increased coffee throughput

Preparations started in June 2023, right after the event, by writing up a report, processing feedback, sketching a schedule for the next event.
In the four months before the event, we invited many guests and followed up with reminders, refined the agenda, and prepared some of the logistics.
While originally there were ideas to make some progress on project governance topics, some key people couldn't make it this time and it turned out that the schedule wouldn't have allowed for it anyway.

A brief survey on state the 6-months objectives from the last workshop showed that it wouldn't make sense to have a separate agenda item.
There is progress on a few of the items though:
- @zimbatm launched [Nix packaging as a service](https://discourse.nixos.org/t/beta-launch-nix-packaging-as-a-service/34683)
- The [commercial support page](https://nixos.org/community/commercial-support) on nixos.org got more specific with respect to which support services are offered
- @jeremiahs is developing a plan to implement a [CIS benchmark](https://www.cisecurity.org/cis-benchmarks) and configuration profile for NixOS
- [RFC 140 got merged](https://media.ccc.de/v/nixcon-2023-35713-not-all-packages-anymore-nix) and @infinisil worked on [better tooling to work with local files in derivations](https://www.tweag.io/blog/2023-11-28-file-sets/)

# Event

The event took place in two large rooms and the hallway, and spanned two days, starting Saturday at 10:00 and ending at 19:00 with a group photo, and continuing on Sunday at 10:00 until it phased out around 17:00.

![](./XXX.jpg)

We had around 35 attendees on Saturday and 25 on Sunday, arriving from all over Europe, and we were happy to meet both first-time participants as well as regulars.
In addition to all the people giving presentations, we were particularly happy welcome NixOS Foundation board member @zimbatm, @delroth from the infrastructure team, `niv` author @nmattia, and many others.

# Lightning talks

At the beginning of each day we had guests highlighting recent topics from the ecosystem in brief talks.

On Saturday:
- Alex (@ners) welcomed everyone and provided an overview of the two following days
- Valentin (@fricklerhandwerk) gave a brief update on recent work in Nix maintenance and documentation
- Elton (@EltonUX) summarised the last two workshop sessions ([November 2022](https://discourse.nixos.org/t/2022-11-26-nix-nixpkgs-nixos-hackathon-in-zurich-rapperswil-jona/23402/11) and [May 2023](https://discourse.nixos.org/t/zurich-23-05-zhf-hackathon-and-workshop-report/29093)), and gave taste of what would expect participants this time
- Ivan (@iminicik) and Auguste (@augustebaum) reported on their mob programming experience with Summer of Nix
- Silvan (@infinisil) made his traditional introduction to working on ZHF
On Sunday:
- Ivan (@imincik) introduced the [Nixpkgs geospatial software maintainer team](https://discourse.nixos.org/t/creating-nix-geospatial-team/23454) he founded
- Matthias (@mat) brought our attention to how commercial interests impact community dynamics in open source 

# ZHF Hackathon

Before and after the talks in the morning, there was plenty of time for introductions or catching up.
Plenty of Coffee, fresh vegan sandwiches and wraps, and λ shaped cookies were waiting in the hallway.

Snacking was accompanied by hacking, in which most of attendees participated this time.
@infinisil was available to assist beginners and experts alike with navigation and debugging.
People worked on a range of issues, from trivial typos, over cursed Python environments, to surprisingly deep issues with the Nixpkgs `stdenv` infrastructure and hard-coded limitations in Hydra.
Over the weekend, [22 ZHF pull requests](https://github.com/NixOS/nixpkgs/issues?q=ZurichZHF+created%3A%3E2023-11-24) were opened and most of them got merged.

# UX workshop

TODO

# Acknowledgements

This event was made possible by Prof. Dr. Farhad Mehta, professor of informatics at the OST, by accommodating us in two large, modern computer rooms with a beautiful lake view.
Thanks a lot to Raffael Das Gupta (@das-g) for your support with the venue.
The event was sponsored by the NixOS Foundation, providing budget for food and drinks, and Tweag, the Modus Create Open Source Program Office lead by Mathieu Boespflug (@mboes), enabling Elton Vecchietti (@eltonUX) to run the UX workshop.

Thanks to all the participants for your attendance and active involvement, and for providing [detailed feedback on the event](https://github.com/nix-community/developer-workshop/issues/3) so we can make it even better next time.

# Looking ahead

We’re already set to organise the next event to keep up the momentum.
Save the date:

> Saturday 25th and Sunday 26th of May 2024

Looking forward to more hacking, snacking, knowledge sharing, and improving Nix for everyone!
We hope to meet many more leading contributors from the Nix ecosystem, better learn to know each other, and work on hard problems together.
Subscribe to [`nix-community/developer-workshop`](https://github.com/nix-community/developer-workshop) to stay up to date with planning and preparations.
