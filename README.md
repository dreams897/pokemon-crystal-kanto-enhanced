# Pokémon Kanto Enchanced - Crystal Port
## This is a work in progress port of [Pokémon Kanto Enhanced](https://github.com/dreams897/pokered-GBC-Kanto-Enhanced) to the Crystal engine

### Inspired by [RegularLuna's Red++ v3](https://github.com/JustRegularLuna/rpp-backup)

### Main Features:

* First real attempt at porting Pokemon Red to the Crystal engine?!
* QOL updates and bugfixes to the Kanto region while keeping everything very familiar
* Smooth 60fps
* New ENBY (non-binary) player choice being added in addtion to boy/girl!
* Girl/Green/Leaf sprite changed to fit gen 1 look
* Only original 151 Pokémon are obtainable and will not be changed or expanded
* All Starters can be obtained through in-game trades with NPCs in addition to your initial choice
* Most text has been decapitalized
* Switched Good Rod and Super Rod locations
* New text speed options: Instant, Fast, and Medium (Fast being the default)
* New animated Ditto sprite and Bulbasaur added to the Day Care!
* The Day Care aims to be massively improved with new sprites, a PC in the corner, more accessable entrance, and will be added to the map/Fly
* Tangela will be exclusive to the Safari Zone
* New trades have been added, see list below!
* Wild Pokémon areas aim to be a balance between Red, Blue and Yellow

### Roadmap:

* Finish porting all work done so far in [Pokémon Kanto Enhanced](https://github.com/dreams897/pokered-GBC-Kanto-Enhanced)
* Add in Safari Zone

## Frequently Asked Questions

### Q: How is this different from Luna's version?
A: This project is based on the Crystal disassembly and adds a newer engine and code. Compared to Luna's this actually removes many features that I felt were too "new" for the game, or at least my vision of it. I wanted to update the game but still give it that gen 1 feel. This version does not include any new maps such as Mt. Moon Square, Faraway Island, etc. and Mew is now behind the truck in Vermilion dock instead of Faraway island. Also featuring 60fps, only 151 original Pokémon available, the gambler in Viridian city is lying down once agin, many sprites and the tilesets were reverted back to gen 1. Ditto at the Day Care is a new animated sprite and the Day Care in general has been greatly improved visually, but I probably won't be using the egg feature because it doesn't make a lot of sense without baby Pokémon. In-game trades have also been changed, among various other features.

### Q: Are you keeping the newer gen 2 features like cell phone, Pokegear, etc?
A: Some features that are included in Crystal do fit the vision for this project but not all of them. I will not be including the cell phone feature or egg hatching, because they don't add anything useful to this port. With no baby Pokemon and no script changing (dialogue) I see no reason to add these features. I will be keeping features such as shiny Pokemon, berry trees, and the clock!

### Q: Are all Pokémon available?
A: All original 151 Pokémon are obtainable and carefully placed throughout the map or available through trades, Celedon Prize Room, or gifts. No Pokémon past gen 1. 

### Q: Is MISSINGNO still an issue (feature)?
A: I'm probably going to make MISSINGNO a properly numbered Pokémon for less problems, but haven't implemented that yet.

### Q: Is Mew available?
A: Mew will be behind the truck and should be accessable after getting 4+ gym badges

### Q: What are the new in-game trades?
A: As follows:

Give: Marowak 
Get: Haunter (evolves!)

Give: Pikachu 
Get: Staryu

Give: Hypno 
Get: Kadabra (evolves!)

Give: Gloom 
Get: Bulbasaur

Give: Rhyhorn 
Get: Graveler (evolves!)

Give: Primeape 
Get: Machoke (evolves!)

Give: Ninetails 
Get: Charmander

### Q: Is there a Move Deleter/Relearner?
A: There will be a new house in Fuchsia City with both a Move Deleter and Relearner added! Also the grandpa of Bill is still next to it.


### Credits:

* RegularLuna for inspiring me to make this
* lwelyk for coding and support (this is a fork of what they started)

[Discord Channel](https://discord.gg/cSCDrA96yh)


[![Build Status][ci-badge]][ci]

This is a disassembly of Pokémon Crystal.

It builds the following ROMs:

- Pokemon - Crystal Version (UE) (V1.0) [C][!].gbc `sha1: f4cd194bdee0d04ca4eac29e09b8e4e9d818c133`
- Pokemon - Crystal Version (UE) (V1.1) [C][!].gbc `sha1: f2f52230b536214ef7c9924f483392993e226cfb`
- Pokemon - Crystal Version (A) [C][!].gbc `sha1: a0fc810f1d4e124434f7be2c989ab5b5892ddf36`
- CRYSTAL_ps3_010328d.bin `sha1: c60d57a24bbe8ecf7cba54ab3f90669f97bd330d`
- CRYSTAL_ps3_us_revise_010710d.bin `sha1: 391ae86b1d5a26db712ffe6c28bbf2a1f804c3c4`
- CGBBYTE1.784.patch `sha1: a25517f60ca0e887d39ec698aa56a0040532a4b3`

To set up the repository, see [INSTALL.md](INSTALL.md).


## See also

- [**FAQ**](FAQ.md)
- [**Documentation**][docs]
- [**Wiki**][wiki] (includes [tutorials][tutorials])
- [**Symbols**][symbols]

You can find us on [Discord (pret, #pokecrystal)](https://discord.gg/d5dubZ3).

For other pret projects, see [pret.github.io](https://pret.github.io/).

[docs]: https://pret.github.io/pokecrystal/
[wiki]: https://github.com/pret/pokecrystal/wiki
[tutorials]: https://github.com/pret/pokecrystal/wiki/Tutorials
[symbols]: https://github.com/pret/pokecrystal/tree/symbols
[ci]: https://github.com/pret/pokecrystal/actions
[ci-badge]: https://github.com/pret/pokecrystal/actions/workflows/main.yml/badge.svg
