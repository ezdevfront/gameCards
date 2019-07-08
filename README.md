# gameCards
Simple Cardgame packaged as a Windows WPF project.
Written in C# with Visual Studio 2017 and a simple "Model-view-controller".
Unit test cases for basic functions are provided in separate folder. However when CardGame.App is opened in visual Studio, Unit-test project is included as normal. All tests are runnable in VS 2017. Most likely VS 2019 as well.

* Default number of Decks are set to 2 in project, its however easy to change in source code.


* Implements basic functionality according to specs:
* -Deck is created in sorted order hearts(Ace, 2, 3...King), diamonds, clovers, spades.
   If 2 or more decks are present: hearts( Ace, Ace, 2, 2, 3, 3...King, King) etc same as above.
* Functions
* -Pull card -shows first card in deck and shows it until next card i drawn.
* -Shuffle Deck -shuffles deck in random order.
* -Sort Deck -sorts the deck accoring to color and value.

* Unit tests are provided in CardGameApp.UnitTests/UnitTest1.cs
* Sort, Shuffle, Pull Card are all present as Unit tests.

* Grafical layer has some extras in: "New Game" and "Quit button"
* Also when deck is shuffled or sorted, backside of card deck is shown.

Enjoy!

