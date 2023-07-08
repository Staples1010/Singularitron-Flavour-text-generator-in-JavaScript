# Singularitron-Flavour-text-generator-in-JavaScript

This project showcases a flavour text generator that can be used to display random combinations of verbs and nouns. This idea was first seen on <a href="https://www.youtube.com/ZackFreedman">Zack Freedman's</a> "<a href="https://www.youtube.com/watch?v=sxfJOMjZeIs&t=3s">Singularitron</a>" and was made to show useless loading text while useful stuff happens in the background. <a href="https://github.com/ZackFreedman/Singularitron/blob/master/SingularitronFirmware/flavortext.h">Check out Zack's code!</a>

# Modifications
In this version, some modifications have been made to the original code:

- The Patreon sponsors have been removed.
- The previous 20-character limit per line has been eliminated.
- The array now includes "ing" forms of verbs, allowing for multi-word verbs such as "Backing up."

# Usage
The flavour text generation functions provide different flavours based on their respective arrays. Here's a brief overview of each function:

```FlavourTextGenerator()```
This function generates a random flavour text by selecting a verb from a combination of constructiveVerbs and destructiveVerbs arrays and a noun from the nouns array.

```constructiveFlavourTextGenerator()```
This function generates a constructive flavour text by selecting a verb from the constructiveVerbs array and a noun from the nouns array.

```destructiveFlavourTextGenerator()```
This function generates a destructive flavour text by selecting a verb from the destructiveVerbs array and a noun from the nouns array.

# Examples
Here are some examples of the generated flavour texts:

Aligning your mom
Deallocating hot tub
Constructing the funk
Dissolving the impostor

# Try it
Check out my <a href="https://codepen.io/Staples1010/pen/MWEMpGK">CodePen</a> to see the generator in action.

Feel free to use these functions in your projects to add some fun and random flavour text!

Note: The original code is the work of Zack Freedman, with modifications made for this particular use case.
