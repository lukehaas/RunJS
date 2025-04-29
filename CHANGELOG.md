### Version 3.1.1 - 29 April 2025
- Fix an issue that affected searching for snippets

### Version 3.1.0 - 20 April 2025
- Add new Magic Comment feature
- Updated Open AI model list
- Improved AI context
- Add the ability to stop AI content generation
- New ColorCode theme
- Added an NPM Packages button to the activity bar
- Fixed an issue that caused values set via prompt() to be undefined
- Fixed an issue with cursor positioning in indented snippets
- Improved handling for tabs that have become unresponsive
- Improved formatting method
- Upgraded Node.js to version 20.16.0.
- Upgraded Chromium to version 128.
- Upgraded V8 to version 12.8.

### Version 3.0.3 - 08 October 2024
- AI chat - chat with Open AI models for code generation and questions.
- Improved support for top-level await.
- Added an activity bar.
- Added support for alert(), confirm() and prompt().
- Various performance improvements.
- Increase hover delay for inline tooltips.
- Added icons to settings tabs.
- Improved support for installing native modules.
- Upgraded Node.js to version 20.15.1.
- Upgraded Chromium to version 126.
- Upgraded V8 to version 12.6.

### Version 2.12.1 - 21 May 2024
- Fix an issue that caused file content to be loaded twice when opening a file.

### Version 2.12.0 - 24 April 2024
- Improved support for ES modules
- Updated build options to move away from Babel naming conventions
- Tab titles now default to the first line of text within the associated editor
- Added the ability to import and export snippet libraries
- Added the ability to toggle syntax highlighting on output results
- Added a shortcut for displaying completion suggestions
- Rename the runtime values setting to expression results
- Line matching now appends values to lines if the source line is the same
- Deleting snippets now requires confirmation

### Version 2.11.0 - 24 February 2024
- Add ability to re-open closed tabs.
- Output context menu improvements.
- Change auto-save to occur on change instead of run.
- Improve handling of extra wide tooltips.
- Prevent pasting when closing a tab with the middle mouse click on Linux.
- Upgrade Node to 20.9.0.
- Upgrade Chromium to 122.
- Upgrade V8 to 12.2.

### Version 2.10.1 - 20 December 2023
- Add support for regular expression pattern modifiers plugin proposal.
- Add support for optional chaining assignment plugin proposal.
- Add tab context menu options for closing other tabs and closing tabs to the right.
- Add support for trailing commas in generic types.
- Improve handling for custom fonts.
- Support TypeScript version 5.2.
- Upgrade Node to version 18.16.1.
- Upgrade Chromium to version 116.
- Upgrade V8 to version 11.2.
- Various bug fixes.

### Version 2.9.0 - 18 April 2023
- Outdated NPM packages can now be updated.
- Fix an issue that caused the formatting settings to always display default values.
- Auto fold proto properties in output results.
- Upgraded Node to version 18.14.0.
- Upgraded Chromium to version 112.
- Upgraded V8 to version 11.2.
- Dropped support for Windows 7 and Windows 8.

### Version 2.8.0 - 06 March 2023

- Add support for top-level await.
- Change the way auto-updates are handled.
- Rename Preferences to Settings.
- Fix a Prettier code formatting issue.
- Fix an issue that caused some system fonts to not appear in the font list.
- Fix an issue that could cause RunJS to open off-screen on Windows.
- Upgrade Node to 16.17.1.
- Upgrade Chromium to 108.
- Upgrade V8 to 10.8.

### Version 2.7.5 - 26 January 2023

- Fix an issue that caused loop protection to always be enabled.
- Fix an issue that caused inconsistent positioning of some error messages.
- Fix an issue that caused some web requests to be blocked.
- Improvements to how prototypes are displayed in output results.
- Nested objects in output results are now auto-folded.
- Improvements to module scoping when setting a working directory.

### Version 2.7.4 - 09 December 2022

- General improvements to error handling.
- Better handling of shortcuts when windows are open.
- Update TypeScript to version 4.9.
- Fix missing install button when importing mising packages.
- Fix an issue that caused tsserver to remain running after quitting.

### Version 2.7.3 - 09 November 2022

- Make autocomplete case insensitive.
- Fix an issue that caused snippet suggestions not to appear when writing their full alias.
- Fix an issue that caused language services to fail for some Windows users.
- Remove support for deep links.

### Version 2.7.1 - 05 October 2022

- Add cursor position placeholder to snippets
- Rename the "Transpilation" tab to "Build"
- Move the preference option for bundling from the advanced tab to the build tab
- Prompt to save when closing a tab that has previously been saved and now has unsaved changes
- Files can now be opened via drag and drop
- Improved guarding against infinite loops
- Added icons to the layout options in the view menu
- Added a helpful tooltip to the environment variables window
- Added a context menu to the burger menu on Windows
- Upgraded Node to version 16.16.0
- Upgraded Chromium to version 106
- Upgraded V8 to version 10.6

### Version 2.6.0 - 17 August 2022

- Added support for bundling to enable ESM imports
- Added Ayu theme
- Minor UI tweaks to snippets and environment variable windows
- Guard against pasting very large files
- Upgraded Node to 16.14.2
- Upgraded Chromium to 102
- Upgraded V8 to 10.2

### Version 2.5.1 - 05 July 2022

- Fix an issue that affected light theme icons.

### Version 2.5.0 - 28 June 2022

- Add support for snippets.
- Some preference options now have tooltips to better explain their function.
- Autocomplete suggestions now have icons.
- Fixed an issue that could cause the menu to be unresponsive on Windows and Linux.
- Updated the naming for items in the Tools menu.

### Version 2.4.1 - 25 May 2022

- Fix an issue with sync scrolling.

### Version 2.4.0 - 24 May 2022

- Type information and relevant documentation can now be displayed on hover.
- Function signatures can now be displayed while typing.
- Added an option to confirm before closing a tab.
- Editor and output panes can now be scrolled synchronously.
- Windows and Linux have an updated UI with a more minimal appearance.
- Updated the way formatting options are managed.
- Added 'Stop' and 'Kill' items to the Action menu.
- Upgraded Node to version 16.13.2.
- Upgraded Chromium to version 100.
- Upgraded V8 to version 10.

### Version 2.3.0 - 05 February 2022

- Output URLs can now be opened via cmd/ctrl-click.
- Added support for console.assert().
- Added a shortcut and menu item for toggling block comments.
- Tabs can now be closed by clicking the middle mouse button.
- Fixed an issue with the comment shortcut not working on international keyboards.
- Fixed an issue that caused the save-as modal to appear when saving a newly opened file.
- Fixed an issue that could cause line duplication when formatting code.
- Improved the way system fonts are retrieved.
- Added support for Spanish.

### Version 2.2.2 - 20 December 2021

- Add ability to set tab titles.
- Add icons to theme menu
- Remove need for restart from activation/deactivation.
- Move deactivation button to Manage License dialog.
- Upgraded Node to 16.9.1.
- Upgraded Chromium to 96.
- Upgraded V8 to 9.6.
- Numerous improvements for better performance and reliability.
- Opened files now appear in a new tab.
- Fixed an issue with find/replace.
- Fixed an issue that could cause tooltips not to appear.
- Improved syntax highlighting for TypeScript.
- Updated UI theme colours for greater consistency with macOS Monterey.
- Improved handling of large files.
- Improved handling of large output.
- Improved handling of escape characters in output.
- Windows builds are now signed.

### Version 2.1.3 - 22 August 2021

- Fixed an issue with escaped line-breaks in output.
- Improved accuracy of line matching in some scenarios.
- Added more shortcuts for tab navigation.
- Fixed an issue that could cause language services to not start on
- Windows machines with spaces in the directory path.

### Version 2.1.1 - 26 July 2021

- Fixed an issue that caused Intel mac users to be auto-updated onto an arm build

### Version 2.1.0 - 24 July 2021

- Added ability to switch between horizontal and vertical layout.
- Added a new premium theme, One Dark.
- Added a preference option to hide the tab bar when only one tab is present.
- Upgraded Node to 14.16.0.
- Upgraded Chromium to 91.
- Upgraded V8 to 9.1.
- Optimised and improved the formatting method.
- Fixed output highlighting issues for symbols and regex.
- Fixed a language service disconnection issue.
- Fixed an issue that caused unnecessary re-runs when toggling Babel.
- Fixed an issue with toolbar height on macOS Big Sur.
- Added more shortcuts for navigating tabs.

### Version 2.0.1 - 26 June 2021

- Fixed an issue that caused the preferences window to be clipped on Windows.
- Fixed an issue with importing local files.

### Version 2.0.0 - 19 June 2021

- Added support for multiple tabs
- Added support for autocomplete
- Added support for type checking
- Added a new menu called Tools
- Moved NPM Package Management and Environment Variable Management under the new Tools menu
- Updated app icon
- Added two new themes - SynthWave '84 and Shades of Purple
- Made Babel presets configurable
- Added a new Babel plugin - plugin-proposal-async-do-expressions
- Changed the way transpiled code is shown - it can now be displayed in the main output pane
- Fixed an issue that caused internal packages to be accessible as imports
- Fixed an issue with multi-line template strings
- Fixed an issue with regex output styling

### Version 1.15.1 - 11 April 2021

- Fix an issue that caused displaying output to be slow on Windows

### Version 1.15.0 - 09 April 2021

- Increase accuracy of output
- Errors are no-longer shown in isolation - where appropriate
- Improved output for async and generator functions
- Proxies and Promises and no-longer displayed unwrapped in the output
- Maps and Sets now show values in the output
- Fixed an issue where NPM would fail to install packages for some users.
- Fixed an error that occurred when opening the About dialog on Linux.
- Updated V8 to version 8.9
- Updated Node to version 14.16.0
- Updated Chromium to version 89

### Version 1.14.1 - 25 February 2021

- Fix issue with opening menu windows on Windows.

### Version 1.14.0 - 21 February 2021

- Add Apple M1 support
- Add builds for Linux ARMv7 and ARM64
- Add support for console.clear()
- Core-js polyfills are no-longer included if Babel is disabled
- Fix issues with menus on first launch
- Update V8 to version 8.7
- Update Node to version 12.18.3
- Update Chromium to version 87
- Fix issue #225 - output issue

### Version 1.13.1 - 07 February 2021

- Fix issue #215 - unable to copy output text

### Version 1.13.0 - 05 February 2021

- Add ability to stop execution of script
- Fix issue where focus would be lost when clicking on the title bar
- Fix issue where the RunJS window wouldn't re-opened when opening a file from the File menu
- Fix issue where errors from promises were not being displayed
- Fix issue where some fonts were mislabeled
- Refactored some core parts of RunJS for performance improvements

### Version 1.12.2 - 08 November

- Fix issue #193 - closure issue
- Fix issue with displaying objects with over 800 properties

### Version 1.12.1 - 02 November

- Fix code caching issue

### Version 1.12.0 - 01 November 2020

- Add auto-scroll option
- Add ability to display instance properties and **proto**
- Add loading spinner to show when code is running
- Fix for bug that could cause duplicate output results to appear
- Fix for bug that caused searching for namespaced NPM packages to fail
- Fix for bug that caused removed environment variables to still be available
- Performance improvements
- Update V8 to 8.5
- Update Node to 12.6.3
- Update Chromium to version 85

### Version 1.11.0 - 29 August 2020

- Add ability to match output line to source line
- Add support for console time methods
- Add support for find/replace
- Improve styling for forms on dark mode
- Add support for context-menu
- Improve support for promises
- Tabbing a selected now indents it
- Update V8 to version 8.3
- Update Node to version 12.14.1
- Update Chromium to version 83
- Fix issue #167 - JSON formatting issue

### Version 1.10.1 - 24 July 2020

- Fix issue with unchangeable babel options
- Add a new theme - 'Visual Studio'

### Version 1.10.0 - 17 July 2020

- Improve protection for long running scripts
- Environment variable inputs now select on focus
- Brief visual highlight for new NPM packages and environment variables
- Improve scrollbar styling
- NPM package table header is now sticky
- Fix issue #127 - nested objects and arrays are not expandable
- Fix string formatting and line break issues
- Add decorators as an option
- Rework handling of NPM
- Add support for console.table
- Replace esprima with estree for better modern syntax support
- Gutter folds now only show on hover
- Add support for matching highlights
- Make source type unambiguous for top level `this` support
- Change shortcut for formatting to Alt+Shift+F
- Add install assist for missing packages
- Add prettier formatting options
- Add sublime keymap
- Add option for auto-closing brackets

### Version 1.9.0 - 08 May 2020

- Add clear option to edit menu
- Add Fantasque font
- Improve scrollbar styling
- Add ability to toggle Babel plugins from preferences
- Display sound icon when audible
- Fix issue #105 - Mute print function
- Fix issue #125 - Save cancellation error

### Version 1.8.0 - 02 February 2020

- New icon - designed by Giuseppe Caruso
- Add ability to set environment variables
- Fix for #100 - Loop when formatting
- Relax `process` stripping - #114

### Version 1.7.0 - 29 September 2019

- RunJS for Mac is now notarized
- Add ability to take screenshots
- Address #95 - process.memoryUsage() is unavailable
- Add ability to format code via Prettier
- Fix an issue with installing packages with long names

### Version 1.6.0 - 08 August 2019

- Fix issue #88 - Set Work directory not working on Windows10
- Fix issue #87 - Can RunJS remember the window position/size between usages?
- Fix issue #84 - Themes do not apply except Dracula on 1.53
- Show welcome message when RunJS is opened for the first time

### Version 1.5.4 - 03 July 2019

- Fix issue #85 - Set Work directory not working

### Version 1.5.3 - 17 June 2019

- Enhancement #82 - Increase font size to more than 30px
- Fix issue #81 - Assigned function call on last line does not evaluate

### Version 1.5.2 - 12 June 2019

- Fix issue #79 - TypeScript won't run

### Version 1.5.1 - 10 June 2019

- Fix issue #67 - Output is scrambled in lines
- Fix issue #75 - Let `fs` work in working directory
- Fix issue #78 - Set working directory no longer working

### Version 1.5.0 - 22 April 2019

- Fix issue #61 - Settings window won't open on Linux
- Support editor shortcuts on non-darwin systems
- Add ability to toggle output
- Add update option to menu
- Fix issue #69 - multiple declarations cause syntaxerror
- Fix issue #68 - Caching problem?
- Fix issue #66 - Quitting from macOS doc causes error

### Version 1.4.0 - 10 March 2019

- Fix issue #58 - console formatting bug
- Divide preference options into tabbed sections
- Add ability to choose font options
- Log NPM errors

### Version 1.3.1 - 03 March 2019

- Fix issue #55 - quirky handling of string outputs
- Fix issue #54 - exception ordering issue
- Fix issue #52 - missing exception outputs
- Fix issue #50 - User defined window properties persisted
- Fix issue #14 - extra line-break at the end of output
- Fix line-number misalignment

### Version 1.3.0 - 17 February 2019

- Fix issue #48 - Babel stacktrace bug
- Add preference option for loop protection
- Set Working Directory now allows for importing local files
- Add shortcut for installing Node packages
- Add new window for viewing transpiled output
- Add preference option for holistic evaluation
- Add preference option to show undefined values in output
- Fix issue #51 - incorrect syntax highlighting for strings

### Version 1.2.4 - 06 February 2019

- Fix issue #8 - dialog is hidden in vim command mode
- Fix issue #26 - setInterval keeps running
- Fix issue introduced in 1.2.3 that prevented the app quitting

### Version 1.2.3 - 02 February 2019

- Guard against long running loops - fixing #42 and #6

### Version 1.2.2 - 29 January 2019

- Fix issue #47 function declarations are remembered between executions
- Fix issue #44 cmd+w should not quit the app
- Fix issue #36 path is sometimes undefined
- Implement enhancement #15 zooming should increase font size

### Version 1.2.1 - 20 January 2019

- Prevent autoeval on start if autoeval is disabled
- Improve error messages for syntax issues
- Fix issue #37 bug in handling async..await

### Version 1.2.0 - 07 January 2019

- Add support for installing Node packages

### Version 1.1.0 - 27 December 2018

- Upgraded Electron to version 4.0.0
- Handle calls to `alert` and `confirm`
- Improved handling for `console.log`
- Added support for auto-closing brackets

### Version 1.0.2 - 10 December 2018

- Fixed an issue with variables declared within brackets

### Version 1.0.1 - 02 December 2018

- Improved support for TypeScript
