# tree-view-filter

Atom package which hides files in the tree view that don't match the provided pattern(s).

![screencast](https://raw.githubusercontent.com/monsterkodi/tree-view-filter/master/img/screencast.gif)

## usage

Press `alt-cmd-shift-f` or invoke `Tree View Filter:Show` to focus the filter pattern editor, 
enter your pattern and press Enter/Return to confirm.

To restore the tree view to its unfiltered state:  
either press `Escape` when the filter editor has focus  
or click on the clear button to the right.

## known issues

The filter only sets the display style of the file entries to 'none'. 
When navigating the tree view with the keyboard, the invisible items still get focus.  
I am not sure yet if this can be resolved without changing the tree-view package itself.

## todo

* nicer style (blend in with status bar)
* update filter when directory is expanded
* specs

## credits

* screencast generated with [dergachev/screengif](https://github.com/dergachev/screengif)
* file pattern matching by [minimatch](https://www.npmjs.com/package/minimatch)

and the usual suspects

* almost as good as coffee: [coffeescript](http://coffeescript.org/)
* a truly hackable editor: [atom](https://atom.io/)
* grunt, grunt, [grunt](http://gruntjs.com/)

## warning

This is my first Atom plugin, hacked together in an evening.  
It probably won't break anything (e.g. delete all your code :)  
but still: use at your own risk!

[atom package](https://atom.io/packages/tree-view-filter)
