# NightWatch.js + SublimeText3
Short snippets for writing Nightwatch.js tests in SublimeText a bit faster.

Nightwatch.js - Framework for writing E2E tests based on Node.js, using Selenium WebDriver (http://nightwatchjs.org)<br>
SublimeText3 - Nice text editor (http://www.sublimetext.com/3)

# How to install and use (in Windows)?
1.  Clone this repository to the folder [%APPDATA%\Sublime Text 3\Packages\User]
2.  Open any of your existing file in SublimeText and start typing 'nw'
3.  Select the desired command from the autocomplete-menu and press TAB

Type more than 'nw' and command list will be shorter.<br>
For example: 'nwfnv' converts to the<br>
.waitForElementNotVisible('selector', timeout, abortOnFailure(boolean [optional]), function(){<br>
&nbsp;&nbsp;&nbsp;&nbsp;//optional callback <br>
&nbsp;&nbsp;}, 'optional message')

Use the TAB after placing of the function, for changing/deleting parameters of current function.

To create a new file with tests use the command 'nwnl' (Night Watch New List of tests)<br>
To add a new test to an existing file use the 'nwnt' (Night Watch New Test)

Commands begin with the prefix 'nw-'<br>
Assertions and Verifications begin with the prefix 'nw_'

So, you can start typing 'nw_', just to get the assertions/verifications or 'nw-' to get just the list of commands.
