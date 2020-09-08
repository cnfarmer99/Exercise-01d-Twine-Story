# Exercise-01d-Twine-Story
Exercise for MSCH-C220, 3 September 2020

This exercise is should be the final step in creating a minimum-requirement solution for Project 01. You task is to create a story in Twine, export it as a JSON file, and make sure it works with our Python game engine.



Now, launch Twine and create a new project (name it whatever you want). Create a Twine project with at least eight passages. If you need more information about how to format the description or create links, you can review the [Harlowe 3.1.0 manual](https://twine2.neocities.org/#markup_link) or the [Twine 2 Guide](https://twinery.org/wiki/twine2:guide). The engine we have built will remove style markup, and it understands the `[[text->passage]]` or the `[[text|passage]]` link format.

After you have tested your project in Twine and are happy with the result, tap on the name of the project (at the bottom of the window) to open the menu. Change the Story Format to Twison 0.0.1 (if it is not installed, see the instructions in Exercise-01c-Export-from-Twine). Press the Play button, and then copy all the JSON-formatted text that appears in the browser.

Back in Visual Studio Code, open game.json and replace the contents of that file with the JSON from your new Twine project. Save the file.

Open main.py and run the game. Does it work as you would expect? 

Save these files and quit Visual Studio Code. In GitHub Desktop, you should now see main.py and game.json highlighted. Add a Summary message at the bottom of that panel, and push the "Commit to master" button. On the right side of the top, black panel, you should see a button labeled "Push origin". Press that now.

If you return to and refresh your GitHub repository page, you should now see that your files have been changed (with a new date).

Now edit the README.md file. When you have finished editing, commit your changes, and then turn in the URL of the main repository page (https://github.com/[username]/Exercise-01d-Twine-Story) on Canvas.

The final state of the file should be as follows (replacing my information with yours):

# Exercise-01d-Twine-Story

Exercise for MSCH-C220, 3 September 2020

An interactive-fiction game engine, composed in Twine, exported with Twison, and written in Python

## Implementation

Built using Visual Studio Code and Python 3.8.5. game.json was created in Twine 2 and exported with Twison 0.0.1 (https://github.com/lazerwalker/twison)

## References

None

## Future Development

None

## Created by

Jason Francis
