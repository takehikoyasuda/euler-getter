# Euler Getter

Euler Getter is a topology strategy game where shape, loops, and holes decide the winner.

Players take turns claiming cells on a surface. Since both players move alternately, the final territories usually contain almost the same number of cells. The winner is decided not by area, but by the Euler characteristic of each player's territory.

## Play

- English version: https://takehikoyasuda.github.io/euler-getter/
- Japanese version: https://takehikoyasuda.github.io/euler-getter/jp/

## About the game

Euler Getter is played on the projective plane.

The game provides three different visual models of the same surface, so players can compare how the same topology appears in different representations.

The main idea is simple:

- Blue and Red take turns claiming cells.
- When the board is filled, each territory is scored.
- The score depends on the Euler characteristic of the territory.
- Connected pieces, loops, and holes matter.
- The player with the higher score wins.

## What is Euler characteristic?

Euler characteristic is a number that describes the shape of a region.

Roughly speaking, it is affected by how many connected pieces the region has and whether it contains loops or holes. In Euler Getter, this makes the game different from ordinary territory games: choosing cells is not only about taking space, but about creating the right shape.

## Features

- Browser-based HTML game
- Play on the projective plane
- Three selectable visual models of the projective plane
- 3D view and flat view
- Human vs human, human vs AI, and AI vs AI modes
- Built with JavaScript and Three.js
- No external audio files; sound is generated in the browser

## Running locally

Clone or download this repository, then open `index.html` in a modern browser.

For best results, use a recent version of Chrome, Edge, Firefox, or Safari.

The file structure should look like this:

```text
euler-getter/
├── index.html
└── js/
    └── three.min.js
