# Dictionaries for Sublime Text 2

The following repository contains some dictionaries for the sepll checker feature of Sublime Text.

Each language was downloaded from the Open Office list. Credits to the people working on that languages! Read every LANG.txt for details.

	http://extensions.services.openoffice.org/en/dictionaries

## Language List

 * Català
 * Dansk
 * Ελληνικά
 * Español
 * Français
 * Italiano
 * Nederlands
 * Română
 * Polski
 * Português (do Brasil)
 * Português (Europeu)
 * Svenska

## Idea

Since installing a new language requires some non easy procedures. The idea is to collect here the dictionaries ready for use.

Today this contains a list of some languages, the idea is to extends the list with help from the community.

## Adding a new language

My primary language is Spanish, then I'm not sure of the state and quality of the different languages added here.

Please if you found a better dictionary or something to improve, your change will be welcome.

To add a new language:

 * Download the language file from link above.
 * Rename the "some.oxt" file to "some.zip"
 * Unzip the file
 * Look for three files: "lang.aff", "lang.dic" and "readme_lang.txt"(or something similar)
 * Open the "lang.aff" to check the encoding used. Such the line: "SET ISO-8859-1"
 * Convert that file to UTF-8 from the used encoding
 * Convert "lang.dic" to UTF-8 from the used encoding.
 * Convert "readme_lang.txt" to UTF-8 from the used encoding.
 * Change "SET ISO-8859-1" to "SET UTF-8"
 * Copy "readme_lang.txt" to "lang.txt"
 * Copy these three files to this repository
 * Open a pull request to help improve this package! Thank you.