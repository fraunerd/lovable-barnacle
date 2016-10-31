#Example page created using fraunerd-pokedex.json
Check out the index.html for an example of how to turn the JSON file's content into a formatted table. 

##How to access a Pokémon
A Pokémon's data can be directly accessed by using the **index number**. Keep in mind that the index numbers start at 0 and the Pokédex starts at 1, so:
>Index Number equals Pokédex Number-1.

E.g.: Bisasam/Bulbasaur, while *Number 1* in the Pokédex, is **pokedata[0]** in the example.

##How to access a value (e.g. English name)
To access a value, you can use the corresponding key:
>JSON.stringify(pokedata[i].en)

This will give you the English name of a Pokémon.

###The keys
These are the keys I included:
* nummer - Pokédex Number
* de - German Name
* en - English Name
* ei - km/Egg
* bonbon - km/Candy

