# themis-api
Themis doesn't really offer an API, but here is some documentation anyway.
You can view the api in your browser or even better, import it in a program called [insomnia](https://insomnia.rest/):

[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=themis-rug&uri=https%3A%2F%2Fglitchcat.github.io%2Fthemis-api%2Finsomnia-import.json)

Link: https://glitchcat.github.io/themis-api/

## insomnia client
If you happen to test some stuff in the insomnia rest client this is what you should know:

`{{ _.base_url }}` is just a placeholder for `https://themis.housing.rug.nl`

`{{ _.year_url }}` is a placeholder for the year it extracted from the "GET course" call, which is as of writing this equal to `/2020-2021`

Both of these are configured in the insomnia enviroment, which should automatically get imported.

# credits
https://github.com/jozsefsallai/insomnia-documenter
