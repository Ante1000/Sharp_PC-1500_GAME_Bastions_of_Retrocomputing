# PROFANE ATTACK

A strategy game in BASIC for the Sharp PC-1500, PC-1500A and Tandy PC-2.

## The game

The CATHODIC CHURCH (CC) - a fictional organisation - holds ten places in Europe, called Bastions of Faith, from Lourdes to the Vatican (numbered 0-9). Each place is defended by militants and keeps valuable relics and gold. You lead Satanists, Mercenaries and Jihadists. Conquer all ten places to win the war; if you lose all your people, the Cathodic Church (CC) wins.

- **Satanists** spew brimstones, hellish stones of demonic sulphur (each Satanist one per round). You cannot buy them: they join you when
  you conquer a place.
- **Mercenaries** are needed to hurl inverted crosses, which, as everyone knows, are deeply terrifying to the
  devout and the clergy, and lethal to their very souls (each mercenary hurls one per round). Mercenaries also stand
  in the front line: the militants strike them first and reach the Satanists only when no mercenaries are left.
- **Jihadists** fight on their own, without weapons, and their killing power is monstrous. They
  stay with you for the next fights, but militants hunt them, above all when they are far
  outnumbered.

- **F – Fight:** choose a place, decide how many crosses and brimstones to use, then fight or
  retreat. The fight goes on round by round until one side has nobody left; at most a third
  of the militants fall in one round, so it lasts at least three rounds. A conquered place
  gives you its gold and relics, some crosses and its own treasure, a sixth of its
  militants join you as mercenaries, and new Satanists join you.
- **B – Buy:** inverted crosses (25 gold), brimstones (110), jihadists (400) and mercenaries
  (80).
- **S – Sell:** relics (at a price that changes after every fight), mercenaries (50) and
  jihadists (320). The game first shows how many of each you have.
- **R – Resources** and **E – End**.

Every element counts: crosses need mercenaries to hurl them, brimstones need Satanists,
mercenaries protect the Satanists, and jihadists do what throwing cannot. Leave any of them
out and you win clearly less often.

The first places are easy and every next one is harder. Places 7, 8 and 9 are rich places,
with twice as many militants and twice as much gold, but not twice as many relics: what one of
them gives you is not enough for the next one. Save gold and relics from the first places; if
you use up all your gold in every fight, you will not get through Weltenburg and the Vatican
(place 9), the richest of all. Once you have conquered Loreto (place 6) or a higher place, the
Cathodics fight back: from time to time one of your places breaks free and has to be conquered
again.

Full rules: [instructions_v1.7.pdf](instructions_v1.7.pdf) ([instructions_v1.7.docx](instructions_v1.7.docx)).

## Installation

You need a PC-1500A, or a PC-1500 or PC-2 with a RAM module (CE-151 or larger): the game
needs about 5.9 KB of memory. To load the recording you need the CE-150 (for the PC-2: the
Radio Shack printer/cassette interface).

1. Switch off the computer, insert it into the CE-150 and connect the audio output of a
   computer or player to the EAR jack of the CE-150.
2. Switch on, select PRO mode and type `NEW0` [ENTER], then `CLOAD` [ENTER].
3. Play [profane_attack-v1.7.wav](profane_attack-v1.7.wav) (name on the tape: `PROFANE`,
   about 7 minutes).
4. Select RUN mode and type `RUN` [ENTER].

You can also type in the listing [profane_attack-v1.7.txt](profane_attack-v1.7.txt). Leave
out the REM lines: the recording does not contain them either, and with them the program
would not leave enough memory for its variables on a PC-1500A. The place names and treasures in lines
970–986 contain small letters (SML key).

## Older versions

Version 1.6 (with anticlericals instead of Satanists, and without the throwing rules) is kept
in [archive/v1.6](archive/v1.6).
