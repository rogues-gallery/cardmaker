# CardMaker

CardMaker is an application that generates graphics via data sources. It has a graphical user interface for designing layouts and offers scripting functionality.

This application was created to help me generate components for a board game. You can put all of your variable data into a CSV or Google Spreadsheet and then create layouts in CardMaker. This separates your layout and data so you do not have to manually re-create each card. 

Command line based export support is in development (coming soon!). Soon you will be able to build CardMaker into a workflow!

## Download

Latest stable (I hope) release binary: [Download 1.0.0.2](https://github.com/nhmkdev/cardmaker/releases/tag/v.1.0.0.2)
Latest releases (may be a bit unstable): [Download Releases](https://github.com/nhmkdev/cardmaker/releases)

[Download The Game Crafter templates for CardMaker](https://raw.githubusercontent.com/wiki/nhmkdev/cardmaker/CardMaker_TGC_Templates.zip)

## Sample

![](https://raw.githubusercontent.com/wiki/nhmkdev/cardmaker/readme_sample.png)

The above image was generated by the following input data row from a CSV:

| Count | Name | image | skill1 | skill1value | skill2 | skill2value | ability |
| --- | --- | ---- | ---- | ---- | ---- | ---- | ---- |
| 1 | Siani Malia | che.png | T |  3 | B | 4 | Ranged Battle: +1 on all die Rolls @[opt] | 

While there is some interpretation of the data by CardMaker to generate the final result, many of the values are direct references. The layout configuration in CardMaker controls the details of how to actually present the data.

[Further Details on how the Elements for this Layout are configured](https://github.com/nhmkdev/cardmaker/wiki/user-readme-sample)

## Guides / Help

* [CardMaker User Guides Section](https://github.com/nhmkdev/cardmaker/wiki/user)
* [BoardGameGeek CardMaker Guild](https://www.boardgamegeek.com/guild/2250) - Good place for bugs/request/discussions

Note: The code that is submitted may not match the latest binary.

## Code Status

Compiles with Visual Studio Community Edition 2019

See more details in the [Developers Section](https://github.com/nhmkdev/cardmaker/wiki/developers)

[TODO / Wishlist](https://github.com/nhmkdev/cardmaker/wiki/developers-todo)

Toxicity Level: Medium-High
 * Needs more comments
 * Needs warning cleanup
 * Needs some shuffling to allow for more narrow and focused unit testing
 * Needs more unit tests!
 * Every method should be implemented based on an interface and classes should implement hundreds of interfaces (just kidding!!!)

## The Google Issue

If you plan to outright copy the parts of the code that operate with Google Spreadsheets please be aware that the source
currently uses the client id that is associated with my CardMaker application. [Code File](https://raw.githubusercontent.com/nhmkdev/cardmaker/master/CardMaker/Card/Import/GoogleReferenceReader.cs)

You will need to modify this code to correctly use your application.

## Games Developed with CardMaker

CardMaker played some role in the development of these games (prototyping or otherwise). Let me know if you have a game that should be listed here.

| Game Link(s) |
| --- |
| [Cardpocalypse](http://cardpocalyp.se/) & [Cardpocalypse Steam Link](https://store.steampowered.com/app/904400/Cardpocalypse/) |
| [Cave Paintings](http://rnrgames.com/cave-paintings) |
| [Iliad: Heroes of Troy](http://www.escapevelocitygames.com/iliad/)<br/> |
| [Town Builder: Coevorden](https://boardgamegeek.com/boardgame/255633/town-builder-coevorden) & [(Publisher page)](http://www.firstfishgames.com/our-games/town-builder-coevorden/) |
| [NEVO](https://www.thegamecrafter.com/games/nevo) |
| [COBRA](https://www.thegamecrafter.com/games/cobra1) |
| [Context Switch](https://www.thegamecrafter.com/games/context-switch) |
| [Executive Shuffle](https://www.thegamecrafter.com/games/executive-shuffle) |
| [Fairness](https://www.thegamecrafter.com/games/fairness) |
| [Root Cause Analysis Team](https://www.thegamecrafter.com/games/root-cause-analysis-team) |
| [Hard Stop](https://www.thegamecrafter.com/games/hard-stop) |

## History

2009 - First created and publicly released CardMaker

20XX - Lots of bug fixes and features

2015 - CardMaker goes open source

2017 - CardMaker is finally marked as 1.0.0.0 for no specific reason.

### The Name

"CardMaker" and "Card Maker" are both references to the same application. I just never standardized the name.

## Special Thanks

* Eric Raué
* Kolja Geldmacher
* Everyone that has contributed to the project through emailing bugs and requesting features

## Original Author

CardMaker was originally created in 2009 by Tim Stair.
