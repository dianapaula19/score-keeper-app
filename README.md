# Score Keeper: Quidditch edition

> **Original version:** this README and some fixes were added in 2026. To see the project exactly as it was first built, browse commit [`db36b73`](https://github.com/dianapaula19/score-keeper-app/tree/db36b7360c37096911f4d8d47e62f211e710b2b7) (2020-03-16).

An Android app that keeps the score of a Quidditch match between **Gryffindor** and
**Slytherin**: +10 for a goal through a hoop, +150 for catching the Golden Snitch, after which
the app announces the winner (or a tie). A reset button starts a new match, and
there is a separate layout for landscape.

Made for the *Google Developer Challenge Scholarship* (Android Basics, Udacity, December 2017).

## Screenshots

<p>
  <img src="docs/start.jpg" width="24%" alt="A new match, 0 to 0">
  <img src="docs/winner.jpg" width="24%" alt="Gryffindor wins 190 to 60">
</p>
<img src="docs/landscape.jpg" width="60%" alt="Landscape layout">

Rendered in 2026 from the app's own layouts with [Paparazzi](https://github.com/cashapp/paparazzi):
a new match, Gryffindor winning after catching the Snitch, and the landscape layout.

This repository holds the app module (`src/`) only. To run it, create an empty Android Studio
project and replace its `app/src` folder with this `src` folder.
