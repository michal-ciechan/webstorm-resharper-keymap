# WebStorm ReSharper Keymap

Webstorm key map file to match as close as possible ReSharper's (Visual Studio) settings.

Being a C# Developer using Visual Studo for 10 years and have got Visual Studio / ReSharper shrotcuts engrained in my head, and recently getting a new laptop and noticing all my keymaps are wrong in WebStorm, I decided to upload my KeyMap to GitHub for

 1. As a personaly repository for this file, and be able to track changes / merge conflicts
 2. Help anyone else with the same issue coming to WebStorm from Visual Studio / ReSharper!

 ## Warnings

There may be some non-standard shortcuts here, which I will try to point out whenever I can!

Certain shortcut combinations are not possible in WebStorm e.g. (`Ctrl`+`T`, `T`, `T`) for `Search text`, also I found certain shortcuts to be too slow to use in WebStore such as (`Ctrl` + `T`, `T`) for `Navigate` -> `Class`, so may have been omitted!

I will try to list these in seperate section of this Readme!

# Installation

You can install this keymap by placing it in the default location that WebStorm looks for keymaps and then restarting WebStorm.

I found that this is one of the following:


## Hard Link form GitHub

I personally checked out this GitHub repo, and then created a `Hard Link` form the cloned file, to the WebStorm keymap folder using the following command:

**

 - `%USERHOME%\.WebStormXXX\config\jba_config\win.keymaps`
  - `%USERHOME%\.WebStormXXX\config\keymaps`

Where `.WebStormXXX` is the WebStorm version!

E.g. (one of)

 - `C:\Users\lndco\.WebStorm2018.2\config\jba_config\win.keymaps`
  - `C:\Users\lndco\.WebStorm2018.2\config\keymaps`

### Making Hard Link

```
mklink /H "C:\Users\lndco\.WebStorm2018.2\config\jba_config\win.keymaps\Visual Studio _ReSharper_GitHub.xml" "C:\Users\lndco\Documents\GitHub\webstorm-resharper-keymap\Visual Studio _ReSharper_GitHub.xml"
```

# Key Remaps

<div>
  <ul>
    <li>Debug - <kbd>F5</kbd></li>
  </ul>
</div>


 - Go To Symbol - <kbd>Ctrl</kbd> + <kbd>T</kbd>
 - Surround With - <kbd>Ctrl</kbd> + <kbd>E</kbd>, <kbd>U</kbd>
 - Go Back - <kbd>Ctrl</kbd> + <kbd>-</kbd>
 - Go Forward - <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>-</kbd>
