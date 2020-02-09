![CHSplit](https://github.com/Tornith/CHSplit/blob/master/logo.png?raw=true)<br>
## A tool to assist with score grinding in Clone Hero

# !!! IMPORTANT: The current version of CHSplit does *not* work with CHLauncher !!!

**CHSplit** allows you to easily track your score progress throughout runs of your songs in **Clone Hero**. Inspired by [LiveSplit](https://livesplit.org/).

## Features
* **Difference with your personal best** - CHSplit remembers your previous runs of songs, compares your current run with your personal best and shows you the difference in each section.
* **Everything is automatic** - CHSplit reads the song info and sections and splits fully automatically based on your selected song in-game and your playthrough. You don't have to manually search for anything! It also separates splits based on the song's speed, difficulty and chosen modifiers.
* **No need to overwrite any Clone Hero files** - CHSplit automatically detects an instance of Clone Hero and reads the values directly from the game.
* **Many new features soon!** - CHSplit is still early in development with a lot of planned features. You can track the development progress on the public [Trello page](https://trello.com/b/bgwuqQQ4/chsplit).

## Options
CHSplit allows you to **customize** your experience with the program. By navigating to the menu in the top left of the app window you can open the side menu where you'll find the **Options** button. Here you'll find a variety of preferences to toggle on and off.
* **Game version selector** - Here you have to specify what version of Clone Hero you're running. **You always have to select the correct version or CHSplit will not work!** This list will automatically update with future releases of Clone Hero and requires you to be connected to the internet to download the correct files *(only needs to be downloaded once, then you are free to stay offline)*.
* **Various customizables:**
    * **Always on top** - Makes the CHSplit's window stay above any other window.
    * **Always show active section difference** - Displays the difference between your PB and current total score in the current highlighted active section.
    * **Show current score in an active section** - Displays the current total score in the current highlighted active section.
    * **Anchor last section to the bottom** - Attaches the last section of a song to the bottom of the window making it always visible with the current PB.
    * **Show song's progress bar** - Displays the song's current time and progress bar.
    * **Hide the total score panel** - Hides the total score and total difference panel for minimalistic display.
    * **Show animations** - Animate the song progress bar stripes, smooth out auto-scroll and animate sidebars opening *(If you're using two monitors with different refresh rates it is recommended to be toggled off to prevent frame limiting)*.
    * **Autoscroll to active section** - Scroll to the current active highlighted section upon entering it in-game.
* **Style selector** - Choose a style of the program that suits you. *Planned to be highly customizable in the future*.

## Installation
CHSplit is a **fully portable** application, with the exception of the `offset` files. CHSplit comes bundled with offset files for the latest version of Clone Hero, as of that CHSplit's version release, otherwise they ***need*** to be downloaded either automatically upon choosing the corresponding version in the app's options or manually from the [`remote/offset`](https://github.com/Tornith/CHSplit/tree/master/remote/offsets) folder above.
1. **Download** the latest CHSplit version in the [releases tab](https://github.com/Tornith/CHSplit/releases) for your corresponding OS.
1. **Extract** the files from the downloaded archive to your desired folder.
1. **Launch** CHSplit and choose your CH version in the options:
    1. With internet connection available, the `offset` files will be downloaded **automatically**.
    1. Without internet connection, please download the corresponding `offset` files **beforehand** from the [`remote/offset`](https://github.com/Tornith/CHSplit/tree/master/remote/offsets) folder above and place them into the *offset* folder within the directory of your `CHSplit.exe` file.
    
## FAQ
**Q: Does it work with CHLauncher?**<br>
*A: As of the v0.2 release, CHLauncher does **not** work with CHSplit. However it is currently my top priority to make CHLauncher compatible with CHSplit at the moment.*

**Q: Where do I report bugs?**<br>
*A: If you find any sort of bugs, please report them here on GitHub in the [issues tab](https://github.com/Tornith/CHSplit/issues). Please search for your issue first to avoid any duplicate reports. Please attach your latest log file in your report if you're able to.*

**Q: My game is lagging whenever I have CHSplit open. What's up with that?**<br>
*A: If you're using a dual monitor setup with different refresh rates, please either make sure to run CHSplit on your higher refresh rate monitor or try **disabling animations** and enabling **always on top** in the settings. CHSplit is rendered using your GPU and there is an ancient bug with Windows where the higher refresh rate monitor gets limited to the lower refresh rate if there is something being rendered on the other monitor.*

**Q: Is feature *XYZ* planned?**<br>
*A: You can find all planned features and their development progress on the public [Trello page](https://trello.com/b/bgwuqQQ4/chsplit). If you'd like to suggest any features you can use the **Feature request** template in the [issues tab](https://github.com/Tornith/CHSplit/issues) (Please avoid duplicates)*

**Q: When will the next version get released?**<br>
*A: Please be patient, it will be released when it's ready. I am a university student and I do this in my free time and I can't spend it all coding, that'd drive me nuts.*

**Q: Is it compatible with previous Clone Hero versions?**<br>
*A: CHSplit is compatible with every major release of Clone Hero starting from v23.2.2.*

**Q: Is CHSplit going to be released for x86, Mac and Linux in the future?**<br>
*A: Yes, I plan to release CHSplit for all of those in the future.*

**Q: It's not working!**<br>
*A: Please report your bugs and issues here on GitHub in the [issues tab](https://github.com/Tornith/CHSplit/issues). Be as much descriptive as possible.*

## Licence
MIT License

Copyright &copy; 2020 Tornith

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

When using the CHSplit or other GitHub logos, be sure to follow the [GitHub logo guidelines](https://github.com/logos).
