# Searchable Linkable Open Public Indexed (SLOPI) Communication

[![Gitter](https://badges.gitter.im/good-labs/community.svg)](https://gitter.im/good-labs/community)
[![Kanban](https://img.shields.io/badge/kanban-board-black.svg)](https://github.com/orgs/good-labs/projects/3#column-5299249)
[![https://good-labs.github.io/greater-good-affirmation/assets/images/badge.svg](https://good-labs.github.io/greater-good-affirmation/assets/images/badge.svg)](https://good-labs.github.io/greater-good-affirmation)

## tl;dr

Messages written in the SLOPI (pronounced "sloppy") communication style are:

- **Searchable**: Messages can be found using Google or other search engines.
- **Linkable**: Messages have a permalink on the web. Ideally the URL [doesn't change][] or redirects.
- **Open**: Messages are in the open, like [open access][] articles with the full text available.
- **Public**: Messages are public. No login is required.
- **Indexed**: Messages are indexed by search engines. Or **Indexable** (if you prefer) by a [discovery layer][] you operate because [data liberation][] is possible.

[doesn't change]: https://www.w3.org/Provider/Style/URI
[open access]: https://en.wikipedia.org/wiki/Open_access
[discovery layer]: https://en.wikipedia.org/wiki/Discovery_layer
[data liberation]: https://en.wikipedia.org/wiki/Google_Data_Liberation_Front

## Canonical reference for SLOPI

[Searchable Linkable Open Public Indexed (SLOPI) Communication or Why open source projects should avoid Slack](http://blog.greptilian.com/2020/01/25/slopi-communication/) is an attempt at a canonical reference for SLOPI. Feedback is very welcome!

## Inspirations for SLOPI

The phrasing used in SLOPI, especially with regard to messages being searchable and linkable, is inspired by the [discussion][] criteria of [Core Infrastructure Initiative (CII) Best Practices][] program.

## Examples of SLOPI communication

Examples of tools that support the SLOPI communication style include:

- mailing lists with public archives
- public forums
- public issue trackers
- [Gitter][]
- IRC channels with public logs ([#social][] from W3C, for example)
- Matrix rooms with public logs (many [matrix-static][] examples)
- XMPP rooms with public logs ([XFS][], for example)
- Rocket.Chat rooms with public logs (Inkscape's [#team_devel][], for example)
- public roadmaps
- public kanban boards

[Gitter]: https://gitter.im
[#social]: http://socialwg.indiewebcamp.com/irc/social/today
[matrix-static]: https://view.matrix.org
[XFS]: http://logs.xmpp.org/xsf/
[#team_devel]: https://chat.inkscape.org/channel/team_devel

(As part of [issue #2][] we are gathering examples in the wild in a [spreadsheet][].)

## When not to be SLOPI

While open source projects should endeavor to communicate in the SLOPI style whenever possible (as discussed in [issue #12][]), this style is inappropriate for security, code of conduct violations, and telling co-workers on your floor that you brought in donuts.

The SLOPI style can take some getting used to if you are new to open source culture. It's ok to be a little sloppy. Please don't worry if the message you send isn't perfect. The fact that you sent it in the open is appreciated. Open source is getting friendlier. A thick skin isn't as necessary as it was in the past.

## Open source organizations that favor a SLOPI communication style

### The Apache Software Foundation (ASF) requires open communications

[The Apache Way][] indicates an embrace of open communications, saying (emphasis added):

> "**Open Communications**: as a virtual organization, **the ASF requires all communications related to code and decision-making to be publicly accessible** to ensure asynchronous collaboration, as necessitated by a globally-distributed community. Project mailing lists are archived, publicly accessible, and include:
> 
> - dev@ (primary project development);
> - user@ (user community discussion and peer support);
> - commits@ (automated source change notifications); and
> - occasionally supporting roles such as marketing@ (project visibility),
> 
> ...as well as restricted, day-to-day operational lists for Project Management Committees. **Private decisions on code, policies, or project direction are disallowed; off-list discourse and transactions must be brought on-list.** More on [communications][] and the [use of mailing lists][]."

[The Apache Way]: https://apache.org/theapacheway/
[communications]: https://www.apache.org/dev/pmc.html#mailing-list-naming-policy
[use of mailing lists]: https://apache.org/foundation/mailinglists.html

### Debian will not hide problems

Commitment 3 from the [Debian Social Contract][] is "**We will not hide problems**" and is expressed in this way (emphasis added):

> "We will keep our entire bug report database **open for public view at all times**. Reports that people file online will promptly become visible to others."

[Debian Social Contract]: https://www.debian.org/social_contract

## Companies involved in open source that favor a SLOPI communication style

### Gitlab has most company communications public on the Internet

The [Single Source of Truth][] section of the "GitLab Values" chapter of their team handbook states (emphasis added):

> **By having most company communications and work artifacts be internet-public, we have one single source of truth for all GitLab team members, users, customers, and other community members.** We don't need separate artifacts with different permissions for different people.

[Single Source of Truth]: https://about.gitlab.com/handbook/values/#single-source-of-truth

### Mozilla has an FAQ and resources for when, why and how to work open

Mozilla's [Working open][] FAQ came out of a 2013 [Practicing Open][] talk and has the following to say under **Open vs. Transparent** about moving from "passively transparent" to "open" (emphasis added):

> - **transparent**: Public, but not necessarily enabling participation.
> - **passively transparent**: Not private; decisions aren’t actively hidden, but are difficult to locate. They may not even be documented. This is usually not done intentionally.
> - **actively transparent**: **Everything is written down, is easily searchable and is locatable by interested parties.** This requires intentional, sustained effort.
> - **open**: **Public and participatory. This requires structuring efforts so that "outsiders" can meaningfully participate (and become "insiders" as appropriate).**

[Working open]: https://wiki.mozilla.org/Working_open
[Practicing Open]: https://openmatt.org/2013/10/02/open_mozilla/

## Academic research

### Considering the Use of Walled Gardens for FLOSS Project Communication by Megan Squire

In [Considering the Use of Walled Gardens for FLOSS Project Communication][] [Megan Squire][] argues that transparency in decision making is a key value in many free, libre, and open source (FLOSS) software projects, often achieved through publicly archived mailing lists. She names a number of projects with publicly logged IRC channels such Ubuntu, OpenStack, Puppet, Perl 6, and many Apache projects. She describes an increasingly popular practice of using Slack and among the 18 projects she surveyed "the majority of projects which are using walled gardens are not creating archives of these communications." She argues that "archives preserve a record of decisions and can help bring new contributors up to speed."

[Considering the Use of Walled Gardens for FLOSS Project Communication]: https://doi.org/10.1007/978-3-319-57735-7_1
[Megan Squire]: https://github.com/megansquire

## Contributing

We love contributors! Please see our [Contributing Guide][] for ways you can help.

[discussion]: https://github.com/coreinfrastructure/best-practices-badge/commit/65ebe74d7bfdf661502978311200d0c32f7b8be8
[Core Infrastructure Initiative (CII) Best Practices]: https://bestpractices.coreinfrastructure.org
[issue #2]: https://github.com/good-labs/slopi-communication/issues/2
[issue #12]: https://github.com/good-labs/slopi-communication/issues/12
[spreadsheet]: https://docs.google.com/spreadsheets/d/1wvG3XTd5YwA-SliOUCavQgqfK1jLVnlL9tuUsjHR0Ik/edit?usp=sharing
[Contributing Guide]: CONTRIBUTING.md
