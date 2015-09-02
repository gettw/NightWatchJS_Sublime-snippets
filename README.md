# NightWatch.js + SublimeText3
Short snippets for writing the Nightwatch.js tests in SublimeText a bit faster.

Nightwatch.js - Framework for writing E2E tests based on Node.js, using Selenium WebDriver (http://nightwatchjs.org)
SublimeText3 - text editor (http://www.sublimetext.com/3)

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

To create a new file with tests use the command 'nwnl' (Night Watch New List of tests)
To add a new test to an existing file use 'nwnt' (Night Watch New Test)

Commands starts with prefix 'nw-'

Assertions and Verifications starts with prefix 'nw_'

So, you can to start typing 'nw_', only to get the assertions/verifications or 'nw-' to get the list just of commands.
