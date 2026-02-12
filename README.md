# Pokémon Crystal Plus

This is a fork of the [Pokémon Crystal disassembly](https://github.com/pret/pokecrystal) at [PRET](https://github.com/pret).

This fork adds new features while maintaining compatibility with the base game. It doesn't modify core save data structures unnecessarily.

## Branches

There are several branches, each with different features:

**qol-features** branch:
* Running shoes with updated sprites
* Updated surf sprites
* Reuse Repel
* Infinite text speed option
* Infinite TMs + TM names in menu
* Trade back NPC in Elm's lab
* Trainer card shows all 16 badges in color
* Celebi event resotred after beating E4
* Allow fishing while surfing
* Pocket PC as Key Item
* Unique colors for thrown Pokeballs
* 60 FPS overworld


**following-pokemon** branch:
* All Pokemon now follow behind player
* Updated NPC Overworld Pokemon sprites, replacing generic
* Updated Party Menu Icons, replacing generic
* Vanilla Crystal otherwise

**master** branch:
* Combination of above branches
* Also added Electivire and Magmortar as held-item trade evolutions, just for fun.
* Electirizer and Magmarizer are found in Team Rocket Base B3F and Mount Mortar B1F respectively

<img src="https://github.com/user-attachments/assets/bdeb5d00-a2d9-4c3d-b448-ef061b11289d" width="400" height="790">

<img src="https://github.com/user-attachments/assets/5a23fed0-7263-4ac4-8081-9201cc157fa0" width="400" height="790">

## Planned Features
* Difficulty selection.
* Add ability to get all 251 mons.

## Known Bugs
* I haven't found any yet but I am sure there are plenty.

## Credits
* Following Pokemon branch came directly from Fellowship of the ROMs fork of pokecrystal [Pokémon Crystal](https://github.com/fellowship-of-the-roms/pokecrystal) - Modified slightly to ensure vanilla save compatability. 
* MegamanOmega and [Pokémon Crystal Clear](https://shockslayer.com/crystal-clear/) - Following Pokemon sprites.
* [Pokémon Polished Crystal](hhttps://github.com/Rangi42/polishedcrystal) - Another great Crystal Hack and sorce of Electivire and Magmortar sprites.
* [pokecrystal Wiki](https://github.com/pret/pokecrystal/wiki/Tutorials) - Many great tutorials.

Tried to make sure I also gave credit in commits when possible, but if I missed anyone, please feel free to reach out!


# Pokémon Crystal [![Build Status][ci-badge]][ci]

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
- [**Tools**][tools]

You can find us on [Discord (pret, #pokecrystal)](https://discord.gg/d5dubZ3).

For other pret projects, see [pret.github.io](https://pret.github.io/).

[docs]: https://pret.github.io/pokecrystal/
[wiki]: https://github.com/pret/pokecrystal/wiki
[tutorials]: https://github.com/pret/pokecrystal/wiki/Tutorials
[symbols]: https://github.com/pret/pokecrystal/tree/symbols
[tools]: https://github.com/pret/gb-asm-tools
[ci]: https://github.com/pret/pokecrystal/actions
[ci-badge]: https://github.com/pret/pokecrystal/actions/workflows/main.yml/badge.svg
