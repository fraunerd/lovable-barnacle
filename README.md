# Frau Nerd's pokedex.json
A (German/English) Pokédex for Pokémon GO.

##What's in the JSON file?
The file [pokedex.json](pokedex.json) contains the following Pokémon GO Pokédex data:
- The Pokédex number.
- The Pokémon's German name.
- The Pokémon's English name.
- The kilometres needed to hatch its egg. (Basically: Does this hop out of a 2/5/10 kilometre egg?)
- The kilometres needed to get a candy if you use this Pokémon as your buddy.


##How to use fraunerd-pokedex.json
A Pokémon's data can be accessed by using the **index number**. Keep in mind that the index numbers start at 0 and the Pokédex starts at 1, so: **Index Number equals Pokédex Number-1.** E.g.: Bisasam/Bulbasaur, while **#001** in the Pokédex, has the **index number 0**.

###Accessing a value
To access a value, you can use the corresponding key. For example: **pokedata[0].en** will give you the English name of the 1st Pokémon, which is "Bulbasaur".

* nummer - Pokédex Number
* de - German Name
* en - English Name
* ei - km/Egg
* bonbon - km/Candy

###Example Entries
This is how the entries are stored in the JSON file:
> {
   "nummer": "001",
   "de": "Bisasam",
   "en": "Bulbasaur",
   "ei": "2",
   "bonbon": "3"
 },
 {
   "nummer": "002",
   "de": "Bisaknosp",
   "en": "Ivysaur",
   "ei": "-",
   "bonbon": "3"
 }

###Example Page
For an **example** including a formatted table, check out the [example folder](example). This is what the formatted table looks like:

<img src="http://fraunerd.de/wp-content/uploads/2016/10/pokedex.png" width="300px">
