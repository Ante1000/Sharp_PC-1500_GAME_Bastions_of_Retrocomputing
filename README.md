# BASTIONS OF RETROCOMPUTING

![Hooded Tech Priests in despair among retro computers in a gothic church; a Sharp PC-1500 shows: UNLEASH SYSTEM DAEMONS?](images/system_daemons.jpg)

A strategy game in BASIC for the Sharp PC-1500, PC-1500A and Tandy PC-2.

## The game

**The CATHODIC CHURCH (CC)** - a fictional organisation with a **profound interest in vintage computing** - maintains ten places across Europe, called Bastions of Vintage IT, from Lourdes to the Vatican (numbered 0-9). In these sites of retro computing the Cathodic Church keeps its vintage and NOS treasures: old hardware from IBM, HP, Apple, Commodore, Atari, Sharp, Casio, NEC and others. They are revered and heavily protected, and no outsider is let in. The security systems of every bastion are run by TECH PRIESTS, who also guard its gold and its retro stuff. Your task is to conquer the bastions by breaking through the Tech Priests' defences. You lead a team of highly skilled programmers: Ghosts, Hackers and Gurus. Conquer all ten places to win the war; if you lose all your people, the Cathodic Church wins.

Nobody gets hurt in this war: it is fought with code. A hacker, ghost or guru is eliminated when the Tech Priests defeat their solution, their code or their system, and leaves the battlefield in one piece for a long relaxation and a complete rewrite; Tech Priests fall the same way, when their systems crash, and spend the rest of the war in the Cathodic Church's retreat centre, waiting for the main spiritual help desk.


- **Hackers** fight with Killer Disks (K-DISKS): disks on which they prepare system daemons, endless loops, merge conflicts, malicious code and deadlocks, which drive the Tech-Priests' machines into an infernal overheat or a thermal meltdown (each hacker runs one per round; every disk is used only once). Killer Disks get through the firewalls: they hit as often in the first round as later. A hacker without a disk still attacks with plain code and viruses, but ten times weaker.
  Hackers also stand in the front line: the Tech Priests strike them first and reach the ghosts
  only when no hackers are left.

- **Ghosts** silent, brilliant programmers who strike with surgical precision: their sinister, unholy code finds every flaw in the Tech Priests’ systems. They unleash hidden bugs, plagues of self-replicating worms, corrupted servitor firmware, poisoned data-rites, and the dreaded Miracle Exploit — a zero-day opening through which no firewall, no ward, and no machine-spirit can hold. They need API keys to attack (each ghost uses one per round; every key is
  used only once); a ghost without a key still attacks, but six times weaker. You cannot hire them: they join you as volunteers when you conquer a place.
  
- **Gurus** fight alone, without Killer Disks or API keys. They strike with a huge,
  meticulously prepared Dependency Hell that paralyses the Tech Priests' systems and inflicts sheer terror among them - and power of Gurus is monstrous. They stay with you for the next fights, but Tech Priests hunt them, above all when they are far outnumbered.

 **KEYS**
- **F – Fight:** choose a place, decide how many Killer Disks and API keys to take, then fight
  or retreat. Every place has a **weak spot** (`WEAK TO K-DISKS`, `KEYS` or `GURUS`): there the hits
  of that weapon count three times. Every Killer Disk and API key is used only once: in each round each hacker runs
  one disk and each ghost uses one key, until they are all used; those not used come back to
  you after a won fight. The Tech Priests strike your hackers first, then your ghosts: when the
  last of them fall, `NO HACKERS LEFT!` or `NO GHOSTS LEFT!` appears, and the disks or keys still
  in the fight lie idle. Hackers and ghosts who have used up their disks or keys do not just stand
  there as shields: they fight on, ten and six times weaker. The fight goes on round by round until one side has nobody left; at
  most a third of the Tech Priests fall in one round, so it lasts at least three rounds. From
  the second round on, while you have fewer people than the Tech Priests, `S` appears on the
  round screen (`ROUND3:CC 120 vs YOU 45  S`): press **S to surrender**. You keep your people
  and the unused disks and keys, and the place keeps only the Tech Priests it has left, so your
  next attack is easier. A conquered place gives you its gold and retro stuff, some Killer
  Disks and its own retro treasure, a sixth of its Tech Priests defect to you as hackers, and new ghosts join you.
- **B – Buy:** Killer Disks (price 10 gold), API keys (price 26 gold), gurus (price 520 gold) and hackers (104 gold).
- **S – Sell:** retro stuff, hackers (65 gold) and gurus (416 gold). Retro stuff sells for 475
  gold at the start; after every fight its price rises by 0-100 gold, and every sale lowers it
  by 0-250 gold, but never below 250: it slowly rises for a player who sells now and then. The game first shows how many of each you have.
- **R – Resources** and **E – End** (E shows `Y=END`: Y ends the game, any other key brings the menu back).

Every element counts: Killer Disks need Hackers to run them, Ghosts need API keys to create malicious code, Hackers protect the Ghosts, and Gurus do what disks and demonic code cannot. Leave any of them out and you win clearly less often.

The first places are easy and every next one is harder. Places 7, 8 and 9 are rich places,
with twice as many Tech Priests and more than twice as much gold, but not twice as much retro
stuff: what one of them gives you is not enough for the next one. Save gold and retro stuff
from the first places; if you use up all your gold in every fight, you will not get through
Hohensalzburg and the Vatican (place 9), the richest of all. Once you have conquered Avila
(place 5) or a higher place, the Tech Priests fight back: from time to time one of your places
breaks free and gets back the Tech Priests it had at the start. Winning it back gives half its
gold and half its retro stuff (no treasure): a chance to collect a little more for the Vatican.

Full rules: [instructions_v2.3.pdf](instructions_v2.3.pdf) ([instructions_v2.3.docx](instructions_v2.3.docx)).

## Installation

You need a PC-1500A, or a PC-1500 or PC-2 with a RAM module (CE-151 or larger): the game
needs about 5.6 KB of memory. To load the recording you need the CE-150 (for the PC-2: the
Radio Shack printer/cassette interface).

1. Switch off the computer, insert it into the CE-150 and connect the audio output of a
   computer or player to the EAR jack of the CE-150.
2. Switch on, select PRO mode and type `NEW0` [ENTER], then `CLOAD` [ENTER].
3. Play [bastions-v2.3.wav](bastions-v2.3.wav) (name on the tape: `BASTIONS`,
   about 7 minutes).
4. Select RUN mode and type `RUN` [ENTER].

You can also type in the listing [bastions_of_retrocomputing-v2.3.txt](bastions_of_retrocomputing-v2.3.txt). Leave
out the REM lines: the recording does not contain them either, and with them the program
would not leave enough memory for its variables on a PC-1500A. The place names, treasures and
some messages contain small letters (SML key).

## Older versions

- Version 2.2 (with garrisons, weak spots ×1.5 and lower prices) is kept in
  [archive/v2.2](archive/v2.2).
- Version 2.1 (still called PROFANE ATTACK: Hackers and Ghosts without disks or keys cannot attack,
  K-Disks are stopped by the firewalls in the first round) is kept in [archive/v2.1](archive/v2.1).
- Version 2.0 (the same IT world, without weak spots and garrisons, with stronger gurus) is kept
  in [archive/v2.0](archive/v2.0).

Earlier versions take place in a different setting: religious wars.
- Version 1.7 (the religious war: Satanists with brimstones, mercenaries with inverted crosses,
  jihadists, militants and relics) is kept in [archive/v1.7](archive/v1.7).
- Version 1.6 (first functional version) is kept in [archive/v1.6](archive/v1.6).
