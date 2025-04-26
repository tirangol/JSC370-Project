# An Analysis of Competitive Pokémon Usage on Pokémon Showdown

This project is a statistical study of all Pokemon and their competitive usage numbers on Pokemon Showdown, attempting to find the properties of a Pokemon that contribute most to its usage. Only the Pokemon's base statistics, typing, and common movesets are considered. Data from [Smogon](https://www.smogon.com/dex/sm/pokemon/) and [Veekun](https://veekun.com/dex/pokemon/search) is used to extract Pokemon and move information, while common moves and usage numbers are obtained from Smogon's [monhtly compiled analyses](https://www.smogon.com/stats/) of Pokemon Showdown! games (specifically, data from January 2019 was used).

To reproduce the dataset, run the initial code chunks inside `final.Rmd`, which should generate a file called `dataset.Rda` which is used by the website and by later code in the same file.

As the final assignment of JSC370, the website is available [here](https://tirangol.github.io/JSC370-Project/index.html) and the final PDF report is available [here](https://github.com/tirangol/JSC370-Project/blob/main/final.pdf).
