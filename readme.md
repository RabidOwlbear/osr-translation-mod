## OSR Translation module

This module contains the localization files and items from the OSR-Helper, OSR-Item-Shop, and OSR-Character-Builder modules. These assets may be used to create translations of these modules.

### How To Use
#### Compendiums: 
This module includes several compendiums contaning various elements of the modules listed above. To add a translation, unlock the desired compendium, and add a new folder named after the language being translated into, followed by the 2 character language code in parenthesis eg English (en).
The included items may be importerd into the game world, translated and then added back to the appropriate compendium.

#### Language Files:
The language files for each module are located in this modules directory in the sub-directory named languages. The languanmge file for each module can be found in its respective folder. The language files are JSON files. These files may be edited with a text editor. It is recommended to use a rich text editor such as notepad++, vscode, or similar.

Create copy of the en.json file that you wish to translate, renaming it with the lowercase 2 character language code of the language your are translating into.

If you are unsure of the languge code, make sure that you are using the desired foundry language, then while in the game worls, press the f12 key on your keyboard to open the developer console. Navigate to the console tab in the console, and enter the following and press enter.
```
game.i18n.lang 
```
This will display the two character language code. eg. "en"

Once you have created the copy of the en.json file and renamed it you may begin translating the module text.
On opening the file you should see some text similar to the example below. This is the localization data for the module you are translating.

```
"OSRH.settings.timeJournal.name": "Name Of Journal Entry",
"OSRH.settings.timeJournal.hint": "Name Of Journal Entry To Use For Time Keeping",

```
In the above example, only the text in quotes on the right side of the colon needs translating.

Once all the necesary text has been translated make sure to save the file in the same location as the en.json file you copied.

Once all the items/journals etc. hav been translated and added to the module compendiums, and the new language file has been created and translated you can make a zip file containing the module folder and its contents. Please make sure to add the language name or language code to the zip filename. 
