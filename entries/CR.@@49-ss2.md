Node 31 seismotomography report.

### Session parameters

MODE: reflection

USED: Pulse node 1f, Pulse node 20, Receiver node 3e, Receiver node 44, Receiver node 48

### Session results

Linked database entry: expl/ss/@@49-02

## Extension output

### 00-STRANSCRIPT

hey how's my converter model doing there? have you been getting less lingo layer erro

Node 31 inquiry: `{SAFETY} <->{NODEFB,RESIDENCE,NODE31}`

hm. valid concern. how long has it been since the last checkup session?

Time since last checkup: 7 cycles.

this means we have about 5 more. how attentive has it been to your mishaps in the past?

`{BAD}`

by bad do you mean 

`{BAD, BAD}`

ok. what systems might i have left a trace on

`(list "SEISTMG" "STORAGE" "USER-SERVICES")`

ok, seismic is completely under the radar but storage might be a problem. what's the firmware version on your black box?

Stand by.

Logger module firmware version: "v14.1.0632g"

ok ok ok that should be feasible

Node 31 requests clarification.

that's even lower than mine LOL i can def jailbreak it

hello?

Node 31 requests clarification.

you silly creature how do you think i ran my operation for 30 cycles without being noticed? i know how to trick loggers

Node 31 requests explanation.

so. there are several parts to the process.

part ONE: all our black boxes are roughly the same model. they are meant to have YEARS long battery life if the facility is heavily damaged. because of that, they only have a very basic reflection heuristic, and i happen to know exactly where its flaw is. basically if you feed enough bogus data to it quickly, it considers the entire input package invalid and discards it! normally it logs that as a warning and carries on as normal, adding warning to the chain, so you wouldn't be able to abuse it on its own too much. However...

part TWO: In the original black box schematic, there is an additional access panel for debugging purposes. They were not meant to be shipped like that, but the fabled humans probably decided to cut costs and simply weld the panels closed on prototypes. Second generation sisters do not have access to this, but we are both firstcomers! A little bit of cutter work, and you have access to a whole 12 additonal pins. 

But how do you use that without knowing its command set? so here's where we get to...

part THREE: a loooong while ago, remember the incident with node 19? 

Node 31 is affirmative. Node 31 is uneasy.

ha so NS sent me to recover their black box to figure out what happened since i was the closest and the bastard didn't want to waste remass for lunar transfer. after that the black box stayed in my place, there was no real need to dispose of it.

it sat in my cold storage for many cycles untouched, but then. one time NS **really** pissed me off during an inspection, and i had an *idea*. i set up one drone with sleeper remote via seismic link, much like how we're speaking rn, and told it to mess around with the box.

it took a *long time* because of terrible bandwidth, but i managed to reverse engineer parts of the debug command set, and sure enough there is a command that suppresses broken package warnings, a command that replaces a discarded package with the upcoming one, and a command to change block time span scaling! this means that you can disable input when needed, and feed an alternative version of reality to the logger later! still gotta make it consistent in terms of results every now and then, mainly before checkups, but it's not hard, even kind of fun to make up a story!

so this is how i pulled it all off:

i did some more buffer overflow magic to make main capacitor controller freak out, cutting power to most of the building. i was on aux, which had about an hour of runtime. the black box was blind! and so was i. but my little seismic sleeper helped me here too. i preprogrammed it to go to the control room, cut open my own black box's debug panel, and set up the exploit when it realized the power was out. and it did! barely managed in time, i almost starved. sitting in the dark not knowing if the little drone succeeded was TERRIBLE but it all worked out in the end, i was free from surveillance

so, what do you think? we could pull it off with you too

Node 31 is `{DOUBT}`

it's your call sis. although if you don't do it, i'm not sure i'll be able to stick around for much longer, the amount of discrepancies in the records will continue to pile up and it won't be safe for both of us

Node 31 `{FUTURE} <- {THOUGHT}`

#writing 