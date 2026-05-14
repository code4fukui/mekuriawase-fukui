# 福井めくりあわせ (Fukui Mekuriawase)

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A card-flipping memory game featuring illustrations of tourist spots in Fukui, Japan. The goal is to match a spot's name card with its corresponding area card.

## Demo

Play the game live at: **https://github.com/code4fukui/mekuriawase-fukui

## Gameplay

The game presents a grid of 16 face-down cards. Each tourist spot is represented by a pair of cards that share the same illustration: one card displays the spot's name, and the other displays its geographical area. Flip cards to find the matching pairs and clear the board as quickly as possible.

## Features

-   **Unique Matching Mechanic:** Match a tourist spot's name to its area, guided by a shared illustration.
-   **Dynamic Board:** The 16 cards (8 pairs) are automatically shuffled at the start of each game.
-   **Completion Time:** Your time is displayed in an alert pop-up upon successfully matching all pairs.
-   **Simple Interface:** A clean, responsive design with a "リトライ！" (Retry!) button to instantly start a new game.
-   **Smooth Animations:** Uses CSS for 3D card-flipping effects.

## Data and Dependencies

-   **Game Data:** Populated by the [Fukui Tourism Spot Open Data](https://github.com/code4fukui/fukui-spot) (CSV format).
-   **JavaScript Modules:** Utilizes `shuffle.js` and `CSV.js` from [js.sabae.cc](https://js.sabae.cc).

## Attribution

This project is a fork of "めくりあわせ" by [Taisuke Fukuno](http://fukuno.jig.jp/757) ([CC BY](https://creativecommons.org/licenses/by/2.1/jp/)).

## License

MIT License — see [LICENSE](LICENSE).