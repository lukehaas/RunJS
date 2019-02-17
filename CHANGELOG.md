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