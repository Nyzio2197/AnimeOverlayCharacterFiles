# AnimeOverlayCharacterFiles
All the character files used in Anime Overlay

If you wish to create a new character, do the following:

Fork this repository
Find an audio clip of the character, either talking or making a noise. Without any background music if possible, try to isolate the sound
Rename that audio file to: sound.mp3
Find a peeker of the character, cut out the background, and make the image square
Make sure the image is in png format, and rename it to [your character name here].png
Create a JSON file that fills out this for:

{
	"First" : "",
	"Last" : "",
	"Tags" : [
		"Gender" : "",
		"Sauce" : "",
		"Genre" : [
			"Anime" : "false",
			"Light Novel" : "false",
			"Manga" : "false",
      "Game" : "false"
			]
		]
}

First is first name
Last is last name, if there's a middle name add it here too
Gender is either "Female" or "Male"; no trap or reverse trap please
Sauce is the name of the Anime/Game/LN/Manga it's from. If there is multiple sources, put the original name regardless of season
Genre is filled out simply, if it is any of the categories change the "false" to "true"

Save the JSON file
Put all 3 files into a folder named [first name] all lowercase and without spaces
compress it into a .zip file
Start a pull request

Once you've done that, I will look through your request to check that everything is in order and add it to this repository
