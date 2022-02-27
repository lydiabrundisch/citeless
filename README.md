# citeless

Remove citations of author and year for better readability.

![citeless](https://user-images.githubusercontent.com/94746211/155845329-c6934cba-ca74-4b25-b1c0-c7850f169489.gif)

## How to use citeless

Drag the code in the bookmarklet file into your bookmarks bar. Give the bookmark a clear name e. g. citeless. <br>
Alternatively, you can use drag this link into your bookmarks bar: <a href="javascript:t=document.getSelection();t=t.toString();t=t.replace(/((\s|\n)\(([^\)]+)\d\d\d\d\))|(\s\(([^\)]+)\n)|((\s|\n)\(([^\)]+)\n\d\d\d\d\))|((\s|\n)\(\d\d\d\d\))/g, '');navigator.clipboard.writeText(t);" class="entrylink">citeless</a> <br>
Select a text from which you want to remove citations. <br>
Click on the bookmark. <br>
The edited text is now copied to your clipboard and ready to be pasted in your notetaking app of choice. <br>

## Why to use citeless

Studies often have a list of citations for any claim. <br>
While this is good as a scientific practice, it can impair the readability of the text. <br>
This bookmarklet cleans up the text for reading and notetaking.
