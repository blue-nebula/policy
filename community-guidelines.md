# Blue Nebula Community Guidelines

The following document presents the guidelines the community commits itself to adhere to. The goal is to create a nice atmosphere in the community for discussion, development and gameplay, and to handle disturbances transparently, following a clear set of rules.


## Preamble

The guidelines and rules are defined by the community for the community.
They're not fixed, but improved in a continuous process, where existing rules are reviewed, new ones can be added and obsolete ones can be removed. All guidelines are published on GitHub, and everybody is encouraged to open issues and have constructive discussions about changes.

There are two types of entries in this document. The majority are guidelines, which means they are not strictly binding. However, every member of the community is advised and encouraged to stick to them.

Furthermore, there are some rules. Yes, rules can be annoying, but experience shows that in a game, some are necessary. They're kept to a minimum.

**Note:** rules must follow the [RFC 2119](https://tools.ietf.org/html/rfc2119) keywords. This makes it easy to identify them in this document, and doesn't leave space for interpretations. Keywords must use **BOLD UPPERCASE** markup to help users identify them quickly.



## Community language

The language used for global project communication should be English. This language is widely used within the global open-source community, as almost everyone has learnt this language as their main resp. next to their main language.

Communication in the forum should be done in English as well, so that everyone can participate. We don't mind bad English at all, as long as we can understand what you mean.

In-game, it is recommended to use English, too. Otherwise, some players are always excluded from discussions, which they might take as offense.


## Multiplayer rules

These rules are the core of our in-game community. Please read carefully. Violating users may be sanctioned, depending on the severity of the violation.

The rules are used by moderators and the team to administrate the game. They serve as a playbook for moderating activities.



### Scope

These rules only apply to users using the official Blue Nebula master server. They are split into *player rules* and *server rules* and *moderation rules*.



### Player rules

These rules affect everyone who is playing on servers listed on the Blue Nebula master server. Third party master servers are not goverened by these from Blue Nebula's point of view, but they're free to use these as well.

Players **SHOULD** use English for communication. This is the game's main language, and most players understand it. It is fine to discuss in other languages, but if there are non-speakers, please try to not exclude those by using a different language.

Players **MUST** respect other players. Insults are part of every shooter's gameplay and are allowed, unless they are harassing, racist or alike. Players **SHOULD** however try to remain calm and use non-offensive language.

Players **MUST** adhere to server-specific rules, unless they violate these guidelines or law (both the player's country's as well as the server's country's). The scope of these rules is ruled in the [Server rules](#server-rules) section. If players disagree with rules or they consider them to be unlawful, players **SHOULD** leave immediately again.

Players **MUST** respect administrative decisions, and **SHOULD NOT** try to circumvent them. Changing IP addresses to evade bans or mutes is not permitted. They **SHOULD NOT** start an in-game argument about actions taken agains themselves or other players (this involves changing names while being muted etc.).

Players **MAY** post a complaint against actions of moderators if they believe they did not violate any of these rules on the [forums](https://go.blue-nebula.org/forums). Such complaints **MUST** be precise and there **SHOULD** be evidence, e.g., in the form of a demo recording or screenshots. The Blue Nebula team **MUST** hear both sides. Whitnesses **MAY** post their point of view, as long as it is objective.
Actions taken by the team in either way **SHOULD NOT** be disclosed in public. There are exceptions for this rule, though. It is up to the team to decide whether or not to disclose them, depending on the case.



## Server rules

These rules apply to all servers that want to be listed on the Blue Nebula master server. Third party master servers are not goverened by these from Blue Nebula's point of view, but they're free to use these as well. Servers which connect to our master server are assumed to agree with these rules. In case of violations, they might be removed from the server using bans. However, we will try to contact server owners first and start a dialog. Bans are the last resort only.

The major goal of these rules is to make sure players, especially new ones, are not confused by non-default gameplay. Given our observations, we are concerned that this might scare off users or give them a wrong first impression of the game. We try to make sure that experiments are possible, but this is communicated appropriately to the users. Right now, only the `serverdesc` and `servermotd` are available for this, but we plan to add additional functionality to help with this.

Servers which modify the gameplay noticeably **MUST** declare this so it is visible to players from the server list *(1)* . The Blue Nebula defines a list of changes which are clearly considered as a modification. This lead will also contain items which are considered to *not* to modify the gameplay and therefore safe to set. This list is subject to regular reviews and may be modified to include more items. The more extensive the list is, the safer it is for both sides. Modifications **SHALL** be announced by the team in advance, and server owners **SHALL** receive a chance to change their servers. We do not require prior permission or reviews of any kind, but encourage server owners to share their work. They might inspire us to improve the game with their ideas!

Servers which host only a subset of the modes **SHOULD** declare this so it is visible to players from the server list *(1)* .

Servers which host only a single mode **MUST** declare this so it is visible to players from the server list *(1)* . They **SHOULD** furthermore inform users on connect *(2)* .

Server owners are encouraged to share experiments by adding their servers on the list. Those servers **MUST** declare this so it is visible to players from the server list *(1)* . Experimental servers **MUST** make sure they take appropriate measures so incompatible clients will not connect (e.g., by increasing the protocol version to a value which is higher than what is used in the latest development version of Blue Nebula).

Servers **CAN** set up their own rules. Those rules **MUST** be available in English at least. They **MAY** be available in additional languages. Servers **MUST** clearly communicate such rules to players *(2)* . Rules not mentioned there **MUST NOT** lead to moderative actions against players by any party. Custom rules do not have to be enforced by the global moderation team, however they **MAY** enforce them.

Servers **MUST NOT** act unlawfully. This just creates problems for the server owners, the players and might also cause trouble for Blue Nebula.

Servers **MUST NOT** spam messages excessively. Periodic messages are fine, though. We suggest an interval of at least 3 minutes.

Server-side defined text (i.e., the `serverdesc`) **MUST NOT** be offensive, and **SHOULD** be "safe for work". 
*TODO: add definition for NSFW (no insults, no sex-related words, no violence for a start I guess)*

Servers **MUST NOT** disable the global moderation. Moderators **MUST** be permitted access, and they **MUST** be granted the permissions the master server assigns to them when they authenticate. 

*(1) As of yet, server owners **MUST** use the `serverdesc` (i.e., the server name displayed in the server browser) for this purpose. This description **SHOULD** be as precise as possible (for example: "XYZ's experimental server", "XYZ's custom server", ...). (In the future, we will add a badge system that will make this easier).*

*(2) Servers **MUST** inform users about this in their `servermotd` (the message displayed to people who connect to the server).*



### Moderation rules

Blue Nebula hosts a global moderation system to protect regular users from abuse. Moderators are subject to special rules. As mentioned in the preamble: they **MUST** consider these rules to be a playbook for how to use and *not* use their permissions. It's a good idea to have a copy around while playing the game!

Moderators **MUST** only take action when players violate a player rule. They **MUST** warn players in advance, to give them a chance to stop bad behavior. Moderative actions are considered a last resort.

Moderators **SHOULD** get a demo to be able to prove their point in case there's a dispute about a specific action. This is only possible when a server has recording of demos enabled.

If more than one moderator is connected to the same servers, they **SHOULD** discuss actions beforehand. The rule "when in doubt, for the accused" applies (i.e., no moderative action is taken when there is no majority for a specific action). We trust moderators to be objective towards players. They **MUST NOT** privilege friends or similar.



## Development rules

The following rules affect development only. Users can skip this section unless they intend to add content to the game.

Development **MUST** take place in English. Code, issues, pull requests, documentation etc. need to be done in English. This is standard in most open-source projects.
Developers are free to create issues for problems they've been carried onto in different languages, however they are responsible for the communication with the reporting user and need to translate questions from both sides for each other.

Code contributions **MUST** be licensed under the existing license (i.e., the zlib license, please see the licensing remarks in the repository for more information).
All code **MUST** comply with the DFSG.
Code contributions **MUST** follow a coding style. This style is defined by the developers internally, and **SHOULD** be publicly available.

All content (i.e., media) added to the game **MUST** be licensed under a compatible license, which complies with the [DFSG](https://people.debian.org/~bap/dfsg-faq.html). (This rule does not apply for existing content.)
