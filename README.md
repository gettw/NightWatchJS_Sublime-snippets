# NightWatch.js + SublimeText3
Short snippets for writing the Nightwatch.js tests in SublimeText a bit faster.

# How to install and use (in Windows)?
1.  Clone this repository to the folder [%APPDATA%\Sublime Text 3\Packages\User]
2.  Open any of your existing file in SublimeText and start typing 'nw'
3.  Select the desired command from the menu and press TAB

Type more than 'nw' and command list will be shorter. 
For example: 'nwfnv' converts to the 
.waitForElementNotVisible('selector', timeout, abortOnFailure(boolean [optional]), function(){
    //optional callback
  }, 'optional message')

Use the TAB after placing of the function, for changing/deleting parameters of current function.
