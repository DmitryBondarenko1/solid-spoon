**Working with Consoles**

 - Introduction
 - Selecting Color Scheme
 - Customizing Console Font 
 - Customizing Console Colors
 - Running Console
 - Managing Console
 
 **Introduction**

Console in IntelliJ IDEA is a more advanced tool than a regular application console. Besides common functions like input and output you can change it's appearance and behaviour according to your preferences and сonsequently work more efficiently.

This article covers only standard IntelliJ IDEA application console. For inforamtion on specific consoles like JShell, Terminal, Groovy, refer to the corresponding separate articles.
 
 **Selecting Color Scheme**

As said above, you can flexibly tune IntelliJ IDEA's console appearance according to your preferences. To do so, first you have to select a Color Scheme.

IntelliJ IDEA's appearance is set up by Color Schemes. They define interface color, code highlighting in the editor, search results, and consoles. By default, IntelliJ IDEA has two Color Schemes: default (white colored) and Darcula (dark colored). You can add, delete, and modify Color Schemes.

**To customize color scheme**

Go to **Settings** -> **Editor** -> **Color Scheme**.

Select a Color Scheme you want to further edit from the **Scheme** dropdown list. Note that here you also have the ability to **Export** and **Import** Color Schemes. Schemes are saved in .icls, .jar or .xml. You can create your own schemes and share them with other users around the world.

![enter image description here](https://github.com/DmitryBondarenko1/solid-spoon/blob/master/Scheme1.jpg)

Once set up, you can easily switch to a desired scheme in the main screen of IntelliJ IDEA. To switch between schemes, select **View** -> **Quick Switch Scheme** in the main menu. In the appeared list, click the desired scheme.

![enter image description here](https://github.com/DmitryBondarenko1/solid-spoon/blob/master/Switch1.jpg)

**Customizing Console Font** 
 
Once you selected a Color Scheme, you can proceed to configure a console font. Navigate to the **Console Font** section where you can define preferred font style, size, spacing, and other font parameters. While **Font**, **Size**, **Line Spacing** parameters are self-explanatory, **Fallback Font** parameter is used to display symbols not supported by the main font. As you make your settings, font example is instantly shown in the preview screen at the bottom of the menu.

![enter image description here](https://github.com/DmitryBondarenko1/solid-spoon/blob/master/font1.jpg)

**Customizing Console Colors** 

Next, navigate to the color settings in the **Console Colors** menu. Here you can individually configure color, font style, and highlighting rules for input, error, and output messages. Additionally, you can also define ANSI and Log Console colors.

**To customize console color**

Select a desired console area you want to customize, see table below for available options.

|Console Area|  Description|
|--|--|
| Background| Defines the background color |
| Error output | Defines the color of error messages |
| Standard output | Define the color of output messages  |
| System output | Defines the color of output system messages |
| User input| Defines the color of user input messages |

Specify your desired console color settings using the menu in the the right-hand pane.

![enter image description here](https://github.com/DmitryBondarenko1/solid-spoon/blob/master/ConsoleColor2.jpg)

Note that along with Console, you can set your own colors and fonts for the Debugger and other IntelliJ IDEA components.

**To re-assign ANSI colors**

Select a color in the ANSI menu from the list and specify ANSI color to be assigned in the the right-hand pane.

You can always return to default color settings by clicking **Reset** in the top right corner of the menu.

**Running Console**

Let's have a look at what you have just set up and run a simple Java "Hello World" application. After clicking **Run** in the main menu, you see a console with the application output at the bottom of the IntelliJ IDEA main screen. Note that "Hello World!" is highlighted with a red dotted line in accordance with the settings you have made. 

![enter image description here](https://github.com/DmitryBondarenko1/solid-spoon/blob/master/hello2.jpg)

**Managing Console**

Since IntelliJ idea is a smart tool, it enables you to fine-tune a console view even further by manipulating it on the go. Let's play a bit with the application you have just run and make console float. To do so, navigate to the right-hand pane menu of the console and choose **Floating** option. Console now becomes unattached from the main application screen and it is displayed on top of other windows in the operating system. 

![enter image description here](https://github.com/DmitryBondarenko1/solid-spoon/blob/master/float2.jpg)
