# Getting Started

1. Download a copy of this vault and open it with Obsidian.md
2. Copy a PDF of The One Ring Core Rules into the `_Assets/PDFs/official` directory. The file **must** be named `TOR_Core_Rules.pdf` for the links to it to work correctly. Once you've done this, the very bottom of this note should display the title of the book instead of an error message! This is enabled by the PDF++ plugin that allows you to snip segments of a PDF and make them appear in your notes. You can copy other official PDFs following the naming conventions listed [[_Assets/PDFs/official/Readme|here]].
3. Create your Company by making a duplicate of the `New Company` folder, or directly editing its files. The vault is designed to support multiple simultaneous TOR games, with all of the notes for each fellowship company stored in its own folder ("Hamar and Leylin/" is provided as an example). Note that some of the notes use dataview queries to automatically make lists (see [[An Unlikely Duo]] as an example). You will need to edit the queries to use your own folder name. 
4. Create your PC(s) by making a new file in `PCs/` within your company's directory. Name the file after your character, then use the Obsidian command palette to `Insert Template` and select `PC-Template` from the list.  Your basic stats are defined in the properties section at the top of the file, but you'll need to fill in the basic some info in the top section, click the boxes to mark your Skills, and add your gear. 
	- Note that PC notes are designed to be opened in a separate, narrow tab on the side of the screen (like this [[screenshot-adventure.png|screenshot]]). ![[screenshot-adventure.png|right lp relative wmed]]
	- If you add the `disable_tracks` to the `cssclasses` property in a file, then it will not let you click the boxes used for showing stats. This is helpful to enable to make sure you aren't accidentally changing your stats.
	- When editing a file in source mode, if you see  ` =this.XX` that is a dataview query which will pull in a value from the properties. You should edit the property instead of replacing the command.
	- Note that some styles aren't applied when in editing mode. Instead of boxes for skills, you'll see text like ` 1/6 ` . The tracker boxes will only render if you are in Reader mode (press cmd-E or click the book icon in top right of the editor).
5. Create your first Phase by making a new file in your `Phases/` directory. Use the Obsidian command palette to `Insert Template` and select `Phase-Template` from the list.
	- Your  new file should show up in the Phases list for your company note, sorted by the value of the `phase` property. I suggest starting with `1.1` for the first session, `1.2` for the second, etc leading up to `2.1` when you move on to your second Adventure Phase.
	- I break each phase down into Scenes using headings within a file.
	- There are templates for Councils, Combats, and Skill Endeavors that you can add within a phase to get a nice info box. Note that some of the formatting doesn't work in edit/live preview mode. Changing to reading mode (cmd-e on Mac) should make trackers appear correctly.
6. ![[screenshot-combat.png|right lp relative wmed]]Fight a battle using the Combat Excalidraw file. This shows the beautiful tracker made by @Pokke. 
	- The [Excalidraw Plugin](https://github.com/zsviczian/obsidian-excalidraw-plugin) is used to let you easily drag images (PCs, enemies, etc) around.
	- Some sample tokens are provided. You can group them with Parry (shield) and Might (diamond) shapes to display extra info. 
	- You can use the Command Palette to `Load Workspace`  and select Combat to get a window breakdown similar to what is shown in the screenshot.
7. Notes can display adversaries in nice stat blocks [[AdversariesCON#^MessengerOfLugburz|like these]]. The blocks are rendered using the The One Ring 2E Statblocks plugin. The adversaries themselves need to be stored in YAML format. I have converted all of [[AdversariesCON|Circle of Nom's custom adversaries]] into this format. Check out all of their great homebrew content on [itch.io](https://circleofnoms.itch.io/the-one-ring-2e-homebrew-materials)!
	- Since all the adversaries are included in one big file, you need to refer to them with block IDs using `^` symbol when making a link to a file. Some of these IDs are currently broken.
8. Check the [[Rules]] file to remind yourself of key rules, or [[Rafamirs_Loremaster_Charts_v1_8.pdf|Rafamir's Loremaster Charts]]. Some example content from the rules have been provided (e.g., the [[Dwarves of Durn's Folk|Dwarf]] and [[Hobbits of the Shire|Hobbit]] cultures); you will need to add your own content for others. *TODO*: Instead of including content from the rules, we could use PDF++ to embed content from the PDFs into these pages. That way they will only appear for users who own the PDF ([[Men of Bree]] is an example).
9. For best results, keep all of your own files just inside your Company folders. This way if the vault gets updated you'll be able to easily copy over your content.
10. Hopefully this is enough to get you started. Customizing Obsidian can be a deep rabbit hole, so you'll have to decide how much time you want to spend playing versus setting up your environment. Either way, have fun!


## Vault Layout
- `_Assets/` holds the content files that drive the rest of the vault. Be sure to copy in your rulebook files as mentioned above in Getting Started.
- Some Cultures and Callings have been included as examples. You can put in the data for your own following a similar structure.
- (add more info here?)

## More Info

### Hotkeys
The vault comes with the following hotkeys predefined (for a mac, not sure about windows):
- `cmd-e` - Toggle Read and Edit view
- `cmd-s` - Toggle Source and Live Preview Edit modes.


### FAQ
1. What is Obsidian.md?
Obsidian.md is a powerful knowledge base and note-taking application that operates on top of a local folder of plain text Markdown files. It allows users to create and manage interconnected notes, making it ideal for personal knowledge management and organization. 
2. Will this vault get updated?
Maybe - check [the github repo for the latest]()
3. Will this documentation get updated?
Who knows?!


![[TOR_Core_Rules.pdf#page=1&rect=77,526,548,668|TOR_Core_Rules, p.Front Cover]]

*Are you seeing an error message above this? That means you haven't added the core rules PDF to your `_Assets/PDFs/official/*` directory! See getting started above.*

