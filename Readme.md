###About the Mistral Package for Sublime Text

The Mistral package for sublime text contains a ton of snippets you can use to build Mistral workflows using Sublime Text. Both Sublime Text 2 and 3 are supported. This package uses the base YAML syntax highlighting included with Sublime Text.

###Pre-Requisites

To install the Mistral pacakge, you first need to install Sublime Text. Go to the following link to download, http://www.sublimetext.com/. This a great application for editing text and supports Linux, Mac, and Windows equally well.

###Install Method 1 - Will Bond's Package Control (Recommended)
Will Bond has made a great plugin that loads packages into Sublime Text. If you use this method you will automatically get updates of the Mistral package when they are released. I highly recommend using this approach.

1. Start Sublime Text
2. Install Package Control from will bond following the instructions at http://wbond.net/sublime_packages/package_control.
3. Press `ctrl+shift+p` (Windows/Linux) or `command+shift+p` (Mac) and type Install Package. You should see "Package Control: Install Package".
4. Type Mistral and press Enter.

###Getting started
A few steps and you will be on your way.

1. Create new file and give it the extension `.mist` and open it in Sublime Text
2. If it doesn't automatically get recognized (You will see Mistral in the bottom right corner), then press `ctrl+shift+p` (Windows\Linux) or `command+shift+p` (Mac) and type `Mistral` and press `Enter`. You should see the bottom right of the status bar change.
3. Type `start,Tab` from the selection box. It will instantly give you a base Mistral file to start and you can set the name accordingly.
4. Use the following snippets to build out your Mistral file and get your workflows going. 
	* `acts,Tab` --> Actions - Create an 'actions:' section in the file.
	* `act,Tab` --> Action - Create a skeleton of action within the 'actions' section.
	* `bec,Tab` --> base: std.echo - Create an action with std.echo as the base.
	* `bem,Tab` --> base: std.email - Create an action with std.email as the base.
	* `bhttp,Tab` --> base: std.http - Create an action with std.http as the base.
	* `bjs,Tab` --> base: std.javascript - Create an action with std.javascript as the base.
	* `bmhttp,Tab` --> base: std.mistral_http - Create an action with std.mistral_http as the base.
	* `bssh,Tab` --> base: std.ssh - Create an action with std.ssh as the base.
	* `wfs,Tab` --> Workflows - Create a 'workflows:' section that will also start off your first workflow.
	* `wf,Tab` --> Workflow - Create a single workflow within an already created 'workflows' section.
	* `tec,Tab` --> task: std.echo - Create std.echo task within the 'tasks' section of the workflow.
	* `tem,Tab` --> task: std.email - Create std.email task within the 'tasks' section of the workflow.	
	* `thttp,Tab` --> task: std.http - Create std.http task within the 'tasks' section of the workflow.
	* `tjs,Tab`` --> task: std.javascript - Create std.javascript task within the 'tasks' section of the workflow.
	* `tmhttp,Tab` --> task: std.mistral_http - Create std.mistral_http task within the 'tasks' section of the workflow.
	* `tssh,Tab` --> task: std.ssh - Create std.ssh task within the 'tasks' section of the workflow.

###License
Copyright (c) 2015 Giampiero De Ciantis <gdeciantis@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
