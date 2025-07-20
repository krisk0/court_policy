# Court Policy

Disables certain events and options unappropriate for court owner's religion or policy. Allows AI or human player to define their own court policy.

## Untested

Not thoroughly tested, use at your own risk. File bug report if you encounter a problem.

## Motivation

My servant tells me that my son engages in extramarital carnal affairs, I immedialtely mobilize my men to drive the fornicator away…

In base game and in Elder Kings, there is only one option. Liege sends the fornicator away and accuses them of adultery. It seems unnatural. Suppose I created a custom religion that accepts all kind of sex and adultery, and I have some lovers at court. Why should I stop extramarital sex of others?

## Technical requirements

* Crusader Kings version Crown 1.15.0.2.
* Elder Kings modification version 0.15.1.

## Features

1. Allows to define court policy on what is allowed by general people.
2. Allows to define court policy on what diseases court physician should never heal.

Currently the following policies can be defined:

* Allow man-to-woman extramarital sex.
* Allow man-to-man and woman-to-woman extramarital sex.
* Allow close relatives extramarital sex.
* Ban healing of sanies lupinus (that leads to lycantropy).
* Ban healing of sanguinare vampiris (that leads to vampirism).

In absense of policy, defaults appropriate for court owner's religion apply. For instance, ideal masters and other necromantic religions allow any kind of sex and ban healing of both sanies lupinus and sanguinare vampiris.

Sanies lupinus and sanguinare vampiris healing mechanic is changed. In EK mod, these two diseases either heal by itself (even in absense of court physician or if court physcian's skill is very poor), or progress to lycanthropy/vampirism. The choice is completely random and does not depend on anything (religion, skills, personality, imprison status). In this mod, the two useful diseases do not heal at all if there is no physician or if suzerain is unlanded; physician skill determines healing success chance.

AI liege and player may set their policy to their taste. AI policy might be modified in approximately 5 years. Player can change their policy any time via decision "Define court policy".
