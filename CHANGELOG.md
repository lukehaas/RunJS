## Version 1.6.0 - 08 August 2019
  - Fix issue #88 - Set Work directory not working on Windows10
  - Fix issue #87 - Can RunJS remember the window position/size between usages?
  - Fix issue #84 - Themes do not apply except Dracula on 1.53
  - Show welcome message when RunJS is opened for the first time

## Version 1.5.4 - 03 July 2019
  - Fix issue #85 - Set Work directory not working 

## Version 1.5.3 - 17 June 2019
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