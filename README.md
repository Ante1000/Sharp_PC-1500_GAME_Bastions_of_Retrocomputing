# PROFANE ATTACK

A strategy game in BASIC for the Sharp PC-1500, PC-1500A and Tandy PC-2.

## The game

The CATHODIC CHURCH (CC) - a fictional organisation - holds ten places in Europe, called Bastions of Faith, from Lourdes to the Vatican (numbered 0-9). Each place is defended by militants and keeps valuable relics and gold. You lead anticlericals, mercenaries and jihadists, armed with inverted crosses and brimstones. Conquer all ten places to win the war; if you lose all your people, the Cathodic Church (CC) wins.

- **F – Fight:** choose a place, decide how many crosses and brimstones to use, then fight or
  retreat. The fight goes on round by round until one side has nobody left; at most a third
  of the militants fall in one round, so it lasts at least three rounds. A conquered place
  gives you its gold and relics, some crosses and its own treasure, and a quarter of its
  militants join you as mercenaries.
- **B – Buy:** inverted crosses (25 gold), brimstones (80), jihadists (500) and mercenaries
  (150). Jihadists and mercenaries stay with you for the next fights.
- **S – Sell:** relics (at a price that changes after every fight), mercenaries (100) and
  jihadists (400). The game first shows how many of each you have.
- **R – Resources** and **E – End**.

The first places are easy and every next one is harder. Places 7, 8 and 9 are rich places,
with twice as many militants and twice as much gold, but not twice as many relics: what one of
them gives you is not enough for the next one. Save gold and relics from the first places; if
you use up all your gold in every fight, you will not get through Weltenburg and the Vatican
(place 9), the richest of all. Once you have conquered Avila (place 5) or a higher place, the
Cathodics fight back: from time to time one of your places breaks free and has to be conquered
again.

Full rules: [instructions_v1.6.pdf](instructions_v1.6.pdf) ([instructions_v1.6.docx](instructions_v1.6.docx)).

## Installation

You need a PC-1500A, or a PC-1500 or PC-2 with a RAM module (CE-151 or larger): the game
needs about 5.9 KB of memory. To load the recording you need the CE-150 (for the PC-2: the
Radio Shack printer/cassette interface).

1. Switch off the computer, insert it into the CE-150 and connect the audio output of a
   computer or player to the EAR jack of the CE-150.
2. Switch on, select PRO mode and type `NEW0` [ENTER], then `CLOAD` [ENTER].
3. Play [profane_attack-v1.6.wav](profane_attack-v1.6.wav) (name on the tape: `PROFANE`,
   about 7 minutes).
4. Select RUN mode and type `RUN` [ENTER].

You can also type in the listing [profane_attack-v1.6.txt](profane_attack-v1.6.txt). Leave
out the REM lines: the recording does not contain them either, and with them the program
would not leave enough memory for its variables on a PC-1500A. The place names and treasures in lines
970–986 contain small letters (SML key).
