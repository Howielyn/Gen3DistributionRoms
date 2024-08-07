# Information about the ROMs

## Egg Events
As discussed in the video, each egg events have interal randomization, but there is the possibility to overrule it using button combinations. Below are all the combinations listed for each event.

### PCNY Eggs
- 0 → A: Chansey
- 1 → B: Drowzee
- 2 → A + B: Exeggcute
- 3 → R: Farfetch’d
- 4 → R + A: Kangaskhan
- 5 → R + B: Lickitung

### PCJP Eggs
- 0 → A: Bellsprout
- 1 → B: Meowth
- 2 → A + B: Oddish
- 3 → R: Poliwag

### PokéPark Eggs
- 0 → A: Cacnea
- 1 → B: Corphish
- 2 → A + B: Corsola
- 3 → R: Igglybuff
- 4 → R + A: Minun
- 5 → R + B: Pichu
- 6 → R + A + B: Plusle
- 7 → L: Psyduck
- 8 → L + A: Skitty
- 9 → L + B: Spinda
- 10 → L + A + B: Spoink
- 11 → L + R: Surskit
- 12 → L + R + A: Taillow
- 13 → L + R + B: Whismur
- 14 → L + R + A + B: Wynaut

## Mystery Gift
One of the custom events we made is getting a Potion or a Pokéball from the delivery guy. Sometimes the delivery guy makes a mistake and gives you an item you weren't supposed to get. Below we'll go a bit more into detail on how this works exactly.

### How does the randomness work?
The scripts does an RNG call and performs a modulo 1000 operation on it to get a random value. Based on this outcome you either get:
- Potion (0 - 494)
- Pokéball (495 - 990)
- Rare item (991 - 999)

I won't spoil here what the rare items exactly are. But... if you would like to know, they are listed in my Discord server.

Link to the Discord:
https://discord.gg/pVGFUcCAVS
