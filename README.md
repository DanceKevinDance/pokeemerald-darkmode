# Pokémon Emerald - Dark Mode

This is a fork of pret's pokeemerald decomp to add a dark mode style UI to the game. The reason I make these is to make it playable for myself, a person with a severe visual disability, but the hope is that others either like me or who just prefer darker UIs can also get some use and enjoyment out of it. As such, this isan accessibility-first hack, not one with peak aesthetics in mind. I'm neither a designer nor a programmer. My goal was to get a dark mode without having to spend hours perfecting every little menu element color. I think it looks decent, but not perfect. By all means, if you're interested in making it look better, fork it or suggest changes.

[Here's some screenshots!](https://imgur.com/a/WDl06kj)

(The original README is at the bottom and the INSTALL is the same as pret's original)

## Reworked Menus:

Battle UI
Bag
Options Menu
Dialog/selection Boxes
Pokedex
PokeNav
Party Screen
Shop
PC
Summary Screen
Most other smaller menus I found
Probably some I can't think of


## Known Issues:

-On the starter selection screen, the box that shows the Pokémon's name is messed up. This is unavailable as it shares a palette entry with text that is used literally everything else in the game, so it was a lesser of two evils
-In the Pokedex, when you select a Pokémon and scroll over to the 'size compared to you' screen, that no longer really works Like above, it was that or mess up text elsewhere.
-Some screens are not going to look nearly as pretty as vanilla. I'm sorry, but I would rather get a useable game up and be able to spend that time applying this to other hacks rather than trying to trace every simple palette index to change colors of every little section. Again, I'm not a designer by any means. I just want to be able to play the game.


## How to Play:

### Build it Yourself:
The INSTALL.md is the same as pret's original repo because the instructions are the same when it compes to compiling it yourself. 

### Patch a legit Pokémon Emerald ROM:
There will be a release page on the right. Find the most recent one and see the instructions there. The ROM should be the default Pokémon Emerald Version ROM and it should work with most.

### Is there a hack you like that there isn't a dark mode patch for yet?
Assuming the hack shared a lineage with pret's pokeemerald, check the releases on this repo. There will be a loose files option when you can download it and drop the files into that repo. Obviously this requires you to clone and build that repo first. This may require some tweaking if the ROM is heavily edited and I make no promises that any will work at all. 


## My Other Projects:

[Pokémon Crystal Dark Mode](https://github.com/DanceKevinDance/pokecrystal_darkmode)
- [Pokémon Super Crystal - Dark Mode](https://github.com/DanceKevinDance/Pokemon_Super_Crystal_DarkMode/releases/tag/release)

[The Elder Scrolls IV: Oblivion Remastered - Dark Mode UI](https://www.nexusmods.com/oblivionremastered/mods/3317?tab=description)


##Original README starts here

# Pokémon Emerald

This is a decompilation of Pokémon Emerald.

It builds the following ROM:

* [**pokeemerald.gba**](https://datomatic.no-intro.org/index.php?page=show_record&s=23&n=1961) `sha1: f3ae088181bf583e55daf962a92bb46f4f1d07b7`

To set up the repository, see [INSTALL.md](INSTALL.md).

For contacts and other pret projects, see [pret.github.io](https://pret.github.io/).
