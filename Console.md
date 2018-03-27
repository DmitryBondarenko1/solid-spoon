**Working with Consoles**

 - Introduction
 - Configuring Color Scheme (darcula etc)
 - Customizing Console Font 
 - Customizing Console Colors (foreground ect)
 - Selecting Color (color picker)
 - Running Console
 - Managing Console
 
 **Introduction**

Console in IntelliJ IDEA is a much more advanced tool than a standard application console. Besides common functions like input and output it can change it's appearance according to your preferences to increase its readabilty and helps you write code more efficiently with it's smart functions:
    
 - Code completion 
 - Syntax check with inspections
 - Automated insertion of paired brackets, quotes and braces
 - Scrolling through the history of commands using the arrow keys 
 - Quick documentation lookup
 
 **Configuring Color Scheme**

As said above, you can flexibly tune IntelliJ's console view according to your preferences. In particular, you can individually configure color, font style, and highlighting rules for input, error, and output messages.  To do so, you have to configure Color Schemes.

IntelliJ IDEA appearance is set up by Color Schemes. They define syntax and error highlighting in the editor, search results, Debugger and, consoles. By default, the application has two Color Schemes: default (white colored) and Darcula (dark colored). You can add, delete, and modify Color Schemes.

To customize a color scheme

Go to **Settings** -> **Editor** -> **Color Scheme**.

And select a Color Scheme you want to edit from the **Scheme** dropdown list. Note that here you also have the ability to **Export** and **Import** Color Schemes. Schemes are saved in .icls, .jar or .xml format.

Once set up, you can easily switch to a desired scheme in the main screen of IntelliJ IDEA. To switch between schemes, choose **View** -> **Quick Switch Scheme** in the main menu. In the pop-up window that opens select the desired scheme (Colors and Fonts, Code Style, etc.). In the suggestion list, click the desired option.

**Customizing Console Font** 
 
Navigate to the **Console Font** section where you can define preferred font style, size, spacing, and other font parameters. While **Font**, **Size**, **Line Spacing** parameters are self-explanatory, **Fallback Font** parameter is used for symbols not supported by the main font. As you make your settings, font example is instantly shown in the preview at the bottom of the page.

**Customizing Console Colors** 

Move to the colors settings in the **Console Colors** menu. Here you can define how different messages in the console will look like by changing their color, font, and apply effects. Additionally, you can specify how ANSI colors are displayed in the console.

To customize console color

Select the desired console area you want to customize. See below for the available options.

|Console Area|  Description|
|--|--|
| Background| Defines the background color |
| Error output | Defines the view of error messages |
| Standard output | Defines the view of output messages  |
| System output | Defines the view of output system messages |
| User input| Defines the view of user input messages |

Specify your desired console color settings using the menu in the the right-hand pane.

Note that along with Console, you set your own colors and fonts for the Debugger and other IntelliJ IDEA components.

**Running Console**

Let's have a look at what we have just set up and run a simple Java "Hello World" application with console output. After clicking **Run** in the Editor panel, you see a console with the appication output at the bottom of the IntelliJ IDEA main screen. Note that all messages are highlighted in accordance with the settings you have made.

**Managing Console**

Since IntelliJ idea is a smart tool, it further flexibly enables you to fine-tune the console view by re-sizing, re-locating it on the go. Let's play a with the application we've just Run and make it float. To do so, navigate to the right-hand pane menu of the console and choose Floating option as the image shows. Console now becomes not attached to the main application screen and is displayed on top of other windows in the operating system. 

