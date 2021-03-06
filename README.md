# bililiteRange
bililiteRange 2.5.2


bililiteRange is a javascript library that abstracts text selection and replacement.

The basic function is in bililiteRange.js, with the documentation at http://bililite.com/blog/2011/01/17/cross-browser-text-ranges-and-selections/


The other files are assorted javascript libraries that use bililiteRange:

bililiteRange.ex.js: Implements the ex line-editor ( http://ex-vi.sourceforge.net/ex.html ). Depends on the util and undo libraries below. Documentation at
http://bililite.com/blog/2014/04/03/new-bililiterange-plugin-ex/

bililiteRange.fancytext.js: Uses bililiteRange to allow using the Prism syntax highlighter (prismjs.com) to create a simple syntax-highlighting text editor. Documentation at
http://bililite.com/blog/2013/12/16/simple-syntax-highlighting-editor-with-prism/
bililiteRange.fancytextasync.js: Like fancytext but allows stacking multiple highlighters asynchronolously.

bililiteRange.util.js: Adds useful functions for searching and keeping the ranges up-to-date with  changes in the underlying text. Documentation at 
http://bililite.com/blog/2013/02/08/bililiterange-plugins/

bililiteRange.undo.js: Adds an undo/redo stack to editable elements. Documentation at
http://bililite.com/blog/2013/12/25/bililiterange-undo/

jquery.jsvk.js: A jQuery plugin to use Ilya Lebedev's JavaScript VirtualKeyboard (http://www.allanguages.info/). Depends on
bililiteRange for character insertion. Documentation at 
http://bililite.com/blog/2013/01/30/jsvk-a-jquery-plugin-for-virtualkeyboard/

jquery.keymap.js: Not really part of the bililiteRange family, but I use them together. A jQuery plugin to turn keydown codes into understandable characters. Also includes a "hotkeys" plugin that allows keystroke handlers for specific keys, like $(el).on('keydown', {keys: '^A'}, function(){}) . Documentation at
http://bililite.com/blog/2015/01/12/rethinking-keymap/

jquery.livesearch.js: jQuery plugin to do "live" searching for a regular expression; highlights  the text found and scrolls to it as you type. Documentation at
http://bililite.com/blog/2013/03/07/new-jquery-plugin-livesearch/

jquery.savemonitor.js: jQuery plugin to track when an element changes and when it is saved. Documentation at
http://bililite.com/blog/2014/01/16/new-jquery-plugin-savemonitor/

jquery.sendkeys.js: jQuery plugin to simulate keypresses. Documentation at 
http://bililite.com/blog/2015/01/14/rethinking-fn-sendkeys/

jquery.status.js: jQuery plugin to display messages and get user input. Documentation at
http://bililite.com/blog/2013/12/12/new-jquery-plugin-status/

The other files are not mature and are not documented at all.
