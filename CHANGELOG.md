### v0.2 - Settings and QoL improvements
	- Added - Added an options menu to personalize CHSplit:
		- Always on top - Makes the CHS' window stay above any other window.
		- Always show active section difference - In the current active section, displays the difference between your PB and current score.
		- Show current score in an active section - In the current active section, displays the current total score.
		- Anchor last section to the bottom - Attaches the last section of a song to the bottom of the window making it always visible with the current PB.
		- Show song's progress bar - Displays the song current time and progress bar.
		- Hide the total score panel - Hides the total score and total difference text for minimalistic display.
		- Show animations - Animate the song progress bar stripes, smooth out auto-scroll and animate sidebars opening.
		- Autoscroll to active section - On an active section change scroll to the new active section.
	- Added - Added a separate system for backwards compatibility with other versions and future releases of Clone Hero.
	- Added - Message for when CHS is launched without Clone Hero.
	- Added - Dark mode.
	- Added - Escape now closes opened menus.
	- Added - The window position and size is now remembered upon closing.
	- Added - Loading screen.
	- Changed - Disabled CHS in practice for now, caused more issues than needed.
	- Changed - The difference text under the main score display now actually shows the current difference.
	- Changed - Splits files now store every single completed run instead of just PBs.
	- Changed - Changed how the API layer works, greatly improving CHS performance.
	- Changed - Made it so that the menu/practice message is always centered.
	- Changed - Backend now waits for frontend to establish connection.
	- Changed - Progress bar animation is now linear.
	- Fix - Fixed a crash after the game was closed.
	- Fix - Fixed a crash where launching CHSplit before the game would result in a crash.
	- Fix - Fixed last section not getting updated after finishing a song.
	- Fix - Fixed an occasional bug where sections wouldn't get cleared on song change.
	- Fix - Fixed the entire window refreshing on song restart.
	- Fix - Fixed the weird sidebar slide transition when resizing the program's window.
	- Fix - Fixed a bug where auto-scrolling to the last section would scroll to the middle of the section bar.
	- Fix - Fixed some song.ini issues with some Unicode characters.
	- Fix - Fixed the song timer surpassing the song length.
	- Fix - Fixed a crash when song.ini contained duplicate key entries

### v0.1.1 - Hotfix
	- Fix - Fixed when restarting from the endscreen the split file doesn't get properly loaded.
	- Fix - Fixed score screen disappearing when in end screen in-game.
	- Fix - Fixed the empty space below section bar when there are few sections.
	
### v0.1 - Initial Pre-Release