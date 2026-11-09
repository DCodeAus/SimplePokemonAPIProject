# Simple Pokémon API Project

A beginner-friendly web page that looks up a Pokémon by name and shows its picture. It's a good first project if you want to try fetching data from an online API (a web service that sends back data instead of web pages).

It uses the free [PokéAPI](https://pokeapi.co), which needs no sign-up or key.

> For a fuller version with type badges, stats and fuzzy name matching, see [pokemon-finder](https://github.com/DCodeAus/pokemon-finder).

## What's in here

| File | What it does |
|---|---|
| `pokemon.html` | The page: a text box, an **Add Pokemon** button and an empty area for the cards. |
| `pokemon.js` | When you click the button, asks PokéAPI for that Pokémon and adds a card with its name and artwork. |
| `style.css` | How the cards look. |

## How to run it

No installs needed, just a web browser.

1. Download this repository: click the green **Code** button › **Download ZIP**, then unzip it.
2. Double-click `pokemon.html` to open it in your browser.
3. Type a Pokémon's name, such as `pikachu`, and click **Add Pokemon**. Each search adds another card.

You need to be online, because the data comes from PokéAPI.

## Things to know

- **Type names in lower case and spell them exactly** (`pikachu`, not `Pikachu`). If the name isn't found, nothing happens: the page doesn't show an error yet.
- You can see the raw data the page receives by opening an address like https://pokeapi.co/api/v2/pokemon/pikachu in your browser.

## Ideas to build on it

- Accept any capitalisation by converting the input to lower case before searching (`pokemonName.toLowerCase()`).
- Show a friendly message when a Pokémon isn't found.
- Show stats such as HP and attack, add a **Random Pokémon** button, or add a berries lookup.

Inspired by a Pokémon project I came across during Hacktoberfest. It's deliberately bare-bones so it's easy to understand and extend.
