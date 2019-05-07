# twinejs-custom
Minor customization of the tool [twinejs](https://github.com/klembot/twinejs).
Uses "Twine 2.3.1 Web" as it's base

## Changes
- Added more colors for the tags
- The default "gray" tag is shown in the passage block as well, like to other color tags
- Changed the color for some tags
- Changed the text color to black for light colored tags 
- Added visual indicators for special texts in the passage editor, these include:
  - Bold/Italic
  - Code
  - Collapsed
  - Hook
  - Link
- Changes the text color for the above mentioned text types for the Dark Theme
- Gave the `heading` class a more contrasting color in both themes to increase visibility
- Due to readability issues, I have converted the minified JS & CSS to prettified JS & CSS

## Preview
**Tag Colors**

![Tag Colors](/Previews/Tag-Colors.png)


**Light Theme**

![Light Theme](/Previews/Light-Theme.png)


**Dark Theme**

![Dark Theme](/Previews/Dark-Theme.png)

## Reason
- I believe that it will help editing much easier, and prevent error
- Allow more tags color
- Make the content in the editor more *visual*
- I use Twine to make quick flow chart for easy project management, instead of its intended use, thus these changes help my purpose, while should help others as well

## Known Issues
- The "gray" colored tag indicator on the passage border doesn't show up initially if it the only tag. TO fix this, first assign it another color, and then re-assign the gray color, or add another tag and then remove it. Once done, it sharts showing up normally.

## TO-DO
These will be very low-priority changes for me, and hence may never see light of the day. But if I ever get the chance/time to:
- Support for keyboard shortcuts in the editor (Maybe even replace the current one with a rich-text editor, like ckeditor)
- Add more tag colors
- Option to set custom tag colors
- Drop-down/auto-complete when adding tags
