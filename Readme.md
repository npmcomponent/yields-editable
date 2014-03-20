*This repository is a mirror of the [component](http://component.io) module [yields/editable](http://github.com/yields/editable). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-editable`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# editable

  Fixing `contenteditable`, checkout the [demo](http://yields.github.io/editable/index.html) find bugs and report :)

#### Goals
  
  Provide Editor authors with the ability to simply create a UI without thinking
  of the resulting html output, html sanitization or `UndoManager`.

  This might result in multiple tiny components, that each solve a problem `contenteditable` has,
  then Editor authors can simply pick features by installing `editable-*` components and build a UI.

#### Why not use Aloha, RedactorJS etc..

  Both editors are awesome, but they both have large bloated dependencies, such as
  UI components, rangy, jQuery etc..

  Moreover Aloha is 1mb of source code, arguably both cannot be used because of their license.

#### Installation
  
    $ component install yields/editable

#### License

  MIT
