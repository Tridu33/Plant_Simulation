.topic 0x88981338
The window shows the structure of the selected Frame, listing the names of all objects contained within.
.topic 0x8898133a
Enter the name of the object, which you want to find.
.topic 0x88981339
Click Find to find the object whose name you entered into the text box. The program searches the list and highlights the object it found. Click Find again to find additional instances of the search term. If you are searching for several objects and do not remember their exact names, you can use regular expressions in your search, such as ^, $, |, ., *, [, ], to confine your search by exactly putting together the term you want to find. The program does not distinguish between upper and lower case.
.topic 0x889d1386
The window lists the Name of the attribute or of the method in the leftmost column, its Signature, i.e., the data type or data types of its parameters, its Value, if the value is inherited (i) or not inherited (ni) or neither inherited nor not inherited (no entry), and if a waituntil instruction can observe the attribute or the method (asterisk, *) or not (no asterisk). The rightmost column shows the Name of the attribute or of the method in German.
.topic 0x85360cce
Type in the name of the library. You can type in any combination of letters, numbers, spaces, and special characters. The library name does not have to be the same as the name of the library folder.

SimTalk:
setLibraryInfo, getLibraryInfo
.topic 0x85360ccf
Type in the version of the library. You can enter any number of numbers and letters separated by periods.

SimTalk:
setLibraryInfo, getLibraryInfo
.topic 0x85360cd0
Type in a meaningful description of the library. The dialog Manage Class Library shows this description.

SimTalk:
setLibraryInfo, getLibraryInfo
.topic 0x85360cd1
Type in one or more alternative paths for your library. As a rule, you will not enter an alternative path. Plant Simulation identifies a library by its absolute path to the library folder in the Class Library. When you type in an alternative path, this absolute path will also be assigned to this library.
.topic 0x88ef14db
Select what the program finds from the left drop-down list. Then, enter into the drop-down list to the right: The name of an object, a condition, an expression contained in an attribute, part of the source code of a Method, or an expression contained in a table.
.topic 0x88ef14dc
Depending on what you select in the list to the left, you will enter into the right list:

The name of the object you want to find.

A condition. A condition can be a SimTalk expression whose attributes or methods are identical to the expression you enter in the drop-down combo box. You might enter the name of an attribute or a method and the expression you are looking for, such as Proctime = 100, or OpenCtrl = void, etc. Or enter an expression contained in any of the built-in or the user-defined attributes of the objects within the search scope. To evaluate them, Plant Simulation converts the attribute values of the objects to be checked into strings. The source code which you entered into a Method object. This also finds source code in user-defined attributes of type Method. To jump to the location of the source code in the method editor, double-click the source code in the results field. Double-click again to jump to the next occurrence of the source code. To jump to the previous occurrence of the source code, hold down Shift and double-click. An expression contained in a list or table object within the search scope.
.topic 0x88a11398
To use regular expressions in your search, click this. Select any of the displayed regular expressions in the window Regular Expression. The program enters the special characters designating that expression into the right drop-down list. Enter the expression, which you want to find, after the special character.
.topic 0x88a11391
To search for whole words only, select this. When you clear it, the program also searches for parts of words.
.topic 0x88a11392
To match the case, upper or lower, of the expression you entered, select this. To find the expression regardless of the case, clear it.
.topic 0x88a11393
To use regular expressions in your search, select this. The program then finds the regular expressions, which you selected in the Window Regular Expression.
.topic 0x88ef1552
To ignore the name or text that an object inherited in your search, select this. The program then only finds the original name or text, and not the name or text in derived or duplicated objects.
.topic 0x88ef14dd
Enter the name of the folder or the Frame, in which the program is going to start searching for the expression you entered into the text box. Or click the button and select a folder or a Frame in the dialog Select Object.
.topic 0x88ef14d9
To also search all Frames located within the Frame in which the item you are searching for is located, select this.
.topic 0x88ef14da
To start searching for the term, which you entered, click Find.
.topic 0x88ef14de
The program shows the items that it found in the list field. Double-click the name of an object or of the source code in the list field to open its dialog window. Or right-click the object and select Open on the context menu. Double-clicking or selecting Open again jumps to the next occurrence of the found item. When you searched for source code, you can right-click the Method(s) in the results list and select to replace the found source code with the source code, which you enter into the dialog Replace in Selected Methods.
.topic 0x88b513d8
To Replace the new object with the one in the class library, select this. Then, the program does not load the new object, but replaces it with the existing object and merges all inheritance hierarchies into one.
.topic 0x88b513d9
To replace all duplicate objects, click Replace All.
.topic 0x88b513d6
To Rename and keep the duplicate class, select this. Then, enter a new name for the duplicate class object.
.topic 0x88b513d7
Enter a new name for the duplicate object class.
.topic 0x88ca1408
Enter a title for your simulation model file. The title does not have to be the same as the file name.
.topic 0x88ca140a
Enter the subject of the simulation model. Use the subject to group files that belong together. This allows you to search for all files covering a certain subject.
.topic 0x88ca140c
Enter the name of the person who created the simulation model.
.topic 0x88ca140e
Enter a keyword or keywords describing the simulation model. You can use the keyword when searching for the file.
.topic 0x88ca1410
Enter any kind of comment you deem helpful for yourself or any other user of the simulation model. You can use the comment when searching for the file.
.topic 0x85040d2c
To show this dialog, when you open a new model, select this.
.topic 0x85040760
To apply the settings you selected in the dialog to all new models, which you create hereafter, click this.
.topic 0x8504060c
Tu update all libraries, which are not current, to the most current state, click this.
.topic 0x852a083c
Select the language of the currently open simulation model. Plant Simulation saves this setting to the model file.
When you create a new simulation model, the model language determines:

The names of folders and objects, such as MaterialFlow and Station for English or Materialfluss and Einzelstation for German.

The return value of the attributes that correspond to the entries of the drop-down lists.

The contents of the window Show Attributes and Methods. When the model language is German, the window lists the German names of the attributes and methods. For all other model languages the window lists the names in English.

The names, which the feature Auto Complete in the method editor suggests. When the model language is German, the method editor suggests the German names of attributes and methods. For all other model languages it suggests the English names.

When you change the model language, the user interface language of Plant Simulation will not be changed. The user interface language of Plant Simulation is determined by the operating system of your computer. You can change user interface language with the command line argument -UILanguage.

SimTalk:
language
.topic 0x852a083b
Select the date and time format for your simulation model. You can select the English 12 hour, the English 24 hour, or the German date and time format.
.topic 0x852a0bc7
Select which kind of comment the program adds to your model file (.spp), each time you save it: Without comment adds no comment. With comment opens a comment window, each time when you save the model. Enter your comment here. When you select Without comment or With comment the program adds a row to the dialog Model Saving History each time you save the model. When the model crashes, the program adds a description of the problem to the dialog instead of a comment. This helps our software engineers detect what caused the crash. None does not save the history of how you saved your model.
.topic 0x852a083e
Click this and navigate to the folder in which to store the object libraries. Or type in several directories separated by a semicolon. The library manager checks this folder/these folders for the most up-to-date version of a library and lets you download it to your hard drive from there. This way you can add company-specific and project-specific libraries to your simulation model.
.topic 0x884111cd
To show the Names of the objects below their icons in the Frame window, select this.

SimTalk:
ShowObjectNames
.topic 0x884211ea
To show the names of the parts (MUs) in your simulation model, select this. This only works, when you also select Show object names.
.topic 0x884111ce
To show the Labels, which you entered for the objects, below their icons in the Frame window, select this. If you also selected to Show object names, Plant Simulation shows the labels below the names.

SimTalk:
ShowObjectLabels
.topic 0x884111cf
To show the number of an incoming connection for each material flow connection in the Frame window, select this. The program only shows the predecessors in the Frame window when you also select Show connections.
.topic 0x884111d2
To show the number of an outgoing connection for each material flow connection in the Frame window, select this. The program only shows the successors in the Frame window when you also select Show connections.
.topic 0x889015e8
To show the display panels, which you defined for the objects, in the Frame window, select this.

SimTalk:
ShowDisplayPanels
.topic 0x884111df
To show connections, i.e., the Connectors between the objects in the Frame window, select this. An arrow in the middle of the Connector shows the direction. The commands Show predecessors and Show successors only work, when you also select Show connections.
.topic 0x884111e1
To show the grid points in the Frames of an open model, select this. This feature is useful for automatically aligning objects while you insert them. Enter the spacing of the grid intervals on the X-axis and the Y-axis into the text boxes below Frame grid spacing. Or click Show Grid on the toolbar of the Frame. You might want to select Show object borders as well.
.topic 0x884111e4
To show the borders around the icons of the objects, which you inserted into the Frame, select this. This way you can see the full Size of the icon. The size of the border depends on the size of the icon.
.topic 0x884111e7
To show objects of type Comment, which you inserted into your simulation model to provide additional information, select this.
.topic 0x884111d7
To automatically connect adjacent objects and Frames with Connectors, when you insert them, select this. When you connect Frames, the positions of exit and entrance Interface objects have to be close to each other. When you connect objects, the positions of the exits and the entrances of the objects have to be close to each other.

SimTalk:
connectAutomatically
.topic 0x88401554
Select on which side of the object the program places the starting point or the end point of Connectors: Fixed side places the starting point of the Connector at the exit of the object and the end point at its entrance. Angle-dependent takes the angle between the objects into account when determining the starting point or the end point of the Connector.
.topic 0x8841156a
To be able to select an object that moves under the transparent area of the icon of an object in front of it, select this.
.topic 0x884111c8
Enter the distance between the individual grid points from each other on the X-axis, i.e., the horizontal axis of the Frame. The grid points are the points at which the imaginary grid lines intersect.
.topic 0x884111cb
Enter the distance between the individual grid points from each other on the Y-axis, i.e., the vertical axis of the Frame. The grid points are the points at which the imaginary grid lines intersect.
.topic 0x884211de
Enter the number of methods that may be called by other methods to prevent the program from running out of memory. When Plant Simulation exceeds the maximum depth of calls, the simulation stops and the Debugger opens. Increase the number of the maximum depth of calls and continue or correct programming errors contained in the code, if any. To continue, hold down the Ctrl key and double-click the selected line containing the error in the Debugger.

SimTalk:
setMaxDepthOfCalls
.topic 0x884211dc
Enter the maximum number of call chains. During the reset and init phases of your simulation model, the EventController creates a list of all method calls to be executed, the call chain. When the Maximum number of call chains reaches this value, the simulation stops and Plant Simulation shows an error message. Then you can increase the maximum number of call chains and continue or you can correct the faulty source code. To do so, hold down the Ctrl key and double-click the selected line containing the error in the Debugger.

SimTalk:
setMaxNumberOfCallChains
.topic 0x884211db
Enter the maximum number of suspended methods. The number of methods suspended by waituntil and stopuntil statements and by wait statements is limited. When Plant Simulation reaches the number you set, it will not suspend any additional methods and displays an error message. You can then either increase the Maximum number of suspended methods by entering a greater number into this text box, and continue your simulation run or stop the simulation and fix the modeling error. To do so, hold down the Ctrl key and double-click the selected line containing the error in the Debugger.

SimTalk: setMaxSuspendedMethods
.topic 0x884211e2
Enter the Maximum number of samples, to prevent Plant Simulation from spending an excessive amount of time for die rolls, which is caused by an unfortunate selection of the interval bounds.
You can enter a number between 1 and 32000. Plant Simulation ignores values outside of this range without issuing a warning message and keeps the previous value. The greater the value you enter, the later you recognize if the bounds are too close together.
For a normal distribution it may, for instance, happen that Plant Simulation rolls extremely large values. When the bounds are too close together, this may result almost exclusively in outliers. Then Plant Simulation has to create a large number of random numbers consecutively before a valid value is available. This can take up a lot of time.

SimTalk:
setMaxNumberOfSamples
.topic 0x884211e8
Enter the value for Epsilon. The program uses this value in about equal comparisons with the == operator in SimTalk as the tolerance value for which it considers values to be equal or not equal. It considers two values to be about equal, when the difference between the two values is less than the value for epsilon. It considers two values to not be about equal, when the difference between the two values is greater than the value for epsilon.

SimTalk:
setEpsilon, getEpsilon
.topic 0x884211e3
Enter how often per second the program refreshes the graphics in your simulation model. You can enter a number between 1 and 100. Depending on your model a lower number may lead to a higher simulation speed. A higher number results in a smooth animation, which may decrease the simulation speed though.

SimTalk:
setAnimationRefreshRate
.topic 0x852c0a41
Select how often Plant Simulation refreshes the values of the Display Panels in your simulation model. You can select a fraction of the frame rate. Plant Simulation shows to how many frames per second the fraction corresponds.
.topic 0x88401197
Select the unit for the mass. Plant Simulation uses kilograms (kg) as the unit within methods. When you change the unit while modeling, it converts all values, which you already entered into objects, to the new unit.

SimTalk:
getUnit
.topic 0x883f1198
Enter or select the unit for the currency. When you change the currency unit while modeling, Plant Simulation only changes to the new currency symbol, but does not convert the actual values you entered originally!

SimTalk:
getUnit
.topic 0x883f1199
Select the unit for the speed. When you assign a speed in a method, Plant Simulation uses meters per second (m/s) as unit. When you change the unit while modeling, it converts all values, which you already entered into objects, to the new unit.

SimTalk:
getUnit
.topic 0x883f119a
Select the unit for the acceleration. The acceleration only applies to the length-oriented object Conveyor and to the Transporter. SimTalk: getUnit
.topic 0x883f119b
Select the unit for the length. Plant Simulation uses meters (m) as unit within methods. When you change the unit while modeling, it converts all values, which you already entered into objects, to the new unit! This may cause rounding errors.

SimTalk:
getUnit
.topic 0x883f119d
Enter your own length unit (LU), as any given multiple of any of the other length units, such as 1 LU = 0.3141 km.
.topic 0x883f119c
Select the unit of your own length unit setting.

.topic 0x883f11b7
You can change the display of the time scale to meet your specific modeling needs. You can enter a number between 0 and 86400 into the text box time scale 1/ (divided by). You can enter an integer greater than 1 into the text boxes next to transfer if.

.topic 0x883f11b3
If you want to use the standard time format, 24 hours to the day, 60 minutes to the hour, 60 seconds to the minute, you can use the default setting time scale 1/1.0 transfer if 24:60:60.

.topic 0x883f11b5
If you want to simulate a longer period of time and want to display the time in the format years:months:days:hours, enter time scale 1/3600 transfer if 12:30:24, as an hour has 3600 seconds, a year has 12 months, a month has 30 days, and a day has 24 hours.

.topic 0x883f11b6
If you want to divide a minute into 100 subunits instead of into 60 seconds, enter time scale 1/0.6 transfer if 24:60:100. The time value is first divided by 0.6 to take the division into 100 subunits into account and then subdivided. 100 subunits then result in 1 minute.

.topic 0x883f11b4
To use daylight saving time during the months March to October/November in your simulation models, select this. In the European Union, daylight saving time begins at 02:00 o’clock in the morning GMT (Greenwich Mean Time) on the last Sunday in March. It ends at 03:00 o’clock in the morning on the last Sunday in October. In the EU, all time zones change at the same hour. For most of the United States daylight saving time begins at 02:00 o’clock in the morning on the second Sunday of March. It ends at 02:00 o’clock in the morning on the first Sunday of November.
.topic 0x883f11a4
Enter the month when daylight saving time starts. You can enter a number between 1 and 12. Within most of the U.S. and for the entire EU enter 3 for March.

SimTalk:
setDaylightSavingTime
.topic 0x883f11a7
Enter the week when daylight saving time starts. For the default setting -1 daylight saving time starts on the last Sunday of the month you entered under Month Start. Enter a number between 1 and 4. Week 1 is the first week including the Day Start you set, week 4 is the last week of the month.

SimTalk:
setDaylightSavingTime
.topic 0x883f11a8
Enter the day when daylight saving time starts. For the U.S. and the EU, enter 0 for Sunday. 0 stands for Sunday, 1 for Monday, 2 for Tuesday, 3 for Wednesday, 4 for Thursday, 5 for Friday, and 6 for Saturday.

SimTalk:
setDaylightSavingTime
.topic 0x883f11a9
Enter the hour when daylight saving time starts. Enter a number between 0 and 23. For the EU, enter 2 for 02:00 o’clock in the morning.

SimTalk:
setDaylightSavingTime
.topic 0x883f11aa
Enter the month when daylight saving time ends. You can enter a number between 1 and 12. Within most of the U.S. enter 11 for November and within the EU enter 10 for October.

SimTalk:
setDaylightSavingTime
.topic 0x883f11ab
Enter the week when daylight saving time ends. For the default setting -1 daylight saving time ends on the last Sunday of the month you entered under Month End. Enter a number between 1 and 4. Week 1 is the first week including the Day End you set, week 4 is the last week of the month.

SimTalk:
setDaylightSavingTime
.topic 0x883f11ac
Enter the day when daylight saving time ends. For the U.S. and the EU, enter 0 for Sunday. 0 stands for Sunday, 1 for Monday, 2 for Tuesday, 3 for Wednesday, 4 for Thursday, 5 for Friday, and 6 for Saturday.

SimTalk:
setDaylightSavingTime
.topic 0x883f11ad
Enter the hour when daylight saving time ends. For the EU, enter 3 for 03:00 o’clock in the morning.

SimTalk:
setDaylightSavingTime

.topic 0x857a0c57
To show additional information and internal program messages, such as potential problems, select this. When you start the program with the command line parameter -NoWarning, it does not write any of the above to the Console.

SimTalk:
setConsoleFilter

.topic 0x857a0845
To open a dialog prompting you to confirm, when you delete objects or user-defined attributes in your model with the Delete key or the menu command Delete on the context menu, select this. It is especially useful to deactivate this feature when you are cleaning up a large model.
.topic 0x857a07af
To make dialogs, which are open in the foreground, transparent, select this. Dialogs and windows, which open behind them, will then be visible and it will thus be easier to select them. Then, enter a percentage for the Window coverage and for the Transparency level.
.topic 0x857a07b3
Enter the percentage of a window that has to be covered by a dialog located in front of it, so that the dialog, which covers the window, will become transparent.
.topic 0x857a07b0
Enter a value for the transparency level of the covering dialog. 0 percent stands for opaque, 100 percent for almost totally transparent.
.topic 0x857a0768
To show the contents of drop-down list boxes in the SimTalk language, select this. Then Plant Simulation shows the items in the drop-down list boxes of the dialogs in the language, which will be used when getting the attribute belonging to the drop-down list box with SimTalk commands. For German as the Model language, Plant Simulation shows the items in the drop-down list boxes in German. If you select any other of the available model languages, Plant Simulation shows the items in the drop-down list boxes in English. For Japanese as the model language, Plant Simulation reads the attributes belonging to the items in the drop-down list boxes as English strings. When you clear the check box, the program shows the contents of drop-down list boxes in the language of the graphical user interface of Plant Simulation.
.topic 0x857a0861
To show the name of the object as a tooltip, when you drag the mouse over the object in the window of the Frame, select this. Or create a user-defined attribute of type string for all objects and name it tooltip. The Frame shows the text you entered on a new line below the name, when you drag the mouse over the object. When you deactivate Show object names as tooltip, Plant Simulation only hides the name of the object, but continues showing the tooltip, which you entered.
.topic 0x852d0869
To indent the source code you enter according to the SimTalk syntax when starting a new line of code, select this. Then, Plant Simulation indents the lines of code within a SimTalk control structure according to the delimiting keywords. It indents the code between the keywords loop and end, making it easier to follow the logic used.
.topic 0x852d0868
To highlight the current line of your source code in the method editor, select this.
.topic 0x852d0866
To show the line number in front of the line of source code in the method editor, select this.
.topic 0x852d08cd
To show a tooltip with the name of the object or the attribute or the method, when the command Auto Complete reaches a point from which on the name is unique, select this. This way you can press Ctrl+Spacebar without having to type in too many letters.
.topic 0x852d0aa7
To show the data type of the parameters and of the return value of attributes and methods with the tooltip, when the command Auto Complete reaches a point from which on the name is unique, select this.
.topic 0x85e109f0
To show the outlining of a sequence of source code lines, such as control and loop structures, in the method editor as an expansible or a collapsible structure, select this.
.topic 0x852d084a
To find whole words only in your source code, select this. When you clear it, the program also finds parts of words.
.topic 0x852d084c
To match the case of the expression you entered and for which you are searching, select this. To find the expression regardless of lower or upper casing, clear it.
.topic 0x852d085b
To also find regular expressions, select this. This means that you can use wild cards in the term you want to find. You can use the period character . as a wild card for any character. If the editor searches for a.b, it will find all strings consisting of a sequence of the character a, any character, and the character b.
.topic 0x852d085e
To continue searching at the beginning of the source code, after the search reaches the end of the text, select this.
.topic 0x852d086a
Enter the tab size in character widths of a non-proportional font. This is the number of blank spaces with which the method editor indents source code you enter. The commands Edit > Decrease Line Indent and Increase Indent in the Method use this setting when moving your source code by one tab size.
.topic 0x852d0be5
Select the font size which the method editor displays the source code, which you enter into a Method in the Consolas font.
.topic 0x852d0be1
To apply bold face to the selected font of the source code of the methods, select this.
.topic 0x852d0863
Click this and navigate to the folder in which you store the templates for the source code of your methods. You can then select one of the templates in the Method object under Template > Select Template and thus load it into the Method you are programming.
The text box shows the path to the folder in which you store the templates for the source code of your methods. Or accept the default folder Templates.
.topic 0x8dea0d08
Select the type of license which you purchased and which you are using. The license type determines which features of the program you can or cannot use. You can override the setting you select here with the start option /L.
.topic 0x8dea0deb
Select this to acquire your license from a license file instead of from a license server.
.topic 0x8dea0d05
Enter the path to and the name of your license file or click the button and navigate to the folder in which you stored your license file (license.lic) and select it in the dialog, which opens.
.topic 0x8dea0dec
Select this to acquire your license from the license server whose name you enter into the text box to the right.
.topic 0x8dea0ded
Enter the name of this license server. If you use a license server triad, you have to enter the name of the first of three redundant license servers.
.topic 0x8dea0dee
Enter the port number for contacting this license server. For our standard environment the port number is 27006. If you Use a license server triad, enter the port number for contacting this license server. In this case two out of the three redundant license servers always have to be reachable, meaning that one server can fail.
.topic 0x8dea0df0
Select this to acquire your license from the license server whose name you enter into the text box to the right. Enter the name of this license server. If you Use a license server triad, you have to enter the name of the second of three redundant license servers.
.topic 0x8dea0df1
Enter the port number for contacting this license server. If you Use a license server triad, enter the port number for contacting this license server. In this case two out of the three redundant license servers always have to be reachable, meaning that one server can fail.
.topic 0x8dea0df2
Select this to acquire your license from the license server whose name you enter into the text box to the right.
.topic 0x8dea0df3
Enter the name of this license server. If you Use a license server triad, you have to enter the name of the third of three redundant license servers. In this case two out of the three redundant license servers always have to be reachable, meaning that one server can fail.
.topic 0x8dea0df4
Enter the port number for contacting this license server. If you Use a license server triad, enter the port number for contacting this license server.
.topic 0x8dea0e15
Select this to acquire your license from any one of three redundant license servers. This only works, if you are running the license server as a license server triad. Note that two out of the three redundant license servers always have to be reachable, meaning that one server can fail.
.topic 0x8dea0e2d
To query the host IDs of your computer, click this. Plant Simulation then shows the host IDs of your computer in the text box to the right.
.topic 0x8dea0e2e
After you clicked Query Host IDs, Plant Simulation shows the host IDs of your computer here. You can use any one of these host IDs for retrieving your license. You can copy the information from the text box and paste it into the respective field on the website.
.topic 0x8dea0e38
To open help about Licensing Plant Simulation, click this.
.topic 0x85a90dc1
To enter the width and the height of the icon in pixels, select pixels. Plant Simulation automatically converts the pixel values you enter into length units and vice versa.
.topic 0x85a90a6a
Enter the width of the icon in pixels. The size is limited to 9999 x 9999 pixels. Plant Simulation automatically converts the pixel values you enter into length units and vice versa.

SimTalk:
getIconSize
.topic 0x85a90a6b
Enter the height of the icon in pixels. The size is limited to 9999 x 9999 pixels. Plant Simulation automatically converts the pixel values you enter into length units and vice versa.

SimTalk:
getIconSize
.topic 0x85a90dc2
To enter the width and height of the icon in the length units, which you selected under Tools > Model settings/Preferences > Units > Length, select length units. Plant Simulation automatically converts the length units you enter into pixel values and vice versa.
.topic 0x85a90a6d
Enter the width of the icon in length units, which you selected under Tools > Model settings/Preferences > Units > Length. Plant Simulation automatically converts the length units you enter into pixel values and vice versa.

SimTalk:
getIconSize
.topic 0x85a90a6e
Enter the height of the icon in length units, which you selected under Tools > Model settings/Preferences > Units > Length. Plant Simulation automatically converts the length units you enter into pixel values and vice versa.

SimTalk:
setIconSize, getIconSize
.topic 0x85a90dc5
Enter the scaling factor for scaling the size of the icon. The Scaling Factor is the length of one pixel in one length unit. By setting the correct scaling factor, you can place 2D objects in the Frame according to their real coordinates.
.topic 0x8916156f
Enter how often Plant Simulation draws the contents of the object, while a part is located on it. If several MUs with differing speeds are located on the object, the first moving MU determines the time intervals between the animation events.

SimTalk:
NumAnimationEvents
.topic 0x86170c9b
To activate the display panel, select this. When you activate it, Plant Simulation shows it on the same layer as the icon of the object in the Frame. Thus the display panel overlaps the same objects as the icon does and is overlapped by the objects which overlap the icon. To deactivate it, clear the check box.

SimTalk:
DisplayPanel.Active
.topic 0x86170c9e
Enter the x-coordinate of the left top corner of the display panel in the Frame or click the spin buttons. You can enter a number between -5000 and +5000. This position is relative to the coordinates of the reference point of the object.

SimTalk:
DisplayPanel.X
.topic 0x861708e9
To move the left top corner of the display panel in the Frame to the right on the X-axis, click the right spin button. Click the left spin button to move the left top corner of the display panel in the Frame to the left on the X-axis.
.topic 0x86170c9c
The toggle button activates or deactivates inheritance.

A green button means that inheritance is active. Then, the object uses the values for the X-position and for the Y-position of the origin object from which you derived it. When you modify the values of the origin object, this also changes the values of the derived object.

An orange button with a minus means that inheritance is not active. Values you enter only apply to the selected object.
.topic 0x86170c9f
Enter the y-coordinate of the left top corner of the display panel in the Frame or click the spin buttons. You can enter a number between -5000 and +5000. This position is relative to the coordinates of the reference point of the object.

SimTalk:
DisplayPanel.Y
.topic 0x861708ea
To move the left top corner of the display panel in the Frame up on the Y-axis, click the up spin button. Click the down spin button to move the left top corner of the display panel in the Frame down on the Y-axis.
.topic 0x86170ca0
Enter the width of the display panel in the Frame or click the spin buttons. You can enter a width between 1 and 255 pixels.

SimTalk:
DisplayPanel.Width
.topic 0x861708ef
Click the right spin button to increase width of the display panel in the Frame. Click the left spin button to decrease the width of the display panel in the Frame.
.topic 0x86170c9d
The toggle button activates or deactivates inheritance.

A green button means that inheritance is active. Then, the object uses the values for the Width and for the Height of the origin object from which you derived it. When you modify the values of the origin object, this also changes the values of the derived object.

An orange button with a minus means that inheritance is not active. Values you enter only apply to the selected object.
.topic 0x86170ca1
Enter the height of the display panel in the Frame or click the spin buttons. You can enter a height between 1 and 255 pixels.

SimTalk:
DisplayPanel.Height
.topic 0x861708f0
Click the up spin button to increase height of the display panel in the Frame. Click the down spin button to decrease the height of the display panel in the Frame.
.topic 0x86170ca2
To select the color of the border around the edge of the display panel in the Frame, click this. To not display the border color, you can make it transparent by entering the RGB values 0, 128, 128.

SimTalk:
DisplayPanel.BorderColor
.topic 0x86170ca3
The toggle button activates or deactivates inheritance.

A green button means that inheritance is active. Then, the object uses the border color of the origin object from which you derived it. Changing the border color of the origin object also changes the border color of the derived object.

An orange button with a minus means that inheritance is not active. When you change the border color, this only applies to the selected object.
.topic 0x86170ca4
To select the background of the display panel in the Frame, click this. To not display the background color, you can make it transparent by entering the RGB values 0, 128, 128.

SimTalk:
DisplayPanel.BackgroundColor
.topic 0x86170ca5
The toggle button activates or deactivates inheritance.

A green button means that inheritance is active. Then, the object uses the background color of the origin object from which you derived it. Changing the background color of the origin object also modifies the background color of the child object.

An orange button with a minus means that inheritance is not active. When you change the background color, this only applies to the selected object.
.topic 0x86170ca7
To add a new item to the display panel, click this. Then, define the properties of the individual display panel items in the dialog Display Panel Elements, which the display panel shows in the Frame.
.topic 0x8930163b
Enter or select the value which the display panel shows. The value can be any formula which the program evaluates and shows in regular intervals. Within the formula relative paths are resolved relative to the object for which you define the display panel. You can use the tilde (~) to access the Frame in which the object is located. You might enter numMU or ~.myBuffer.numMU. To display static text instead of the value of an attribute or a method, select the Type > Static Text and then enter the respective text.

SimTalk:
setValue
.topic 0x8930163c
Select the x-coordinate of the top left corner of the display panel item on the display panel. Or enter a number between 0 and 255.

SimTalk:
DisplayPanel.setElements, DisplayPanel.getElements
.topic 0x8930163d
Select the y-coordinate of the top left corner of the display panel item on the display panel. Or enter a number between 0 and 255.

SimTalk:
DisplayPanel.setElements, DisplayPanel.getElements
.topic 0x8930163e
Select how the display panel shows the Value. As static text, i.e., as an arbitrary sequence of characters that does not change as opposed to the value of an attribute/method. As text. As a bar if you want to display values of numeric data types. As an LED if you want to display boolean values.

SimTalk:
DisplayPanel.setElements, DisplayPanel.getElements
.topic 0x8930163f
Select where at the X-position of the display panel item on the display panel you want to align Static Text or Text. Left aligns the left border of the text with the position on the X-axis. Center aligns the center of the text with the position on the X-axis. Right aligns the right border of the text with the position on the X-axis.

SimTalk:
DisplayPanel.setElements, DisplayPanel.getElements
.topic 0x89301641
To select the color of the item, click this field.

SimTalk:
DisplayPanel.setElements, DisplayPanel.getElements
.topic 0x89301642
To make the item on the display panel transparent so that the Background color of the display panel shines through, select this. To not make it transparent, clear the check box. Then the background of the display panel is white. When you display bars non-transparent, the area exceeding the value to the Maximum value is shown in white.

SimTalk:
DisplayPanel.setElements, DisplayPanel.getElements
.topic 0x89301646
Enter the length of the bar on the display panel in pixels. The length refers to the Direction of the bar.

SimTalk:
DisplayPanel.setElements, DisplayPanel.getElements
.topic 0x89301648
Enter the height of the bar or the width of the LED on the display panel in pixels.

SimTalk:
DisplayPanel.setElements, DisplayPanel.getElements
.topic 0x8930164a
Select the direction of the bar on the display panel: Growing to the right of the starting point of the bar. Growing to the left of the starting point of the bar. Growing up from the starting point of the bar. Growing down from the starting point of the bar. The bar deflects in the direction up to the Length you enter.

SimTalk: DisplayPanel.setElements, DisplayPanel.getElements
.topic 0x8930164c
Enter the maximum value to which the bar deflects. The default value is 1.

SimTalk:
DisplayPanel.setElements, DisplayPanel.getElements
.topic 0x89301643
Select this to show values, which the setting Type > Text displays, as a percentage instead of just as a number.

SimTalk:
DisplayPanel.setElements, DisplayPanel.getElements
.topic 0x89301644
Select the number of decimal places for values, which the setting Type > Text displays.

SimTalk:
DisplayPanel.setElements, DisplayPanel.getElements
.topic 0x86170ca6
To edit the item of the display panel, which you selected in the Elements Table below, click this. Then, change its properties. Plant Simulation writes the changed values into the items table.
.topic 0x86170ca8
To delete the item from the display panel, which you selected in the Elements Table below, click this. Plant Simulation deletes this item from the items table.
.topic 0x86170ca9
The items table shows the items which you defined for the display panel. The Value can be any formula, which the program evaluates and shows in regular intervals. Within the formula relative paths are resolved relative to the object for which you define the display panel. You can use the tilde (~) to access the Frame in which the object is located. You might enter numMU or ~.myBuffer.numMU. To display static text instead of the value of an attribute or method, select the Type > Static Text and then enter the respective text. X is the X-position of the item. Y is the Y-position of the item. The type is the Display-Type of the item. To add a new item, click New. To edit an item in the table, double-click the respective row, or select it and click Edit above the table. To delete the selected item from the table, click Delete. To load the settings of a display panel, which you saved by clicking the button Save, click Load. To save the settings of a display panel, as a Plant Simulation object file (.obj), click Save. To view the defined items and all of their properties, click Open Table.
SimTalk:
DisplayPanel.setElements, DisplayPanel.getElements, DisplayPanel.setValue
.topic 0x86170caa
The toggle button activates or deactivates inheritance.

A green button means that inheritance is active. Then, the object uses the items of the origin object from which you derived it. Changing the items of the origin object also changes the items of the derived object.

An orange button with a minus means that inheritance is not active. When you change any items, this only applies to the selected object.
.topic 0x86170de1
To load the settings of a display panel, which you saved by clicking the button Save, click this. Navigate to the location of the object file in the dialog Open and select it.
.topic 0x86170e16
To save the settings of the display panel as a Plant Simulation object file (.obj), click this. Then, type in the file name of the object file into the dialog Save As and specify a location.
.topic 0x86170cab
To open the table that contains all items of the display panel, click this. The table shows the names of the items in the rows and all of their properties in the columns. Each defined display panel item provides some of these items: Its Value, its X-position, its Y-position, its Type, its Alignment, its Color, and if it is Transparent or not. For the Type > Bar you can set the Length, the Width, the Direction, and the Maximum value of the bar. For the Type > Text you can select the setting Display as percentage and enter the number of Decimal places.

SimTalk:
DisplayPanel.setElements, DisplayPanel.getElements, DisplayPanel.setValue
.topic 0x89061546
The toggle button activates or deactivates inheritance.

A green button means that inheritance is active. Then the object inherits, i.e., uses, the value from the parent object from which it was derived. When you modify the value of the parent object, the program also modifies the value of the child object.

An orange button with a minus means that inheritance is not active. Values you select or enter only apply to the selected object.
.topic 0x88f20fb5
Enter a name of your choice for the object or accept the name that the program assigns. To change the name, double-click and overtype it. You can enter any combination of letters, digits, and underscore (_) characters, for example MyStation, MyStation1, My_Station_1. The name of an object cannot start with a digit, i.e., you cannot enter 1Station.

SimTalk:
Name
.topic 0x88f20fb7
Enter a term of your choice as the label of the object. You can type in letters, numbers, blanks, and special characters. You can use the label to display objects with the same functionality with the same identifier in the Frame. The Name of the object, on the other hand, has to be unique! The program shows the label which you enter for the objects Report, Dialog, AttributeExplorer and Chart in the title bar of their display windows. If you do not enter a label, the title bar shows the name of the object. The same applies to a toolbar you add to the Toolbox. Select New > Toolbar, then select the toolbar in the structure, press F2 and enter a Label into the dialog Rename.

SimTalk:
Label
.topic 0x87ea103f
To fail the object, select this. From then on, the object will not receive any parts. Parts can exit the object though, when you program this in a Method. The program stops processing and set-up processes until the end of the failure, i.e., it adds the duration of the failure to these times. When you manually fail a station, it remains Failed while any of the failure profiles you defined is Active. It will change to not failed once the last failure (DisruptionEnd) of the last failure profile ends or when you clear the check box. Click OK or Apply to accept your changes.

SimTalk:
Failed
.topic 0x87ea1579
To pause the object while it is processing parts, select Paused. To not schedule it to work, select Unplanned. These are the times that are located outside of the Working hours of the shifts, controlled by the ShiftCalendar, which apply to your installation. To schedule it to work, select Planned. This is the processing time without counting the breaks during the shifts that apply to your installation. Then the object is paused or unplanned, it will not receive any MUs. MUs can exit the object, when you enter MU-path.move into a Method. The program stops processing and set-up processes until the end of the pause or of the unplanned time. During the planned time, the object receives and processes MUs.

SimTalk:
Pause, Paused, Unplanned
.topic 0x87ea0fb9
To close the entrance of the object, select this. The object will finish processing the MUs already located on it, but does not accept any other MUs. Processing starts again when you clear the check box. The first MU in its Forward Blocking List is going to be processed first.

SimTalk:
EntranceLocked
.topic 0x87ea0fc3
To close the exit of the object, select this. The program prevents MUs from being moved on to the successors in the material flow and enters them into the Exit Blocking List of this object. Once the exit is unlocked again, the object moves the first MU in the Exit Blocking List to its successor.

SimTalk:
ExitLocked
.topic 0x88fd0001
To accept the changes you made and to close the dialog window, click OK. When you did not change any settings, we recommend to not click OK, but to click Cancel to close the dialog window.

SimTalk:
closeDialog
.topic 0x88fd0002
To close the dialog window and to discard any changes you made, click Cancel.

SimTalk:
closeDialog
.topic 0x88f10fa2
To apply the changes you made and to leave the dialog window open, click Apply.
.topic 0x84c70623
The processing time is the time during which the MU is located on the object to be processed. It denotes the interval between the time at which the material flow object was set-up for processing this part type and the time at which the object moves the processed part on to its successor. Select a distribution, and enter the values, which that distribution requires, into the text box. The program shows these values along the top border of the tab. Or enter a constant time (Const). Or select to process the MU depending on its type (List(Type)). For the ParallelStation you can select to process the MU depending on the station on which it is located (List(Place)). For the Buffer and the PlaceBuffer you can only enter a constant processing time.

SimTalk:
ProcTime
.topic 0x84c70625
The set-up time is the time it takes to set the object up for processing a different type of MU. An identical name denotes that parts are of the same type. Select a distribution, and enter the values, which that distribution requires, into the text box. The program shows these values along the top border of the tab. Or enter a constant time (Const). Or select to process the MU depending on its type (List(Type)). Or select the Matrix(Type) distribution. When you select the Formula distribution, you can enter a numeric expression or the name of a Method. You can use the anonymous identifier @ to access the MU for which the set-up time applies.

SimTalk:
SetupTime, RemainingSetUpTime
.topic 0x84c70624
The recovery time is the time which is required to set a station into a defined state before it can start processing the next part. The recovery time is useful to model materials handling equipment, such as a robot, which requires a certain time to insert work pieces into or remove them from processing stations. You can use the attribute entranceOpen to check if the entrance is currently open. You can use the attribute timeUntilEntranceOpen to query the time at which the entrance will be open again. Select a distribution, and enter the values, which that distribution requires, into the text box. The program shows these values along the top border of the tab. Or enter a constant time (Const). When you select the Formula distribution, you can enter a numeric expression or the name of a Method. You can use the anonymous identifier @ to access the MU for which the recovery time applies.

SimTalk:
RecoveryTime
.topic 0x84c70690
Select when the recovery time of the station starts: When the part enters the station. When processing of the part is finished: The recovery time elapses after the part is processed, no matter if the part is still located on the station or has left it. When the part exits the station: The recovery time elapses after the part is processed and has left the station.

SimTalk:
RecoveryTimeMode
.topic 0x84c70626
The cycle time is the time during which the second gate at the entrance of a material flow object opens and closes cyclically, regardless of MUs entering the object. The cycle time is useful to model chain conveyors with a fixed chain interval that only transport materials when a free hook is available. You can use the attribute entranceOpen to check if the entrance is currently open. You can use the attribute timeUntilEntranceOpen to query the time at which the entrance will be open again. Select a distribution, and enter the values, which that distribution requires, into the text box. The program shows these values along the top border of the tab. Or enter a constant time (Const). When you select the Formula distribution, you can enter a numeric expression or the name of a Method. You can use the anonymous identifier @ to access the MU for which the cycle time applies.

SimTalk:
CycleTime
.topic 0x84c80644
To automatically set the object up, select this. Then the material flow object triggers the set-up process as soon as the respective MU class intends to move onto it. To define the set-up process in a Method, clear the check box.

SimTalk:
AutomaticSetUp
.topic 0x84c80645
To only start setting-up the material flow object for the next class of MU when it is Empty, select this. MUs of the type for which the object is setting-up can only enter the object, after the set-up process is finished. To allow MUs to enter the object although it has not been set-up for their type yet, clear the check box. Their set-up time begins when all set-up processes which you specified are finished. MUs located on the object will be processed with the settings for the MU class for which the object was set-up before.

SimTalk:
SetUpOnlyWhenEmpty
.topic 0x84c80850
To set the material flow object up after a certain number of parts has been processed, select this. Then, enter the number of parts after which you want the object to set up into the text box. Select Before Next to set the object up after the n-plus-first part wants to move onto the station. Select After Last Part to set the object up immediately after the n-th part was processed.

SimTalk:
SetupAfterNumParts
.topic 0x84c80851
Enter the number of parts after which you want the object to set up. The object also sets up and starts counting anew, starting from 1, when the part type changes before the number you enter is reached. For this reason it may happen that the object does not reach the number of parts of a certain type for which it is to set up.

SimTalk:
SetupAfterNumParts
.topic 0x84c806e6
Select Before Next Part to set the object up immediately after the n-th part was processed. Select After Last Part to set the object up after the n-plus-first part wants to move onto the station.

SimTalk:
SetupAfterNPartsMode
.topic 0x84c8085d
Select if the object has to be set up according to:

The MU Name, meaning that the object sets up, when the name of the part changes.

A user-defined attribute, meaning that the object sets up, when the value of this user-defined attribute of the part changes. You have to enter the name of the attribute into the text box. This user-defined attribute has to be of type string.

Off: Deactivates setting the object up after changing the type to another MU. The station will only be set-up after the number of parts that you selected.

SimTalk:
SetupAttrName,
SetupForType
.topic 0x84c808e1
Enter the name of a user-defined attribute of the part. The material flow object sets up, when a part, whose user-defined attribute has a different value, moves onto the station. The MUs might have a user-defined attribute named Color. Let us assume that the station is set up for “red”. Now, a part with the user-defined attribute value “blue” moves onto the station. For this reason it sets up for “blue”. To change setting-up to MU Name via information flow, assign an empty string ("").

SimTalk:
SetupAttrName
.topic 0x87df0fbb
To activate failures of the object in general, select this. To deactivate them, clear the check box. The failure of the object is only active, when you activate this and the check box Active of the corresponding failure profile!

SimTalk:
FailureActive
.topic 0x87df36f9
To define a new failure profile and to open a dialog, click New. Enter the Name of the failure profile and select if it is Failed and if it is Active or not. You can define the Start time and the Stop time, the Interval and the Duration of this failure profile. Or select the time which the Failure relates to. When you select the check box Availability, Plant Simulation grays the dialog items Interval and Duration out, and you can enter the Availability and the MTTR instead. Or select if the failure relates to The simulation time, The operating time or The processing time.

SimTalk: Failures.getTable, Failures.setTable, Failures.createFailure, Failures.deleteFailure, Failures.getFailure
.topic 0xaf1a36f4
Enter the name of this failure profile, for example the reason why the machine fails.

SimTalk:
Failures.NameOfFailureProfile.Name
.topic 0xaf1a36f5
To activate this failure profile, select this. To deactivate it, clear the check box. The failure of the object is only active when you activate this, i.e., the failure profile itself, and the check box Active on the tab Failures!

SimTalk:
Failures.NameOfFailureProfile.Active
.topic 0x87df0fda
Select a distribution for the time at which the first failure of this failure profile will take place. Enter the values, which that distribution requires, into the text box. Plant Simulation shows these values above the list of distributions which you can select. Or enter a Formula in which you can access the anonymous identifier @.

SimTalk:
Failures.NameOfFailureProfile.Start
.topic 0x87df0fdb
Select a distribution for the time at which the last failure of this failure profile will take place. Enter the values, which that distribution requires, into the text box. Plant Simulation shows these values above the list of distributions which you can select. Or enter a Formula in which you can access the anonymous identifier @. When the object is still failed when the program reaches the Stop time, the failure will last for the Duration you selected.

SimTalk:
Failures.NameOfFailureProfile.Stop
.topic 0x87df0fdc
Select a distribution for the time between the end of the last failure and the start of the next one of this failure profile. Enter the values, which that distribution requires, into the text box. Plant Simulation shows these values above the list of distributions which you can select. Or enter a Formula in which you can access the anonymous identifier @. The value 0 for the Interval and a value greater than 0 for the Duration will produce a single failure.

SimTalk:
Failures.NameOfFailureProfile.Interval
.topic 0x87df0fdd
Select a distribution for the duration of the failure of this failure profile. Enter the values, which that distribution requires, into the text box. Plant Simulation shows these values above the list of distributions which you can select. Or enter a Formula in which you can access the anonymous identifier @. After the time you entered for the failure has elapsed, the program returns the object to the not failed state. When you enter 0, no failures at all will take place.

SimTalk:
Failures.NameOfFailureProfile.Duration
.topic 0x87df1545
To activate the text boxes Availability and MTTR, select this. Then, enter the availability and the mean time to repair of the station instead of the Duration and the Interval of the failure.

SimTalk:
Failures.NameOfFailureProfile.AvailabilityOn
.topic 0x87df154e
Enter the availability of the machine. This is a value between 0 and 100 percent. The availability designates the proportion of time during which a machine is in an operable state. Availability is based on a combination of MTBF and MTTR.

SimTalk:
Failures.NameOfFailureProfile.Availability
.topic 0x87df154f
Enter the Mean Time To Repair (MTTR) of the machine. Optionally you can also enter the lower bound and upper bound for the Erlang-distribution. Plant Simulation then calculates the Erlang-distribution and the negative exponential distribution from these values. When you enter the lower bound and the upper bound for the Erlang-distribution, Plant Simulation calculates the MTTR.

SimTalk:
Failures.NameOfFailureProfile.MTTR
.topic 0x87df0fde
Select the time to which the failures of this failure profile relate: The simulation time consumes the time you entered for the failure Interval, regardless of the state the object is in. The Simulation Time is the time between the beginning of the simulation run (Reset, Start/Stop) and its end. The operating time consumes the time you entered for the failure interval only when the object is operational. The Operating Time will be interrupted by pauses and failures. The processing time consumes the time you entered for the failure interval while the object is processing the part. For point-oriented objects the Processing Time is the time during which a part is located on a material flow object and is being processed by it. For conveying objects, such as the Conveyor, the Processing Time is the time during which its speed is not 0. It can also be working, when the conveyor is moving and does not transport a part.

SimTalk:
Failures.NameOfFailureProfile.Mode
.topic 0x87df36fa
To edit the failure, which you selected in the List of Failure Profiles, click Edit.
.topic 0x87df36fb
To delete the failure, which you selected in the List of Failure Profiles, click Delete.
.topic 0x84ca064e
Click this and select a Method object into which you entered the source code of the entrance control. Once the part enters a point-oriented object, such as the Station. For this setting, the default, the check box is cleared. To activate the entrance control of the point-oriented objects before the standard actions are started, when a part enters the object, select Before actions. Standard actions are starting the processing time or the set-up time, requesting services through the importer, or changing the assembly table of the AssemblyStation. When the Front or the Rear of the part enters a length-oriented object, such as the Conveyor, or Track or a TwoLaneTrack. Remember that a part, for which you entered a length, does not enter these objects all at once, but continually. Depending on the length and the speed of the part, there will a delay between the time the front and the time the rear of the part enters the object.

SimTalk:
EntranceCtrl
.topic 0x84ca0634
Select Front to activate the control as soon as the front of the part enters, i.e., is located on the object. This means that changing the processing time in the entrance control does not affect the part that already entered the object. To set the processing time depending on the part that arrives, define the processing time in a formula.

SimTalk:
EntranceCtrlFront
.topic 0x84ca0636
Select Rear to activate the control as soon as the rear of the part enters the object.

SimTalk:
EntranceCtrlRear
.topic 0x84ca0998
To activate the entrance control of the point-oriented objects before the standard actions are started, when a part enters the object, select Before actions. Standard actions are starting the processing time or the set-up time, requesting services through the importer, or changing the assembly table of the AssemblyStation. Then, you can change the processing time in the entrance control, which then affects processing of the part that is already located on the object. To activate the entrance control after the standard action has been executed, clear the check box.

SimTalk:
EntranceCtrlBeforeActions
.topic 0x84ca064f
Click this and select a Method object into which you entered the source code of the exit control. Plant Simulation activates the exit control, when a part exits the object. The check boxes Front and Rear set when the part triggers the Methods. When you entered an exit control, and the control is Front-activated, the control has to transfer the part, for example with the method move.

SimTalk:
ExitCtrl
.topic 0x84ca0631
Select Front to activate the control as soon as the part is ready to exit the object. The exit control then has to move the part to another object, as the built-in behavior of the material flow object, i.e., moving the part on to the successors along the Connectors, has been overridden by the exit control.

SimTalk:
ExitCtrlFront
.topic 0x84ca0632
Select Rear to activate the control as soon as the rear of the part has completely exited the object. This control does not override the built-in behavior of how MUs move to the successor of the current object.

SimTalk:
ExitCtrlRear
.topic 0x84ca0653
Click this and select a Method object into which you entered the source code of the backward entrance control. Plant Simulation activates the backward entrance control when the MU enters the length-oriented objects Track, TwoLaneTrack or Conveyor via their exit and/or when it moves towards their entrance after entering. The check boxes Front and Rear set, when the MU triggers the Methods.

SimTalk:
BwEntranceCtrl
.topic 0x84ca063a
Select Rear to activate the control as soon as the rear of the MU enters the object.

SimTalk:
BwEntranceCtrlRear
.topic 0x84ca0638
Select Front to activate the control as soon as the front of the MU enters the object.

SimTalk:
BwEntranceCtrlFront
.topic 0x84ca0651
Click this and select a Method object into which you entered the source code of the backward exit control. Plant Simulation activates the backward exit control when the MU exits the length-oriented objects Track, TwoLaneTrack or Conveyor the objects via their entrance and/or when it moves towards their entrance when exiting. The check boxes Front and Rear set, when the MU triggers the Methods.

SimTalk:
BwExitCtrl
.topic 0x84ca0640
Select Rear to activate the control as soon as the back of the MU exits the object at its entrance.

SimTalk:
BwExitCtrlRear
.topic 0x84ca063d
Select Front to activate the control as soon as the front of the MU exits the object at its entrance. The exit control then has to move the part to another object, as the built-in behavior of the material flow object, i.e., moving the part on to the successors along the Connectors, has been overridden by the exit control.

SimTalk:
BwExitCtrlFront

.topic 0x84ca0eff
Select this to call the exit control only once when the part intends to exit the object. Clear the check box to call the exit control again when the part is unblocked.

SimTalk: ExitCtrlOnce
.topic 0x84ca076b
Click this and select a Method object into which you entered the source code of the set-up control. Plant Simulation activates it, whenever a set-up process starts or ends. The control will also be called, when set up is interrupted.

SimTalk:
SetupCtrl
.topic 0x84ca0c33
Click this and select a Method object into which you entered the source code of the pull control. Plant Simulation activates it, whenever the object is ready to accept a new part or when it is ready, when a new part is Waiting at its entrance. In the pull control you can determine which of the MUs, which intend to move onto the object, the object will actually accept. For this you have to get the forward blocking list of the object with the method fwBlockList and unblock a part in that list with the method unblock. Let us assume that red parts are especially important and thus have to priority for being processed. Then you can always pull red parts first from the predecessors and only then pull parts in other colors.

SimTalk:
PullCtrl
.topic 0x84ca0b2b
Click this and select the ShiftCalendar. This ShiftCalendar object contains the data of the shifts in your installation and controls during which shifts the object works. Or you can select the ShiftCalendar in a Frame, drag it to the text box and drop it there.

SimTalk:
ShiftCalendarObject
.topic 0x84ca06f1
To open the Sensor List, click Sensors. Instead, double-click the name of a sensor in the open sensor list. A Sensor is defined by its Sensor-ID, its Position, its length unit, and the Method object triggering it. You can set the position in relation to the length of the object or as an absolute length.
.topic 0x8830110f
The list shows all sensors which you already defined. You can edit or delete existing sensors and add new sensors. The list shows the ID, the position on the length-oriented object, if it is front- or rear-triggered, the path of the control that is executed, and if the sensor was created in the present instance of the object.
.topic 0x8830110b
To create a new sensor, click New.

SimTalk:
createSensor
.topic 0x8830110c
To edit the sensor, which you selected in the list, click Edit.
.topic 0x8830110d
To delete the sensor, which you selected in the list, click Delete.

SimTalk:
deleteSensor
.topic 0xaf181115
Select the type of the position, Relative or Length, from the drop-down list. Then, enter the position of the sensor. When you select Length, you can enter a value between 0 and the length of the object. When you select Relative, you can enter a value between 0 and 1, i.e., between 0 percent and 100 percent. The program then shows 0..1 to the right of the text box. The program uses the length unit you selected under Tools > Model Settings/Preferences > Units > Length. When you enter an invalid value, the program changes the color of the text box to red.

SimTalk:
sensorID(ID).PositionType
.topic 0xaf1815db
Enter how far along the length of the object, starting from the beginning of the Conveyor, the Track, the Turntable or on lane A of the TwoLaneTrack, the sensor is located.

SimTalk:
A.sensorID(ID).Position
.topic 0xaf1815de
Enter how far along the length of lane B of the TwoLaneTrack the sensor is located. When you select Lanes > Both Lanes, the program calculates the position of the sensor on lane B according to the position, which you entered for lane A.

SimTalk:
B.sensorID(ID).Position
.topic 0xaf1815dc
To make the Front of the part activate the sensor on the Conveyor, the Track or on lane A of the TwoLaneTrack, select this. Or select Front and Rear. Then both the front and the rear of the part activate the Method.

SimTalk:
A.sensorID(ID).Front
.topic 0xaf1815df
To make the Front of the part activate the sensor/Method on lane B, select this. Or select Front and Rear. Then both the front and the rear of the part activate the Method.

SimTalk:
B.sensorID(ID).Front
.topic 0x891b10ad
To activate light barrier mode when the Conveyor or the Transporter move backwards, select this. When you select Front, the front of the MU/Transporter in the direction of motion triggers the sensor just like a part does that breaks a light barrier on a conveyor. The light barrier sensor is also triggered when you drop a part on the sensor or when you remove it from it. The sensors on the Tab Load Bay of the Transporter only apply to the loading space. In this case light barrier mode applies to the parts that move on the loading space.

SimTalk:
sensorID(ID).Lightbarriermode
.topic 0xaf1815dd
To make the Rear of the part activate the sensor on lane A, select this. Or select Front and Rear. Then both the front and the rear of the part activate the Method.

SimTalk:
A.sensorID(ID).Rear
.topic 0xaf1815e0
To make the Rear of the part activate the sensor/Method on lane B, select this. Or select Front and Rear. Then both the front and the rear of the part activate the Method.

SimTalk:
B.sensorID(ID).Rear
.topic 0xaf18104f
Select on which lane of the TwoLaneTrack you want to insert the sensor. On both lanes, or on lane A only, or on lane B only.

SimTalk:
sensorID(ID).Lanes
.topic 0xaf181114
When you create a sensor for a Track, you can select, when a Transporter passing over it triggers the sensor: Always, independent of the destination of the Transporter. Or Only when the Transporter has the same destination as the one, which you entered into the sensor. The Transporter’s Automatic routing feature also includes this destination object. When you assign a Destination to the Transporter while automatic routing is active, it drives to the sensor. There it activates the sensor control and a destination control which you defined for the Transporter. The same destination object can be defined in several sensors. It may also be directly reached via different Tracks. Even when a direct route leads to the destination object, the Transporter drives to the nearest sensor, when this sensor can be reached on a shorter route than the destination object itself.

SimTalk:
sensorID(ID).Activate
.topic 0xaf181110
Enter the name of the destination object to which the Transporter drives.

SimTalk:
sensorID(ID).Destination
.topic 0xaf181111
Click this and select the Method object, which the sensor calls. To open the dialog of the object, whose name you entered into the text box, click in the text box, and press the F2 key. As soon as the sensor calls this Method, it passes the Sensor-ID as an optional parameter. When the Method expects a parameter of data type integer, the sensor passes the Sensor-ID to the Method; if you do not enter an integer parameter, the Method will be called without a parameter. The second optional parameter of data type boolean shows the user if the front or the rear of the part triggers the control.

SimTalk:
sensorID(ID).Ctrl
.topic 0x88ea105a
Select the strategy from the drop-down list Strategy according to which the object moves the part on to one of its successor. As a rule you will use an exit strategy, which distributes the flow of materials, when the sequence of operations does not uniquely designate the next object that processes the part. Your objective will be to make a choice that is close to optimal in some respect, say cost or time.

SimTalk:
ExitStrategy
.topic 0x88ea1029
When you select Blocking, the material flow object always moves the part to the designated successor. If that successor is not ready to receive it, the part will be blocked. When moving the part fails, Plant Simulation enters the part into the Forward Blocking List of the designated successor. When you clear the check box, the material flow object moves the part to any of its successors, which is ready to receive it. The part will only be blocked, if none of the successors can receive it. When none of the successors can accept the part, Plant Simulation enters it into the forward blocking list of all successors. In both cases Plant Simulation schedules an Out event for the part, when a successor whose forward blocking list contains the part can accept it.

SimTalk:
ExitStrategyBlocking
.topic 0x88ea36d7
To open a list, into which you enter the names of one ore several services, click this. When a part it to be carried away from the station, it requests a Worker who provides this service or one of the services you entered. When you entered several services, the station searches for the Worker in the order in which you entered the services into the list.

SimTalk:
transportImp.getServices, transportImp.setServices
.topic 0x87e215bf
To allow importers with a higher priority to withdraw resources, i.e., Workers or Exporters from this importer, select Interruptible. The Worker then abandons the current task and takes care of the task that is more important.
When an importer with higher priority requests services, which the freely available resources cannot fulfull, and when sufficient interruptible importers with lower priority are available, to which the required services are brokered at the moment, then as many interruptible importers are interrupted as required to satisfy the importer with higher priority. The tasks (processing/setting-up/repair/transport), which process the interrupted importer, will then be interrupted and the resources are brokered to the importer with higher priority.

SimTalk:
transportImp.Interruptible
.topic 0x88ea36d9
Enter an integer value for the Priority. The higher the value that you enter, the higher is the priority, i.e., the sooner the job will get done. This means that the program processes a service with priority 10 before it processes a service with priority 1.

SimTalk:
transportImp.Priority
.topic 0x88ea36d4
Click this and select the Broker, who assigns the services to the Worker, in the dialog Select Object.

SimTalk:
transportImp.BrokerPath
.topic 0x88ea36d6
Click this and select the MU target to which the Worker carries the part in the dialog Select Object. The MU target is either the Workplace attached to the work station, which processes the part next, or the work station itself.

SimTalk:
MUTarget
.topic 0x88ea36d5
Select a distribution, and enter the values, which that distribution requires, into the text box. The program shows these values below the text box. Or enter a constant time (Const). When you select the Formula distribution, you can enter a numeric expression or the name of a Method. You can use the anonymous identifier @ to access the Worker for whom the maximum dwell time applies. The maximum dwelling time is the time during which the Worker waits for the parts which he is to carry to the target station. Once this time has passed, he walks to the target station, no matter if his carrying capacity is met or not. The Worker picks up the parts which the station finished processing within the maximum dwelling time.

SimTalk:
MaxDwellTime
.topic 0x88ea14ba
Click Open List and enter the data into the list, which the exit strategies Cyclic sequence, MU Attribute, Percentage, and Random require.

SimTalk:
ExitStrategySequence, ExitStrategyMUAttributeList, or ExitStrategyPercentageValues respectively
.topic 0x881b1076
Enter the number of the default successor. This is the successor to which the object moves the MU, when this MU does not have an attribute with the Value you entered into the TableFile. To not move a part, which does not meet one of the conditions in the table, enter 0. To show a message, when a part is to be moved which does not meet any of the conditions in the TableFile, enter -1.

SimTalk:
DefaultSuccessor
.topic 0x881b1075
Select the data type of the attribute from this drop-down list, compare Data Types.

SimTalk:
AttributeType
.topic 0x892f108c
Shows the portion of the statistics collection period during which the object was Working.

SimTalk:
statWorkingPortion
.topic 0x892f1098
Shows the portion of the statistics collection period during which the object was Setting-Up.

SimTalk:
statSetUpPortion
.topic 0x892f108d
Shows the portion of the statistics collection period during which the object was Waiting.

SimTalk:
statWaitingPortion
.topic 0x892f108e
Shows the portion of the statistics collection period during which the object was Blocked.

SimTalk:
statBlockingPortion
.topic 0x892f10a0
Shows the portion of the statistics collection period during which the object was Powering up/down.

SimTalk:
statPoweringUpDownPortion
.topic 0x87e1108f
Shows the portion of the statistics collection period during which the object was Failed.

SimTalk:
statFailPortion
.topic 0x892f108f
Shows the portion of the statistics collection period during which the object was Stopped by a LockoutZone.

SimTalk:
statStoppedPortion
.topic 0x892f1090
Shows the portion of the statistics collection period during which the object was Paused.

SimTalk:
statPausingPortion
.topic 0x892f14b9
Shows the portion of the statistics collection period during which the object was Unplanned, i.e., is not scheduled to work to the statistics collection period.

SimTalk:
statUnplannedPortion
.topic 0x892f1092
Shows the sum of all dwelling times of all MUs during the statistics collection period during which the object was not paused and not failed. This sum is then divided by the capacity and the entire statistics collection period without pauses and failures.

SimTalk:
statRelativeOccupation
.topic 0x892f1091
Shows the portion of the statistics collection period during which the object was Empty in relation to the time during which the object was available.

SimTalk:
statRelativeEmptyPortion
.topic 0x892f1099
Shows the portion of the statistics collection period during which all temporary storage places of the Buffer were occupied in relation to the time during which the object was available.

SimTalk:
statRelativeFullPortion
.topic 0x892f1093
Shows the number of MUs, which are located on the object. When a part enters the object, it only counts the part itself, not its contents: When a Container transporting several entities enters the object, the number of entries increases by 1, not by the number of entities located on the Container!

SimTalk:
numMU
.topic 0x892f1094
Shows the minimum number of MUs that was located on the object. When a part enters the object, it only counts the part itself, not its contents: When a Container transporting several entities enters the object, the number of entries increases by 1, not by the number of entities located on the Container!

SimTalk:
statMinNumMU
.topic 0x892f1095
Shows the maximum number of MUs that was located on the object. When a part enters the object, it only counts the part itself, not its contents: When a Container transporting several entities enters the object, the number of entries increases by 1, not by the number of entities located on the Container!

SimTalk:
statMaxNumMU
.topic 0x892f1096
Shows the number of MUs that entered the object. When a part enters the object, it only counts the part itself, not its contents: When a Container transporting several entities enters the object, the number of entries increases by 1, not by the number of entities located on the Container!

SimTalk:
statNumIn
.topic 0x892f1097
Shows the number of MUs that exited the object. When a part exits the object, it only counts the part itself, not its contents: When a Transporter transporting several MUs leaves the object, the number of exits increases by 1, not by the number of MUs which the Transporter transports!

SimTalk:
statNumOut
.topic 0x8dbe063f
To collect statistics data during a simulation run and to show the most important values on the tab, select this. To deactivate the collection of statistics data, clear the check box.

SimTalk:
ResStatOn, initStat, statistics, updateDialog
.topic 0x87e10fc9
Select the type of the material flow resource. This only affects collecting statistics values of those MUs which are located on the material flow object. Production resources are Source, Drain, Station, ParallelStation, AssemblyStation, and DismantleStation, which produce or process parts. Transport resources are PlaceBuffer, Buffer, Sorter, Track, TwoLaneTrack, Conveyor, AngularConverter, Turntable, Transporter, and Container, which transport parts between stations. Storage is the default setting for the Store, which stores parts.

SimTalk:
ResourceType
.topic 0x88f20fd6
Shows the sum of the total energy consumption.

SimTalk:
statEnergyTotalConsumption
.topic 0x88f20fd7
Shows the portion of the total energy consumption during which the object was working.

SimTalk:
statEnergyWorkingConsumptionPortion
.topic 0x88f20fd4
Shows the portion of the total energy consumption during which the object was setting-up.

SimTalk:
statEnergySetupConsumptionPortion
.topic 0x88f20fd3
Shows the portion of the total energy consumption during which the object was operational.

SimTalk:
statEnergyOperationalConsumptionPortion
.topic 0x88f20fd1
Shows the portion of the total energy consumption during which the object was failed.

SimTalk:
statEnergyFailConsumptionPortion
.topic 0x88f20fd5
Shows the portion of the total energy consumption during which the object was on standby.

SimTalk:
statEnergyStandbyConsumptionPortion
.topic 0x88f20fd2
Shows the portion of the total energy consumption during which the object was off.

SimTalk:
statEnergyOffConsumptionPortion
.topic 0x891b10ac
To activate Curve mode, select this, and click OK or Apply. Then, you can insert the length-oriented objects that contain curves into your simulation model. Select how often the MUs are animated on the length-oriented objects under Animate every x-th pixel. To insert the length-oriented object with its icon, clear the check box. Then the program animates the MUs on them using the Number of Animation Events, which you entered in the icon editor.

SimTalk:
CurveActive
.topic 0x891b124a
Enter the width of the length-oriented curved objects in the Frame. This can be a number between 1 and 500 pixels.

SimTalk:
CurveWidth
.topic 0x891b10ab
Enter the line width of the outline around the border of the length-oriented curved objects. This can be a value between -1 and 100. The value -1 makes the outline invisible. The value 0 stands for a pen width of 1 pixel. The value 1 stands for a stroke weight of 1. This affects zooming in the Frame.

SimTalk:
PenWidth
.topic 0x88141140
To select the color of the length-oriented curved objects proper, click the field next to Color.

SimTalk:
Color
.topic 0x891b1108
To select the color of the outline around the border of the picture of the curved object, click the field next to Color.

SimTalk:
PenColor
.topic 0x891b10a1
Select a style for the line in the middle of the curved object. The icons of the MUs move on this line across your tracks or conveyors.

SimTalk:
MidLine
.topic 0x891b15d2
Select one of the predefined distances or enter a distance of your choice between two pixels on which the program animates the part or the Transporter on the length-oriented curved objects. For the Turntable this setting in addition controls the rotation steps with which the table rotates. When you select 1, the object animates the part/Transporter on every pixel, when you select 10, it animates it on every tenth pixel. The higher the number you enter, the better the performance will be. When you select 1, performance may suffer if your model contains a large number of MUs.

SimTalk:
AnimateOnEveryXthPixel
.topic 0x891b124c
To open the Segments table, which shows information about the starting point and the curved and straight segments of the curved object, which you inserted, click this. You can edit the x-, y- and z-coordinate of a segment and the tangential angle and the radius of an arc segment, while Plant Simulation calculates the remaining, grayed out values.

SimTalk:
getCurveSegments,
setCurveSegments
.topic 0x891b1540
A button that looks like this means that inheritance is active. Then, the object inherits, i.e., uses, the shape of the origin object from which you derived it. When you modify the value of the origin object, the program also modifies the value of the derived object. A button that looks like this means that inheritance is not active. The values only apply to the selected object.
.topic 0x891b159e
To rotate the part on the length-oriented curved objects in the direction of motion when the part turns in a curve, select this.

SimTalk:
RotateMovables
.topic 0x891b15c5
To use the length of the curve in the layout within the Frame as the length of the curved objects, select this. When the dialog of the object is open, the program enters this value into the text box length. When you clear transfer length, you can change the shape of the object in the Frame at will, while the object uses the length which you manually entered. When you select transfer length, the program adapts the length of the graphic, when you change the length if the object only consists of a single straight segment. When the length cannot be exactly displayed in pixels, the program adapts the length of the graphic. If you need to use the exact length, clear transfer length. You can only enter the length of the length-oriented objects, when you deactivate transfer length or when the object consists of a single straight segment.

SimTalk:
TransferLengthToObject
.topic 0x891b15db
To make the inside of the curved object transparent, so that the background color of the Frame shines through, select this. The border of the object remains as it is, i.e. non-transparent. To completely hide the curved object, enter a value smaller than 0 for the Pen weight.

SimTalk:
Transparent
.topic 0x891b0f31
Enter the base height here.
The base height can be inherited, meaning that you can define it once in the class instead of having to define it for each instance individually. It is mainly used in 3D. Here the z-coordinate defines the floor of the installation and the base height defines the distance of the legs from the floor. By changing the setting DeltaZ in the Segments table, you can add an additional offset. The setting DeltaZ also affects the simulation time in 2D.

SimTalk:
BaseHeight
.topic 0x880911f5
To activate the importer, select this. Station, ParallelStation, AssemblyStation, DismantleStation, Buffer, and PlaceBuffer can then import services for setting them up and for processing the parts on them. To deactivate the importer, clear the check box.

SimTalk:
ImporterActive
.topic 0x87e20fc4
To use one set of services for setting the station up for a new part and for processing that part, select this. Then, click Services for Setting-Up and Processing and enter the services into the list. The station then deactivates the set-up-importer. The processing-importer requests an Exporter when set-up starts and releases it after processing is finished.

SimTalk:
imp.Common
.topic 0x87e30fb0
To enter groups of services for setting-up and for processing parts, first select Common resources and click this. Each of these services represents an alternative. To execute the set-up, processing, or repair jobs, the importer always needs all services of an Alternative. When the importer does not have all services of Alternative1, he attempts to get all services of Alternative2, etc. Note that for successive services in the table, which all belong to the same alternative, the name of the alternative only appears after the first service in the table. The set-up-importer requests Exporters before setting-up. By default the object releases the Exporters when set-up is finished and the object is not in the process of setting-up for a part. The processing-importer requests Exporters from the beginning of the processing time to the end of the processing time. By default the material flow object releases the Exporters when processing is finished.

SimTalk:
imp.setServices, imp.getServices
.topic 0x87e30fb1
First, click this to deactivate Inheritance. Only then you can enter data into the list. The toggle button activates or deactivates inheritance.

A green button means that inheritance is active. Then, the object inherits, i.e., uses, the value from the parent object from which it was derived. When you modify the value of the parent object, the program also modifies the value of the child object.

An orange button with a minus means that inheritance is not active. Values you select or enter only apply to the selected object.
.topic 0x87e215bd
To allow importers with a higher priority to withdraw resources, i.e., Workers or Exporters from this importer, select Interruptible.
When an importer with higher priority requests services, which the freely available resources cannot fulfull, and when sufficient interruptible importers with lower priority are available, to which the required services are brokered at the moment, then as many interruptible importers are interrupted as required to satisfy the importer with higher priority. The tasks (processing/setting-up/repair/transport), which process the interrupted importer, will then be interrupted and the resources are brokered to the importer with higher priority.

SimTalk:
imp.Interruptible, setUpImp.Interruptible
.topic 0x87e213c3
To make the material flow object release all processing services or set-up services, when one or more of these services are failed, paused, or interrupted, select All. To only release the failed services, clear it. This only works, when you also select Fail services in the dialog of the Exporter.

SimTalk:
imp.ReleaseAllServices, setUpImp.ReleaseAllServices
.topic 0x87e30fd9
Enter an integer value for the Priority. The higher the value that you enter, the higher is the priority, i.e., the sooner the job will get done. This means that the program processes a setup service or a processing service with priority 10 before it processes a service with priority 1.

SimTalk:
imp.Priority
.topic 0x87e30fd2
Click this and select the Broker, which assigns the setup service or the processing service.

SimTalk:
imp.BrokerPath, setUpImp.BrokerPath
.topic 0x87e30fd4
Click this and select a Method object. It controls how the object requests MUs. The material flow object calls the control, when the importers by default send a request to the Broker.

SimTalk:
imp.RequestCtrl
.topic 0x87e30fd6
Click this and select a Method object. It controls how the object receives MUs. The material flow object calls the control, when the importer was assigned an Exporter.

SimTalk:
imp.ReceiveCtrl
.topic 0x87e30fd8
Click this and select a Method object. It controls how the object releases the Exporters. The material flow object calls the control, when the Exporters would be released by default.

SimTalk:
imp.ReleaseCtrl
.topic 0x886a14fb
To activate the failure-importer, select this. Station, ParallelStation, AssemblyStation, DismantleStation, Buffer, and PlaceBuffer can then import failures, which prevent them from processing arriving parts. The failure-importer can also repair the machine and return it to being operational. To deactivate the failure-importer, clear the check box.

SimTalk:
FailImporterActive
.topic 0x87e2110b
To open a table into which you enter the names of groups of the different repair services, click this. Each of these services represents an alternative. To execute the task repairing, the importer always requires all services of an Alternative. When the importer does not have all services of Alternative1, he attempts to get all services of Alternative2, etc. Note that for successive services in the table, which all belong to the same alternative, the name of the alternative only appears after the first service in the table.

SimTalk:
failImp.getServices, failImp.setServices
.topic 0x87e2110c
First, click this to deactivate Inheritance. Only then you can enter data into the list.

The toggle button activates or deactivates inheritance.

A green button means that inheritance is active. Then, the object inherits, i.e., uses, the value from the parent object from which it was derived. When you modify the value of the parent object, the program also modifies the value of the child object.

An orange button with a minus means that inheritance is not active. Values you select or enter only apply to the selected object.
.topic 0x87e315bf
To allow importers with a higher priority to withdraw resources, i.e., Workers or Exporters from this importer, select Interruptible.
When an importer with higher priority requests services, which the freely available resources cannot fulfull, and when sufficient interruptible importers with lower priority are available, to which the required services are brokered at the moment, then as many interruptible importers are interrupted as required to satisfy the importer with higher priority. The tasks (processing/setting-up/repair/transport), which process the interrupted importer, will then be interrupted and the resources are brokered to the importer with higher priority.

SimTalk:
failImp.Interruptible
.topic 0x87e313c4
To make the material flow object release all repair services, when one or more of the services are failed, paused, or interrupted, select All. To only release the failed services, clear it. This only works, when you also select Fail services of the Exporter.

SimTalk:
failImp.ReleaseAllServices
.topic 0x886a14fe
Enter an integer value for the Priority. The higher the value that you enter, the higher is the priority, i.e., the sooner the job will get done. This means that the program processes a repair service with priority 10 before it processes a service with priority 1.

SimTalk:
failImp.Priority
.topic 0x886a14ff
Click and select the Broker, which assigns the repair service.

SimTalk:
failImp.BrokerPath
.topic 0x886a1500
Click and select a Method object in which you programmed how the material flow object requests Exporters or Workers. The material flow object calls the control, when the object changes to the Failed state. When you entered the control, within the control you have to make sure that the required Exporters or Workers are imported.

SimTalk:
failImp.RequestCtrl
.topic 0x886a1501
Click and select a Method in which you programmed how the material flow object receives Exporters or Workers. The material flow object calls the control, when the failure-importer was assigned an Exporter or Worker.

SimTalk:
failImp.ReceiveCtrl
.topic 0x886a1502
Click and select a Method object in which you programmed how the material flow object releases the Exporters. The material flow object calls the control, when the Exporters would be released by default.

SimTalk:
failImp.ReleaseCtrl
.topic 0x88f20fba
To activate the energy features, select this. Then you can enter values and/or select the available settings. Click Apply to activate the settings.

SimTalk:
EnergyActive
.topic 0x88f20fc1
Enter the power input in kilowatts for the machine when it is working. You can enter a value of data type real or a formula.

SimTalk:
PowerInputWorking
.topic 0x88f20fbf
Enter the power input in kilowatts for the machine when it is setting-up for a part type. You can enter a value of data type real or a formula.

SimTalk:
PowerInputSetup
.topic 0x88f20fbe
Enter the power input in kilowatts for the machine when it is operational, e.g., when it is waiting for a part. You can enter a value of data type real or a formula.

SimTalk:
PowerInputOperational
.topic 0x88f20fbd
Enter the power input in kilowatts for the machine when it is failed. You can enter a value of data type real or a formula.

SimTalk:
PowerInputFailed
.topic 0x88f20fc0
Enter the power input in kilowatts for the machine when it is on standby. You can enter a value of data type real or a formula.

SimTalk:
PowerInputStandby
.topic 0x88f20fc7
Enter the power input in kilowatts for the machine when it is on off. You can enter a value of data type real or a formula.

SimTalk:
PowerInputOff
.topic 0x88f20fd0
Enter the transition time which passes when the object changes its energy state from operational to off. You can enter a value of data type real or a formula.

SimTalk:
TransitionTimeOperationalToOff
.topic 0x88f20fcf
Enter the transition time which passes when the object changes its energy state from off to operational. You can enter a value of data type real or a formula.

SimTalk:
TransitionTimeOffToOperational
.topic 0x88f20fd0
Enter the transition time which passes when the object changes its energy state from operational to standby. You can enter a value of data type real or a formula.

SimTalk:
TransitionTimeOperationalToStandby
.topic 0x88f20fc6
Enter the transition time which passes when the object changes its energy state from standby to operational. You can enter a value of data type real or a formula.

SimTalk:
TransitionTimeStandbyToOperational
.topic 0x88f20fc3
Enter the transition time which passes when the object changes its energy state from standby to off. You can enter a value of data type real or a formula.

SimTalk:
TransitionTimeStandbyToOff
.topic 0x88f20fc2
Enter the transition time which passes when the object changes its energy state from off to standby. You can enter a value of data type real or a formula.

SimTalk:
TransitionTimeOffToStandby
.topic 0x88f20fc4
Enter the transition time which passes when the object changes its energy state from operational to standby. You can enter a value of data type real or a formula.

SimTalk:
TransitionTimeOperationalToStandby
.topic 0x88f20fbc
To open the dialog in which you can select the state transition settings at the Start and the End of a Pause and if you want to Power up early or not. Or select the state transition settings at the Start and the End of the Unplanned state and if you want to Power up early or not.
.topic 0x88f20fc8
Select the energy state transition at the start of a pause of the object. You can select Standby, No change, or Off.

SimTalk:
EnergyPauseStartState
.topic 0x88f20fc9
Select the energy state transition at the end of a pause of the object. You can select Previous state, Operational, Standby, or No change. The previous state is the state the object was in before the pause.

SimTalk:
EnergyPauseEndState
.topic 0x88f20fcd
To power the object up early during a pause so that the machine has the correct energy state at the end of the pause, select this. When you clear the check box, powering up starts at the end of the pause.

SimTalk:
EnergyPausePowerUpEarly
.topic 0x88f20fcb
Select the energy state transition at the start of the unplanned state of the object. You can select Standby, No change, or Off.

SimTalk:
EnergyUnplannedStartState
.topic 0x88f20fca
Select the energy state transition at the end of the unplanned phase of the object. You can select Previous state, Operational, Standby, or No change. The previous state is the state the object was in before the unplanned phase.

SimTalk:
EnergyUnplannedEndState
.topic 0x88f20fce
To power the object up early during an unplanned phase so that the machine has the correct energy state at the end of that phase, select this. When you clear the check box, powering up starts at the end of the unplanned phase.

SimTalk:
EnergyUnplannedPowerUpEarly
.topic 0x88f20fbb
The drop-down list shows the current energy state of the object. When the object is powering up or down, Plant Simulation shows the start state and the end state. Or select the target energy state of the object, provided it is not failed. After you select another state and click Apply, the display changes accordingly.

SimTalk:
EnergyCurrentState, EnergyTargetState
.topic 0x87e40fb2
The list field shows the name, the value, and the data type of the user-defined attributes. Or create user-defined attributes with SimTalk commands. If the data type of the selected user-defined attribute is of type object, method, table, list, stack, or queue, you can press F2 to open the Method/Table.

SimTalk:
createAttr, deleteAttr, getAttrName, getAttrNo, getAttrType, getAttrValue, setAttrValue, InheritValue
.topic 0x87e40fe9
To create a user-defined attribute, click New.

SimTalk:
createAttr
.topic 0x88031098
Enter the name of the user-defined attribute. The name has to be unique, i.e., no other built-in or user-defined attribute or method may have the same name!

SimTalk:
createAttr, getAttrName
.topic 0x88040fca
Select the data type of the user-defined attribute/Variable, compare Data Types.

SimTalk:
createAttr, getAttrType
.topic 0x8804109f
Enter a value that is compatible with this data type you selected. When using the data type time with a random distribution, select the data type randtime.

SimTalk:
createAttr, setAttrValue, getAttrValue
.topic 0x88e1800a
Click Open and enter your source code into the Method that opens. When you selected one of the list data types, enter data into the list or table that opens. To open a user-defined attribute of type Method or Table, you can also add it to the list of Favorites and double-click it in the list.
.topic 0x88040fed
Select a Value from the drop-down list or enter a value into the text box.

SimTalk:
setAttrValue, getAttrValue
.topic 0x87e40fa4
To change the name and data type of the selected user-defined attribute and to activate or deactivate inheritance, click Edit or double-click the name of the user-defined attribute in the list field and modify the values in the dialog. To show the statistics values, which the user-defined attribute collected, click Edit. Then, click the tab Statistics. Here you can set statistics to Active, show the Statistics Table, Charts, and show a Frequency Histogram.
.topic 0x87e40fa3
To delete a user-defined attribute, select it in the list field and click this.
.topic 0x88000888
The list shows all objects/Methods in the Frame, in which the object is located from which you selected the menu command Select Control. Select the name of an object or a Method.

SimTalk:
openObjectSelectBox
.topic 0x88000889
Click Back, to change to the next higher level in the hierarchy of objects when the object or the Method you want to select is located there.
.topic 0x8800087b
To use the absolute path to the object or Method, select Absolute path. The program then enters ~.~.MUs.MyPart for example. By default the program uses the relative path, which looks like this *.MUs.MyPart.
.topic 0x8800087a
Plant Simulation shows the path to the object or Method in the box.
.topic 0x89051564
Select the observable attribute or the observable method to which you would like to add the observer.
.topic 0x883c1178
Click this and select a Method object. Enter the source code of the change path control. The program calls it: When the name of a Folder or a Frame changes. The control is called for all objects contained in the Folder or Frame. The anonymous identifier @ points to the renamed object. When you move a Folder or a Frame. The control is called for all objects contained in the Folder or Frame. The program passes three parameters to the Method that is called: The parameter string1 designates the previous location of the object. The parameter string2 designates the new location of the object. The parameter of data type boolean indicates if you change the path of the object manually (true) or with a Method (false).

SimTalk:
ChangePathCtrl
.topic 0x883c115c
Click this and select a Method object. Enter the source code of the connect control. The program calls it, when you connect two objects with a Connector and when you delete the connection between two objects. The program passes three parameters to the Method that is called: The parameter object1 designates the source object at which the connection starts. The parameter object2 designates the target object where the connection ends. The parameter of data type boolean indicates if the connection is to be established (true) or to be deleted (false).

SimTalk:
ConnectCtrl
.topic 0x883c115a
Click this and select a Method object. Enter the source code of the constructor control. The program calls it, when you duplicate, derive, or instantiate the object (i.e., insert it into a Frame or model).

SimTalk:
ConstructorCtrl
.topic 0x883c115b
Click this and select a Method object. Enter the source code of the destructor control. The program calls it when you delete the object. When a Frame contains subframes and objects, Plant Simulation will call Destructor controls in these Frames as well. When the Destructor control of the object is called, the object still exists. Plant Simulation calls a Connect control before it calls a Destructor control.

SimTalk:
DestructorCtrl
.topic 0x883c1161
Click this and select a Method object. Enter the source code of the drag-and-drop control. The program calls it for the object, which you drag onto another object and drop it there. The dropped object can be an object or text. Plant Simulation passes a parameter of data type string to the called method, which contains the path of the dropped object.

SimTalk:
DragDropCtrl
.topic 0x883c117b
Click this and select a Method object. Enter the source code of the fail control. The program calls it, whenever the Failed state of the object changes. You can change the state in the dialog window of the object by selecting Failed or by assigning the value true or false to the attribute Failed. Within the control you can use the anonymous identifier question mark ? to access the object which triggered the control. The program passes two optional parameters to the Method that is called: The optional parameter of data type boolean indicates if the failures starts (true) or ends (false). The optional parameter of data type string indicates the name of the failure profile that caused the failure.

SimTalk:
FailCtrl
.topic 0x883c1162
Click this and select a Method object. Enter the source code of the move-in-frame control. The program calls it, when the object actually changes the position in the Frame into which you inserted it. The program passes four parameters to the Method that is called: The parameter integer1 designates the x-coordinate of the previous position of the object in the Frame. The parameter integer2 designates the y-coordinate of the previous position of the object. The parameter integer3 designates the x-coordinate of the new position of the object. The parameter integer3 designates the y-coordinate of the new position of the object. Within the Method you can access the moved object with the anonymous identifier question mark (?).

SimTalk:
MoveInFrameCtrl, setPosition
.topic 0x883c1179
Click this and select a Method object. Enter the source code of the move-to-folder control. The program calls it, when you move the object from a folder or a Frame to a different folder. The program passes three parameters to the Method that is called: The parameter string1 designates the previous location (Frame or folder) of the object. The parameter string2 designates the new location of the object. The parameter of data type boolean shows the user if the object is manually moved to a folder (true) or with a Method (false).

SimTalk:
moveToFolder, MoveToFolderCtrl
.topic 0x883c115d
Click this and select a Method object. Enter the source code of the open control. The program calls it, when you double-click the object to open it. Then, the program does not open the dialog of the object, but calls and executes the source code of the open control. To prevent the open control from being executed, hold down Alt while double-clicking the icon of the object.

SimTalk:
OpenCtrl
.topic 0x883c117c
Click this and select a Method object. Enter the source code of the pause control. The program calls it, whenever you change the Paused state of the object, when you either select an entry in the drop-down list Paused/Planned/Unplanned or you assign another value to the attribute Pause. When you get the paused state within the Method, it shows the state after the change. Within the control you can access the paused object with the anonymous identifier ?.

SimTalk:
PauseCtrl
.topic 0x883c115f
Click this and select a Method object. Enter the source code of the plausibility control. The program calls it, when you click OK or Apply in the dialog of the object or in the windows of list objects to apply the changes you made there. At this point in time the Method checks if the entries are plausible or it interprets them.

SimTalk:
PlausibilityCtrl
.topic 0x883c1177
Click this and select a Method object. Enter the source code of the relabel control. The program calls it, whenever you modify the Label of the object. The program passes three parameters to the Method that is called: The parameter string1 designates the current label of the object. The parameter string2 designates the new label. The parameter of data type boolean indicates if the object is relabeled by the user (true) or by assigning a value to the attribute Label (false).

SimTalk:
RelabelCtrl
.topic 0x883c1176
Click this and select a Method object. Enter the source code of the rename control. The program calls it, when you change the Name of the object. The program passes three parameters to the Method that is called: The parameter string1 designates the current name of the object. The parameter string2 designates the new name of the object. The parameter of data type boolean indicates if the object is renamed by the user (true) or by assigning a value to the attribute Name (false).

SimTalk:
RenameCtrl
.topic 0x883c1160
Click this and select a Method object. Enter the source code of the select control. The program calls it, when you click the object with the left mouse button. The program does not select the object.
Instead the Method you entered has to take the appropriate actions, for example by opening the object, or by confirming the selection with the attribute Selected, etc.

Note that the control only reacts on selecting an instance in a Frame in 2D. It neither reacts on a selection in 3D nor on setting the attribute Selected.

SimTalk:
SelectCtrl
.topic 0x883c14bc
Click this and select a Method object. Enter the source code of the unplanned control. The program calls it, whenever the Unplanned state of the object changes, i.e., whether the object is not scheduled to work during the time, which you entered into the ShiftCalendar or whether it is scheduled to work. You can change the state in the dialog of the object by selecting an entry in the drop-down list Paused/Planned/Unplanned or by assigning another value to the attribute Unplanned. Within the control you can access the object with the anonymous identifier ?.

SimTalk:
UnplannedCtrl
.topic 0x892836c9
To create a new observer, click Add. This only works if the attribute or the method of the object is observable.

SimTalk:
addObserver
.topic 0x88e0149b
Select the observable attribute or the observable method, whose value you want to watch.
.topic 0x890c1514
Select the Method, which is going to be executed, when the value of the Attribute or of the Method changes. The name of the attribute/method and the previous value of the attribute/method are passed to the executed Method as parameters. To employ a user-defined attribute of type method as the Method, click the right mouse button in the field Method and select the command Create Control. Then, the program automatically formats the Method correctly.
.topic 0x892836c7
The list field shows the name of the Attribute or the Method, the name of the Method that is going to be executed, and if the object inherits the observer from its class. When you add the observer to the instance of the object, which you inserted into a Frame, it shows an asterisk * in the column Created here.
.topic 0x892836ca
To change the observable attribute or method, which the selected observer watches, and the Method, which is going to be executed, click this. Or double-click the name of the observer in the list field and change the values in the dialog which opens.
.topic 0x892836cb
To remove the selected observer, click this.

SimTalk:
removeObserver
.topic 0x8541089e
To create the selected object in the 3D window when you start it, select this. To not create it, for example because you do not need it in your 3D model, clear the check box.

SimTalk:
CreateIn3D
.topic 0x88f20fae
Enter the length of the first leg of the AngularConverter. It covers the distance from the entry point to the point at which the AngularConverter switches the conveying direction. When Transfer length on the Tab Curve is active, the program adapts the graphic of the AngularConverter, when you change the entry length. When the length cannot be exactly displayed in pixels, the program adapts the length of the graphic. If you need to use the exact length, clear transfer length.

SimTalk:
EntryLength
.topic 0x88f20faf
Enter the length of the second leg of the AngularConverter. It covers the distance from the point at which the AngularConverter switches the conveying direction to the point at which the part exits the object. When Transfer length on the Tab Curve is active, the program adapts the graphic of the AngularConverter, when you change the exit length. When the length cannot be exactly displayed in pixels, the program adapts the length of the graphic. If you need to use the exact length, clear transfer length.

SimTalk:
ExitLength
.topic 0x88f20fb0
Enter the speed with which the MUs moves on the AngularConverter from the entry point to the point at which the AngularConverter switches the conveying direction.

SimTalk:
EntrySpeed
.topic 0x88f20fb1
Enter the speed with which the MUs moves on the AngularConverter from the point at which the AngularConverter switches the conveying direction to the point at which it exits the object.

SimTalk:
ExitSpeed
.topic 0x827503f8
To set the current speed of the conveying object to 0 when it does not transport a part, select this. This might be the case when it is empty or when it is blocked when a part cannot leave it.

SimTalk:
AutomaticStop
.topic 0x84c70c64
The moving time is the time it takes the AngularConverter to switch from lengthwise to crosswise conveyance and vice versa. The moving time is consumed, when the part arrives at the corner at which the AngularConverter switches conveyance and again, when it has completely left the AngularConverter to return the AngularConverter to its original position. Only then can another part move onto the AngularConverter, as it can only accommodate a single part at any one time. Select a distribution from the drop-down list, and enter the values, which that distribution requires, into the text box. The program shows these values along the top border of the tab. Or enter a constant time (Const). When you select the Formula distribution, you can enter a numeric expression or the name of a Method. You can use the anonymous identifier @ to access the part for which the moving time applies.

SimTalk:
MovingTime
.topic 0x8823082d
Select if the AssemblyStation uses an assembly table and if so which kind. Then click Open and enter the required information into the assembly table:
None: The AssemblyStation does not use an Assembly Table. Instead, it expects a part from each predecessor.
Predecessors: Enter the number of the predecessor, which moves the part, into column 1 of the table and the amount into column 2 of the Assembly Table.
MU Types: Enter the name of the part, such as Part, Container, Transporter, Shaft, etc., into column 1 and the amount into column 2 of the Assembly Table.
Depends on Main MU: Enter the name of the main part, the name of the MU, such as Part, Container, Transporter, etc., and the number of parts. Or enter an asterisk * as default name of the main part.

SimTalk:
AssemblyList, PartListMode
.topic 0x882308ca
To open the assembly table, click this. Depending on the setting you selected from the drop-down list, you either enter the numbers of the Predecessors or the MU types into the cells of column 1 and their amount into the cells of column 2.
.topic 0x882308cd
Enter the number of the Predecessor object which moves the main MU to the AssemblyStation. The predecessor is the object that is connected to the selected object with a Connector and that precedes it in the sequence of stations in the simulation model.

SimTalk:
MainMU
.topic 0x882308d1
Select how the AssemblyStation handles MUs: Attach MUs: It attaches the add-on part onto the main MU. Delete MUs: It deletes the add-on part after the assembly operation is finished.

SimTalk:
AssemblyMode
.topic 0x882308d2
Select how the AssemblyStation handles the MU, which is leaving the station: Main MU: It moves the main MU to the succeeding object. New MU: It moves the assembled/new MU to the succeeding object. When you select New MU, the AssemblyStation shows the button and the text box MU. Click this and select the new MU in the dialog Select Object.

SimTalk:
ExitingMU, NewMU
.topic 0x882308d3
Select the sequence in which the AssemblyStation requests parts and/or services: MUs then services: It requests the MUs before it requests the required services. Services then MUs: It requests the services before it requests the MUs required. MUs and Services: It requests the MUs and the services at the same time.

SimTalk:
OrderSequence
.topic 0x892f122b
Shows the portion of the statistics collection period during which the AssemblyStation was Waiting for add-on parts.

SimTalk:
statWaitingPartsPortion
.topic 0x892f122a
Shows the portion of the statistics collection period during which the AssemblyStation was waiting for Exporters and/or add-on parts.

SimTalk:
statWaitingResPortion
.topic 0x892f122c
To open the table Waiting Times, which shows the sum of the waiting times for add-on parts for each predecessor, click Waiting Times.
.topic 0x886d12e1
Select the Buffer type, i.e., the exit behavior of the MUs from the Buffer: Queue: The parts exit the Buffer in the same order in which they entered it (First In First Out). Stack: The part, which entered last, leaves the Buffer first (Last In First Out).

SimTalk:
BufferType
.topic 0x886d36fc
To show the relative fill level of the buffer as a colored bar at the bottom of its icon in the Frame, select this.

SimTalk:
ShowFillLevel
.topic 0x84c70db0
For the Buffer you can only enter a constant dwell time. For the PlaceBuffer you can only enter a constant processing time. Statistics counts the dwell time as waiting time and not as processing time. The dwell time thus is not prolonged by failures or pauses.

SimTalk:
ProcTime
.topic 0x88070ff8
Enter the line width of the Connector. This can be a number between -1 and 100 pixels.
The value -1 makes the Connector invisible. The value 0 stands for a Connector width of 1 pixel. The value 1 stands for a stroke weight of 1. This affects zooming in the Frame.

SimTalk:
Width
.topic 0x880711a5
To select the color of the Connector, click the field next to Color.

SimTalk:
Color
.topic 0x87e40fa5
Enter the length of the Converter. After you inserted it, Plant Simulation shows its length here. When the part is conveyed straight through along the direction of insertion, its length and the length of the parts determine how many parts it can accommodate.

SimTalk:
Length
.topic 0x87e40fa7
Enter the width of the Converter. Plant Simulation inserts the Converter with the standard width of 1 meter.

SimTalk:
Width
.topic 0x87e40fa6
Enter the speed with which the Converter conveys the parts. Or enter -1 for an infinite speed.

SimTalk:
Speed
.topic 0x87e40fb0
Select the strategy according to which the Converter conveys the parts to the next material flow object: Default exit makes all parts exit through the Default exit which you select to the successor attached to that exit. Straight conveys the part straight through to the next station. Feed in allows parts from a branch line to only enter the main line when no part is located on the main line within the free space which you enter. The free space is the distance between two successive parts on the main line. MU Attribute conveys the part according to a built-in or a user-defined attribute of the part. Click Open List and enter the name of the attribute of the part, the value of the attribute, and select on which side it is to exit. Enter the number of the Default exit. Repeat this for each attribute you enter. MU Name conveys the part according to its name. Click Open List and enter the name of the part and select on which side it is to exit. Enter the number of the Default exit. Method conveys the part according to the source code you enter into the strategy method in which you determine the side of the Converter at which the part will exit the Converter. Enter the name of the method into the text box Strategy method.
SimTalk:
Strategy
.topic 0x87e40fa8
Select the number of the default exit at which the part exits the Converter. 1 is laterally to the right in the insertion direction, 2 is against the insertion direction, 3 is laterally to the left in the insertion direction, 0 is along the insertion direction.

SimTalk:
DefaultExit
.topic 0x87e40fb1
To open the exit list for the parts, click this. For the Strategy > MU Attribute you can enter the name of the attribute of the part, its value and select on which side it exits. Repeat this for each attribute you enter. For the Strategy > MU Name you can enter the name of the attribute of the part and select on which side it exits. Repeat this for each attribute you enter.

SimTalk:
setAttributeList, getAttributeList
.topic 0x87e40fb3
Select the data type of the attribute that determines to which station the Converter moves the part.

SimTalk:
AttributeType
.topic 0x87e40fa9
Click this and select a Method object in the dialog Select Object. Enter the source code of the strategy method in which you determine the side of the Converter at which the part will exit the Converter. The Converter calls the control as soon as the part wants to enter it. Set the side with the attribute ExitForNextEnteringMU.
.topic 0x84c70e12
The moving time is the time it takes the Converter to lift the part onto a different conveying level and to then lower itself and move back to the default position. This time always elapses when the Converter has to change the direction of the part and when a part enters from a side, i.e., not along the preferred insertion direction. Select a distribution from the drop-down list, and enter the values, which that distribution requires, into the text box. The program shows these values along the top border of the tab. Or enter a constant time (Const). When you select the Formula distribution, you can enter a numeric expression or the name of a Method. You can use the anonymous identifier @ to access the part for which the moving time applies.

SimTalk:
MovingTime
.topic 0x892f1198
Shows the portion of the statistics collection period during which the Converter was raising or lowering itself without conveying a part.

SimTalk:
statMovingEmptyPortion
.topic 0x892f1199
Shows the portion of the statistics collection period during which the Converter was raising or lowering itself while conveying a part.

SimTalk:
statMovingLoadedPortion
.topic 0x880036c3
To synchronize the transfer of MUs from station to station, select this. Then a part is only moved on to the next station within the balanced line, when all stations have finished processing their parts and when none of the stations are failed, paused or unplanned. To deactivate line balancing, clear the check box.

SimTalk:
Active
.topic 0x88001181
Enter the name of the first station of the group of stations, which you want to balance.

SimTalk:
getFirstStation, setFirstAndLastStation
.topic 0x8800114d
Enter the name of the last station of the group of stations, which you want to balance.

SimTalk:
getLastStation, setFirstAndLastStation
.topic 0x880036c0
To permit parts on the balanced stations to be moved on, although no part is ready to move on from the predecessor of the balanced line, select this. This results in an idle cycle.

SimTalk:
EmptyCycleAllowed
.topic 0x8855121d
Select how the DismantleStation distributes MUs to its successors:
MUs to all successors: Select Create MUs from the drop-down list Dismantle mode to create a new part for each successor and to move that part there.
Select Detach MUs from the drop-down list Dismantle mode to move the MUs to each successor in turn, except for the successor that receives the main MU.
For these settings you have to fill out the Dismantle Table:
MUs exiting independent of other MUs: It attempts to move each part on to the successor you defined, as soon as possible.
Main MU after other MUs: It first moves the add-on parts on to the successor, and then the main MU.

SimTalk:
Sequence
.topic 0x8855121e
To open the dismantle table, click this. The DismantleStation then opens a table with three columns. Enter the path to the class of the MUs into the column MU, such as .MUs.Part, .MUs.Container or .MUs.Transporter. Enter the number of MUs that are dismantled into the column Number. If you do not enter a number, the DismantleStation uses the default value 1, if you selected the Dismantle mode > Create MUs. If you selected the Dismantle mode > Detach MUs, the DismantleStation moves the parts on to the successor that will also receive the main MU. Enter the number of the successor into the column Successor. If you do not enter a value, the DismantleStation uses the default value 1.

SimTalk:
DismantleList
.topic 0x88551221
Select how the DismantleStation handles the add-on parts: Detach MUs: It detaches the add-on parts from the main MU and moves them on to the successor which you entered into the Dismantle Table. Create MUs: It creates add-on parts.

SimTalk:
DismantleMode
.topic 0x88551223
Enter the number of the successor to which the DismantleStation moves the main MU.

SimTalk:
MainMU
.topic 0x88551225
Select how the DismantleStation moves the main MU or a new MU on to its successor. Main MU: Moves the main MU on to the succeeding object. New MU: Deletes the main MU, creates a new MU, and moves it on to the successor. The DismantleStation shows the button and the text box MU.

SimTalk:
MainMU, ExitingMUMode
.topic 0x88551226
Enter the path to the class of the new MU into the text box, or click the button and select the new MU in the dialog Select Object.

SimTalk:
NewMU
.topic 0x892915aa
Shows the percentage of the sum of the times during which the MUs were located on a Working object, in relation to the statistics collection periods of all MUs. In general, this is the life time of the MUs.

SimTalk:
statWorkingPortion
.topic 0x892915bb
Shows the percentage of the times during which the objects were setting-up for the MUs, in relation to the statistics collection periods of all MUs. In general, this is the life time of the MUs, compare Setting-Up.

SimTalk:
statSetUpPortion
.topic 0x892915ab
Shows the percentage of the times during which the objects were waiting for the MUs, in relation to the statistics collection periods of all MUs. In general, this is the life time of the MUs, compare Waiting.

SimTalk:
statWaitingPortion
.topic 0x892915bc
Shows the percentage of the sum of the times during which the MUs were located on an object that was Stopped, in relation to the statistics collection periods of all MUs. In general, this is the life time of the MUs.

SimTalk:
statStoppedPortion
.topic 0x892915ad
Shows the percentage of the sum of the times during which the MUs were located on an object that was failed, in relation to the statistics collection periods of all MUs. In general, this is the life time of the MUs.

SimTalk:
statFailPortion
.topic 0x892915ae
Shows the percentage of the sum of the times during which the MUs were located on a paused or unplanned object, in relation to the statistics collection periods of all MUs. In general, this is the life time of the MUs.

SimTalk:
statPausingPortion
.topic 0x892915b3
Shows the average life-span of MUs, which were created and removed from the installation during the statistics collection period. Only those MUs are counted for which you activated product statistics.

SimTalk:
statAvgLifeSpan
.topic 0x892915b9
Shows the average time interval between exits of the MUs that the Drain removed from the installation. It results from adding up the times of all intervals, and then dividing them by the number of intervals. Statistics only starts counting from the time the first part arrived!

SimTalk:
statAvgExitInterval
.topic 0x892915b1
Shows the number of MUs that the Drain removed from the installation, starting at the time, at which you activated Type dependent statistics.

SimTalk:
statDeleted
.topic 0x892915b5
Shows the number of MUs that the Drain removed from the installation in an hour over all observed times during which the Drain was available.

SimTalk:
statThroughputPerHour
.topic 0x892915b7
Shows the number of MUs that the Drain removed from the installation in a day over all observed times during which the Drain was available. This is the value of the throughput per hour multiplied with 24.

SimTalk:
statThroughputPerDay
.topic 0x892915a2
To activate statistics collection depending on the type of the MU, which the Drain removed from the installation, select this.

SimTalk:
TypeStatOn
.topic 0x892915a0
To open the Detailed Statistics Table, click this. It itemizes the MUs, which the Drain removed from the installation, according to their types.

SimTalk:
typeStatistics
.topic 0x87f30fe0
The program shows the current simulation time of the simulation run in the box next to Time. Click Time to change the display of the time between the Relative time: The program resets the relative time to zero, when it starts the simulation run. This is the default. Current time plus simulation time: The program adds the simulation time to the time and date at which it started the simulation run.

SimTalk:
AbsSimTime, SimTime
.topic 0x850106c3
To reset your simulation model, click this. The program calls all Methods named reset in your simulation model. The Reset call deletes all unprocessed events, resets the simulation time to 0, resets the statistics, and removes all failures of all machines in the simulation model. When you click Reset while the simulation is running, Plant Simulation finishes processing the current event and then resets the model. It does not change the Paused state of objects.

SimTalk:
reset
.topic 0x850106be
To start the simulation, click this. To stop the simulation after the active simulation event has been processed, click the button again. The program calls init methods when you click Start if they have not been called yet.

SimTalk:
start, stop, StartStopCtrl, init, InitCtrl
.topic 0x85010e30
To start the simulation run without MU Animation and Icon Animation, click this. This makes the simulation considerably faster.

SimTalk:
startWithoutAnimation
.topic 0x850106c0
To process the next simulation event in line, to stop the simulation afterwards, and to thus proceed through your model step-by-step, click this. When you hold down Shift while clicking Step, Plant Simulation opens the Method Debugger for all methods and formulas, which are executed while the event is being processed. This means that the debugger opens for all executed controls, formulas and for suspended methods, which were woken up. If init methods have not been called yet, the init methods are started instead of processing an event.

SimTalk:
step, StartStopCtrl
.topic 0x850106c1
To open the Dialog Window of the Event Debugger, click this. The List of Scheduled Events contains all currently scheduled events in ascending order, allowing you to find out, which events are scheduled to be executed at which point in time.

SimTalk:
getEventList
.topic 0x850106c5
To increase the speed of the simulation, drag the slider to the right or press the right arrow key. To decrease the speed of the simulation, drag it to the left or press the left arrow key.

SimTalk:
Speed
.topic 0x850106d2
To pause the simulation until the time span between two events has elapsed in real time, select this. Then, enter the Scaling Factor into the text box to the right. You have to activate real time mode to achieve a smooth animation in 3D. Animations, which you imported into the 3D only run, when you activate real time mode. The simulation objects move with the speed of the corresponding 2D object and the real time factor, which you enter here.

SimTalk:
RealTime
.topic 0x850106d3
Enter or select the scaling factor for real time mode. The scaling factor sets the time that elapses between two events in real time. The duration of an event in real time is the simulation time divided by the scaling factor you entered. The resulting duration is an integer value.

SimTalk:
RealTimeScale
.topic 0x850206ce
Enter the date and the time on which the absolute time during the simulation is based.

SimTalk:
Date
.topic 0x850206cf
Enter the time at which the simulation will be finished. Enter a relative time, i.e., the period of time during which the simulation runs. The program compares this period with the simulation time and stops the simulation run, when both are identical. Let us assume that it is July 04, 12 o'clock noon and the simulation is to run for two days. To make the simulation run for two days, type in 2:00:00:00. If you do not want to write this out in full, you can also just type 2::: and click Apply to make the program translate this to the full format 2:00:00:00.

SimTalk:
End
.topic 0x850206d0
Enter the time at which the EventController resets statistics and deletes all statistics values it collected up to that time. The program starts collecting new statistical data for all material flow objects anew from this time on. This way you can discard data collected during the warm-up phase, which might distort the simulation results.

SimTalk:
StartStat
.topic 0x85020839
To step over animation events and to stop at the next event which is relevant to the simulation in any window, select Step over animation events. Then, click Step on the tab Controls. to process a single simulation event at a time.
.topic 0x85020d09
To delete all MUs from all Frames, when you reset the simulation model by clicking the Reset button or by calling the method reset, select this.

SimTalk:
DeleteMUsOnReset
.topic 0x85020e4c
To show a summary report of the parts which the Drain deleted, select this. At the end of the simulation run the report checks all Drain objects within the entire simulation model which removed parts from the plant.

SimTalk:
SummaryReport
.topic 0x850506e5
To stop executing the event at a breakpoint, which you inserted, select this.

SimTalk:
BreakPointsActive
.topic 0x850506e7
Enter the name of the file to which the Event Debugger writes all events. If the file does not exist, the Event Debugger creates it.

SimTalk:
TraceFile
.topic 0x850506e8
To make the Event Debugger write all events to the file the name of which you enter into the text box Trace file, select this.

SimTalk:
TraceActive
.topic 0x850506e9
To open the dialog Breakpoints, click this.
.topic 0x881c1075
The list shows the event type, the start time, the stop time, the receiver and the sender of the event.
.topic 0x881c1067
To insert a new breakpoint, click this. Then, define the breakpoint that stops the simulation when a certain event takes place in The Dialog Breakpoint.
.topic 0x881c1068
To edit an existing breakpoint, select it in the list of breakpoints and click this.
.topic 0x881c1069
To delete the selected breakpoint from the list, click this.
.topic 0x854c08eb
Enter the object that receives the breakpoint with its absolute path. If you do not enter a receiver, this breakpoint applies to events with any receiver.

SimTalk:
setBreakpointReceiver, getBreakpointReceiver
.topic 0x854c08ec
Enter the object that sends the breakpoint with its absolute path. Whenever the object creates an event, you can stop the simulation and track the execution. If you do not enter a Sender, this breakpoint applies to events with any sender.

SimTalk:
setBreakpointSender, getBreakpointSender
.topic 0x854c08e6
Enter the time, at which the breakpoint will be activated. If you do not enter a value for the start time and the stop time, no limits apply for the interval during which the breakpoint is active.

SimTalk:
setBreakpointStartTime, getBreakpointStartTime
.topic 0x854c08e7
Enter the time, at which the breakpoint will be deactivated.

SimTalk:
setBreakpointStopTime, getBreakpointStopTime
.topic 0x854c08e8
Select the type of event for which the breakpoint is active. The asterisk (*) stands for any type of event.

SimTalk:
setBreakpointType, getBreakpointType
.topic 0x854c08ed
Enter any condition you would like to apply to the definition of the breakpoint. Before an event is released for execution, the Event Debugger checks the expression you entered. This expression may be anything that returns a boolean value. When the condition returns true, the Event Debugger stops the simulation. When you use a formula for the condition, you can access the receiver using the anonymous identifier @. You might enter @.Name = "Wheel" AND @.getNo = 4 or @.length<100

SimTalk:
getBreakpointCondition, setBreakpointCondition
.topic 0x854c08ee
To select an existing file, into which the Event Debugger writes the scheduled events of the objects, click this.

SimTalk:
setBreakpointTraceFile, getBreakpointTraceFile
.topic 0x854c08ee
Enter the name of the file. When you do not enter a name, the Event Debugger does not create a trace file.
.topic 0x850506ef
The event list contains the types of scheduled events, which the objects in your simulation model entered and which the EventController has to process. It is sorted ascending by time. It lists the type of event, the scheduled processing time, the receiver and the sender of the event, and parameters.
.topic 0x85050d0b
To reset your simulation model, click this. The program calls all Methods named reset in your simulation model. The Reset call deletes all unprocessed events, resets the simulation time to 0, resets the statistics, and clears any failure of any machine. When you click Reset while the simulation is running, Plant Simulation will finish processing the active event and then reset. It does not change the paused state of objects.

SimTalk:
reset
.topic 0x850506ec
To start the simulation, click this. To stop the simulation after the active simulation event has been processed, click the button again.

SimTalk:
start, stop
.topic 0x85010e30
To start the simulation run without MU Animation and Icon Animation, click this. This makes the simulation considerably faster.
.topic 0x850506ed
To process the next simulation event in line, to stop the simulation afterwards, and to thus proceed through your model step-by-step, click this. When you hold down Shift while clicking Step, Plant Simulation opens the Method Debugger for all methods and formulas, which are executed while the event is processed. This means that the debugger opens for all executed controls, formulas and for suspended methods, which were woken up. Clicking Debug does the same.

SimTalk:
step
.topic 0x85050d0e
To open the Method Debugger for all methods and formulas, which are executed while the event is processed, click this. This means that the debugger opens for all executed controls, formulas and for suspended methods, which were woken up. Holding down Shift while clicking Step accomplishes the same, in the EventDebugger and in the EventController.
.topic 0x850506ee
To close the window of the Event Debugger, click this or click the X in the title bar.
.topic 0x883c117a
Click this and select a Method object. Enter the source code of the init control. Plant Simulation calls this control once at the beginning of the simulation run during the init phase before the objects are initialized and before init methods are executed. Within the init control you can change the Worker Creation Table of the Workerpool for the next simulation run. This cannot be accomplished in an init method as this method would be called too late in time.

SimTalk:
InitCtrl
.topic 0x880f15d9
Select if the exit strategy is blocking or non-blocking: When you select Blocking, the FlowControl always moves the part on, when the designated successor can receive it. When you clear the check box, the FlowControl moves the part on, when any of its successors can receive it.

SimTalk:
ExitBlocking
.topic 0x880f1027
Select the strategy according to which the FlowControl distributes the MUs among its successors.

SimTalk:
ExitBehavior
.topic 0x881d800b
Click Open List and enter the data into the list, which the exit strategies Cyclic sequence, MU Attribute, MU Name, and Percentage require.

SimTalk:
setExitList, getExitList
.topic 0x881d0ef2
Click Open List to open a table and enter the percentages. The n-th row in the table defines the n-th successor’s portion. The FlowControl only receives an MU from the predecessor, for which the difference between the desired value and the actual value is greatest.

SimTalk:
setEntryList, getEntryList
.topic 0x881d0ef3
Select a distribution for receiving the MUs from the predecessors and enter the parameters, which this distribution requires into the text box.

SimTalk: EntryDistribution
.topic 0x881d102f
The toggle button activates or deactivates inheritance.

A green button means that inheritance is active. Then, the object inherits, i.e., uses, the value from the parent object from which it was derived. When you modify the value of the parent object, the program also modifies the value of the child object.

An orange button with a minus means that inheritance is not active. Values you select or enter only apply to the selected object.
.topic 0x880f1602
Enter the name of the Method, whose return value determines the number of the successor to which the FlowControl moves the part. In the method, you can access the FlowControl with the anonymous identifier ?. The anonymous identifier @ points to the part, which is to be moved on.

SimTalk:
ExitSelectionMethod
.topic 0x880f11a3
Select the data type of the attribute from this drop-down list, compare Data Types.

SimTalk:
AttributeType
.topic 0x880f11a1
Enter the number of the default successor. This is the successor to which the FlowControl moves the MUs, when none of the MUs has an attribute with the Value you entered into the TableFile. To not move a part, which does not meet one of the conditions in the table, enter 0. To show a message, when a part is to be moved which does not meet any of the conditions in the TableFile, enter -1.

SimTalk:
DefaultSuccessor
.topic 0x881d1030
Select a probability distribution from the drop-down list Distribution and enter the parameters, which this distribution requires into the text box. The upper bound of a distribution should be greater by one than the lower bound, as the upper bound is not part of the range that the program creates.

SimTalk:
ExitDistribution
.topic 0x880f1601
Select the property of the successor according to which the FlowControl moves the part.

SimTalk:
ExitSelectionProperty
.topic 0x880f102a
A FlowControl, which you inserted into a Frame, shows its next aimed at successor. This is the successor, which is served next according to the exit strategy. When you clear Blocking, this does not have to be the successor to which the part is actually moved.
.topic 0x881d15da
When you select Blocking, the FlowControl only receives MUs from the next designated predecessor. MUs Waiting on other predecessors cannot be received. When you clear Blocking, the FlowControl receives MUs from any of its predecessors. The entry strategy only takes effect, when the blocking list of the FlowControl contains several MUs and the FlowControl is unblocked because of a successor getting ready to receive a part.

SimTalk:
EntryBlocking
.topic 0x881d1028
Select the strategy according to which the FlowControl receives the MUs from its predecessors.

SimTalk:
EntryBehavior
.topic 0x881d1603
Enter the name of the Method, whose return value determines the predecessor from which the FlowControl receives the part. In the method, you can access the FlowControl using the anonymous identifier ?.

SimTalk:
EntrySelectionMethod
.topic 0x881d105b
Select the property of the predecessor according to which the FlowControl receives the MUs.

SimTalk:
EntrySelectionProperty
.topic 0x881d102b
A FlowControl, which you inserted into a Frame shows its next aimed at predecessor. This is the predecessor, which is served next according to the entry strategy. When you deactivate Blocking, this does not have to be the predecessor from which the part is actually received.
.topic 0x891a1565
To select a color in the dialog Colors, click the field next to Color.
.topic 0x891a1567
Select filled, to fill an ellipse or a rectangle with the Color you selected.
.topic 0x891a127f
Select the direction in which the color gradient blends. This feature is only available for filled rectangles.
.topic 0x891a127e
Enter the line weight, i.e., the thickness of the line you draw, in pixels.
.topic 0x891a126c
Select a line style of the line. Or draw lines with arrowheads pointing left or right at their ends.
.topic 0x891a126e
Enter the layer onto which the program draws the vector object. Enter a negative number, -1 for example, to draw the vector object onto the foreground of the Frame. Enter a positive number to draw the vector object onto the background of the Frame.
.topic 0x891a1578
Select a font size for the text you enter into the text box or into the dialog Enter Text.
.topic 0x891a1577
Enter the text, which you want to show on the background/foreground of the Frame.
.topic 0x858409b4
Enter the title of the user-defined ribbon tab with which the program shows the ribbon tab to the right of the predefined ribbon tabs.

SimTalk:
UserMenuTitle
.topic 0x858409b5
To show and activate the user-defined ribbon tab which you defined to the right of the predefined ribbon tabs, select this.
To deactivate and hide it, clear the check box.

SimTalk:
ShowUserMenu
.topic 0x858409b6
Enter the name of the Command that the program shows on the user-defined ribbon tab in the Frame.
Then enter the Method to be executed when you select the command into the cell to the right.

SimTalk:
UserMenu
.topic 0x858409c5
Enter the name of the Method , which the Command calls and executes, into the corresponding text box.
If the method expects a parameter, Plant Simulation automatically passes it. The objects, which you selected in the Frame, are passed to this parameter, which has to be of data type list.

SimTalk:
UserMenu
.topic 0x891a1579
Select the representation mode. It determines how Plant Simulation shows the selected Frame: With its icon. With its contents. With its contents including the background. Plant Simulation shows the background of your modeled component with the Background color you selected for the Frame in which you modeled it. If you do not select a background color, the object will be transparent. This way you can “project” the object onto a plant layout drawing so that the layout drawing shines through. The represented area does not show the grid.

SimTalk:
RepresentationMode
.topic 0x891a1583
Enter the x-coordinate of the left top corner of the representation area in the Frame or click the spin buttons. The position of the built-in objects within the representation area of the Frame is relative to the reference point of the representation area designated by the red crosshairs. The borders of the area itself are shown as green dashed lines.

SimTalk:
setRepresentationArea, getRepresentationArea
.topic 0x891a1585
To move the x-coordinate of the left top corner of the representation area in the Frame to the right, click the right spin button. To move it to the left, click the left spin button.
.topic 0x891a1589
The toggle button activates or deactivates inheritance of the settings of the representation area and of the axes origin.

A green button means that inheritance is active. Then the object inherits, i.e., uses, the value from the parent object from which it was derived. When you modify the value of the parent object, the program also modifies the value of the child object.

An orange button with a minus means that inheritance is not active. Values you select or enter only apply to the selected object.
.topic 0x891a1584
Enter the y-coordinate of the left top corner of the representation area in the Frame or click the spin buttons. The position of the built-in objects within the representation area of the Frame is relative to the reference point of the representation area designated by the red crosshairs. The borders of the area itself are shown as green dashed lines.

SimTalk:
setRepresentationArea, getRepresentationArea
.topic 0x891a1585
To move the y-coordinate of the left top corner of the representation area in the Frame upwards, click the up spin button. To move it downwards, click the down spin button.
.topic 0x891a1582
Enter the width of the representation area or click the spin buttons. The position of the built-in objects within the representation area of the Frame is relative to the reference point of the representation area designated by the red crosshairs. The borders of the area itself are shown as green dashed lines.

SimTalk:
setRepresentationArea, getRepresentationArea
.topic 0x891a1588
To increase the width of the representation area, click the right spin button. To decrease the width of the representation area, click the left spin button.
.topic 0x891a1581
Enter the height of the representation area or click the spin buttons. The position of the built-in objects within the representation area of the Frame is relative to the reference point of the representation area designated by the red crosshairs. The borders of the area itself are shown as green dashed lines.

SimTalk:
setRepresentationArea, getRepresentationArea
.topic 0x891a1587
To increase the height of the representation area, click the up spin button. To decrease the height of the representation area, click the down spin button.
.topic 0x891a1590
Enter the x-coordinate of the 3D origin or click the spin buttons. The Frame shows the origin of the axes, which also is the reference point of the contents of the Frame, as red crosshairs.

SimTalk:
AxesOrigin
.topic 0x891a1592
To move the x-coordinate of the 3D origin to the right, click the right spin button. To move it to the left, click the left spin button.
.topic 0x891a1591
Enter the y-coordinate of the 3D origin or click the spin buttons. The Frame shows the origin of the axes, which also is the reference point of the contents of the Frame, as red crosshairs.

SimTalk:
AxesOrigin
.topic 0x891a1593
To move the y-coordinate of the 3D origin upwards, click the up spin button. To move it downwards, click the down spin button.
.topic 0x887f159a
Click this to make Plant Simulation re-calculate the representation area according to the objects contained in that area.
.topic 0x883c115e
Click this and select a Method object. Enter the source code of the close control. The program calls it, when you close the object window. For list objects the program passes a parameter, of data type boolean, to the Method that is called. This parameter shows if the contents of the list window has changed or not.

Note that the control does not react on closing a 3D window.

SimTalk:
CloseCtrl
.topic 0x883c14bf
Click this and select a Method object. Enter the source code of the permit-delete control. The Frame or the folder calls it, when you attempt to delete the object for which you programmed the control. When the method returns false, the program does not delete the object. When the method returns true, the program deletes the object and calls a Destructor control method, provided you entered one.

SimTalk:
PermitDeleteCtrl
.topic 0x88ed14d5
Click this and select the ShiftCalendar or enter the name of the ShiftCalendar object that controls the shifts of the Frame.

SimTalk:
ShiftCalendarObject
.topic 0x891e1575
Enter the scaling factor. The program uses it to compute the length of polygon lines that you create. The scaling factor is the length of one pixel in length units. By setting the correct scaling factor, you can place 2D objects in the Frame according to their real coordinates. The Horizontal grid spacing shows the distance between two grid points on the X-axis using the Scaling Factor you entered. The Vertical grid spacing shows the distance between two grid points on the Y-axis. When you change the scaling factor, the program shows the new horizontal and vertical grid spacing in the dialog.

SimTalk:
ScalingFactor
.topic 0x89031553
To move the selected object up in the sequence of the successors, click Up.
.topic 0x89031554
To move the selected object down in the sequence of the successors, click Down.
.topic 0x880911f4
An Interface object, which you insert into a Frame and connect with a Connector, shows its type here: An Entrance through which MUs enter the Frame or an Exit through which MUs exit the Frame.

SimTalk:
isEntry, isExit
.topic 0x88090fbd
Enter the maximum number of external connections the Interface may have. Depending on the type, any number of Interfaces may have more than one predecessor or successor. The default setting -1 denotes an unlimited number of external connections.

SimTalk:
MaxConnections
.topic 0x88090fc5
Enter the position at which an arriving or leaving Connector is shown at the icon of the Frame. You can enter a value between 0 and 100 percent. Position 0 is either the top or the left hand side at the icon of the Frame, position 100 the bottom or the right hand side at the icon.

SimTalk:
Position
.topic 0x88090fcd
Select the side of the icon of the Frame at which the Interface is to be located: the Top, the Right hand side, the Bottom, the Left hand side of the Frame or depending on the angle. Angle-dependent takes into account the angle between the objects when determining the starting point or the end point of the Connector.

SimTalk:
Side
.topic 0x88191034
Enter the length of the Conveyor. After you inserted it into your simulation model, Plant Simulation shows its length here. The length of the Conveyor and the sum of the lengths of all MUs located on it determine how many MUs the Conveyor can accommodate at any one time. The length of the MUs will only be evaluated, when you enter an unlimited Capacity. When Transfer length is active, the program adapts the graphic, when you change the length of a Conveyor, which only consists of a single straight segment. You can only enter the length, when you deactivate transfer length or when the Conveyor consists of a single straight segment. When the length cannot be exactly displayed in pixels, the program adapts the length of the graphic. If you need to use the exact length, clear transfer length.

SimTalk:
Length

.topic 0x88190f1b
Enter the width of the Conveyor. After you inserted it into your simulation model, Plant Simulation shows its width here.
You can only enter the length, when you deactivate transfer length or when the Conveyor consists of a single straight segment. When the width cannot be exactly displayed in pixels, the program adapts the width of the graphic. If you need to use the exact length, clear transfer length.

SimTalk:
Width
.topic 0x8819100d
Enter the final transport speed of the MUs on the Conveyor. When you change the speed, the program automatically recalculates the Time, and vice versa, provided you deactivated the feature Acceleration. The processing time is the Length divided by the speed. When you activate acceleration, the Conveyor attempts to reach the final speed no matter if a part is located on it or not. A part entering the Conveyor moves with the actual speed of the Conveyor. When the Conveyor currently accelerates, the part will accelerate as well. Or enter -1 for an infinite speed.

SimTalk:
Speed
.topic 0x881e1087
To make the MUs accumulate on the object, select this. This allows the MUs to move front to end to each other, when the exit of the object is Blocked. To make the MUs retain their distance to each other, i.e., make all succeeding MUs stop moving when the preceding part cannot exit the object, clear the check box. When the object is blocked, it stops, i.e., it reduces its speed to 0.

SimTalk:
Accumulating
.topic 0x88190fc0
To make the Conveyor move in reverse against the direction of the material flow, select this. Note that not only the Conveyor itself, but also the MUs moving on the Conveyor, can move forward and in reverse. This means that a part may enter the Conveyor at its exit and leave it at its entrance.

SimTalk:
Backwards
.topic 0x881913c5
To make the Conveyor increase its speed, select this. Then, you can enter the Acceleration with which it speeds up and the Deceleration with which it slows down. The Conveyor also shows the actual Current speed with which it moves. When you change the Speed, the program recalculates the Time and vice versa, when you deactivate acceleration. When you activate acceleration, the Conveyor attempts to reach the final speed no matter if a part is located on it or not. A part entering the Conveyor moves with the actual speed of the Conveyor. When the Conveyor currently accelerates, the part will accelerate as well. To deactivate acceleration, clear the check box.

SimTalk:
AccelerationEnabled
.topic 0x8819107e
The program shows the current speed of the object at the present time here, provided you selected the check box Acceleration.

SimTalk:
CurrentSpeed
.topic 0x88191038
Enter the Acceleration with which the Conveyor increases its speed. You can enter any real number greater than or equal to 0. You can only enter a value for the acceleration after you select the check box Acceleration.

SimTalk:
Acceleration
.topic 0x8819103c
Enter the Deceleration with which the Conveyor slows down. You can enter any real number greater than or equal to 0.
.topic 0x88191079
Enter the time a part takes to cover the empty Conveyor. When you change the Time, the program automatically recalculates the Speed. Or enter 0 as the Time.

SimTalk:
Time
.topic 0x88191196
Select the distance type for the space between the parts. Then enter the actual distance into the text box MU distance. Gap determines the distance between the rear of the preceding part and the front of the succeeding part. Pitch determines the distance between the front of the preceding part and the front of the succeeding part. Minimum Gap determines the minimum distance between the rear of the preceding part and the front of the succeeding part. This setting prevents the Conveyor from stopping and from waiting for new parts and allows it to run dry. Minimum Pitch determines the minimum distance between the front of the preceding part and the front of the succeeding part. This setting prevents the Conveyor from stopping and from waiting for new parts and allows it to run dry.

SimTalk:
MUDistanceType
.topic 0x88191628
Select the MU distance type and then enter the desired distance of the current part to the preceding part which the Conveyor enforces, when the next part enters.

Depending on the setting for MU distance type the MU distance determines for:

Gap the distance between the rear of the preceding part and the front of the succeeding part.

Pitch the distance between the front of the preceding part and the front of the succeeding part.

When no further parts arrive, the Conveyor stops once the distance has been reached. As soon as the next part arrives, it starts to transport parts again. The default value -1 means that the Conveyor does not use the MU distance and parts can enter at any time as the predecessor provides them.

SimTalk:
MUDistance
.topic 0x84ca0655
Click this and select a Method object. Enter the source code of the speed control. The Line/loading space of type Line of the Transporter call the control as soon as they reach their final speed after accelerating or decelerating or when they stop after decelerating.

SimTalk:
SpeedCtrl, LoadBaySpeedCtrl
.topic 0x88200fe5
Enter how many MUs the object can hold in the X-dimension. The capacity is the product of X-dimension times Y-dimension times Z-dimension.

When you decrease the dimension of the object, make sure that no MUs are located on the storage places that will be deleted by this action! Either delete these MUs or move them to another storage place on the smaller loading space.

SimTalk:
XDim
.topic 0x88200fe6
Enter how many MUs the object can hold in the Y-dimension. The capacity is the product of X-dimension times Y-dimension times Z-dimension.

When you decrease the dimension of the object, make sure that no MUs are located on the storage places that will be deleted by this action! Either delete these MUs or move them to another storage place on the smaller loading space.

SimTalk:
YDim
.topic 0x88200f72
Enter how many MUs the object can hold in the Z-dimension. The Z-dimension allows to stack parts on the object. The capacity is the product of X-dimension times Y-dimension times Z-dimension..

When you decrease the dimension of the object, make sure that no MUs are located on the storage places that will be deleted by this action! Either delete these MUs or move them to another storage place on the smaller loading space.

SimTalk:
ZDim

.topic 0x861c0cc5
To open the table of the angles, at which the robot picks the part up or at which it places it, click this. You can view or fine-tune these settings: The name of the predecessor at which the robot picks the part up or the name of the successor onto which the robot deposits the part. The angle between the station in the column Name and the robot.

SimTalk:
setAnglesTable, getAnglesTable
.topic 0x861c0cc7
To open the table of the rotation times, click this. These are the times, which the robot needs to rotate from the station in the leftmost column to the respective stations in the columns to the right and vice versa. Or enter a Time factor with which all times in the table are multiplied. This way you can simulate the robot with different speeds without having to manually change the times in the table.

SimTalk:
setTimesTable, getTimesTable
.topic 0x861c0cc9
Select this, if you want the robot to rotate back to its default position after it has deposited the part. Then, enter the Default angle at which the default position is located.

SimTalk:
GoToDefaultPosition, DefaultAngle
.topic 0x861c0e2f
Enter the time factor with which all times in the Times Table are multiplied. This allows to simulate the robot with different speeds without having to manually change the times in the table.

SimTalk:
TimeFactor
.topic 0x861c0ccb
Enter the angle to which the robot rotates when you selected Go to default position. If you would like the robot to rotate to the side on which the start position is located, add 180° to this angle.

SimTalk:
DefaultAngle
.topic 0x861c0cca
Enter the blocking angle which the robot cannot cross while rotating. This prevents the robot from taking the shortest way. The default setting -1 means that no blocking angle applies and that the robot thus takes the shortest way. You can enter an angle between 0 and 360 degrees.

SimTalk:
BlockingAngle
.topic 0x84ca0c99
Click this and select a Method object. Enter the source code of the target control in which you determine the successor to which the robot transports the part. The robot calls the control as soon as it has picked up the part. As opposed to the exit control, the part is not ready to exit the object yet. You have to set the destination object in the method setDestination. Plant Simulation also calls the control when the robot has deposited the part. In this case you have to set the object at which the robot is going to pick up the next part with the method setDestination. Plant Simulation only calls the target control while unloading when you deactivated the check box Go to default position.

SimTalk:
TargetCtrl
.topic 0x88c71008
Enter the Capacity, i.e., the number of MUs that can stay on the object at any one time. Enter -1 for an infinite capacity, i.e., an unlimited number of stations. Once the capacity is reached, the object does not accept any additional MUs.

SimTalk:
Capacity
.topic 0x88061026
Select how the Sorter sorts the MUs located in it: A Descending sort order moves the part with the highest value, with respect to the sort criterion, first. An Ascending sort order moves the part with the lowest value first.

SimTalk:
Order
.topic 0x884511fb
Select when the Sorter sorts the MUs located in it: On Entry sorts the parts each time when a new part enters. When all MUs are located in the Sorter, the sort criterion is assumed not to change. Thus, select the setting On Entry only when the value of the attribute or the method you use as the sort criterion does not change while a part is located on the Sorter. On Access maintains the sequence of MUs regardless of any sort order changes. After a part enters the sorter or before a part leaves it, it sorts the MUs with the current values of the sort criterion for all MUs.

SimTalk:
TimeOfSort
.topic 0x884511fc
Select the Sort criterion. Depending on the setting you select, the program shows additional drop-down lists and/or text boxes.

SimTalk:
SortCriterion
.topic 0xaf1411f7
Select the sorting category from the left drop-down list. Then, select the sorting criteria from the right list.
.topic 0x884511fd
Select the sorting criteria for the sorting category you selected, from the right drop-down list.

SimTalk:
SortProperty
.topic 0x885d102c
To define your own sort criteria, select the setting Method. The sort criterion is the return value of a user-defined method which the program calls for each part. Within the method you can sort the objects in the Sorter according to two or more attributes.

SimTalk:
SortMethod
.topic 0x884511f6
To sort the MUs according to the sort criteria you defined, click this.

SimTalk:
sort
.topic 0x88080ffb
When you select Blocking, the Source remembers the time at which it was supposed to produce the next MU. It then produces the following MUs at the next possible point in time, i.e., when the MU that was blocked by the successor, was moved on. The Source stops creating parts when the simulation time has reached the Stop time.
When you clear Blocking, the Source creates another MU exclusively at the time of creation you entered.

SimTalk:
Blocking
.topic 0x88080fcc
Select the point in time at which and how the Source produces MUs:

Interval adjustable: It produces the first MU at the Start time. The time of creation designates the Interval between two creation events. It produces the last MU at the Stop time.
If you do not enter a Stop time for this setting, Plant Simulation produces the amount of parts you entered at most. The default value of -1 designates an unlimited number of parts to be produced. Otherwise the Source produces parts until the Stop time is reached and ignores the Amount of parts you entered.
When you select a constant time all MUs are produced at this point in time.

Number adjustable: It produces the number of MUs, which you enter as the Amount. When you activate the check box Generate as batch, the amount does not designate the number of parts, but the number of batches that the Source produces. The times at which the MUs are created are distributed according to the distribution you select for the Interval.
When you select a constant time all MUs are produced at this point in time.

Delivery table: It produces MUs according to the delivery time, the class, the number the name, and the attribute which you enter into the Delivery Table.

Trigger: It produces MUs according to the values that a set of Trigger objects controls.
SimTalk:
TimeOfGeneration
.topic 0x8808118d
Enter the amount of parts (MUs) which the Source produces.
This setting is only possible for the Time of creation > Number Adjustable and Interval Adjustable.
When you do not enter a Stop time for the setting Interval Adjustable, Plant Simulation produces the amount of parts you entered at most. The default value of -1 designates an unlimited number of parts to be produced. Otherwise the Source produces parts until the Stop time is reached and ignores the Amount of parts you entered.
For the setting Interval Adjustable the Source might possibly create more parts than the Amount you entered, when the check box Generate as batch is activated. This is because the lots are produced in their entirety.
For the setting Time of creation > Number Adjustable the value does not designate the amount of MUs but the amount of batches/lots which the Source produces when you activated Generate as batch.

SimTalk:
Number, TimeOfGeneration
.topic 0x8808118e
The Source produces MUs according to the values that one or several Trigger objects control. Click Trigger and enter the name(s) of the Trigger object(s) into the list that opens. Each Trigger in this list sends orders to produce MUs to the Source. Open the Trigger, click the tab Values, make sure that the Trigger type > Input is selected and click Values.

SimTalk:
Trigger
.topic 0x88080fdf
The three settings Interval, Start, and Stop determine the points in time at which the Source produces the parts:
The Start time designates the point in time at which the Source produces the first MU. It produces additional MUs after the time, which you enter as the Interval, has elapsed.
The Stop time designates the point in time at which the Source produces the last MUs. When you enter 0 as the Stop time, the Source produces MUs according to the Amount you entered.
Select a distribution from the drop-down list, and enter the values, which that distribution requires, into the text box. The program shows these values along the top border of the tab.

SimTalk:
Interval
.topic 0x88080fe0
The Start time designates the point in time at which the Source produces the first MU. Select a distribution from the drop-down list, and enter the values, which that distribution requires, into the text box. The program shows these values along the top border of the tab.

SimTalk:
Start
.topic 0x88080fe1
The Stop time designates the time at which the Source does not produce any more MUs. Select a distribution from the drop-down list, and enter the values, which that distribution requires, into the text box. The program shows these values along the top border of the tab.

SimTalk:
Stop
.topic 0x88080fcf
Select which type of MUs and how the Source produces MUs: Constant: It produces one type of MU only. Enter its path into the text box MU. Sequence cyclical: It produces the MUs in a fixed sequence, which you enter into a table. As soon as the Source has processed the sequence, it repeats the production sequence periodically. Sequence: It produces MUs according to the sequence table, whose name you entered into the text box next to Table. As opposed to Sequence cyclical, Sequence processes the sequence only once, not repeatedly. Random: It produces MUs in random frequencies according to the values which you entered into the frequency table. Percentage: It produces MUs in percentages according to the values which you entered into the percentage table.

SimTalk:
MuSelection
.topic 0x881e08b4
The object produces one type of MU only. Enter the path to this type of MU into the text box next to MU.

SimTalk:
Path (Source),
NewMU (Assembly),
MUPath (Portioner)
.topic 0x88081187
Enter the path to the frequency table, to the sequence table, or to the percentage table according to which the Source produces the MUs.

SimTalk:
Path
.topic 0x88081190
To make the Source produce the number of MUs, which you entered into the cell Number of the Table in a single lot, select this. When you select Number adjustable as the time of creation, the amount does not designate the number of parts, but the number of batches that the Source produces. Then the Source produces the entire set of parts all at once at the given start time and attempts to move all of the parts on to the next object in a single lot. To make the Source produce the MUs as a sequence of individual parts, clear the check box.

SimTalk:
GenerateAsBatch
.topic 0x892f1195
To write all events, for which the Source produced MUs during a simulation run, into a table, select this. Then you can click Open to open the creation table.

SimTalk:
CreationTableActive, creationTable
.topic 0x892f1194
To open the creation table of the Source, when you selected the check box Creation table, click Open.

SimTalk:
creationTable
.topic 0x88191035
Enter the Length of the Track. After you inserted it, Plant Simulation shows its length here. The length of the Track and the sum of the lengths of all MUs located on it determine how many MUs it can accommodate at any one time. When Transfer length is active, the program adapts the graphic, when you change the length of a Track, which only consists of a single straight segment. When the length cannot be exactly displayed in pixels, the program adapts the length of the graphic. If you need to use the exact length, clear transfer length. You can only enter the length, when you deactivate transfer length or when the Track consists of a single straight segment.

SimTalk:
Length
.topic 0x88101027
Click this and select a List object in the dialog Select Object. Enter all destination objects into this List object, which the Track can reach, when the Transporter moves in reverse on it.

SimTalk:
BwDestList
.topic 0x8810102a
Click this and select a List object. Enter all destination objects into this List object, which the Track can reach, when the Transporter drives forward on it.

SimTalk:
FwDestList
.topic 0x882a1210
Enter the length of the Turnplate. After you inserted it, Plant Simulation shows its length here. The Turnplate only rotates parts, which it can accommodate in their entirety, meaning that they are shorter or as long as the value you enter here. When Transfer length on the Tab Curve is active, the program adapts the graphic of the Turnplate, when you change the length. When the length cannot be exactly displayed in pixels, the program adapts the length of the graphic. If you need to use the exact length, clear transfer length.

SimTalk:
Length
.topic 0x882a1212
Enter the speed with which the Turnplate conveys the part, while it is located on the plate.

SimTalk:
Speed
.topic 0x882a1211
Enter the time it takes the Turnplate to rotate by 90 degrees. To rotate the part immediately, without using up any time at all, enter a rotation time of 0.

SimTalk:
RotationTimePer90Degrees
.topic 0x882a1215
Select the strategy according to which the Turnplate rotates the part: Angle rotates the part according to the rotation Angle you enter. MU Attribute rotates the part according to a built-in or a user-defined attribute of the part. Click Open List and enter the name of the attribute of the part, the value of the attribute, and the rotation angle. MU Name rotates the part according to its name. Click Open List and enter the name of the part and the rotation angle. Method rotates the part according to the strategy method. Within this method you have to call the method rotatePart with the rotation angle as parameter. Enter the name of the method into the text box Strategy method.

SimTalk:
Strategy
.topic 0x882a1213
Enter the angle to which the Turnplate rotates the part. The rotation angle should be a multiple of 90. If you enter an angle other than that, Plant Simulation rounds this angle to the next angle that is divisible by 90. Or enter a value greater than 360 degrees as long as it is divisible by 90. This way the turnplate can rotate the part several times around its own axis to simulate packing machines. By default the turnplate rotates the part 90 degrees clockwise. To rotate the part counter-clockwise, enter negative angles.

SimTalk:
Angle
.topic 0x882a1216
Select the data type of the attribute that determines the rotation angle by which the Turnplate rotates the part. This applies to Strategy > MU Attribute.

SimTalk:
AttributeType
.topic 0x882a1217
To open the rotation angles list for the parts, click this. For the Strategy > MU Attribute you can enter the name of the attribute of the part, the value of the attribute, and the rotation angle. For the Strategy > MU Name you can enter the name of the attribute of the part and the rotation angle.

SimTalk:
setAttributeList, getAttributeList
.topic 0x882a1214
Click this and select a Method object. Enter the source code of the strategy method which rotates the part around the rotation angle which you specify. The Turnplate calls the control for the Strategy > Method as soon as the booking point of the part is located on the center of rotation of the Turnplate. Within this method you have to call the method rotatePart with the rotation angle as parameter.

SimTalk:
StrategyCtrl
.topic 0x882a1203
Enter the length of the Turntable. After you inserted it, Plant Simulation shows its length here. The Turntable only rotates parts, which are shorter or as long as the value, which you enter here. When Transfer length on the Tab Curve is active, the program adapts the graphic of the Turntable, when you change the length. When the length cannot be exactly displayed in pixels, the program adapts the length of the graphic. If you need to use the exact length, clear transfer length.

SimTalk:
Length
.topic 0x882a1193
Enter the position of the fulcrum around which the Turntable rotates. You can enter a value between 0 and the length of the Turntable. 0 denotes the point at which you start inserting the Turntable.

SimTalk:
RotationPoint
.topic 0x882a1191
Enter the speed with which the Turntable transports the part, while it is located in the table. Or enter -1 for an infinite speed.

SimTalk:
Speed
.topic 0x882a1190
Enter the time which it takes the Turntable to rotate by 90 degrees.

SimTalk:
RotationTimePer90Degrees
.topic 0x882a1199
Select, when the Turntable rotates towards its target object: When the part has completely entered the Turntable. When the part has reached the rotation point/the fulcrum in the table. When the part is located in the center of the Turntable, i.e., when both ends of the part have the same distance from the edges of the turntable. When you want the turntable to not rotate automatically, but only when the part has reached a user-defined sensor, select User-defined with Sensor. In the sensor control, you have to tell the turntable to call the method setDestination.

SimTalk:
RotateWhen
.topic 0x882a1194
Select this, if you want the Turntable to return to its default position, when the part has left the Turntable and when no new part is ready to be rotated. Then, enter the default angle at which the default position is located.

SimTalk:
GoToDefaultPosition, DefaultAngle
.topic 0x882a1195
Enter the angle to which the Turntable rotates, when you selected Go to default position. The default position is located at this angle. If you would like the Turntable to rotate to the side on which the start point is located, add 180 degrees to this angle.

SimTalk:
DefaultAngle, GoToDefaultPosition
.topic 0x882a1198
Type in the name of the user-defined attribute of the part, which triggers its rotation, so that it exits the table driving backwards. This attribute can be an attribute of type boolean or a Method which returns a value of type boolean. This setting will only be evaluated, when you select Any as the side in the Exit Angle Table.

SimTalk:
MURotationAttribute
.topic 0x882a1200
To open the table of the entry angles at which the MUs move onto the Turntable, click this. You can view or fine-tune these settings: The number of the predecessor. The name of the predecessor. The angle at which the Connector from this predecessor connects to the Turntable. At which side it turns toward the predecessor. When you select Start Point, the Turntable turns with the side, at which you started inserting the Turntable, towards this predecessor. When you select End Point, the Turntable turns with the side, at which you finished inserting the Turntable, towards this predecessor. When you select Any, the Turntable calculates the smallest angle and turns with this calculated side towards this predecessor.

SimTalk:
setEntryAngles, getEntryAngles
.topic 0x882a1197
To open the table of the exit angles at which the parts leave the Turntable, click this. You can view or fine-tune these settings: The number of the successor. The name of the successor. The angle the Connector from the Turntable connects to this successor. At which side it turns towards the successor. When you select Start Point, the Turntable turns with the side, at which you started inserting the Turntable towards this successor. When you select End Point, the Turntable turns with the side, at which you finished inserting the Turntable towards this successor. When you select Any, the Turntable calculates the smallest angle and turns with this calculated side towards this successor. With this setting the part can leave backwards or forwards, depending on the side which can be reached with the smallest angle. When you select MU keeps Direction, the Turntable turns this side of the Turntable towards this successor which makes the part keep its direction. When you select MU leaves backwards, the Turntable turns this side of the Turntable towards this successor so that the Turntable turns the part around and it leaves moving backwards.

SimTalk:
setExitAngles, getExitAngles
.topic 0x84ca0c44
Click this and select a Method object. Enter the source code of the target control in which you determine the successor to which the MU is moved. The Turntable calls the control as soon as the part has completely moved onto the turntable or has reached the center of rotation. As opposed to the exit control, the part is not ready to exit the object yet. You have to set the destination object with the method setDestination.

SimTalk:
TargetCtrl
.topic 0x892f1196
Shows the portion of the statistics collection period during which the object was rotating Empty, i.e., without moving a part.

SimTalk:
statRotationEmptyPortion
.topic 0x892f1197
Shows the portion of the statistics collection period during which the object was rotating while moving a part.

SimTalk:
statRotationLoadedPortion
.topic 0x889b1034
Enter the Length of lane A of the TwoLaneTrack. After you inserted it, Plant Simulation shows its length here. The length of the lanes of the TwoLaneTrack and the sum of the lengths of all Transporters located on it determine how many Transporters it can accommodate at any one time. Each lane of the TwoLaneTrack may have its own length to realistically model the length of the lanes, when the TwoLaneTrack turns a corner. In that case the outside lane is longer than the inside lane. When Transfer length is active, the program adapts the graphic, when you change the length of lane A of a TwoLaneTrack, which only consists of a single straight segment. When the length cannot be exactly displayed in pixels, the program adapts the length of the graphic. If you need to use the exact length, clear transfer length. You can only enter the Length of lane A, when you deactivate transfer length or when the TwoLaneTrack consists of a single straight segment.

SimTalk:
A.Length, A.occupiedLength
.topic 0x889b0fb9
To close the entrance of lane A, select this. The TwoLaneTrack will finish transporting the Transporters already located on it. It does not accept any additional Transporters and enters those into the Forward Blocking List of lane A. Transporting starts again, when you clear the check box. The first Transporter in the Forward Blocking List of lane A is going to be moved on first.

SimTalk:
A.EntranceLocked
.topic 0x889b0fc3
To close the exit of lane A, select this. The TwoLaneTrack prevents Transporters from being moved on to the successors in the material flow and enters them into the Exit Blocking List of lane A of the TwoLaneTrack. Once the exit is unlocked again, the TwoLaneTrack moves the first Transporter in the Exit Blocking List of lane A on to its successor.

SimTalk:
A.ExitLocked
.topic 0x889b104d
Enter the Length of lane B of the TwoLaneTrack. After you inserted it, Plant Simulation shows its length here. The length of the lanes of the TwoLaneTrack and the sum of the lengths of all Transporters located on it determine how many Transporters it can accommodate at any one time. Each lane of the TwoLaneTrack may have its own length to realistically model the length of the lanes, when the TwoLaneTrack turns a corner. In that case the outside lane is longer than the inside lane. When Transfer length is active, the program adapts the graphic, when you change the length of lane B of a TwoLaneTrack, which only consists of a single straight segment. When the length cannot be exactly displayed in pixels, the program adapts the length of the graphic. If you need to use the exact length, clear transfer length. You can only enter the length of lane B, when you deactivate transfer length or when the TwoLaneTrack consists of a single straight segment.

SimTalk:
B.Length, B.occupiedLength
.topic 0x889b15d0
To close the entrance of lane B, select this. The TwoLaneTrack will finish transporting the Transporters already located on it. It does not accept any additional Transporters and enters those into the Forward Blocking List of lane B. Transporting starts again, when you clear the check box. The first Transporter in the Forward Blocking List of lane B is going to be moved on first.

SimTalk:
B.EntranceLocked
.topic 0x889b15d1
To close the exit of lane B, select this. The TwoLaneTrack prevents Transporters from being moved on to the successors in the material flow and enters them into the Exit Blocking List of lane B of the TwoLaneTrack. Once the exit is unlocked again, the TwoLaneTrack moves the first Transporter in the Exit Blocking List of lane B on to its successor.

SimTalk:
B.ExitLocked
.topic 0x889b10af
Enter the track pitch between lane A and lane B. The track pitch is the distance between the center lines of the two lanes of the two-lane track.

SimTalk:
TrackPitch
.topic 0x889b10c8
Select the side of the TwoLaneTrack on which traffic moves: Right-hand traffic or left-hand traffic.

SimTalk:
Traffic
.topic 0x889b15d3
Click this and select a List object. Enter all destination objects into this List object, which the TwoLaneTrack can reach, when the Transporter drives forward on lane A. This forward destination list of lane A concurrently is the backward destination list of lane B.

SimTalk:
DestListA
.topic 0x889b15d4
Click this and select a List object. Enter all destination objects into this List object, which the TwoLaneTrack can reach, when the Transporter drives forward on lane B. This forward destination list of lane B concurrently is the backward destination list of lane A.

SimTalk:
DestListB
.topic 0x8f360f37
Select how the material and the amount of the fluid is to be created:

By a fixed material and a fixed amount for every MU. For this setting you can enter the Material and the Amount per MU.

By the MU Name depending on the MU names that are defined in the Mapping table.

By the MU Attribute, for which you can enter the Material attribute and the Amount attribute of the MU.

The name of each material that is to be used has to be defined in the MaterialsTable.

SimTalk:
FluidDependsOn
.topic 0x88aa0ec5
Enter the name of the material that the DePortioner creates. It applies when you select Fixed under Fluid depends on.

SimTalk:
Material
.topic 0x8f360f43
Enter the total amount in liters of the fluid which the DePortioner creates. It applies when you select Fixed under Fluid depends on.

SimTalk:
AmountPerMU
.topic 0x8f360f3a
Enter the name of the table file that contains the MU Name of the arriving MU, and the Material and the Amount of the fluid, which the DePortioner creates. It applies when you select MU Name under Fluid depends on.

SimTalk:
MappingTable
.topic 0x8f360f3f
Enter the name of the Material attribute, which defines the material which the DePortioner creates. It applies when you select MU Attribute under Fluid depends on.

SimTalk:
AttrNameMaterial
.topic 0x8f360f40
Enter the name of the Amount attribute, which defines the amount of the material which the DePortioner creates. It applies when you select MU Attribute as the definition method of the Fluid depends on.

SimTalk:
AttrNameAmount
.topic 0x887b0f05
Shows the current inflow rate, i.e., the amount of liters of the material which flows into the fluid object.

SimTalk:
currentInFlowrate
.topic 0x888b0eda
Shows the amount of material that flowed through the object.

SimTalk:
statThroughput
.topic 0x888b0edb
Shows the amount of material that the FluidDrain drained from the installation in an hour while the FluidDrain was available.

SimTalk:
statThroughputPerHour
.topic 0x888b0edc
Shows the amount of material that the FluidDrain drained from the installation in a day while the FluidDrain was available. This is the value of the throughput per hour multiplied with 24.

SimTalk:
statThroughputPerDay
.topic 0x888b0ed9
Shows the maximum flow rate, i.e., the amount of liters of the material per second that flowed through the FluidDrain.

SimTalk:
statMaxFlowRate
.topic 0x88ab12db
Enter the outflow rate with which the material flows out of the object and flows through the objects of type Pipe to the next object in the flow of materials.
If the object has several successors, it passes this outflow rate on to each of the successors.

SimTalk: OutflowRate
.topic 0x88aa0ec5
Enter the name of the material, i.e., the ingredient which the FluidSource is to produce and pass on objects of type Mixer or Tank. These then create the intermediate or finished product by mixing the ingredients.

SimTalk: Material
.topic 0x88aa12ca
Click this and select the MaterialsTable in the dialog Select Object. The MaterialsTable object contains the data of the different materials which the fluid object can produce.
Or you can select the MaterialsTable in a Frame, drag it to the text box and drop it there.

SimTalk:
MaterialsTable
.topic 0x88aa0f06
Shows the current outflow rate, i.e., the amount of liters of the material that flows out of the fluid object per second.

SimTalk:
currentOutFlowrate
.topic 0x888b0ed7
Shows the amount of material that flowed out of the FluidSource.

SimTalk: statAmount
.topic 0x887b0ee2
Enter the volume of the Mixer, i.e. the space that is available for the indredients or the product respectively in the mixing container.

SimTalk:
Volume
.topic 0x88ab0f00
Enter the name of the intermediate or of the finished product which the Mixer is to produce by mixing the ingredients.

SimTalk:
Product
.topic 0x88ab0eec
Enter the amount of the intermediate or of the finished product which the Mixer is to produce by mixing the ingredients.
The default value -1 means that the finished product fully exploits the volume of the Mixer.

SimTalk: ProductAmount
.topic 0x887b0f07
Shows the current fill level of the container in which the Mixer transmutes the materials.

SimTalk:
currentFillLevel
.topic 0x887b0f53
Click this and select a Method object. This Method object contains the source code of the ingredient complete control.
Plant Simulation activates the ingredient complete control when an ingredient of the recipe has completely arrived in the Mixer.

SimTalk:
IngredientCompleteCtrl
.topic 0x887b0eed
Shows the current amount of material that is located in the container of the fluid object at the moment.

SimTalk:
currentAmount
.topic 0x8ec312da
To open the entrance of the Pipe so that materials can flow through it, select this. This way you can model a valve to open and to close the Pipe. To close the Pipe, clear the check box.

SimTalk: PipeOpened
.topic 0x8ec30f30
For a Pipe that is located directly after a FluidSource/Tank/Mixer, you can enter the outflow rate with which the material flows out of the Pipe to the next object in the flow of materials. The default value -1 denotes that the Pipe uses the same outflow rate as its predecessor.
With this setting you can create the effect that not all of the succeeding Pipes connected to a FluidSource/Tank/Mixer have to have the same outflow rate. If the predecessor of the Pipe is another Pipe, Plant Simulation ignores the value.
The outflow rate is the amount of liters of the material that flows off in a second.
SimTalk:
OutflowRate
.topic 0x887b0f09
This field shows the name of the material that currently flows through the Pipe.

SimTalk:
currentMaterial
.topic 0x88ac0f02
Enter the total amount of the material which the Portioner is to transmute into the MU.

SimTalk: AmountPerMU
.topic 0x88ac0f01
Enter number of the Predecessor object which delivers the material to the Portioner.

SimTalk: PrecedessorNumber
.topic 0x88ac0f08
This field shows the current filling time, i.e., the time it takes the Portioner to transmute the materials into the MU.

SimTalk:
currentFillingTime
.topic 0x882408d6
Click this and select a Method object. Enter the source code of the importer request control in which you programmed how the Broker requests importers. The program calls the control, whenever the Broker receives a request or when it would handle the request again when an Exporter registers as being available. In the source code of the Method you yourself have to make sure that the request is taken care of, e.g. with the method engage. With this control you can model your own assignment strategies.

SimTalk:
ImpRequestCtrl
.topic 0x882408d7
Click this and select a Method object. Enter the source code of the exporter request control in which you programmed how the Broker requests Exporters. The program calls the control, whenever an Exporter registers as being available with its Broker, so that it may be assigned a new importer. In the source code of the Method you yourself have to make sure that the request is taken care of, e.g. with the method engage. With this control you can assign a specific importer to the Exporter.

SimTalk:
ExpRequestCtrl
.topic 0x880e111d
Shows the actual number of open requests.

SimTalk:
openRequests
.topic 0x880e111f
Shows the total number of open requests.

SimTalk:
statOpenRequests
.topic 0x880e111e
Shows the number of satisfied requests.

SimTalk:
satisfiedRequests
.topic 0x880e1120
Shows the total number of satisfied requests.

SimTalk:
statSatisfiedRequests
.topic 0x880e1125
Shows the amount of available capacities.

SimTalk:
openCapacity
.topic 0x880e1127
Shows the total amount of open capacities.

SimTalk:
statOpenCapacity
.topic 0x880e1126
Shows the amount of brokered capacities.

SimTalk:
mediatedCapacity
.topic 0x880e1128
Shows the total amount of brokered capacities.

SimTalk:
statMediatedCapacity
.topic 0x880e1026
To collect statistics data of the Broker, select this. To deactivate statistics collection, clear the check box.

SimTalk:
BrokerStatOn
.topic 0x87e2110d
To open the service statistics table, which shows the Dwelling Time and the Mediation Time per service, click this.

SimTalk:
serviceStat
.topic 0x880a15c9
When the check box is deactivated and the Exporter provides services for an importer, Plant Simulation does not interrupt the corresponding process of the importer at the beginning of a failure. The corresponding event thus persists. During a failure new requests to the Exporter remain unsatisfied. When you activate the check box and the Exporter provides services for an importer, Plant Simulation interrupts the corresponding process for the duration of the failure. When Plant Simulation interrupts processing, for example through a failure of the Exporter, Plant Simulation deletes the respective Out event and adds it anew at the end of the failure according to the remaining processing time.

SimTalk:
FailServices
.topic 0x88c7100a
Enter an integer value for the Priority of the Exporter. The higher the value that you enter, the higher is the priority, i.e., the sooner the job will get done. This means that the program processes a service with priority 10 before it processes a service with priority 1.

SimTalk:
Priority
.topic 0x88c71009
Enter the Capacity of the Exporter. The capacity is a value greater than or equal to zero and designates the maximum number of services it can export.

SimTalk:
Capacity
.topic 0x880a100c
Click this and select the Broker, who assigns the services to the importer, in the dialog Select Object. You might also type in .Models.Frame.MyBroker. The program enters the Exporter into the list of administered Exporters, which this Broker manages. To view them, select View > Exporters.

SimTalk:
BrokerPath
.topic 0x88061024
Click this and select a Method object. It controls how the Exporter/Worker handles the order. The order control is called whenever the Exporter/Worker is assigned to an importer. The Method is defined by two parameters, which characterize the importer: The parameter of data type object designates the importer. The parameter of data type integer designates its type: 0 designates the failure/remove failure-importer, 1 the set-up-importer, 2 the processing-importer, and 3 the transport-importer.

SimTalk:
OrderCtrl
.topic 0x88061025
Click this and select a Method object. It controls how the Exporter/Worker releases the order. The Exporter/Worker calls the release control as soon as an importer releases the object. When the control is called, the Exporter/Worker has already left its importer. You yourself have to make sure that the Exporter/Worker is assigned new importers, for example with the method findNewImporter. In this case the Exporter/Worker will not automatically register as being available with its Broker. The method is defined by two parameters, which characterize the importer: The parameter of data type object designates the importer proper. The parameter of data type integer designates its type: 0 designates the failure/remove failure-importer, 1 the set-up-importer, 2 the processing-importer, and 3 the transport-importer.

SimTalk:
ReleaseCtrl
.topic 0x880b15df
Shows the portion of set-up time of the services of the overall statistics time of the Exporter, weighted with the capacity. The overall statistics time is the statistics collection period without the unplanned time and the paused time.

SimTalk:
statServicesSetupPortion
.topic 0x880b15db
Shows the portion of the processing time of the services of the overall statistics time of the Exporter, weighted with the capacity. The overall statistics time is the statistics collection period without the unplanned time and the paused time.

SimTalk:
statServicesWorkingPortion
.topic 0x880b15dc
Shows the portion of the repairing time of the overall statistics time of the Exporter, weighted with the capacity. The overall statistics time is the statistics collection period without the unplanned time and the paused time.

SimTalk:
statServicesRepairingPortion
.topic 0x880b15dd
Shows the portion of the waiting time of the services for an importer of the overall statistics time of the Exporter, plus the time the services spent waiting for a part at the importer, weighted with the capacity. The overall statistics time is the statistics collection period without the unplanned time and the paused time.

SimTalk:
statServicesWaitingPortion, statServicesWaitingImpPortion, statServicesWaitingMUPortion
.topic 0x880b15c4
Shows the portion of the failed time of the services of the overall statistics time of the Exporter, weighted with the capacity. The overall statistics time is the statistics collection period without the unplanned time and the paused time.

SimTalk:
statServicesFailedPortion
.topic 0x880b15de
Shows the portion of the statistics collection period during which the Exporter was operational, weighted with the capacity. The overall statistics time is the statistics collection period without the unplanned time and the paused time.

SimTalk:
statExporterOperationalPortion
.topic 0x880b15c1
Shows the portion of the statistics collection period during which the Exporter was paused.

SimTalk:
statExporterPausedPortion
.topic 0x880b15c3
Shows the portion of the statistics collection period during which the Exporter was unplanned.

SimTalk:
statExporterUnplannedPortion
.topic 0x880b15da
Shows the portion of the statistics collection period during which the Exporter was failed.

SimTalk:
statExporterFailedPortion
.topic 0x880b113d
Shows the capacity that is available at the moment.

SimTalk:
freeCapacity
.topic 0x880b0efd
Shows the capacity that is brokered at the moment.

SimTalk: mediatedCapacity
.topic 0x880b0efe
Shows the sum of the capacities that are brokered at the moment.

SimTalk: statSumMediatedCapacity
.topic 0x880b113e
Shows the sum of the released capacity that the Exporter placed with any importer.

SimTalk:
statSumFreeCapacity
.topic 0x880b112d
Shows the minimum capacity that is available. When the Exporter did not collect any valid value yet, the tab shows -1.

SimTalk:
statMinFreeCapacity
.topic 0x880b112e
Shows the maximum capacity that is available. When the Exporter did not collect any valid value yet, the tab shows -1.

SimTalk:
statMaxFreeCapacity
.topic 0x880b112f
Shows the minimum occupied capacity. When the Exporter did not collect any valid value yet, the tab shows -1.

SimTalk:
statMinMediatedCapacity
.topic 0x880b1130
Shows the maximum occupied capacity. When the Exporter did not collect any valid value yet, the tab shows -1.

SimTalk:
statMaxMediatedCapacity
.topic 0x880b1006
To collect statistics data of the Exporter, select this. To deactivate statistics collection, clear the check box.

SimTalk:
ExpStatOn
.topic 0x883c117d
Click this and select a Method object. Enter the source code of the available control of the Exporter and the Worker. Plant Simulation calls it, whenever the Exporter or the Worker changes its state to available.

SimTalk:
AvailableCtrl
.topic 0x883c117e
Click this and select a Method object. Enter the source code of the not-available control of the Exporter and the Worker. Plant Simulation calls it, whenever the Exporter or the Worker changes its state to not available.

SimTalk:
NotAvailableCtrl
.topic 0x892d15e5
Enter the length of the FootPath. After you inserted it, Plant Simulation shows its length here. The FootPath can accommodate any number of Workers, as they themselves do not have a length. A Worker enters the FootPath at position 0 and exits it after covering the length you enter. When Transfer length is active, the program adapts the graphic, when you change the length of a FootPath, which only consists of a single straight segment. When the length cannot be exactly displayed in pixels, the program adapts the length of the graphic. If you need to use the exact length, clear transfer length. You can only enter the length, when you deactivate transfer length or when the FootPath consists of a single straight segment.

SimTalk:
Length
.topic 0x8db60db7
To activate the LockoutZone, select this. It then creates failures and stops the processing operations of all assigned Objects, when one of these stations fails. To deactivate it, clear the check box.

SimTalk:
Active
.topic 0x8dbb0dbc
Click this and select a Method object. Enter the source code of the stop control. The LockoutZone calls the stop control when one of the stations assigned to it fails. The anonymous identifier @ designates the triggering station, the anonymous identifier ? designates the LockoutZone.

SimTalk:
StopCtrl
.topic 0x8dbb0dbd
Click this and select a Method object. Enter the source code of the resume control. The LockoutZone calls the resume control when all failures of the assigned stations were removed and the stations can thus continue processing parts.

SimTalk:
ResumeCtrl
.topic 0x8dbb0dbe
Select the stop mode: Stop immediately stops the processing operations of all stations that are part of the LockoutZone as soon as one of the stations assigned to it fails. Note that none of the other stations in the model are stopped! Within this period of time additional failures can take place for the assigned stations, several failures of differing stations can thus overlap. The stations only start processing parts again after all failures were removed. They then only use up the remaining processing time. Stop when service arrives only stops the stations assigned to the LockoutZone when the repair services, which the failed station requested, are assigned. Depending on your modeling situation this can be at a different point in time. If you model footpaths on which the Worker walks to the station, Plant Simulation considers the Worker as received once he has reached the station. For Exporters or Workers who can be beamed, the service is considered to be received once the broker has assigned the service. This corresponds to the behavior of the receive control.

SimTalk:
StopMode
.topic 0x8dbe0dd8
Shows the portion of the statistics collection period during which the stations were stopped by a LockoutZone in percent.

SimTalk:
statStoppedPortion
.topic 0x8dbe0dc1
Shows how often the LockoutZone stopped the stations.

SimTalk:
statStoppedCount
.topic 0x8dbe0dc7
Shows the total time during which the LockoutZone stopped the processing operations of the assigned stations.

SimTalk:
statStoppedSum
.topic 0x8dbe0dc9
Shows the mean time during which the LockoutZone stopped the processing operations of the assigned stations.

SimTalk:
statStoppedMu
.topic 0x8dbe0dcb
Shows the standard deviation of the time during which the LockoutZone stopped the processing operations of the assigned stations.

SimTalk:
statStoppedDelta
.topic 0x8dbe0dd4
Shows the mean time of the intervals during which the LockoutZone stopped the processing operations of the assigned stations.

SimTalk:
statStoppedIntervalMu
.topic 0x8dbe0dd6
Shows the standard deviation of the intervals during which the LockoutZone stopped the processing operations of the assigned stations.

SimTalk:
statStoppedIntervalDelta
.topic 0x88d214bd
To make your facility work in shifts, select this. To deactivate shifts, clear the check box.

SimTalk:
Active
.topic 0x88d5148d
Before you can enter data into the table on the tab, click the toggle button Inheritance, so that it is deselected.

.topic 0x88931591
Enter the efficiency in percent with which the Worker works. It determines how fast the Worker performs the task assigned to him: With an efficiency of 100 percent he requires the exact processing time, which you entered. With an efficiency of 200 percent he requires half of the processing time, which you entered. With an efficiency of 50 percent he requires twice the processing time, which you entered.

SimTalk:
Efficiency
.topic 0x88931571
Enter the speed with which the Worker walks on the FootPath to the designated Workplace at the Workstation.

SimTalk:
Speed
.topic 0x889312e4
Enter the name of the shift during which the Worker works. When you do not enter a specific shift on the Tab Shift Times of the ShiftCalendar, the Worker works during all shifts defined in this ShiftCalendar.

SimTalk:
Shift
.topic 0x880a1011
To open a list, into which you enter the names of the services, which the Exporter/Worker provides, click this. Enter the name of the service into the cell. The Exporter/Worker attempts to provide the services in the order in which you enter them into the list. You might enter drilling, milling, turning, etc. If you want the Worker to provide additional services, you can enter these services into the Creation Table.

SimTalk:
services
.topic 0x88931574
Click this to deactivate Inheritance. Only then you can enter data into the list.
.topic 0x88931575
Here the Worker who carries a part shows the brokered or the assigned service. For the loading time you can query this service with the method getExportedServices.
.topic 0x86160c7c
Shows the portion of the transporting time from Workplace to Workplace of the services of the overall statistics time of the Worker. The overall statistics time is the statistics collection period without the unplanned time and the paused time.

SimTalk:
statServicesTransportingPortion
.topic 0x86160c7e
Shows the portion of the time of the services of the overall statistics of the Worker spent for getting to the Workplace or back to the WorkerPool to get the next job order. The latter only applies when you select Get job orders in the pool only. The overall statistics time is the statistics collection period without the unplanned time and the paused time.

SimTalk:
statServicesEnRouteToJobPortion
.topic 0x86160bc4
Shows the distance which the instance of the Worker traveled from the Workerpool to the Workplaces attached to the stations and between the stations.

SimTalk:
statTraveledDistance
.topic 0x8920156d
Click this to deactivate Inheritance. Only then you can enter data into the table.
.topic 0x8920156c
To open the table, into which you enter information pertaining to the Workers to be created and inserted into your model, click this. You can enter up to 30 different types of additional services into the columns to the right of Additional Services. Or leave gaps between the services in the table. This way you can enter identical services one below the other, even when you want some Workers to not provide these services.

SimTalk:
setCreationTable, getCreationTable
.topic 0x892012e5
To make the Worker get new work orders for performing a service at a station in the WorkerPool only, select this. When you clear the check box, new orders can be assigned to the Worker anywhere while he walks on a FootPath.

SimTalk:
GetJobOrdersInPoolOnly
.topic 0x89201604
Select the travel mode of the Worker:

Move freely within area

The Worker moves freely within the area of the simulation model avoiding the obstacles, which you defined in the 3D-Viewer.

Walk along footpaths Fußwegen

The Worker walks on the footpaths, which you inserted between the stations/workplaces, to the station at which he performs his job.

Beam to workplace

The Worker is going to be beamed to the assigned workplace instantaneously when he cannot get to this workplace on a footpath.

SimTalk:
WorkersTravelMode
.topic 0x89201605
To make the Worker do his job from his current location, when there is no free Workplace available at the station, to which he was assigned, select this. When you clear the check box, the program shows an error message.

SimTalk:
WorkersCanWorkRemotely
.topic 0x89201611
Click this and select the parts buffer into which the Worker deposits the parts he could not deliver, when he walks back to the WorkerPool at the end of his shift. The parts buffer can be any one of the material flow objects, which accepts parts. When you did not assign a parts buffer to the WorkerPool, Plant Simulation shows a warning and stops the simulation. When the next shift starts, Plant Simulation treats the parts in the parts buffer according to the exit strategy you selected for the parts buffer. When you select Carry part away, the carrying Worker requests the service, which you entered.

SimTalk:
PartsBuffer
.topic 0x86e106ea
Click this and select a Method object into which you entered the source code of the entrance control. Plant Simulation activates the entrance control once the Worker has entered the object.

SimTalk:
EntranceCtrl
.topic 0x86e106eb
Click this and select a Method object into which you entered the source code of the exit control. Plant Simulation activates the exit control once the Worker has left the object.

SimTalk:
ExitCtrl
.topic 0x887f159b
Click this and select the Station, to which you want to assign the Workplace. This station is a material flow object that supports an importer, e.g. Station/ParallelStation/AssemblyStation/ DismantleStation. To automatically enter the Station, drag the Workplace close to a side of the material flow object, which you want to use as the Station.

SimTalk:
Station
.topic 0x887f1599
First, click this to deactivate Inheritance. Only then you can enter data into the list.
.topic 0x887f1598
To open the list into which you enter the services, which the Workplace supports, click this. Enter an expression of your choice into the cell, and click Apply. You might enter different names for the different services, such as drilling, milling, turning, etc. or group them by name. When you do not enter any services into the list, the Worker can execute any service on this Workplace. When you do not insert a Workplace, when no Workplace is present that supports this service, or when all Workplaces that support this service are occupied, the program transports the Worker to the work station itself, where he will perform his task.

SimTalk:
supportedServices
.topic 0x887f15bb
To make the Worker stay at the Workplace after completing his job, select this. If you clear the check box, he returns to the WorkerPool immediately after finishing his job.

SimTalk:
WorkerStaysHere
.topic 0x8e280e2a
The loading time is the time it takes the Worker for picking up a part at a station. After the loading time has elapsed, the Worker waits for the delay time to pass if he still has carrying capacity. If not, he immediately carries the part to the target station and places it there. Select a distribution, and enter the values, which that distribution requires, into the text box. The program shows these values along the top border of the tab. Or enter a constant time (Const). When you select the Formula distribution, you can enter a numeric expression or the name of a Method. You can use the anonymous identifier @ to access the part for which the loading time applies. The anonymous identifier ? points to the Workplace. You can access the Worker with ?.cont.

SimTalk:
LoadingTime
.topic 0x8e280e29
The unloading time is the time it takes the Worker for placing the part he picked up at another station onto the target station. Select a distribution, and enter the values, which that distribution requires, into the text box. The program shows these values along the top border of the tab. Or enter a constant time (Const). When you select the Formula distribution, you can enter a numeric expression or the name of a Method. You can use the anonymous identifier @ to access the part for which the unloading time applies. The anonymous identifier ? points to the Workplace. You can access the Worker with ?.cont.

SimTalk:
UnloadingTime
.topic 0x882110aa
The MU shows the unique identifying number of each instance of the MU class next to Number. The Source assigns this number, when it creates the MU. You cannot change this number! The combination of MU class, Name and Number enables Plant Simulation to uniquely identify and access the instance of a mobile object, for example .MUs.Transporter:107053.

SimTalk:
getNo
.topic 0x882110ab
The conveying direction of Part and Container on the material flow object can be either of these: Forward. The part moves with its front in the direction of motion of the material flow. Lateral right. The part moves with its right hand side in the direction of motion. Backward. The part is turned 180° and moves backwards against the direction of motion. Lateral left. The part moves with its left hand side in the direction of motion. We advise against manually changing the conveying direction, but to let AngularConverter/Turntable do that.

SimTalk:
ConveyingDirection
.topic 0x882015fc
Enter the length of the mobile object. The length-oriented objects use the length to determine how many MUs they can hold.

SimTalk:
MULength
.topic 0x882010a7
Enter the location of the booking point of the mobile object when it is conveyed lengthwise. This value is the distance from booking point 0, which is located at the front of the MU, in the direction of motion. You can enter a relative value between 0 and 1. Plant Simulation uses it, when the Conveying direction is forward or backward.
When you are modeling conveyor systems, the booking point oftentimes represents the center of gravity of the part. Once the booking point, i.e., the center of gravity of the part, has transferred onto a conveyor, the part starts moving with the speed you set for this conveyor.

SimTalk:
BookPntLRelative
.topic 0x882015e7
Enter the width of the mobile object. The length-oriented objects use the width after the AngularConverter has changed the conveying direction to determine how many MUs it can hold.

SimTalk:
MUWidth
.topic 0x882015e9
Enter the location of the booking point of the mobile object when it is conveyed crosswise. This value is the relative distance from booking point 0, which is located at the right hand side of the MU, in the direction of motion. You can enter a relative value between 0 and 1. Plant Simulation uses it, when the conveying direction is lateral right or lateral left.
When you are modeling conveyor systems, the booking point oftentimes represents the center of gravity of the part. Once the booking point, i.e., the center of gravity of the part, has transferred onto a conveyor, the part starts moving with the speed you set for this conveyor.

SimTalk:
BookPntWRelative
.topic 0x882015fd
Enter the height of the MU. The height is important if you want to use the z-dimension of the part in 3D.

SimTalk:
MUHeight
.topic 0x886912b4
Enter the relative height of the booking point of the MU. The height is only important if you want to use the z-dimension of the part in 3D. You can enter a relative value between 0 and 1.

SimTalk:
BookPntHRelative
.topic 0x891c0ea9
To activate vector graphics mode, select this, and click OK or Apply. Then, Plant Simulation shows the graphics of the parts with the correct size and with the correct distance to each other while animating the simulation model.

SimTalk:
VectorgraphicsActive
.topic 0x891c07c2
Select the fill color of the vector graphic of the mobile object. The fill color fills the interior of the built-in vector graphic with the color that you select.

SimTalk:
VectorgraphicsColor
.topic 0x891c0a16
Select the border color of the vector graphic of the mobile object. Plant Simulation surrounds the fill color with the border color in the Border width that you select. The border color also sets the color of the direction arrow.

SimTalk:
VectorgraphicsBorderColor
.topic 0x891c0d2a
Enter the border width of the vector graphic of the mobile object. Plant Simulation surrounds the fill color with the border width in the Border color that you select.

SimTalk:
VectorgraphicsBorderWidth
.topic 0x891c0ea7
To show the direction arrow on the vector graphic of the mobile object to illustrate the conveying direction, select this. The Border color, which you select, sets the color of the direction arrow.

SimTalk:
VectorgraphicsShowDirectionArrow
.topic 0x891c0ea8
To show the state of the mobile object as a colored border around its vector graphic, select this. The states are yellow for blocked, red for failed, and blue for paused. The state color overwrites the Border color that you selected.

SimTalk:
VectorgraphicsShowState
.topic 0x891c0ead
Select the direction of the animation line on the vector graphic of the object Transporter: Lengthwise or Crosswise to the direction of movement.

SimTalk:
VectorgraphicsAnilineDirection
.topic 0x882210ae
To collect statistics data for the MU during a simulation run, select this. The tab then shows the most important statistical data.

SimTalk:
ProdStatOn
.topic 0x882210bc
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Production.

SimTalk:
statProductionTimePortion
.topic 0x882210c4
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Production that was processing parts, compare Working.

SimTalk:
statProdWorkingPortion
.topic 0x882210bb
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Production that was Setting-up.

SimTalk:
statProdSetupPortion
.topic 0x882210c1
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Production that was Waiting.

SimTalk:
statProdWaitingPortion
.topic 0x882210b8
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Production that was Stopped by the LockoutZone.

SimTalk:
statProdStoppedPortion
.topic 0x882210b5
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Production that was Failed.

SimTalk:
statProdFailPortion
.topic 0x882210b2
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Production that was Paused.

SimTalk:
statProdPausingPortion
.topic 0x882210bd
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Transport.

SimTalk:
statTransportTimePortion
.topic 0x882210c5
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Transport that was processing parts, compare Working.

SimTalk:
statTranspWorkingPortion
.topic 0x882210b9
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Transport that was Setting-up.

SimTalk:
statTranspSetupPortion
.topic 0x882210c2
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Transport that was Waiting.

SimTalk:
statTranspWaitingPortion
.topic 0x882210b6
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Transport that was Stopped by the LockoutZone.

SimTalk:
statTranspStoppedPortion
.topic 0x882210b3
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Transport that was Failed.

SimTalk:
statTranspWaitingPortion
.topic 0x882210b0
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Transport that was Paused.

SimTalk:
statTranspWaitingPortion
.topic 0x882210be
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Storage.

SimTalk:
statStorageTimePortion
.topic 0x882210c6
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Storage that was processing parts, compare Working.

SimTalk:
statStoreWorkingPortion
.topic 0x882210ba
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Storage and was Setting-up.

SimTalk:
statStoreSetupPortion
.topic 0x882210c3
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Storage that was Waiting.

SimTalk:
statStoreWaitingPortion
.topic 0x882210b7
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Storage that was Stopped by the LockoutZone.

SimTalk:
statStoreStoppedPortion
.topic 0x882210b4
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Storage that was Failed.

SimTalk:
statStoreFailPortion
.topic 0x882210b1
Shows the portion of the statistics collection period during which the MU was located on a material flow object of type Storage that was Paused.

SimTalk:
statStorePausingPortion
.topic 0x88251619
Enter the speed with which the Transporter drives on the Track/TwoLaneTrack. When you disable Acceleration, the Transporter attempts to reach its final speed immediately without accelerating. Once it reaches the final speed, it drives on with this constant speed. Or enter -1 for an infinite speed.

SimTalk:
Speed
.topic 0x88251618
To make the Transporter drive in reverse on the Track/TwoLaneTrack, select this. When the Transporter moves from a Track/TwoLaneTrack onto a Track/TwoLaneTrack, it may enter the Track at the Track’s exit and leave it at its entrance. This only applies when the Transporter moves from a Track/TwoLaneTrack to a Track/TwoLaneTrack, but not from a point-oriented object onto a Track/TwoLaneTrack. Driving forward or in reverse are not properties of the Track/TwoLaneTrack, but of the Transporter driving on it! Suppose Acceleration is enabled and the Transporter drives forward on the Track with a certain speed while Backwards is deactivated. Then, you select Backwards. This will result in the Transporter slowing down until its speed is 0. Then it accelerates in the reverse direction until it reaches its final speed. When you then disable Acceleration, the Transporter attempts to reverse its direction of motion immediately without slowing down and accelerating.

SimTalk:
Backwards
.topic 0x88251617
To make the Transporter increase or decrease its speed on the Track/TwoLaneTrack, select Acceleration. Click Apply to activate the text box Acceleration and to show the Current speed.

SimTalk:
AccelerationEnabled
.topic 0x8825161a
Enter the Acceleration with which the Transporter increases its speed on the Track/TwoLaneTrack. You can enter any real number greater than or equal to 0.

SimTalk:
Acceleration, movingAcceleration
.topic 0x8825161b
Enter the Deceleration with which the Transporter reduces its speed on the Track/TwoLaneTrack. You can enter any real number greater than or equal to 0.

SimTalk:
Deceleration
.topic 0x882515e1
To designate the active Transporter as the tractor of the tugger train, which pulls or pushes the trailers, select this.

SimTalk:
IsTractor
.topic 0x882536f0
The start delay duration is the time after which a Transporter, which collided with the one driving in front of it, starts moving after the Transporter driving in front started moving again. Select a distribution from the drop-down list, and enter the values, which that distribution requires, into the text box.

SimTalk:
StartDelayDuration
.topic 0x88250fbe
Select the type of loading space of the Transporter.

Store denotes a loading space consisting of loading places along the X-axis and the Y-axis onto which the Transporter places the parts it loads.

Track denotes a passive length-oriented loading space onto which the Transporter loads and unloads parts. This is especially handy for modeling a CrossSlidingCar and other types of materials handling equipment.

Or enter Controls and define Sensors. The animation on the length-oriented loading space requires an animation line. As Plant Simulation does not create the animation line automatically, you have to create it in the icon of the object. The Length of the loading space is independent of the MU length of the Transporter proper.

Line denotes an active length-oriented loading space similar to a conveyor being part of the loading space, which transports the loaded parts forwards or backwards. The CrossSlidingCar makes extensive use of this type of loading space.

SimTalk:
LoadBayType
.topic 0x882710ca
Enter the length of the loading space. The animation on a length-oriented loading space requires an animation line! As the program does not automatically create the animation line, you have to assign a suitable icon. For vector graphics we defined the animation line, you cannot change it. The length of the loading space is independent of the length of the Transporter proper.

SimTalk:
LoadBayLength
.topic 0x882710cb
Enter the speed with which the loading space of the Transporter moves. When you enable Acceleration, the speed of the loading space is the same as its Current speed.

SimTalk:
LoadBaySpeed
.topic 0x882710ce
To make the loading space on the Transporter move backwards, select this. To make it move forwards, clear the check box.

SimTalk:
LoadBayBackwards
.topic 0x882710cc
To make the loading space of the Transporter increase its speed, select this.

SimTalk:
LoadBayAccelerationEnabled
.topic 0x882710cd
Enter the Acceleration with which the loading space of the Transporter increases its speed. You can enter any real number greater than or equal to 0.

SimTalk:
LoadBayAcceleration
.topic 0x882710cf
Enter the Deceleration with which the loading space of the Transporter reduces its speed. You can enter any real number greater than or equal to 0.

SimTalk:
LoadBayDeceleration
.topic 0x882710d1
To open the dialog into which you can enter the controls pertaining to the Type of loading space you selected, click this.
The loading space of type Store provides the Entrance control and the Exit control.
The loading space of type Track provides the Entrance control, the Exit control, the Backward entrance control, and the Backward exit control.
The loading space of type Line provides the Entrance control, the Entrance control, the Backward entrance control, the Backward exit control, and the Speed control.

SimTalk:
EntranceCtrl, EntranceCtrlFront, EntranceCtrlRear, ExitCtrl, EntranceCtrlFront, EntranceCtrlRear, BwEntranceCtrl, BwEntranceCtrlFront, BwEntranceCtrlRear, BwExitCtrl, BwExitCtrlFront, BwExitCtrlRear, LoadBaySpeedCtrl
.topic 0x882511e0
To make the Transporter independently find the shortest route to its Destination object along the direction of motion, select this. Except for the destination object, the route consists of objects of type Track/TwoLaneTrack, which are connected with Connectors. The route can also cover subframes or surrounding Frames, as long as the Tracks are connected with Connectors via Interface objects. Or enter a Route weighting factor.

SimTalk:
AutomaticRouting
.topic 0x88251109
Enter the name of the attribute, which is used for controlling the weighting of routes. The value of the attribute RouteWeightingAttr determines the name of user-defined attributes of Tracks/TwoLaneTracks. All lengths of the Tracks/TwoLaneTracks will then be multiplied with the value you assigned to the user-defined attribute. The user-defined attributes have to have the data type real. If you assign a negative value to the user-defined attribute, this Track/TwoLaneTrack will not be used for automatic routing. All Tracks/TwoLaneTracks, which do not have a user-defined attribute with the name designated by the route weighting attribute use the factor 1.0.

SimTalk:
RouteWeightingAttr
.topic 0x882036dd
Click this and select the destination object to which the Transporter drives. For Part and Container the destination object is the object to which the Worker carries the part. The Transporter automatically finds the destination object using the destination lists of the objects of type Track/TwoLaneTrack. When you activate Automatic routing, you do not need to define destination lists at all. The Transporter will automatically find its destination object. When a sensor, into which you entered this target object is the Destination, can be reached on a shorter route than the destination object itself, then automatic routing directs the Transporter to this sensor.

SimTalk:
Destination, DestinationListRow
.topic 0x882e10eb
Click this and select a Method object. Enter the source code of the driving control. In it, you program to which successor the Transporter moves, when it has covered the entire Track, and when you did not enter an exit control.

SimTalk:
DriveCtrl
.topic 0x882e10ec
Click this and select a Method object. Enter the source code of the routing control. The Transporter calls it, when the program automatically predicted a route to the destination. Within this control you might read out the newly calculated route with the method getRouteToDestination. You might then manipulate this route and assign the changed route with the method setRoute. You might also check if the entrance or the exit of one of the Tracks along the predicted route is closed and then drive around this Track.

SimTalk:
RoutingCtrl
.topic 0x882e10ef
Click this and select a Method object. Enter the source code of the destination control. The Transporter calls it, when it has reached and covered its destination. When you enter an exit control for the destination, the Transporter does not activate the destination control.

SimTalk:
DestCtrl
.topic 0x882e10f1
Click this and select a Method object. Enter the source code of the collision control. When the Transporter crashes into another Transporter, i.e., the successor moves with a higher speed than the predecessor, the faster Transporter calls the collision control. For tugger trains this applies: When a tugger train collides, the collision control of the tractor will always be triggered. Within the control method the anonymous identifier @ is the Transporter, which actually collides, while the anonymous identifier ? denotes the tractor of the train.

SimTalk:
CollisionCtrl
.topic 0x882e10f2
Click this and select a Method object. Enter the source code of the distance control. The Transporter for which you entered the distance control calls it when it gets closer to any other MU than the Distance you enter. Plant Simulation calls the control when the distance becomes too small and when it becomes too great.

SimTalk:
DistanceCtrl
.topic 0x882e10f3
Enter the distance from which on the Transporter calls the Distance control to prevent the MUs from getting too close to each other or from moving away too far from each other. You can enter a value greater than 0.

SimTalk:
Distance
.topic 0x87e00fd9
Click this and select a Method object. Enter the source code of the speed control. The Transporter calls it, when it reaches its final speed after accelerating or decelerating on a Track/TwoLaneTrack or when it stops after decelerating.

SimTalk:
SpeedCtrl
.topic 0x882e14e0
Click this and select the ShiftCalendar. This ShiftCalendar object contains the data of the shifts in your installation and controls during which shifts the Transporter works.

SimTalk:
ShiftCalendarObject
.topic 0x882f10f4
To run the Transporter off of a battery, select this. To operate it without battery power, clear the check box.

SimTalk:
BatteryUsed
.topic 0x882f10f6
Enter the active charge of the battery in ampere hours (Ah). You can enter any value between 0, which means that the battery is empty, and the Capacity of the battery.

SimTalk:
BatCharge, BatCharging
.topic 0x882f10f8
Enter the basic consumption of the battery in ampere (A). As long as the Transporter is running on battery, the battery consumes the energy you enter here, no matter if it is moving or not.

SimTalk:
BatBasicCons
.topic 0x882f10fe
Enter a value for the energy the Transporter consumes in ampere (A) while it drives.

SimTalk:
BatDriveCons
.topic 0x882f10fa
Enter the capacity of the battery in ampere hours (Ah).

SimTalk:
BatCapacity
.topic 0x882f1100
Enter the reserve capacity of the battery in ampere hours (Ah). Once the charge falls below the value you enter here, the Transporter calls the Charge control in which you program how the battery is recharged.

SimTalk:
BatReserve
.topic 0x882f10fc
Enter a value for the charge current in ampere (A).

SimTalk:
BatChargeCurrent
.topic 0x882f10f3
Click this and select a Method object. Enter the source code of the charge control. The Transporter calls it, whenever the battery charge falls below the Reserve value. It also calls the charge control when the charge is 0 or when it reached the value, which you entered as the Capacity.

SimTalk:
BatChargeCtrl
.topic 0x882210c0
Shows how many Transporter instances of this class existed during the statistics collection period. The program only counts those MUs whose product statistics was active during the simulation run. The MUs may be located in different Frame hierarchies.

SimTalk:
statCount
.topic 0x882210c7
Shows how many Transporter instances of this class were removed from the installation during the statistics collection period. The program only counts those MUs whose product statistics was active during the simulation run.

SimTalk:
statDeleted
.topic 0x882210bf
Shows the average life-span of the MUs, which were created and removed from the installation during the statistics collection period. The program only counts those MUs whose product statistics was active during the simulation run.

SimTalk:
statAvgLifeSpan
.topic 0x883e1434
To collect resource and driving statistics data for the Transporter and to display the most important statistical data on the tab itself, select this. To deactivate the collection of statistics, clear the check box.

SimTalk:
ResStatOn
.topic 0x883e1436
Shows the time portion of its life-span during which the Transporter had an order and was loaded.

SimTalk:
statOrderOccPortion
.topic 0x883e143a
Shows the time portion of its life-span during which the Transporter had an order and was not loaded (Empty).

SimTalk:
statOrderEmptyPortion
.topic 0x883e1450
Shows the time portion of its life-span during which the Transporter was returning to its base.

SimTalk:
statHomeDrivingPortion
.topic 0x883e1438
Shows the portion of the statistics collection period during which the Transporter was ready.

SimTalk:
statTspReadyPortion
.topic 0x883e143c
Shows the portion of the statistics collection period during which the Transporter was Failed.

SimTalk:
statTspFailPortion
.topic 0x883e143e
Shows the portion of the statistics collection period during which the Transporter was Paused.

SimTalk:
statTspPausingPortion
.topic 0x883e1440
Shows the portion of the statistics collection period during which the Transporter was Unplanned, i.e., was not scheduled to work to the statistics collection period.

SimTalk:
statTspUnplannedPortion
.topic 0x883e1442
Shows the portion of the statistics collection period during which the Transporter was Empty.

SimTalk:
statEmptyPortion
.topic 0x883e1444
Shows the capacity-based ratio of the time during which the Transporter was occupied, not paused and not failed to the time the object was not paused and not failed.

SimTalk:
statRelativeOccupation
.topic 0x883e1446
Shows the number of MUs, which are located on the Transporter.

SimTalk:
numMU
.topic 0x883e1448
Shows the minimum number of MUs, which were located on the Transporter.

SimTalk:
statMinNumMU
.topic 0x883e144a
Shows the maximum number of MUs, which were located on the Transporter.

SimTalk:
statMaxNumMU
.topic 0x883e144c
Shows the number of MUs that entered the Transporter. When an MU enters the object, the object only counts the MU itself, not its contents: When a Transporter transporting several entities enters the object, the number of entries increases by 1, not by the number of entities located on the Transporter!

SimTalk:
statNumIn
.topic 0x883e144e
Shows the number of MUs that exited the Transporter. The rules described under Entries apply.

SimTalk:
statNumOut
.topic 0x883e1439
Shows the distance which the Transporter traveled on a Track.

SimTalk:
statTraveledDistance
.topic 0x88461200
Select a Column Separator for exporting or importing a list: Tab, Space or Semicolon.

SimTalk:
ColumnSeparator
.topic 0x88461202
Select a Decimal Separator for exporting or importing a list: . (Period) or, (Comma).

SimTalk:
DecimalSeparator
.topic 0x88461203
Select how the program saves and opens entries of data type time from the drop-down list Time format. This way you can save values of data type time in a format that spread sheet applications that cannot read our internal time format, also recognize.

SimTalk:
TimeFormat
.topic 0x88461204
Enter the number of columns, which the program uses for internally allocating memory for the text file.
.topic 0x88461205
Enter the number of rows, which the program uses for internally allocating memory for the text file.
.topic 0x88471206
Prints the row number in front of each cell.

SimTalk:
PrintRowNumber
.topic 0x88471207
Prints the column number above each column.

SimTalk:
PrintColumnNumber
.topic 0x88471208
Prints the data type of each column.

SimTalk:
PrintDataType
.topic 0x88471209
Prints the user-defined row index on each page.

SimTalk:
RepeatRowIndex
.topic 0x8847120a
Prints the user-defined column index on each page.

SimTalk:
RepeatColumnIndex
.topic 0x8847120b
Prints nested tables the list or table contains also.

SimTalk:
PrintInternalLists
.topic 0x8847120c
Prints columns using the column width of the widest column. When you do not check this, the program uses the value you set under Format > List > Column width and entries may overprint other entries.

SimTalk:
GenerateColumnWidth
.topic 0x8926157d
Enter the expression you would like to find into the text box Find what.
.topic 0x8926157e
Enter the expression into the text box Replace with that is to replace the expression you entered into the text box Find what.
.topic 0x89261582
Select Match entire cell contents to only find the characters in cells, which exactly and completely match the expression you entered into the text box Find what.
.topic 0x89261580
Select Match case to only find text that has the same pattern of upper and lower case as the expression you entered into the text box Find what.
.topic 0x8926157f
Select if you want to Search in Rows, i.e., to the right across rows, or down through Columns.
.topic 0x89261581
Select the Search criterion from the drop-down list:
.topic 0x8926157a
Click Find Next, so that the program finds the next instance of the expression you entered into the text box Find what.
.topic 0x8926157b
Click Replace to replace this instance of the search term or to show the text box Replace with.
.topic 0x8926157c
Click Replace All to replace all instances of the search term.
.topic 0x8837117f
The box Range shows the selected range of cells or columns.
.topic 0x88391156
Select the alignment of the cells of the column(s) or of the cell(s) you selected: Left, Right, Center.

SimTalk:
Alignment, setAlignmentCells, getAlignmentCell, setAlignmentColumn, getAlignmentColumn, setAlignmentRow, getAlignmentRow, isAlignmentColumn, isAlignmentRow
.topic 0x88391157
Select the font size for the text you enter into the cells of the column(s) or into the cell(s) you selected: Small, Medium/Normal, Large, or Extra Large/Huge. The list automatically adjusts the width and the height of the cells to the font size you selected.

SimTalk:
FontSize, setFontSizeColumn, getFontSizeColumn, setFontSizeRow, getFontSizeRow, setFontSizeCells, getFontSizeCell
.topic 0x88391158
To select the color of the text, which you enter into the cells of the column(s) or into the cell(s) you selected, click the drop-down arrow.

SimTalk:
FontColor, setFontColorCells, getFontSizeCell, setFontColorColumn, getFontColorColumn, setFontColorRow, getFontColorRow
.topic 0x88391159
To select the color of the background of the cells of the column(s) or of the cell(s), which you selected, click the drop-down arrow.

SimTalk:
BackgroundColor, setBackgroundColorCells, getBackgroundColorCell, setBackgroundColorColumn, getBackgroundColorColumn, setBackgroundColorRow, getBackgroundColorRow
.topic 0x852208f1
To set that the column index belongs to the contents of the TableFile, select this. Then the column index is inherited together with the contents of the TableFile when Inherit Contents is active.
To set that the column index belongs to the format of the TableFile, clear the check box. Then the column index is inherited together with the format of the TableFile when Inherit Format is active.

SimTalk:
ColumnIndexContents
.topic 0x883a114f
To allow read-only access in the open window of the list object, select this. To allow read and write access to the entire list in the List Editor, i.e., the dialog window, clear the check box.

SimTalk:
EditorReadOnly
.topic 0x883a1150
To allow read-only access to the entire list with Methods, select this. To allow read and write access to the entire list with Methods, clear the check box.

SimTalk:
InfoflowReadOnly
.topic 0x883b1151
Enter the number of rows of the list. If you do not enter a value for the Number of columns and/or the Number of rows, the dimension of the list is not limited.

SimTalk:
MaxDim, MaxYDim
.topic 0x883b1152
Enter the number of columns of the TableFile. If you do not enter a value for the Number of columns and/or the Number of rows, the dimension of the list is not limited.

SimTalk:
MaxDim, MaxXDim
.topic 0x883b1153
Enter the column width in character widths of a non-proportional font. To simultaneously change the width of several columns, mark the range of columns before entering a number here.

SimTalk:
ColumnWidth, setColumnWidth, getColumnWidth
.topic 0x88381154
Select one of the data types from the list. When you select the data type Date, you can type in the day, the month and the year in this order. When you apply the date, the program enters it in the date format of the language of the model, year, month, day for English. Or type in the American format 2008/11/13 if your model language is English.

SimTalk:
DataType, setDataType, getDataType, setDataTypeDefault
.topic 0x88381155
For the data types Integer, Real, Length, Weight, Speed, Acceleration, Money, and String you can restrict the data the user can enter in the window of the list object to certain values by entering a format string. The Format String does not restrict assignments via Methods.

SimTalk:
setCommonFormat, setCommonFormatData, getCommonFormatData, CommonFormatColumnIndex
.topic 0x88381182
Select this to allow for quickly accessing the user-defined column/row index. Then, Plant Simulation internally creates a data structure that reduces the search effort, but slightly increases memory usage and the time required for changing the index.

SimTalk:
FastAccessColumnIndex, FastAccessRowIndex
.topic 0x88381183
Select this to only allow unique entries in user-defined indexes, depending on the data type. The program issues a warning when you attempt to assign an entry that already exists. When you assign an entry for an index that already exists in a Method, the program does not issue a warning message!

SimTalk:
UniqueKeyColumnIndex, UniqueKeyRowIndex
.topic 0x88871314
Enter the number of the Column in which the active cell will be located.

SimTalk:
Cursor, CursorY
.topic 0x88871315
Enter the number of the Row in which the active cell will be located. This cell will then be the starting point for scrolling within the list or table. This makes moving within large tables easy and comfortable.

SimTalk:
Cursor, CursorX
.topic 0x88871316
The box Occupied columns shows the number of columns of the table that contain an entry.
.topic 0x8853128b
To sort the contents of the cells in the time sequence in ascending order, click this.
.topic 0x8853128c
To fill blank cells in column 2 with the Default value you set, click this.
.topic 0x884f1215
Select if the time values are Relative or Absolute values. Depending on the setting you select, the data type of column 1 is time or datetime. The program automatically converts values you enter. For the absolute time reference enter a point in time on a certain date (datetime) into the text box Reference date. For the relative time reference enter a duration (time) into the text box Reference time.

SimTalk:
Absolute
.topic 0x884f1216
Depending on the setting you selected as Time reference, you can define a Reference time (relative) or a Reference date (absolute). The program adds its value to the time column of the TimeSequence to offset the data you set there. By changing the Reference time/date, you can shift the values in time without re-entering the data.

SimTalk:
ReferenceDate, ReferenceTime
.topic 0x884f1217
Enter the Default value of the time sequence. The default value is especially important for a TimeSequence that defines the evolution of the value of a Trigger object because the Trigger assumes the default value outside of its active interval. In addition, The program uses the default value to fill blank cells in column 2 of the TimeSequence, when you click Set Value on the tab Contents.

SimTalk:
DefaultValue
.topic 0x88511218
Enter a relative or an absolute path to the value to be recorded. When you enter an invalid path, the TimeSequence does not record any data. When you select Watch mode, the path must reference an observable value.

SimTalk:
Path
.topic 0x88511219
Select the mode with which the TimeSequence adds new time-value pairs to the columns of the table. Watch: Each time, when an observable value changes. Sample: Periodically, during the Interval you enter, no matter if the value actually changes or not.

SimTalk:
Sample
.topic 0x88511291
When you select Sample Mode, enter the time that elapses between the points in time at which the TimeSequence records data.

SimTalk:
SmpPeriod
.topic 0x8851121a
To record values, select Active. To not record any values, clear it.

SimTalk:
Active
.topic 0x88f21507
To show the list window in which the AttributeExplorer displays the objects and the attributes you defined, click this. To close the list window in which the AttributeExplorer displays the objects and attributes you defined, click the X in the title bar.

SimTalk:
Active, AttributeTable, ExplorerTable
.topic 0x88f5152d
A selected button means that Inheritance is active. Then, the object inherits, i.e., uses, the settings on the tab from the parent object from which it was derived. When you modify the value of the parent object, the program also modifies the value of the child object. A deselected button means that inheritance is not active. Values you select or enter only apply to the selected object.
.topic 0x88f51529
To display the values of the observable attributes of any of the stations, which you entered, select this. The program displays the background of the cells in different colors to show if the attribute is observable or not.

SimTalk:
Mode
.topic 0x88f5152a
To enable editing the values of the attributes of any one of the stations you entered, select this. The program writes the values you modified back to the dialogs of the objects, when you click Apply/OK.

SimTalk:
Mode
.topic 0x88f5152b
To enable read only mode for the values of the attributes of the stations you entered, select this. Then, you can only view, but not edit the values. The program updates the values, when you click Apply.

SimTalk:
Mode
.topic 0x88f51506
Select how the AttributeExplorer shows the objects, which you enter. With their entire Path, Name only, or Label only.

SimTalk:
ObjectRepresentation
.topic 0x88f51508
Select how the AttributeExplorer shows the attributes, which you enter. With their Alias, which is a description you entered, in addition to the built-in name of the attribute or with their Name only.

SimTalk:
AttributeRepresentation
.topic 0x88f5152e
To show any explanations you entered into the text box Comment, select this. To not show it, clear the check box.

SimTalk:
ShowComment, Comment
.topic 0x88f51530
A selected button means that Inheritance is active. Then, the object inherits, i.e., uses, the text you entered into the parent object from which it was derived. When you modify the comment of the parent object, the program also modifies the value of the child object. A deselected button means that inheritance is not active. Text you enter only applies to the selected object.
.topic 0x88f5152f
Enter an explanation for the objects and values you defined here. Select Show comment to display it above the list field.

SimTalk:
Comment, ShowComment
.topic 0x88f41532
To enter the names of the attributes whose values you want to edit or view, into the cells in the column Name, click Attribute Viewer.
.topic 0x88fd1544
Enter the path to and the name of the Object whose attributes you want to show.

SimTalk:
AttributeTable
.topic 0x88fd1535
Select from the drop-down list if you want to view the built-in attributes of this object, or its user-defined attributes, which you defined.
.topic 0x88fd1531
Depending on what you selected above, the AttributeExplorer displays the built-in attributes or the user-defined attributes here.
.topic 0x88fd36de
Select one, or several contiguous attributes (Shift+click), and click this to add them to the attributes to be shown.
.topic 0x88fd1536
The AttributeExplorer adds the attributes, which you selected in the left hand list box, to the attributes, which it is going to show. To add a sub-attribute of an attribute, type in the attribute, and the sub-attribute into the cell. You might, for example enter imp.priority.
.topic 0x85e10b7f
Click this and select the Frame, in which you want to start finding the attributes of the objects. Select Include subframes to also include any Frames located within the Frame you selected.

SimTalk:
StartNode
.topic 0x85e10b80
To also include the Frames which are inserted in the Frame, which you selected under Frame in the text box above, into your query, select this.

SimTalk:
IncludeSubframes
.topic 0x85e109e9
To also include the MUs located within the Frame, which you selected under Frame in the text box above, into your query, select this.

SimTalk:
IncludeMUs
.topic 0x8849120f
Enter the name of the text file from which you want to import data. Or enter the name of the text file to which you want to export data. Or click the button and select a file in the dialog Open.

SimTalk:
FileName
.topic 0x88f51520
Select the encoding with which Plant Simulation saves the text file it writes: ANSI is an 8-bit character set that allows you to represent up to 256 characters (0 through 255). The ANSI character set is a superset of the 7-bit ASCII character set. UTF-8 is another encoding of the Unicode character set. Each character is represented by one to three bytes. Unicode is a 16-bit character set that includes almost all of the written languages of the world. Plant Simulation saves Unicode in UTF-16 encoding. Each character is represented by two bytes.

SimTalk:
Encoding
.topic 0x8849120d
To delete the file whose name is contained in the text box File Name, click this.

SimTalk:
remove
.topic 0x884b1211
The program shows the path and the name of the linked file in this text box after you dragged a file from the Windows Explorer to the Plant Simulation Frame.

SimTalk:
FileName
.topic 0x884b1212
To embed the file, which you drag-and-drop onto the Frame, into the Plant Simulation model, select this. Then that version of the file will become part of the simulation model, meaning the program does not mind, when you move the original file to another location. Changes to the file after embedding it will naturally not be reflected if you embed it. Embedding may significantly increase the file size of your .spp model file. When you clear the check box, the program creates a link to the file in the file system of your computer. If you move or delete the file, the link will become invalid and Plant Simulation will not be able to find the file and open it.

SimTalk:
Embed
.topic 0x881f10a6
To activate the Generator, select Active. To deactivate it, clear the check box.

SimTalk:
Active
.topic 0x881f10a2
Enter the time at which the Generator activates the Interval control for the first time. When you enter 0 as the Start time and a value greater than 0 for the Interval, the program triggers the control immediately after you started the simulation. Or select any of the probability distributions. Then, you have to enter the parameters, which the selected distribution requires.

SimTalk:
Start
.topic 0x881f10a3
Enter the time at which the Generator activates the Interval control for the last time. As Interval and Duration always appear in pairs, the Duration control may be activated even after the time you entered here. If you do not want any time limit to apply for activating the Interval control, enter 0. Or select any of the probability distributions. Then, you have to enter the parameters, which the selected distribution requires.

SimTalk:
Stop
.topic 0x881f10a4
Enter the Interval, i.e., the time span between the activation of two Interval control methods. When you enter 0, the program does not trigger any controls and stops the Generator. Or select any of the probability distributions. Then, you have to enter the parameters, which the selected distribution requires.

SimTalk:
Interval
.topic 0x881f10a5
Enter the Duration, i.e., the time span between activating the Interval control and the Duration control. Or select any of the probability distributions. Then, you have to enter the parameters, which the selected distribution requires.

SimTalk:
Duration
.topic 0x882010a9
Click this and select a Method object. Enter the source code of the interval control. The Generator calls it according to the intervals, which you entered as the Interval.

SimTalk:
IntervalCtrl
.topic 0x882010aa
Click this and select a Method object. Enter the source code of the duration control. The Generator calls it after the time span, which you entered for the Duration (depending on the Interval), has elapsed. It calls the duration control after the interval control. The duration control may be activated for the last time even after the time you entered for Stop.

SimTalk:
DurationCtrl
.topic 0x88a11390
Enter the expression which you would like to find into the text box Find what.
.topic 0x88a11394
Select Up to search toward the beginning of the Method.
.topic 0x88a11395
Select Down to search toward the end of the Method.
.topic 0x88a1138f
Click Find Next, to find the next instance of the expression which you entered into the text box Find what.
.topic 0x88a11397
Click Mark All, to highlight all instances of the expression which you entered into the text box Find what. To perform the action of your choice, use the menu commands under Edit > Bookmarks (Toggle bookmarks, Clear all bookmarks, Go to next bookmark, Go to previous bookmark) or the Bookmarks buttons on the toolbar.
.topic 0x88a1139a
Enter the expression into the text box Replace with that is to replace the expression which you entered into the text box Find what.
.topic 0x88a11397
Click Replace to replace this instance of the search term.
.topic 0x88a1139b
Click Replace All to replace all instances of the search term in the source code.
.topic 0x8907155d
Select the category of template you want to use.
.topic 0x8907155e
Select the template you want to use.
.topic 0x8907155f
View a description of the selected category of the template.
.topic 0x85900a1c
Enter the password for encrypting the Method into the text box Password.

SimTalk:
encrypt
.topic 0x85900a1d
Enter the password for encrypting the Method again into the text box Confirm password.
.topic 0x892313c7
The tab shows the names of all variables and their values. The anonymous identifier @ allows you to test a Method without running a simulation. When you enter a path for @ in the method editor and enter this anonymous identifier into a Method, the program will internally replace this anonymous identifier with the path. The anonymous identifier ? allows you to test a Method without running a simulation. When you enter a path for ? in the method editor and enter this anonymous identifier into a Method, the program will internally replace this anonymous identifier with the path.
.topic 0x88ad13c8
The tab shows the sequence in which the methods are called, i.e., the call chain. The first Method to be activated is always located at the bottom of the list, while the top line shows the Method being executed at the moment. Double-click a cell on the tab Call Stack to open the corresponding Method, together with its current settings of local variables and parameters, in the Debugger. Double-click the topmost cell to return to the Method being executed at the moment.

SimTalk:
getCallStack
.topic 0x88ae13c9
The tab shows methods which are ready to be executed immediately. Do not confuse these with the active Method being executed at the moment. Active methods are methods that were called and are now waiting to be executed while other methods, such as other controls triggered by events, are still being executed.
.topic 0x88af13ca
The tab shows methods that were suspended by The waituntil-statement and the stopuntil-statement. The caller of the Method is displayed in parenthesis, preceded by the absolute path. Double-click an entry to change to that Method.
.topic 0x892313c8
Enter any kind of expression which the Debugger is going to evaluate on the tab Expressions. Double-click a row in the list, enter an expression, for example self.xPos+1, and click OK, so that the program applies this entry. You will notice that the Debugger shows self.xPos+1 in the column Expression and current value in the column Value. When you select Show expression for all methods, the program shows this expression in the dialog of all Methods. You can edit the contents of the tab Expressions on the tab itself. To open a variable or an expression whose value has the data type object, you can click in the cell, and press the F2 key. When the tab Expressions shows a local variable or an attribute, you can edit its value in the cells in the column Value.
.topic 0x882910cc
To activate the Trigger during the simulation run, select this. To deactivate it, clear the check box. Instead, you can also right-click the Trigger object in the Frame and select Enable on the context menu. To deactivate it, select Disable on the context menu.

SimTalk:
Active
.topic 0x882910cd
Select the time reference which the Trigger uses during the simulation run. For a Relative time reference enter a point in time (time) into the text box Start time. For an Absolute time reference enter a point in time on a certain date (datetime) into the text box Start date.

SimTalk:
Absolute
.topic 0x882910cf
Enter the point in time (of data type time), at which the Trigger starts working.

SimTalk:
ReferenceTime
.topic 0x88291337
Enter the point in time on a certain date (of data type datetime), at which the Trigger starts working.

SimTalk:
ReferenceDate
.topic 0x882910e4
Enter the time interval during which the Trigger will be active. After this time interval has elapsed, the Trigger value will attain the default value. Define the default value under Values > Values > Value Table.

SimTalk:
ActiveInterval
.topic 0x882910ce
To make the Trigger repeat the values periodically instead of processing them one time only, select this.

SimTalk:
Periodic
.topic 0x882910e6
Enter the duration of a Trigger’s cycle during the simulation run. When you selected Repeat periodically, the program repeats the values after a completed cycle.

SimTalk:
PeriodLength
.topic 0x882a10d1
Select the Trigger type. The trigger types differ in the way how they generate events. The Input Trigger takes the values from a single TimeSequence. Click Values, and enter the values in the Value Table of the TimeSequence. The Combination Trigger generates a new Trigger by combining existing Triggers. Click Combination Table and enter the names of the Triggers that are to be combined. The program saves the result of the combination in the combination list that clicking Values opens.

SimTalk:
Combination, compute
.topic 0x882a10d2
To open the TimeSequence object that contains the current sequence of values of the Trigger, click this. Enter the default value of the Trigger on the tab Start Values > Default value.

SimTalk:
ValueTable
.topic 0x882a10d3
To open the Combination Table, click this and enter the Trigger objects, which the program combines into the combination trigger.

SimTalk:
CombinationTable, compute
.topic 0x882a10d5
For the Combination Trigger you can enter a formula that computes the Trigger’s value pattern. The formula connects the Trigger objects, which you entered into the Combination Table. For a TimeSequence of data type boolean, you can use the boolean operators AND, OR, and NOT. For a TimeSequence with numerical data types, you can use the operators +, -, *, and /.

SimTalk:
Formula
.topic 0x882b10d6
Click Attributes below Trigger and enter the names of the objects and the attributes, which the Trigger controls into the list. Enter the name of the object that the Trigger controls in the column Object. Enter the name of the attribute of this object as a string in the column Attribute. For a Variable object, you do not have to enter an attribute. The Trigger then passes the current value to the attributes of the respective objects. When an error occurs in the value assignment during the simulation run, the program enters the corresponding error message in the column Error Message.

SimTalk:
insertTriggeredAttr, deleteTriggeredAttr
.topic 0x882b10d8
Click Methods below Trigger and enter the names of the methods the Trigger controls into the list.

SimTalk:
insertTriggeredMeth, deleteTriggeredMeth
.topic 0x882b10db
Click Objects to open a table with one column. It shows the name of and the path to the Source object that the program entered, when you selected Time of creation > Trigger in the dialog of the Source, clicked Trigger, entered the name of the Trigger and clicked OK or Apply. Note that you cannot edit this table.
.topic 0x8836114c
Select a Time unit from the drop-down list that scales the time axis of the Trigger. Second, Minute, Hour, or Day
.topic 0x883213a6
Enter a name of your choice for the Variable, or accept the name, which the program suggests. You can enter a combination of letters, digits, and underscore (_) characters, for example MyVariable, MyVariable1, My_Variable_1. The name of an object cannot start with a digit, i.e., you cannot enter 1Variable.

SimTalk:
Name
.topic 0x8804156b
To reset a value, which the Variable recorded during a simulation run, to an initial value during the init phase of the next simulation run, select this. Then, enter the initial value for the next simulation run into the text box.
.topic 0x8804156c
Enter the initial value for the next simulation run.

SimTalk:
InitValue
.topic 0x851d07be
Select the font size for displaying the Variable in the Frame, into which you inserted it.

SimTalk:
Font
.topic 0x851d07bd
To select the color with which Plant Simulation shows the Variable in the Frame window, click the drop-down arrow.

SimTalk:
Color
.topic 0x851d07c1
To show the data type in addition to the name and the value of the Variable in the Frame, into which you inserted it, select this. To hide the data type, clear the check box.

SimTalk:
ShowDataType
.topic 0x851d07c0
To also show the unit of the physical size, select this. Select the unit under File > Model Settings/Preferences > Units.

For the data type randtime you can set with this check box if Plant Simulation shows or hides the distribution parameters in the Frame window.

If you clear Show Units, you can enter the number of decimal places.

SimTalk:
ShowUnit
.topic 0x851d07bf
To make the background of a Variable, which you inserted into a Frame, transparent, select this. Then, the program shows the Variable in that color on the background of the Frame, which you selected as the Font color, i.e., the background color of the Frame shines through the hollow parts of the text.

SimTalk:
Transparent
.topic 0x89351612
To collect statistics data during a simulation run and to show the top five frequencies and the top five durations on the tab, select Active. You can only select Active after you entered a valid name. The Variable only records statistics values for a Variable of Data types string or integer.

SimTalk:
StatisticsActive
.topic 0x89351613
To open the statistics table, click this.

SimTalk:
getStatisticsTable
.topic 0x8935161f
To open a pie chart each showing the frequency and the duration of the value, click this.
.topic 0x89351620
To open a histogram showing the frequency, i.e., the number of occurrences of the value, click this.
.topic 0x88341148
To activate monitoring the global variable Variable via DDE, select Support DDE hotlinks. To deactivate it, clear the check box. You might write the value of the Plant Simulation Variable to Microsoft Excel, which in turn could display the value in a dynamic chart, etc.

SimTalk:
SupportDDEHotlinks
.topic 0x883513ad
First, click this to deactivate Inheritance. Only then you can enter data into the list.
.topic 0x88351149
Enter any comment describing the function of the Variable into the text box on the tab Comment. To show the comment you enter as a tooltip, drag the mouse over the object in the Frame. The tooltip appears as you format it, when you enter it. It does not automatically create line breaks, but shows the text with the line breaks you manually enter by pressing Enter.

SimTalk:
Comment
.topic 0x8918124d
Enter the name of the XML file, which the XMLInterface opens, when you want to import data. When you export data, it specifies the name of the file which it saves.

SimTalk:
FileName
.topic 0x8918156b
Enter the context of the data you want to import. The context designates the node of the structure of the XML document at which the XMLInterface starts reading data. You might enter the names of certain data, or of certain objects that you are interested in, for example Data/Objects.

SimTalk:
Context, setContext
.topic 0x89181259
Click this and select a Method object, in which you programmed how to extract and to sequentially process the imported data. The import method is called by the method openRead for all objects, which are contained in the XML file.

SimTalk:
ImportMethod
.topic 0x8e0b0e0e
To show the object in the Frame with its Current icon, select this. Clear the check box to show the object with its default look.

SimTalk:
UseIcon
.topic 0x8e0b0e0d
Enter the width with which the object is displayed in the Frame. If you enter long text, you have to adjust the width so that the text fits into the object boundaries without being cut off. If you check Use icon, the object is shown with the width of the icon. To change the width, you can also hold down Ctrl+Shift and drag the left or the right side of the icon.

SimTalk:
Width
.topic 0x8e0b0e0f
Enter the height with which the object is displayed in the Frame. To change the height, you can also hold down Ctrl+Shift and drag the top or the bottom of the icon.

SimTalk:
Height
.topic 0x8e0b0e0c
Click this and select a Method object. Enter the source code of the control which is going to be executed when you click the Button or when you select an item in the Drop-down list. The anonymous identifiers ? and @ are set to the object when the method is called. When you enter a control without parameter, it is called once when you release the Button. Or enter a control which expects a boolean value as parameter. This control is called with the value true when you click the Button and with the value false when you release it.

SimTalk:
Control
.topic 0x88a814f3
To inherit the settings you select below, select Inherit Settings.
.topic 0x88a813b6
To show statistics values of the ParallelStation, select this. The Chart only adds material flow objects to the display for which you selected the check box Resource statistics on the Tab Statistics. You can select any number of classes.
.topic 0x88a813b7
To show statistics values of the AssemblyStation, select this. The Chart only adds material flow objects to the display for which you selected the check box Resource statistics on the Tab Statistics. You can select any number of classes.
.topic 0x88a813b8
To show statistics values of the DismantleStation, select this. The Chart only adds material flow objects to the display for which you selected the check box Resource statistics on the Tab Statistics. You can select any number of classes.
.topic 0x88a813be
To show statistics values of the Source, select this. The Chart only adds material flow objects to the display for which you selected the check box Resource statistics on the Tab Statistics. You can select any number of classes.
.topic 0x88a813bf
To show statistics values of the Drain, select this. The Chart only adds material flow objects to the display for which you selected the check box Resource statistics on the Tab Statistics. You can select any number of classes.
.topic 0x88a813bd
To show statistics values of the Store, select this. The Chart only adds material flow objects to the display for which you selected the check box Resource statistics on the Tab Statistics. You can select any number of classes.
.topic 0x88a813b9
To show statistics values of the PlaceBuffer, select this. The Chart only adds material flow objects to the display for which you selected the check box Resource statistics on the Tab Statistics. You can select any number of classes.
.topic 0x88a814f2
To show statistics values of the Buffer, select this. The Chart only adds material flow objects to the display for which you selected the check box Resource statistics on the Tab Statistics. You can select any number of classes.
.topic 0x88a813ba
To show statistics values of the Sorter, select this. The Chart only adds material flow objects to the display for which you selected the check box Resource statistics on the Tab Statistics. You can select any number of classes.
.topic 0x88a813bb
To show statistics values of the Conveyor, select this. The Chart only adds material flow objects to the display for which you selected the check box Resource statistics on the Tab Statistics. You can select any number of classes.
.topic 0x88a81613
To show statistics values of the Turntable, select this. The Chart only adds material flow objects to the display for which you selected the check box Resource statistics on the Tab Statistics. You can select any number of classes.
.topic 0x88a81614
To show statistics values of the AngularConverter, select this. The Chart only adds material flow objects to the display for which you selected the check box Resource statistics on the Tab Statistics. You can select any number of classes.
.topic 0x88a81616
To show statistics values of the Converter, select this. The Chart only adds material flow objects to the display for which you selected the check box Resource statistics on the Tab Statistics. You can select any number of classes.
.topic 0x88a81617
To show statistics values of the Turnplate, select this. The Chart only adds material flow objects to the display for which you selected the check box Resource statistics on the Tab Statistics. You can select any number of classes.
.topic 0x88a813bc
To show statistics values of the Track, select this. The Chart only adds material flow objects to the display for which you selected the check box Resource statistics on the Tab Statistics. You can select any number of classes.
.topic 0x88a81618
To show statistics values of the TwoLaneTrack, select this. The Chart only adds material flow objects to the display for which you selected the check box Resource statistics on the Tab Statistics. You can select any number of classes.
.topic 0x88a813c0
Select the type of resource(s) for which you would like to show statistical data in the Chart under Resource type. Select the Resource type on the tab Statistics of an object collecting statistical data. With the check boxes in the Statistics Wizard you can restrict, which objects the program shows. Production is the default for Source, Drain, Station, ParallelStation, AssemblyStation, and DismantleStation. Select the type of resource(s) for which you would like to show statistical data in the Chart. Select the Resource type on the tab Statistics of an object collecting statistical data. With the check boxes in the Statistics Wizard you can restrict, which objects the program shows. Transport is the default for the PlaceBuffer, Buffer, Sorter, Track, TwoLaneTrack, Conveyor, AngularConverter, Turntable, Transporter, and Container.
.topic 0x88a813c1
Select the type of resource(s) for which you would like to show statistical data in the Chart. Select the Resource type on the tab Statistics of an object collecting statistical data. With the check boxes in the Statistics Wizard you can restrict, which objects the program shows. Storage is the default for the Store.
.topic 0x88a813b4
Select the criteria according to which the program sorts statistical data from the drop-down list Sort criterion: To sort the stations by their name in alphabetical order from A to Z, select Sort criterion > Name. To sort the stations in the order that meets your needs, drag the stations onto the Chart in the order it is to show them. To change the order at a later point in time, edit the table of the Input channels by cutting the respective columns of the objects and pasting them in the desired order.
.topic 0x88a814f4
Select the statistics type: Resource Statistics, Energy Statistics, or Occupancy.
.topic 0x88a813c2
To also show statistical data of objects contained in Frames contained in the Frame in which the Chart is located, select Include subframes.
.topic 0x88a814f5
To reapply the settings while the simulation model is initialized, select Reapply at Init.
.topic 0x8866159d
To show the data, which the Chart collected in the display window, click this. To open the dialog of the Chart, double-click anywhere in the display window. To delete one of the displayed objects, click Table File next to Data source and delete the object from the input channels table. To delete the entire contents of the input channels table, hold down Shift while you drag-and-drop a new object onto the Chart. To show the data, you can also right-click the Chart object in the Frame and select Show on the context menu.

SimTalk:
Active
.topic 0x886612da
To make a Chart of the Category Histogram or Plotter collect data during the simulation run, select this. To deactivate data collection, clear the check box.

SimTalk:
CollectData
.topic 0x88661060
Select whether the Chart takes the data you want to display from a table file or from a set of input channels.
.topic 0x88661296
Enter the name of and path to the table file containing the data, or click the button and select the table in the dialog Select Object.

SimTalk:
DataTable
.topic 0x88661297
Enter the Range of the table cells you want to show.

SimTalk:
DataRange
.topic 0x88661294
To open a table into which you enter the input channels, click Table File. These channels are, as a rule, the paths to attributes or methods of objects, whose values you want to display.
.topic 0x88661298
Select which mode with which the Chart update the displayed data.
.topic 0x88661299
Enter the time span (Interval) after which the Chart takes the next sample.

SimTalk:
NumIntervals, SampleInterval
.topic 0x85530b55
Select one of these categories:

Chart shows a number of values or several sets of a number of values.

Histogram shows the frequency distribution for one or several input channels. Here you can select the check box Accumulated.

Plotter shows the progression of one or more values over time. Here you can select the check box Step curve. XY Graph shows a number of x-y pairs of values or several sets of x-y pairs of values. This setting is active only when you select Table File as the Data Source.

SimTalk:
Category
.topic 0x85530920
Select the type of Chart, which displays the values of the simulation run. A record consists of the entries of a row or a column, depending on the setting you selected under Display > Data.

SimTalk:
ChartType
.topic 0x85530924
To turn the chart left or right, enter an angle of Rotation or drag the horizontal slider in the display window.

SimTalk:
Rotation
.topic 0x85530c84
To turn the chart up or down, enter the Height or drag the vertical slider in the display window.

SimTalk:
Height
.topic 0x85530921
Select one of these 3D effects: None adds no 3D effect to the Chart type you selected. Shadow adds a black shadow to the chart type. 3D adds three-dimensional depth to the chart type. Gradient bars adds an effect between a gradient and a 3D look to the chart types columns and bars. Contoured for the chart types 3D Columns and 3D Surface.

SimTalk:
Effect
.topic 0x85530953
Select how the Chart shows the records: Graph shows the records as a graph only in the Chart window. Table shows the records as a table only in the Chart window. Graph and Table shows the records as a graph and as a table in the Chart window.

SimTalk:
GraphTable
.topic 0x8869129b
Select how the Chart shows the data to be visualized: In Rows or in Columns. This way you can present different views of the same record.

SimTalk:
DataInColumn
.topic 0x85530922
To display the Chart itself in the Frame, instead of the icon of the object, select this. We advise to increase the size of the icon of the Chart in the Frame: Hold down Shift+Ctrl, grab one of the four corners of the icon with the mouse and drag the icon to a convenient size.

SimTalk:
DisplayInFrame
.topic 0x85530c0e
To interrupt the line, which the Chart draws for values that are not defined, select this. To continue drawing the line, clear the check box.

SimTalk:
GapWhenNull
.topic 0x85530a1f
Enter the value the Chart takes to be as an undefined value. When a point takes this value, the Chart does not display it. The default value is -999999, i.e., a value that most likely none of the values to be displayed ever takes.

SimTalk:
NullValue
.topic 0x85530862
To create an accumulated histogram, select this. As the Chart then adds the sum of all previous values to each value, the last value thus will be 100 percent.

SimTalk:
Accumulated
.topic 0x85530c2c
To show a step curve instead of straight lines connecting the data points, select this. A step curve might show some trends more clearly but might not quite be as accurate as the straight lines.

SimTalk:
StepCurve
.topic 0x886a12b4
To show grid lines on the Y-axis in the display window of the Chart, select this. To hide them, clear the check box.

SimTalk:
XGrid, YGrid
.topic 0x886a12b5
To show grid lines on the X-axis in the display window of the Chart, select this. To hide them, clear the check box. Enter the maximum Number of grid lines that the Chart shows on the X-axis.

SimTalk:
YGrid, XGrid
.topic 0x886a12b9
Enter the number of grid lines, which the Chart shows on the X-axis. The Chart also shows a label for each grid line on the X-axis. When you are displaying a large number of data sets, it makes sense to enter a smaller number so that the labels can be shown completely. When the number of grid lines is greater than the number of data sets on the X-axis, the Chart only shows as many grid lines as there are data sets. When the number of grid lines is smaller than the number of data sets, the Chart reduces the number of grid lines and labels.

SimTalk:
XGridlines
.topic 0x886a12b7
To activate logarithmic scaling on the Y-axis, select this. This is useful if the data to be displayed is scattered across several orders of magnitude. Logarithmic representation cannot show negative values.

SimTalk:
YLog
.topic 0x886a12b8
To activate logarithmic scaling on the X-axis, select this. This is useful if the data to be displayed is scattered across several orders of magnitude. Logarithmic representation cannot show negative values.

SimTalk:
XLog
.topic 0x886a14f6
For the Category > Plotter you can enter the number of values the Chart collects over time per channel. The more values the Chart collects, the more memory the program uses. Once the Chart reaches the number you entered, it starts dropping the least recent values.

SimTalk:
NumValues
.topic 0x886a14f7
To add a scrollbar to the Chart window for the setting Category > Plotter, select this. Clear the check box to not add a scrollbar. When the scrollbar is active, you can enter a Feed rate in grid units, which sets the number of grid units by which the Chart scrolls, when it reaches the right border of the display.

SimTalk:
Scrollbar
.topic 0x886a14fa
For the Category > Plotter you can enter a feed rate in grid units, which sets the number of grid units by which the Chart scrolls, when it reaches the right border of the display. You can enter a number between 0.1 and 12. Enter 0.1 for smooth scrolling, enter 12 to scroll the entire page.

SimTalk:
FeedRate
.topic 0x886a12bc
For the Category > Histogram you can enter a step size. This is the width of the intervals into which the Chart divides the frequency distribution.

SimTalk:
StepSize
.topic 0x886a12c0
Enter the first value of the range the Chart is to display on the Y-axis into the left text box. The default setting 0 ... * means that the program shows the vales between 0 and the largest displayed value.

SimTalk:
YScaleMin
.topic 0x886a12c1
Enter the last value of the range the Chart is to display scaled on the Y-axis into the right text box. Use the asterisk * to designate open or semi-open ranges along the Y-axis and along the X-axis.

SimTalk: YScaleMax.
.topic 0x886a12df
Enter the first value of the range the Chart is to display scaled on the X-axis in the left text box.

SimTalk:
XScaleMin
.topic 0x886a12be
Enter the last value of the range the Chart is to display scaled on the X-axis in the right text box. The default setting 0 … 0 means that the program shows the entire range of definition.

SimTalk:
XScaleMax
.topic 0x886a14f8
When you select the Category > Plotter, the Range X defines the time span, which the Chart shows in the display. Or define the Feed rate by which the Chart scrolls when it reaches the right hand side of the display. You can enter a number between 0.1 and 12. The number 0.1 stands for smooth scrolling, while 12 scrolls the entire page.

SimTalk:
XRange
.topic 0x8868129a
Enter any text that the program shows as the title of the Chart in the Chart window in this text box. Select a font for the Title, select if you want to use Bold face and/or Italic face and select a relative Size on the Tab Font.

SimTalk:
Title
.topic 0x886812a3
Enter any text that the program shows as the subtitle of the Chart in the Chart window in this text box. Select a font Subtitle, select if you want to use Bold face and/or Italic face on the Tab Font.

SimTalk:
Subtitle
.topic 0x886812a4
Enter any text that the program shows in the Chart window on the X-axis.

SimTalk:
XLabel
.topic 0x8868129c
Enter any text that the program shows in the Chart window on the Y-axis.

SimTalk:
YLabel
.topic 0x886812a6
Enter any text that the program shows in the Chart window on the Z-axis.

SimTalk:
ZLabel
.topic 0x886812db
Select if and on which side of the Chart window the program shows the legend for the values the Chart displays.

SimTalk:
LegendLocation
.topic 0x886812a1
To open the table Annotations, click Annotations. Add additional lines and text to the Chart.

SimTalk:
Annotations

.topic 0x887012e8
To add additional colors to the color table, click Add. Define a color in the dialog Colors, and click OK to add that color to the bottom of the Color table.
.topic 0x887012e6
To delete the color you selected from the Color table, click Delete.
.topic 0x887015c6
For the Chart types Line with Markers and Spline with Markers you can select the size of the markers from the drop-down list.
.topic 0x886b12c4
Select a font from the drop-down list for the labels. This font does not apply to the Title, the Subtitle and to data displayed in Table format in the Chart window.

SimTalk:
LabelFont
.topic 0x886b12c6
To apply bold face to all labels, select Bold. This does not apply to the Title, the Subtitle and to data displayed in Table format in the Chart window.

SimTalk:
LabelFont
.topic 0x886b12c2
To italicize all labels, select Italic. This does not apply to the Title, the Subtitle and to data displayed in Table format in the Chart window.

SimTalk:
LabelFont
.topic 0x886b12c3
Select a size for the lettering for all labels. This does not apply to the Title, the Subtitle and to data displayed in Table format in the Chart window.

SimTalk:
LabelFont
.topic 0x886b12cc
Select a font from the drop-down list for the Title of the Chart displayed in the Chart window.

SimTalk:
TitleFont
.topic 0x886b12cd
To apply bold face to the Title of the Chart which is displayed in the Chart window, select Bold.

SimTalk:
TitleFont
.topic 0x886b12c5
To italicize the Title of the Chart which is displayed in the Chart window, select Italic.

SimTalk:
TitleFont
.topic 0x886b12cb
Select a size for the lettering from the drop-down list for the Title of the Chart displayed in the Chart window.

SimTalk:
TitleFont
.topic 0x886b12d2
Select a font from the drop-down list for the Subtitle of the Chart which is displayed in the Chart window.

SimTalk:
SubtitleFont
.topic 0x886b12d3
To apply bold face to the Subtitle of the Chart which is displayed in the Chart window, select Bold.

SimTalk:
SubtitleFont
.topic 0x886b12d0
To italicize the Subtitle of the Chart which is displayed in the Chart window, select Italic.

SimTalk:
SubtitleFont
.topic 0x886b12d8
Select a font from the drop-down list for data, which the Chart shows in Table format in the Chart window.

SimTalk:
TableFont
.topic 0x886b12d7
Select a size for data, which the Chart shows in Table format in the Chart window.

SimTalk:
TableFont
.topic 0x8db30db5
Select if the Checkbox is active (true) or not active (false). Plant Simulation automatically switches between the icons of the checkbox according to their name/state. Always create a set of two icons, one for on and one for off, and name them accordingly. Assign names in pairs to the icons according to their state, for example TrueIcon1 and FalseIcon1.

SimTalk:
Value
.topic 0x8db30db7
Click this and select a Method object. Enter the source code of the control which is going to be executed when the Value of the Checkbox changes.

SimTalk:
Control
.topic 0x88a213a5
Enter a name of your choice for the Comment into this text box or accept the name which the program suggests. You can enter a combination of letters, digits, and underscore (_) characters, for example MyComment, MyComment1, My_Comment_1. The name of an object cannot start with a digit, i.e., you cannot enter 1Comment.

SimTalk:
Name
.topic 0x890413a3
Enter a detailed description appending the short note you entered into the Text box on the Tab Display.

SimTalk:
Cont,
appendToContent
.topic 0x88a413a2
To inherit or not inherit the contents of the Comment, click the toggle button next to the text box.
.topic 0x88a41501
To save the contents of the text box in rich-text format, which preserves all of the formatting properties which you applied, select this.

SimTalk:
SaveAsRichedit
.topic 0x88a3139c
Enter the text that the program shows, when you insert the Comment object into a Frame. Enter a short text, or you will not be able to see or select the Comment in the Frame.

SimTalk:
Text
.topic 0x88a3139d
To inherit or not inherit the Text of the Comment, which you enter into the box to the left, click the toggle button.
.topic 0x88a3139f
Select a font size for displaying the Comment in the Frame, into which you inserted it.

SimTalk:
Font
.topic 0x88a313a0
To select the color of the text proper with which Plant Simulation shows the Comment in the Frame, click the drop-down arrow. The program only shows the color in the Frame into which you inserted the Comment, not in the open dialog window.

SimTalk:
Color
.topic 0x88a313a2
To select the color of the background of the Comment which you inserted into a Frame, click the drop-down arrow.

SimTalk:
BackgroundColor
.topic 0x88a3139e
To make the background of a Comment object, which you inserted into a Frame, shine through the hollow parts of the text, select Transparent.

SimTalk:
Transparent
.topic 0x885c123d
To show the dialog with the dialog items you created, click Show Dialog. The Dialog executes the Callback method with the parameters you entered into the text boxes for Argument for open, Argument for apply or Argument for close, so that you can detect if they perform the functions you programmed.

SimTalk:
openDialog, open
.topic 0x885c123e
To edit a dialog item which you created in the Dialog, click Edit Dialog. The Dialog then selects the dialog item in the display window and you can move it by dragging it to another to another position. To edit its properties, click it with the right mouse button and select Open on the context menu.
.topic 0x87db1517
To insert a dialog item into the dialog you are creating, click into the text box with the right mouse button and select the respective item on the context menu. Or select to show or hide the OK, Cancel and Apply buttons (Show default buttons) and to open the dialog you create modal, meaning that the user cannot open another dialog until he closes the present dialog (Open modal). Once you have inserted dialog items, the tree shows the structure of your dialog. Changing the order in the structure modifies the layout of the dialog. To change the order of the tabs in the dialog, select a tab on the tab Elements, hold down the Shift key and press the up arrow or the down arrow to move this tab to the left or to the right. The dialog shows the first tab in the structure as the leftmost tab.
.topic 0x890b1519
Select what kind of characters the user can enter into the text box.
.topic 0x890b1517
To show a password that the user enters into the text box with superscripted lower case Xes, instead of as clear text, select this.

SimTalk:
setPasswordMasking, getPasswordMasking
.topic 0x88fb1528
Enter the name of a table or click the button and select a table in the dialog Select Object. Activate the column index in the TableFile and enter the column headings the list view shows into the header cells. Enter the items the list view shows into the cells of the columns.

SimTalk:
setTable, getTable
.topic 0x885d1240
Enter the name of the dialog item. The Dialog shows this Name in the text box on the tab Elements. You can enter the same Name for dialog items, as long as those dialog items are not located in the same group of items. Groups of items are: Group Box, Menu, Tab Control and Tab. We recommend to enter a unique identifier, containing the type of dialog item, for example xyz_button, xyz_list, etc. A Method object can call this dialog item using the Name you entered. For some dialog items you can enter a Caption in addition.

SimTalk:
setCaption, getValue
.topic 0x885d1241
Enter the text the Dialog shows as the caption of the dialog item in your dialog. A caption is especially handy if you develop application object libraries in several languages and want the user to be able to switch languages. In addition you can enter special characters and blanks, which you cannot use in the name.

SimTalk:
setCaption, getValue
.topic 0x890c1513
Enter the parameter that is passed to the callback method. The Callback method executes this parameter when the user performs the respective action. Be aware that the parameters are case-sensitive!

SimTalk:
setCallbackArgument
.topic 0x885d1245
Enter the position on the X-axis, where the program places the dialog item in the Dialog you define. This value corresponds to the average width of characters of your system font, not to pixels. If you cannot see the dialog items you inserted, check the settings for the position first. If you entered identical values for different dialog items, the Dialog places them on top of each other, so that you can only see the first item(s) you inserted.

SimTalk:
DialogX
.topic 0x885d1246
Enter the position on the Y-axis, where the program places the dialog item in the Dialog you define. This value corresponds to lines of characters of the system font, not to pixels. You can enter a value from 0 to 10 for example. If you cannot see the dialog items you inserted, check the settings for the position first. If you entered identical values for different dialog items, the Dialog places them on top of each other, so that you can only see the first item(s) you inserted.

SimTalk:
DialogY
.topic 0x88fb151a
Enter a group id, i.e., a number, for grouping any number of radio buttons to denote, which radio buttons belong together. Group ID 1 might stand for one set of radio buttons, while Group ID 2 might stand for another set. The user can only select one radio button of a group.

SimTalk:
setGroupID
.topic 0x8914151c
Enter an Image ID, i.e., the number of the icon, or the name of the image. The image is an icon of the Dialog to which the image belongs.

SimTalk:
createImage, setIcon, getIcon
.topic 0x890c1512
Enter the width of the dialog item in the average width of characters of your system font. The default value of 0 sets the width to the values defined by us.
.topic 0x886912b3
Enter the height of the dialog item in lines of characters of your system font. The default value of 0 sets the height to the values defined by us.
.topic 0x890c1516
Select Enable to activate the respective dialog item in the Dialog. When the user selects it, it triggers the Callback method, which executes the actions you programmed. Clear it to deactivate the dialog item, i.e., to gray it out in the Dialog, and thus make it not available to the user.

SimTalk:
setSensitive
.topic 0x885d127d
For a dialog item of Type New Drop-Down List Box and New List Box the Dialog shows the button Items. Click it to open a dialog into which you enter the items they show.

SimTalk:
setIndex, getIndex
.topic 0x89031552
Click this and enter the items which the drop-down list box and the list box show into the dialog Items. To add an item to the list field, enter its name into the text box and click Insert or press the Enter key. Repeat this for all the items you want to add. To delete an item from the list, select it in the list field and click Delete. To move an item up one position in the list, select it in the list field and click Move Up. To change the name of an item in the list, select it in the list field, type another name into the text box, and click Rename.
.topic 0x87db125d
To show the standard buttons in the dialog you are creating, select this. To hide these buttons, clear the check box.

SimTalk:
ShowStandardButtons
.topic 0x87db109a
To open the dialog window you are creating modal, select this. Then, the user cannot open any other Plant Simulation dialog windows until he closes the window of the user-defined dialog. To allow the user to open other dialog windows in addition to the dialog you are creating, clear the check box.

SimTalk:
OpenModal
.topic 0x885f1251
Enter the position on the X-axis of your computer screen at which the program shows the Dialog, when you open it. The default setting -1 for both X-position and Y-position centers the Dialog on screen.

SimTalk:
DialogX
.topic 0x885f1250
Enter the position on the Y-axis of your computer screen at which the program shows the Dialog, when you open it. The default setting -1 for both X-position and Y-position centers the Dialog on screen. The unit is pixels, the zero point is the left top corner of the screen.

SimTalk:
DialogY
.topic 0x884d1214
Click this and select a Method object. It contains the actions, which the dialog items execute. Or you can accept the default, namely the user-defined attribute of type method named self.callback.

SimTalk:
CallbackMethod
.topic 0x88fb1523
Enter the callback argument, i.e., a string, for the Open action, which the Dialog executes, when it executes the Callback method. The default setting is Open. The Open section of the callback method initializes the contents of the dialog window or sets the dialog items to values of your choice.

SimTalk:
ArgumentForOpen
.topic 0x88fb1524
Enter the callback argument, i.e., a string, for the Apply action, which the Dialog executes, when it executes the Callback method. The default setting is Apply. The Dialog executes the Apply section of the callback method, when the user clicks OK or Apply in the dialog window of the Dialog you define. The source code you enter may evaluate new or changed values.

SimTalk:
ArgumentForApply
.topic 0x88fb1525
Enter the callback argument, i.e., a string, for the Close action, which the Dialog executes, when it executes the Callback method. The default setting is Close. The Dialog executes the Close section of the callback method, when the user clicks Cancel in the dialog window of the Dialog you define, or when he closes it with Close on the title bar.

SimTalk:
ArgumentForClose
.topic 0x886510e9
To activate the display of the Display, select this. When the Display is not active, the program shows its icon in the Frame instead of a value.

SimTalk:
Active
.topic 0x8813105d
Click this and select the attribute or method, whose value the Display displays. If you want to show the value of a global variable, you can enter the path to the Variable itself. Or enter an expression, such as buffer.numMU+1.

SimTalk:
Path
.topic 0x8813105c
Enter a brief description (Comment) of the displayed value. You might enter the name of the attribute that the Display displays, such as Fill level buffer. The Display shows this text below the value in the Frame window.

SimTalk:
Comment
.topic 0x8813105e
Select the operating mode of the Display. Sample mode updates the display with the frequency you enter into the text box Interval. Watch mode updates the displayed value any time the value changes.

SimTalk:
Sampler, SmpPeriod
.topic 0x8813105f
When you select Sample mode, the Display shows the text box Interval. Enter the update frequency of the display.

SimTalk:
SmpPeriod
.topic 0x8813118b
When you select Bar or Pie mode, the Display shows the minimum reached value here.

SimTalk:
getMinimum
.topic 0x8813118c
When you select Bar or Pie mode, the Display shows the maximum reached value here.

SimTalk:
getMaximum
.topic 0x8813118a
When you select Bar or Pie mode, the Display shows the current value here.

SimTalk:
getValue
.topic 0x881310e3
To reset the minimum and maximum values shown on the tab, click this.

SimTalk:
resetMinMax
.topic 0x88141099
Select how the Display displays the data it records. Text mode shows the value as text. Bar and Pie mode map the value to a range of values. They visualize values inside the range by the height of a bar or a filled segment of the pie. An empty bar/pie corresponds to values below or equal to the lower bound. A full bar/pie represents values above or equal to the upper bound.

SimTalk:
DisplayType
.topic 0x88141065
Enter the Minimum value of the displayed range of values.

SimTalk:
MinVal
.topic 0x881410e7
Enter the Maximum value of the displayed range of values.

SimTalk:
MaxVal
.topic 0x88141063
Select the font size of the text and of the Comment, which the Display displays in Text mode.

SimTalk:
Font
.topic 0x88141064
To make the background of a Display, which you inserted into a Frame, transparent, select this. Then, the Display shows the space around the text in the color you selected as the Color on the background of the Frame, i.e., the background color of the Frame shines through the hollow parts of the text.

SimTalk:
Transparent
.topic 0x8d53040b
Click this to open the list into which you enter the items which the Drop-Down List displays when you click it.

SimTalk:
Items, Item
.topic 0x8e0b0864
Enter which item in the Drop-Down List will be selected when you open it. This is one of the items which you entered in the list of Items. The value is identified by its index number.

SimTalk:
Value
.topic 0x88e414f1
To open the display window of the Report, click this.
The Display Pane of the Display Window on the right-hand side shows the content of the report which you define on the Tab Content.
The Structure Pane of the Display Window on the left-hand side shows the first two heading levels of the report. Click on a heading in the structure pane to jump to this location in the display pane.

SimTalk:
show
.topic 0x88f00ef6
Define the content which the HtmlReport is to display.
You can enter the content of the HtmlReport as text or you can enter and select settings in the dialog Object Parameters. You define special elements, such as headings, tables, and pictures in purely textual form. Or drag an object from the Frame to the tab Content and drop it there.

.topic 0x8f0a0f0e
Enter the caption which the HtmlReport shows below the statistics table on the HTML page.
.topic 0x8f0a0f16
Enter the identifiers of the columns of the TableFile/List which the HtmlReport shows on the HTML page.
.topic 0x8f0a0f12
Enter the image width with which the HtmlReport shows the picture of the object. Or enter an asterisk (*) for either the width or the height to ensure that the image will not be distorted.
.topic 0x8f0a0f14
Enter the image height with which the HtmlReport shows the picture of the object. Or enter an asterisk (*) for either the width or the height to ensure that the image will not be distorted.
.topic 0x8f0a0f10
Enter the relative Image size in percent to which the HtmlReport scales the screenshot of the object. Instead you can also enter the Image width and the image height. Or enter an asterisk (*) for either the width or the height to ensure that the image will not be distorted. The relative size takes preference over the absolute size.
.topic 0x8f0a0f19
To use the font size and the font color, which you selected for the object Display, on the HTML page, select this.
.topic 0x8f0a0f1a
To show the label of the object Checkbox to the right of the check mark on the HTML page, select this.

.topic 0x88b913e4
To activate the ActiveX control, select this. To deactivate it, clear the check box. You can only activate the ActiveX control after you entered the Class name and the Callback method!

SimTalk:
Active
.topic 0x88bb13e6
Enter the class name of the required ActiveX control. The menu command Tools > ActiveX Class Overview opens a table that shows all ActiveX controls, which are installed on your computer. You might enter excel.application, for Microsoft Excel, word.application, for Microsoft Word, or access.application for Microsoft Access.

SimTalk:
ClassName
.topic 0x88bb13e8
If the ActiveX control requires a license key, enter it here. Normally you do not have to enter a license key.

SimTalk:
LicenseKey
.topic 0x88bb13e9
Click this and select a Method. The program calls this method, as soon as the ActiveX control triggers an event.

SimTalk:
Callback
.topic 0x88bb13ea
To show the active ActiveX control in the Frame, into which you inserted object ActiveX, select this. The program then displays the icon of the ActiveX control on top of the icon of the object.

SimTalk:
InFrame
.topic 0x889c1375
Select or enter the name of the data source (Data Source Name), which you assigned, when you created the user data source. If you would like to work with the default server, you do not have to enter anything. The default server usually is the local server. The list shows all data sources which are available on your computer network.

SimTalk:
DataBase
.topic 0x889c1376
To open the table Info Driver, click this. It shows information about the used driver.

SimTalk:
infoDriver
.topic 0x889c1377
To open the table Info Data Source, click this. It shows information about the used data source.

SimTalk:
infoDataSource
.topic 0x889c1378
To open the table Info Data Types, click this. It shows information about the supported data types.

SimTalk:
infoDataTypes
.topic 0x889c1379
Enter the User name and the Password if your data sources require them.
.topic 0x889c137a
Enter the Password after you entered the User name if your data sources require them.
.topic 0x861709f1
Select this to save the Password in the model file in encrypted form.
.topic 0x889c137b
Select this to stop the execution of the active method and to show the SQL error in the Debugger. Clear the check box to continue executing the method.

SimTalk:
sqlError, ErrorStop
.topic 0x889c137d
Select Format table to automatically format the data table according to the requirements.

SimTalk:
FormatTable
.topic 0x889c1381
Select if the driver (Data Conversion by Driver) or the program (Data Conversion by Application) converts the data.
.topic 0x889c137e
The message window shows the message, which was returned for the last interaction with the database.

SimTalk:
sqlError
.topic 0x889c137f
To log on to the database, click this. After a successful Login, you can click the buttons Driver, Data Source, and Data Types to open tables containing information about the current driver/data source connection.

SimTalk:
login
.topic 0x889c1380
Click Logout to log out of the database.

SimTalk:
logout
.topic 0x88b313d4
To start Gantt and to show the data, which the GanttChart collected in the display window, click this.

SimTalk:
Active
.topic 0x88b413d0
To open the table file containing the settings for displaying planning data, click Options.

SimTalk:
SettingsTable
.topic 0x88b41296
To open the table file containing the planning data proper, click Data.

SimTalk:
DataTable
.topic 0x88b413d1
Before you can enter data, click the toggle button Inheritance, so that it looks like this.
.topic 0x88b41297
Before you can enter data, click the toggle button Inheritance, so that it looks like this.
.topic 0x888a1318
Enter the number of parent individuals of a generation. This value is the number of families within a generation.

SimTalk:
GenerationSize
.topic 0x888a1319
Enter the maximum number of generations for which you would like to perform the optimization. Once that number of optimization steps is reached, the termination control is called.

SimTalk:
NumGenerations
.topic 0x888a131b
Before you can enter data, click the toggle button Inheritance, so that it looks like this.
.topic 0x888a131a
Click Task to open a list, into which you enter the paths to the tables that define the optimization task. Each row stands for a basic task that is part of the entire problem.

SimTalk:
TaskTable
.topic 0x888c131c
Select whether the optimum is going to be a high (maximum) or a low fitness value (minimum).

SimTalk:
Direction
.topic 0x888c131d
Enter the fitness limit of the optimization run. When at least one individual reaches or exceeds this value, the program terminates the optimization and calls the termination control. Otherwise it executes the number of optimization runs, which you enter as the Number of generations.

SimTalk:
FitnessTarget
.topic 0x888c131e
Enter the Average fitness for the individuals of a generation. Once the program reaches this value, it terminates the optimization run. Otherwise it executes the number of optimization runs, which you enter as the Number of generations.

SimTalk:
FitnessTargetAverage
.topic 0x888e131f
Select if the fitness value of the individual proposed solutions is evaluated relative to the worst solution of the generation or relative to absolute zero. Absolute or Relative.

SimTalk:
FitnessReference
.topic 0x888e1320
Select if the parent selection is going to be deterministic, according to its fitness value, or randomly, where all individuals have the same likelihood to be used as parents. Deterministic or Random.

SimTalk:
ParentSelection
.topic 0x888e1321
Select this to take the best solution of a generation over unchanged into the next generation. Clear it to not take it over.

SimTalk:
CloneBestSolution
.topic 0x888e1322
Select how the GAOptimization selects family members, which are going to be used in the next generation: 1of2 Only uses the two child solutions and selects the solution with the better fitness value. 1of4 Uses parent and child solutions and selects the best solution. Prob (probabilistic) Uses parent and child solutions. It employs a stochastic selection. Selection probabilities are proportional to the quality of the solution. Random Selects the individual taken for the new generation regardless of the fitness value.

SimTalk:
OffspringSelection
.topic 0x88921324
Click this and select a Method object. It contains the source code on how to evaluate the newly generated individuals. The program calls it, when the individuals of a new generation have been created. These newly generated individuals are going to be passed to the method as parameter of data type table. Within the method or within a simulation run started by the method, the fitness value is going to be calculated for each newly created individual of the generation. The simulation model calculates the fitness value and writes it into column 2 of the table.

SimTalk:
EvaluationCtrl
.topic 0x88921325
Click this and select a Method object. It controls the alternation of generations. The GAOptimization calls it, when a generation and its offspring generation have been completely evaluated.

SimTalk:
GenerationChangeCtrl
.topic 0x88921326
Click this and select a Method object. Enter the source code of the termination control. The GAOptimization calls it, when the optimization run is terminated. An optimization run is terminated, when evaluation runs have been performed for all generations or when the limit for fitness or the fitness average has been reached or has not been reached. A table containing information about the active and older generations is going to be passed as parameter to the method.

SimTalk:
TerminationCtrl
.topic 0x88921327
Click this and select a Method object. Enter the source code of the error handling control. The GAOptimization calls it, when an error occurred during the optimization. Two parameters are passed to the Method that is called. The first parameter, of data type integer, is the number of the error. The second parameter, of data type string, describes the error itself.

SimTalk:
ErrorCtrl
.topic 0x88941328
Click Adults to open a table, which shows the proposed solutions and fitness values of the active parent generation.
.topic 0x88941329
To open the table, which shows the proposed solutions and fitness values of the active child generation, click this.
.topic 0x8894132a
To open a table, which shows the relationships of the individuals of the child generation to the individuals of the parent generation, click this.
.topic 0x8894132b
Select this and click Apply to save the tables Children, Families and Adults for all generations during the evolution cycle.

SimTalk:
Evolution
.topic 0x8894132c
Click Evolution to open a table that shows data for the Population, Adults, Children, and for Families.
.topic 0x8894132d
To open a table that shows the best solutions of all generations until now, click this.
.topic 0x8894132e
Enter the number of best solutions, which the GAOptimization is going to save.

SimTalk:
NumBestSolutions
.topic 0x8894132f
To open a table that shows the Best Fitness, Average Fitness and Worst Fitness value for each Generation evaluated until the current simulation time, click this.
.topic 0x887a1305
Enter the share of chromosomes in percent that may be created for the initial generation by using the initialization data.

SimTalk:
InitRate
.topic 0x887a1303
Select the data type of the items of the chromosomes.

SimTalk:
DataType
.topic 0x887a1307
Enter the default minimum value that the GARangeAllocation uses when you did not enter an explicit Minimum for the item on the tab Contents.

SimTalk:
StandardMinimum
.topic 0x887a1308
Enter the default maximum value that the GARangeAllocation uses when you did not enter an explicit Maximum for the item on the tab Contents.

SimTalk:
StandardMaximum
.topic 0x887a1309
Enter the default interval value that the GARangeAllocation uses when you did not enter an explicit Interval for the item on the tab Contents.

SimTalk:
StandardInterval
.topic 0x887c130e
Enter a value for the probability, which refers to the entire individual of the genetic operator, which is going to be applied to a newly created chromosome.

SimTalk:
CrossoverProb, CrossoverDelta
.topic 0x887c130f
Enter a value for the probability, which refers to each individual item of the genetic operator, which is going to be applied to a newly created chromosome.

SimTalk:
MutationProb, MutationDelta
.topic 0x887c1310
Enter a value for the delta per generation, which sets the change of the probabilities for the genetic operators over the generations.

SimTalk:
CrossoverProb, CrossoverDelta
.topic 0x887c1311
Enter a value for the delta per generation, which sets the change of the probabilities for the genetic operators over the generations.

SimTalk:
MutationProb, MutationDelta
.topic 0x887312e9
Enter the share of chromosomes (in percent) that may be created for the initial generation by using the initialization data.

SimTalk:
InitRate
.topic 0x887312ea
Select the data type of the items of the chromosomes.

SimTalk:
DataType
.topic 0x887312eb
Enter the number of items that are to be selected from the definition set.

SimTalk:
Selection
.topic 0x887412ec
Select the type of crossover: OX (Order Crossover) attempts to preserve the relative position and thus the sequence of items of a chromosome as far as possible. If an item is contained in the remaining set of chromosome 1 and in the crossover set of chromosome 2, it will be eliminated from the remaining set and the following items will move up. PMX (Partially Matched Crossover) makes the absolute position of the items take precedence over the sequence. If an item is contained in the remaining set of chromosome 1 and in the crossover set of chromosome 2, this item is replaced by an item from the crossover set in chromosome 1 that is not contained in the crossover set of chromosome 2.

SimTalk:
CrossoverOperator, CrossoverProb, CrossoverDelta
.topic 0x887412ed
Select the genetic operator: The Inversion Operator inverts the sequence within a defined range of the individual. The Mutation Operator randomly changes individual genes. When you select inversion, you can enter a value for the Start probability and for the Delta per generation. When you select mutation, you can enter a value for the Start probability and for the Delta per generation.

SimTalk:
Mutation
.topic 0x887412ee
Enter a value for the probability of the genetic operators Mutation and Inversion and Crossover, which is going to be applied to a newly created chromosome.

SimTalk:
CrossoverProb, CrossoverDelta, InversionProb, InversionDelta, MutationProb, MutationDelta
.topic 0x887412f5
For the setting mutation the probability refers to each individual item.

SimTalk:
MutationProb, MutationDelta
.topic 0x887412f0
For the settings inversion and crossover the probability refers to the entire individual.

SimTalk:
CrossoverProb, CrossoverDelta, InversionProb, InversionDelta
.topic 0x887412f1
Enter a value for the delta per generation that sets the change of the probabilities for the genetic operators over the generations.

SimTalk:
CrossoverProb, CrossoverDelta
.topic 0x887412f3
Enter a value for the delta per generation that sets the change of the probabilities for the genetic operators over the generations.

SimTalk:
MutationProb, MutationDelta
.topic 0x887812f4
Enter the share of chromosomes in percent that may be created for the initial generation by using the initialization data.

SimTalk:
InitRate
.topic 0x887812f6
Select the data type of the items of the chromosomes.

SimTalk:
DataType
.topic 0x887812f8
Enter the number of samples after which the genetic algorithm terminates its random search for an initial solution for the start generation.

SimTalk:
NumOfGaSamples
.topic 0x887812f9
Enter the number of crossover trials that the genetic algorithm executes to realize the placements in the matching intersecting range. A rearrangement attempt consists of the search for the cycle exchange for the items of the matching intersecting range.

SimTalk:
NumOfCrossOverTrials
.topic 0x887812fa
Enter the number of mutation trials, which the genetic algorithm executes by using cycle exchanges to meet the position restrictions you defined.

SimTalk:
NumOfMutationTrials
.topic 0x887812fb
Enter a number for the degree of mutation correction, which is the maximum length of the cycles for a cycle exchange that a mutation triggered.

SimTalk:
DegreeOfCorrection
.topic 0x887912fc
Select the type of crossover: OX (Order Crossover) attempts to preserve the relative position and thus the sequence of items of a chromosome as far as possible. If an item is contained in the remaining set of chromosome 1 and in the crossover set of chromosome 2, it will be eliminated from the remaining set and the following items will move up. PMX (Partially Matched Crossover) makes the absolute position of the items take precedence over the sequence. If an item is contained in the remaining set of chromosome 1 and in the crossover set of chromosome 2, this item is replaced by an item from the crossover set in chromosome 1 that is not contained in the crossover set of chromosome 2. Then, enter a Start probability, and a Delta per generation.

SimTalk:
CrossoverOperator, CrossoverProb, CrossoverDelta
.topic 0x887912fd
Enter a value for the start probability of the corresponding genetic operator, which is going to be applied to a newly created chromosome.

SimTalk:
CrossoverProb, CrossoverDelta, InversionProb, InversionDelta, MutationProb, MutationDelta
.topic 0x887912fe
Enter a value for the delta per generation that sets the change of the probabilities for the corresponding genetic operators over the generations.

SimTalk:
CrossoverProb, CrossoverDelta, InversionProb, InversionDelta, MutationProb, MutationDelta
.topic 0x887912ff
Select the genetic operator: The Inversion Operator inverts the sequence within a defined range of the individual. The Mutation Operator randomly changes individual genes. When you select inversion, you can enter a value for the Start probability and for the Delta per generation. When you select mutation, you can select the Mutation Operator, which the genetic algorithm uses, and enter a value for the Start probability and for the Delta per generation.

SimTalk:
Mutation, InversionProb, InversionDelta, MutationProb, MutationDelta
.topic 0x88791300
When you select mutation, you can also select the mutation operator, which the genetic algorithm uses: For random mutations you can define the probabilities for exchanging an item. For a fixed number of mutations you will click Plan and enter the number of mutations per chromosome for each generation.

SimTalk:
MutationOperator
.topic 0x88791301
Enter a number for the Start probability to define the probability for exchanging an item in the first generation.
.topic 0x88791302
Enter a number for the Delta per generation to define the change of this probability for the genetic operators, when the generation changes.
.topic 0x88791312
The GASequence shows the button Plan. It opens a table with four columns of data type integer, where you define the number of mutations per chromosome for each generation. Decreasing the number of mutations allows you to better search for a local optimum during the end phase of the optimization. Enter the first generation into the cells of the column Generation (from), and the number of mutations for this and the following generations into the column Number of Mutations. Modify the number of mutations for a generation by entering values into another line/row of the table. Make sure that column 1 of the table is sorted in ascending order. Enter the number of positions the genetic algorithm may move an item up into the column Max. Position Offset (up) or down into the column Max. Position Offset (down). This is called position offset restriction of a mutation (compare Mutation Operator for sequence tasks). When you do not enter values into the columns Max. Position Offset (up) and Max. Position Offset (down), the genetic algorithm uses a mutation without position offset restrictions.

SimTalk:
Mutation, MutationOperator, MutationPlan
.topic 0x88791304
Enter a value for the start probability of the corresponding genetic operator being applied to a newly created chromosome.

SimTalk:
CrossoverProb, CrossoverDelta, InversionProb, InversionDelta, MutationProb, MutationDelta
.topic 0x88791306
Enter a value for the delta per generation that sets the change of the probabilities for the corresponding genetic operators over the generations.

SimTalk:
CrossoverProb, CrossoverDelta, InversionProb, InversionDelta, MutationProb, MutationDelta
.topic 0x887b130a
Enter the share of chromosomes in percent that may be created for the initial generation by using the initialization data.

SimTalk:
InitRate
.topic 0x887b130b
Select the data type of the items of the chromosomes.

SimTalk:
DataType
.topic 0x887b130d
Before you can enter data, click the toggle button Inheritance, so that it looks like this.
.topic 0x887b130c
Click this and enter the default values of the allocation set into the table. The GASetAllocation uses this default set, if you did not enter a value for an item into the column Allocation Sets of the table on the tab Contents.

SimTalk:
DefaultSet
.topic 0xaf1536e0
To activate the OPCInterface and to write status messages to the Console, select this. To deactivate it, clear it.

SimTalk:
Active
.topic 0xaf1636e4
Enter the name or the IP address of the host computer on which the OPC server runs. If the OPC server runs on the same computer as the OPCInterface or as the PLC, you can leave this field empty. When the OPC server is running remote on another host, you have to configure DCOM as described under Configuring DCOM for Remote Access.

SimTalk:
HostName
.topic 0xaf1636e2
Enter the name of your OPC server. You might enter OPC.Simatic.Net or Matricon.OPCServer, etc.
.topic 0x8cee86fe
Click this to open a list of all servers which are available via the host you entered. Selecting a server in the list inserts it into the text box server name.

SimTalk:
ServerName
.topic 0xaf1636e3
To open the table into which you enter the OPC items, click this. Each row in this table represents a group. Enter the names of the groups into the cells below Group Name. Enter the time in milliseconds after which Plant Simulation updates the values into the cells below Update Interval. Enter the time in milliseconds into the cells below Write Interval. Click Apply. Click in the cell below Group Name and press F2 to open the items list proper for this group. Then, define the items of that group in the sub-table. The items, which you can enter, depend on the respective program running in the PLC control and on the OPC server you are using. Enter the name of the item into the cells below Item Name. Select the type of the item in the cells below Type. Enter an alias for the item into the cells below Alias. Enter the name of a Method in which you defined what is to happen into the cells below Changed-Value Control. Enter the Access Path. It suggests a data path to the server. The access path is an optional piece of information that can be provided by the client. As its use is highly server-specific, we recommend to consult the documentation that came with your OPC server. The Siemens OPC server does not need this information.

SimTalk:
getItems, getItemValue, setItems, setItemValue
.topic 0x8cee0dcc
To import items from a Step7 file, click this. Then, select the.sdf file that you want to import in the dialog Open. Next enter a connection string for all item to be imported. This string will then be appended in front of the names of all items. Finally, enter the name of the callback method, which will be entered for those items, which are defined as exits in Step7.

SimTalk:
addItem, getItems, getItemValue, setItems, setItemValue
.topic 0x8cee0dc8
To open a table that shows the values of the Items you defined, click this. After you selected the group name in the table that opens, the program shows the values of the items alias, data type, and update interval of this group.
.topic 0x8e370d53
Shows how often the Changed-Value Control, which you entered into the Items table, was called.
.topic 0x8e370d15
Shows how often the method getItemValue was called.
.topic 0x8e370c71
Shows how often the method setItemValue was called.
.topic 0xaf1536e0
To activate the OPCInterface and to write status messages to the Console, select this. To deactivate it, clear it. Instead, you can also right-click the SIMITInterface object in the Frame and select Enable on the context menu. To deactivate it, select Disable on the context menu.

SimTalk:
Active
.topic 0x8e430e45
Enter the name of the shared memory block. The SIMIT server has to run on the same computer as the SIMITInterface.

SimTalk:
SharedMemoryName
.topic 0x8e430e46
Enter the time in milliseconds after which Plant Simulation updates the values, i.e., reads them from the shared memory and writes them back to it.

SimTalk:
UpdateInterval
.topic 0x8e430e44
To open the table in which you define the SIMIT items, click this. Each row in this table represents a group. Enter the name of the item into the cells below Item Name. Select the type of the item in the cells below Type. Enter an alias for the item into the cells below Alias. Enter the name of a Method in which you defined what is to happen into the cells below Changed-Value Control. For an item of data type boolean you can also enter an object of type Checkbox as the Changed-Value Control. The program passes two parameters to the Changed-Value Control that is called: The parameter of data type string designates the name of the alias which is defined in the column Alias. The parameter of data type any designates the current value of the Item. If you know the data type of the value, you can also enter it directly. Select if the item is an input value or an output value.

SimTalk:
getItems, getItemValue, setItems, setItemValue
.topic 0x8e430e48
To import items from a shared memory block provided by SIMIT, click this.

SimTalk:
getItems, getItemsFromSimit, setItems
.topic 0x8e430dcd
To open a table that shows the values of items alias, data type, and value, click this.
.topic 0x85a00a4f
To activate the object Socket as such, select this. If you are using it as a server socket, it then listens on the specified Port. If you are using it as a client socket, it attempts to connect to a server.

SimTalk:
On
.topic 0x85a10d0d
Select the protocol for transmitting the data: When you select TCP, you have to select the check box On and clear the check box Server socket for the server. For the client you have to select both On and Server Socket. This establishes a connection across which the data will be exchanged. The TCP protocol ensures that the data packages arrive at the destination. When you select UDP, you have to select On and clear Server Socket for the server. For the client you have to select Server Socket and clear On. You can now exchange data without a connection having to be established. This creates less overhead, but does not guarantee that the data actually does arrive at the destination. The object Socket also supports the IPv6 protocol.

SimTalk:
TCP
.topic 0x85a10a53
Enter the IP address of the computer with which you want to establish the connection. The number 127.0.0.1 designates the local host.

SimTalk:
Host
.topic 0x85a10a54
Enter the port number with which the socket connection exchanges data with other applications. When you cleared Server socket, you have to enter a local port number that is not already used in order to be able to select the setting On.

SimTalk:
Port
.topic 0x85a10a56
Enter the maximum number of connections which can be active at any one time.

SimTalk:
MaxConnections
.topic 0x85a10a55
Click this, and select a Plant Simulation Method. Enter the source code of the callback method. The program calls it when it receives data. During the call two parameters are passed to the method. The parameter of data type integer contains the channel number of the connection. The parameter of data type string contains the received message.

SimTalk:
CallbackMethod
.topic 0x85a10a4e
To use the object Socket as a server socket, select this. To use it as a client socket, clear the check box.

SimTalk:
ServerSocket
.topic 0x85a10a57
Enter the IP address of the client host computer with which you want to establish the connection.

SimTalk:
ClientHost
.topic 0x85a10a58
Enter the port number with which the socket connection exchanges data with client applications. When you cleared Server socket, you have to enter a local port number that is not already used in order to be able to select the setting On.

SimTalk:
ClientPort
.topic 0x88b813e1
The Socket interface shows the active connections on the tab Sessions. It lists the name of the host and, separated by a colon, the internal identifying number for each connection. When the object Socket works in Server socket mode, only this connection to the server socket process is possible.
.topic 0x861109da
Enter the server URL of the host computer on which Teamcenter runs. The default server URL is http://localhost:7001/tc.

The connection string that you enter depends on your Teamcenter provider, for example the IT department of the customer. Consult your Teamcenter provider for more information.

SimTalk:
ServerURL
.topic 0x86110A63
Enter the Active Workspace Server URL of the host computer on which Teamcenter runs. The default server URL is http://localhost:7001/awc.

The connection string that you enter depends on your Teamcenter provider, for example the IT department of the customer. Consult your Teamcenter provider for more information.

SimTalk:
ActiveWorkspaceServerURL
.topic 0x861109d5
Enter the name of the application interface type.

The connection string that you enter depends on your Teamcenter provider, for example the IT department of the customer. Consult your Teamcenter provider for more information.

SimTalk:
ApplicationInterfaceType
.topic 0x861109db
Enter the user name with which you want to log on to Teamcenter. Plant Simulation saves the user name in the model file.

SimTalk:
UserName
.topic 0x861109dc
Enter the password with which you want to log on to Teamcenter. Plant Simulation saves the password in the model file.

SimTalk:
setPassword
.topic 0x8b2609d9
To log on to the Teamcenter database to import items, click this. Then, enter your User name and your Password for Teamcenter into the Teamcenter Login dialog that opens. In case you entered a User name and a Password on the tab Connection, Plant Simulation does not open the login dialog but uses the login data which you entered.

SimTalk:
login
.topic 0x8b2609de
Enter the name of the application interface to which the Sync belongs which you would like to import from Teamcenter. If you want to select the sync and the application interface from a dialog when importing data, just leave the text box empty.
You also have to enter the sync when you enter the application interface.

SimTalk:
ApplicationInterface, Sync
.topic 0x8b2609e1
Enter the name of the sync, which you would like to import from Teamcenter. If you want to select the sync and the application interface from a dialog when importing data, just leave the text box empty.
You also have to enter the Application interface when you enter the Sync.

SimTalk:
Sync, ApplicationInterface
.topic 0x8b2609df
To retrieve the respective JT files in addition to the PLM XML files from Teamcenter, select this.

SimTalk:
RetrieveJTFiles
.topic 0x8b2609dd
Enter the name of the directory into which the PLM XML file and the JT files will be copied or click the button and select the directory.

SimTalk:
Directory
.topic 0x8b2609e0
Enter the name of the style sheet which you want to use when copying data from Teamcenter or click the button and select the style sheet. The style sheet allows you to format the data of the exported PLM XML file in a way that the data relevant for the simulation can be arranged in a simple table structure. This can then be imported into the Plant Simulation Table.

SimTalk:
StyleSheet
.topic 0x8b2609e2
Enter the name of the Plant Simulation table file into which you want to import the PLM XML data, or click the button and navigate to the folder in which the table file is located.

SimTalk:
DataTable
.topic 0x8b270dd0
To log on to the Teamcenter database to export a Plant Simulation Report to Teamcenter, click this. Then, enter your User name and your Password for Teamcenter into the Teamcenter Login dialog that opens. In case you entered a User name and a Password on the tab Connection, Plant Simulation does not open the login dialog but uses the login data which you entered.

SimTalk:
exportReport, login
.topic 0x8b270dce
Enter the path to the Plant Simulation HtmlReport, which you would like to export to Teamcenter, or click the button and select the Report in the dialog that opens.

SimTalk:
Report
.topic 0x8b270a67
Enter the Teamcenter target folder in which the Plant Simulation HtmlReport will be stored.
If you are using Active Workspace, you can click the ellipsis button and select the target folder. This folder has to be a subfolder of the Home folder of the user logged on to Teamcenter.

SimTalk:
TargetFolder
.topic 0x8b270dcf
Enter the Teamcenter target folder in which the Plant Simulation HtmlReport will be stored.
If you are using Active Workspace, you can click the ellipsis button and select the target folder. This folder has to be a subfolder of the Home folder of the user logged on to Teamcenter.

SimTalk:
TargetFolder
.topic 0x852d0868
To highlight the current line of your source code in the method editor, select this.

.topic 0x846505b9
Enter the threshold value for showing or hiding objects in the scene windows, which are less than the value in pixels that you enter. This setting is used for maximizing performance.

.topic 0x846505b8
Enter the sampling accuracy for curved objects in 3D, such as polycurves and splines. Changes to the curve precision only take effect after the next change of the curve.

.topic 0x846505ba
To show the pictures of the stations in different colors, when no separate state objects for the different states exist, select this.
Then 3D automatically colors the graphic of the object red for failed, blue for paused or yellow for waiting, when the object is in the respective state.

.topic 0x846505c2
To move the camera away from you when roll the mouse wheel down, select this. When you roll the mouse wheel up, 3D moves the camera towards you.

.topic 0x846505c3
To move scene the scene as such towards you when you roll the mouse wheel down, select this. When you roll the mouse wheel up, it moves the scene away from you. This is the default setting.

.topic 0x846505c5
To show the grid in new models, select this. To hide it, clear the checkbox

.topic 0x846505c0
To open the dialog Grid Settings, click on this. You can select to show or hide the Base plate on which the grid is placed in the scene window. And you can select the color of the central axes of the grid.

.topic 0x846505c8
Select the OpenGL version you would like to use for rendering the 3D scenes in your simulation models. When 3D is running while the dialog Preferences is opened, the drop-down list only shows the OpenGL versions that the graphics card driver of your graphics card supports.
You can check the features of the individual versions on the Internet.

.topic 0x85900b74
Select the license type with which the model can be opened by another person. The default setting is unrestricted.

.topic 0x85900a1c
Enter the password to restrict access to the model into the text box Password. The other person has to enter this password when opening the model.

.topic 0x85900a1d
Enter the password again into the text box Confirm password.

.topic 0x88141143
To select the color of the text, which the Display shows, and the color of the outline of its display graphic, click the drop-down arrow.

SimTalk:
Color
.topic 0x8ed10f58
To collect statistics data during the simulation run and to show the values on the tab, select this.

SimTalk:
StatisticsActive
.topic 0x8e370ebb
Shows how long it took the object OPC to transmit a single item to the OPC server.

.topic 0x8e370ebc
Shows how long it took the object OPC to get a single item from the OPC server.

.topic 0x8e370ebd
Shows how long it took the object OPC to transmit multiple items to the OPC server.

.topic 0x8e370ebe
Shows how long it took the object OPC to get multiple item from the OPC server.

.topic 0x8ed10f54
Shows the time portion for reading items from the server in percent.

.topic 0x8ed10f55
Shows the time portion for writing items to the server in percent.

.topic 0x8ed10f56
Shows die maximum time for reading an item from the server in milliseconds.

.topic 0x8ed10f57
Shows die maximum time for writing an item to the server in milliseconds.

.topic 0x886a0819
Enter the interval between the grid lines on the Y-axis. It sets the distance of the horizontal grid lines and the labels on the Y-axis.
If you do not enter a value into the text box, Plant Simulation determines a meaningful interval based on the displayed values.

SimTalk:
YGridLineInterval
.topic 0x851d0eb9
Enter the number of decimal places which the object Variable shows in the Frame. It can show up to 15 decimal places.

SimTalk:
DecimalPlaces
.topic 0x88b013d3
Enter the relative position of the converting point along the length of the Converter. The converting point is the point at which the Converter changes the conveying direction of the parts it conveys. You can enter a value between 0.0 and 1.0, denoting a position between 0 % and 100 %.

SimTalk:
RelConvertingPointL
.topic 0x88b013d4
Enter the relative position of the converting point along the width of the Converter. The converting point is the point at which the Converter changes the conveying direction of the parts it conveys. You can enter a value between 0.0 and 1.0, denoting a position between 0 % and 100 %.

SimTalk:
RelConvertingPointW

.topic 0x88000edf
To allow parts to enter the cycle only when the cycle moves all MUs one station on, select this. To allow parts to enter the cycle at any time, clear the checkbox.

SimTalk:
EntranceOnlyOnCycle

.topic 0x85360a5f
To prevent that objects objects, which are located within the locked library, can be opened interactively, select this. You can still open instances of these objects, which are inserted in Frames located outside of the library as usual.
When you develop a library and pass it on and when you want to provide newer versions of the library later on, you should, as a rule, lock the library. This prevents users from inadvertently changing the library. When the user then updates the simulation model with a newer version of the library later on, these changes would be overwritten with the settings of the updated library.

SimTalk:
lockFolder

.topic 0x93a516f1
Select the orientation of the plate which you want to create and insert into the scene.

.topic 0x938e17d0
Select the graphic group to which you want to add the new graphic.

.topic 0x93a2145e
Enter the width of the shape which you want to create.

.topic 0x93a2145d
Enter the depth of the shape which you want to create.

.topic 0x93a2145c
Enter the height of the shape which you want to create.

.topic 0x93a11460
Enter the radius of the shape that you want to create.

.topic 0x939f1464
Enter the text which you would like to add to and show in the scene.

.topic 0x939f1466
Select the text color of the text which you want to add to the scene window.

.topic 0x939f1465
Select the alignment of the text which you want to add to the scene window.

.topic 0x939f1467
Select the background color of the text which you want to add to the scene window.

.topic 0x93a516e9
Click Browse and select a bitmap, which you want to use for the textured plate, in the dialog Select Bitmap. The text box then shows the path to the and the name of the image file.

.topic 0x93a516e7
Enter the thickness of the plate which you want to create and insert into the scene.

.topic 0x93a516f0
To show the texture on both sides of the plate, i.e., on the top and the bottom or on the front and the back, select this.

.topic 0x93a516f3
To fit the picture of the texture to the size of the plate, select this. Depending on the dimensions of your picture you enter under Plate, the texture might be being distorted.

.topic 0x93a516f2
To activate tiling, select this. Then enter the width and the height of the individual tiles in.

.topic 0x93a516ec
Enter the width of the individual tiles.

.topic 0x93a516ed
Enter the height of the individual tiles.

.topic 0x93a7149b
Click this to assign a material to the profile of the fence which holds the wire mesh or the panels.

.topic 0x93a7149c
Click this to assign a material to the posts of the fence that hold the wire mesh or the panels.

.topic 0x93a71498
Select this to create a wire mesh fence between the posts.

.topic 0x93a7149a
Click this to assign a material to the wire mesh that fills the space between the struts of the fence.

.topic 0x93a71497
Select this to create a fence that consists of glas or acrylic glass panes.

.topic 0x93a71499
Click this to assign a material to the panes that fill the space between the struts of the fence. This way you can create panels that resemble glas or acrylic glass panes.

.topic 0x93b21411
Enter the storage bay width of the rack that you want to create.

.topic 0x93b21412
Enter the the storage bay height of the rack that you want to create.

.topic 0x93b21413
Enter the shelf depth of the rack that you want to create.

.topic 0x93b21414
Enter the number of storage bays per storage board of the rack.

.topic 0x93b21415
Enter the number of boards that form the rack.

.topic 0x93b21416
Click this to assign a material to the material of the storage boards.

.topic 0x93b21417
Click this to assign a material to the posts of the rack.

.topic 0x93a61457
Select how you would like to optimize the graphic of the rack:

Post-processing Capability: Creates a particularly fine-granular structure of the graphic.

Performance: Creates a particularly flat structure of the graphic.

.topic 0x93e61664
Enter the Thickness of the individual walls of the rectangle, which forms the walls of the installation as a whole.

.topic 0x93e61666
Click into the color box and select the color for all walls of the installation.

.topic 0x93e61667
Click into the color box and select the color for all window panes of all walls of the installation. You can thus create tinted or mirrored window panes.

.topic 0x93e61668
Click into the color box and select the color for all window frames in all walls of the installation.

.topic 0x939a1424
Enter a Name for the new animatable object. The command then converts the selected graphic into an object which can be animated.

.topic 0x93aa13b8
Enter a value or click the spin buttons to move the position of the object on the X-axis, the Y-axis, and the Z-axis. The settings for the three axes are independent of each other.
For MU instances the settings for the position show the local positions calculated by the animation.

SimTalk:
_3D.Position,
_3D.setGraphicPosition,
_3D.getGraphicPosition,
_3D.StatesPosition
.topic 0x93aa1590
To match the position of the object in the 2D part of the simulation model with the position of the respective object in 3D part, select this.

SimTalk: _3D.PositionsConnected
.topic 0x93aa1580
To match the rotation of the object in the 2D part of the simulation model with the rotation of the respective object in 3D part, select this.

SimTalk: _3D.RotationsConnected
.topic 0x93aa157b
To automatically enter the value you enter into one text box into the remaining two text boxes for scaling the object, select this. This way you do not have to manually enter the same value into each text box over again.

SimTalk:
_3D.Scale,
_3D.setGraphicScale,
_3D.getGraphicScale,
_3D.StatesScale
.topic 0x93aa1592
To automatically enter the value you enter into one text box into the remaining two text boxes for scaling the object, select this. This way you do not have to manually enter the same value into each text box over again.

SimTalk:
_3D.Scale,
_3D.setGraphicScale,
_3D.getGraphicScale
.topic 0x939a1424
Enter a Name for the new simulation object. The command then converts the selected graphic into a simulation object. A simulation object is an object that has a counterpart in 2D.

.topic 0x939a1494
Select the 2D object Class to be used when creating the simulation object. In general these are the material flow objects, some of the resource objects, the object Chart, and the tools.

.topic 0x9390148d
To show the base plate underneath the grid lines in the scene window, select this. To hide the base plate on which the grid is placed, clear it.

.topic 0x9390148f
Click the arrow of the drop-down list Color and select the color of the base plate from the twenty colors provided.
Or click More Colors and click the Select button to select a color in the color matrix.

.topic 0x93901490
Click the arrow of the drop-down list and select the color of the X-axis and of the Y-axis along the bottom and the right-hand side of the scene window from the twenty colors provided.
Or click More Colors and click the Select button to select a color in the color matrix.

.topic 0x93901492
To add a new grid line, click this. Then, enter the settings for the grid line into the list field to the left.

.topic 0x93901493
To delete the selected grid line, select it in the list field and click this.

.topic 0x93901491
Each row in the list field designates a single grid line:

Double-click in the cell Color and select the color of the grid line in the dialog Colors.
Enter a positive value into the cell Interval to set the spacing of the selected grid line.

Select the check box below Visible to show the grid line.

Select the check box below Select for Snapping to make an object, which you insert, snap to the grid line.

When you insert an object, Snap to places the object at the snapping point closest to the point where you position the mouse and click the left mouse button.

When you move an object with the mouse, Snap to places the object closest to the snapping point to which you dragged the object and released the mouse button.

.topic 0x93ad1486
Accept the default frame rate for recording a video or enter a frame rate of your choice.

.topic 0x93ad1488
Accept the default playback rate or enter a frame rate of your choice. The higher the playback rate, the faster the video plays.

.topic 0x93ad148a
When you are simultaneously running a simulation in Plant Simulation and you only want to record a certain section of that simulation, you can enter the duration after which 3D stops recording the sequence.

.topic 0x93ad1489
Accept the default name—default.avi—for the finished AVI file or enter a different name. When you also enter the file extension avi, the Windows Explorer shows the icon for Video Clip files in the list window in the browser window.

.topic 0x93ad1487
Select a codec in the drop-down list. The codec translates the video between its uncompressed form and the compressed form in which it is stored.

.topic 0x9390155c
Scans the graphic for sub-structures that fit into the Bounding cube side length that you define. It then deletes everything that fits in this group. This is useful for visible but unimportant details like screws. Graphics, however small they might be, will not be deleted if they are only part of a larger indivisible graphic node. This is often the case for automatically generated graphics.

SimTalk:
_3D.optimizeByPruningTinyGraphics

.topic 0x93901561
Enter the side length of the cube that surrounds the graphic whose component graphics you would like to remove.

SimTalk:
_3D.optimizeByPruningTinyGraphics
.topic 0x9390155d
Removes graphic components which are not visible from outside. You can select the Cull granularity and the Simplification level. It scans the graphic for hidden parts which will then be deleted. The cull granularity sets the finest structure that 3D checks.
The simplification level sets how close 3D checks the graphic. The higher this setting, the more graphics might be kept. If you need the optimized graphic with the smallest size, select Low.

SimTalk:
_3D.optimizeByVisibilityFilter
.topic 0x93901564
Select the granularity for deleting graphics.

Shapes removes entire component graphics.

Faces removes entire graphic faces.

Triangle Strips removes parts of graphic faces.

Triangles removes triangles.

SimTalk:
_3D.optimizeByVisibilityFilter

.topic 0x93901566
Select the simplification level, i.e., how close the procedure looks at the graphic.

Low designates a low reduction level and a high level of detail. This might cause holes in the resulting graphic.

Super designates a great reduction level and a low level of detail. This setting takes longer to render.

The settings Medium and High are located in between these extremes.

SimTalk:
_3D.optimizeByVisibilityFilter
.topic 0x9390155e
Flattens the structure of the object while preserving its contents. It reduces the graphic structure to a minimal structure that only keeps the visualization running, i.e. the remaining structure levels are those that are needed to hold a material or a texture. If you want to keep grouping information of the selected graphic, select Keep grouping.

SimTalk:
_3D.optimizeByStructureFlattening
.topic 0x9390155f
Select this to keep grouping information of the selected graphic although it might not have a special purpose.

SimTalk:
_3D.optimizeByStructureFlattening
.topic 0x93901567
To translate your settings for optimizing the graphic into SimTalk source code and to copy that code to the clipboard, click this.
You can then paste the source code to a Method and use it while modeling.

SimTalk:
_3D.optimizeByStructureFlattening

.topic 0x93901556
To preview the result of your changes to the settings, click this. You can then either Revert to the settings which the dialog had before you made changes or you can click Accept Result to apply your changes.

.topic 0x93901557
To revert to the settings which the dialog had before you made changes, click this.

.topic 0x93901558
To apply your changed settings, click this. You can then close the dialog by clicking the close button in the title bar of the dialog.

.topic 0x93aa1591
To move the selected grouped graphic (with the center of its base area) to the point of origin of the object it belongs to, click this. This is especially handy when you import graphics, such as .wrl files, which 3D might not place at the position you expected.

SimTalk:
_3D.Position, _3D.importGraphics, _3D.setGraphicPosition, _3D.getGraphicPosition
.topic 0x93aa13b9
To set the axis around which to rotate the object, enter a value for each of the three components (x-y-z) that define the rotation axis.

SimTalk:
_3D.Rotation,
_3D.setGraphicRotation,
_3D.getGraphicRotation
.topic 0x93db147d
Enter the angle of rotation into the text box.

SimTalk:
_3D.Rotation
.topic 0x93aa158a
Enter the x-component of the rotation axis around which to rotate the object.

SimTalk:
_3D.Rotation, _3D.setGraphicRotation, _3D.getGraphicRotation
.topic 0x93aa158b
Enter the y-component of the rotation axis around which to rotate the object.

SimTalk:
_3D.Rotation, _3D.setGraphicRotation, _3D.getGraphicRotation
.topic 0x93aa158c
Enter the z-component of the rotation axis around which to rotate the object.

SimTalk:
_3D.Rotation, _3D.setGraphicRotation, _3D.getGraphicRotation

.topic 0x93aa1585
Enter a value to scale the object on the X-axis. You can only enter positive values, meaning that you cannot downscale the object below the size defined in the Class Library. Entering 0.5 halves the size of the object, entering 2.0 doubles its size.

SimTalk:
_3D.Scale, _3D.setGraphicScale, _3D.getGraphicScale

.topic 0x93aa1587
Enter a value to scale the object on the Y-axis. You can only enter positive values, meaning that you cannot downscale the object below the size defined in the Class Library. Entering 0.5 halves the size of the object, entering 2.0 doubles its size.

SimTalk:
_3D.Scale, _3D.setGraphicScale, _3D.getGraphicScale

.topic 0x93aa1589
Enter a value to scale the object on the Z-axis. You can only enter positive values, meaning that you cannot downscale the object below the size defined in the Class Library. Entering 0.5 halves the size of the object, entering 2.0 doubles its size.

SimTalk:
_3D.Scale, _3D.setGraphicScale, _3D.getGraphicScale

.topic 0x93f8139b
To open the dialog of the respective object in 2D, click this. You can then edit the simulation-relevant settings.
To close the opened 3D dialog after the corresponding 2D dialog was opened, hold down the Shift key while clicking the button 2D. Plant Simulation does not apply any changes you made in the 3D dialog.

.topic 0x84c60dca
To open the dialog Edit 3D Properties of the respective object in 3D, click this. You can then edit the 3D settings of the object.
To close the opened 2D dialog after the corresponding 3D dialog was opened, hold down the Shift key while clicking the button 3D. Plant Simulation does not apply any changes you made in the 2D dialog.

.topic 0x93c514c2
To activate the settings for the material, select this.
To reset all settings pertaining to the material of the object to the values the text boxes had, when you opened the dialog, clear the check box.

SimTalk:
_3D.setGraphicMaterial
_3D.removeGraphicMaterial
.topic 0x93c514b0
Select a diffuse color.

The diffuse color is the color of the object, which it shows under pure white light, where incoming light is reflected in all directions equally. We perceive it as the color of the object itself rather than a reflection of the light.

SimTalk:
_3D.MaterialDiffuseColor
.topic 0x93c514b2
Select an ambient color.

The ambient color is the color of the light reflected from the object, when it is lit by another ambient object in the scene. Ambient intensity refers to the strength of the reflection.

SimTalk:
_3D.MaterialAmbientColor
.topic 0x93c514b3
Select a specular color.

The specular color is the reflected color of the object’s highlights. Specular intensity refers to the strength of the reflection.

SimTalk:
_3D.MaterialSpecularColor
.topic 0x93c514b4
Select an emissive color.

The emissive color is the color emitted by the object,. A lamp shade might have a base color of yellow. When you turn the lamp on, though, the emissive color might be white.

SimTalk:
_3D.MaterialEmissiveColor
.topic 0x93c514be
To set the Transparency, i.e., how opaque or clear the object is, drag the slider. Water might be more clear than opaque. Or enter a value between 0.0, for opaque, and 1.0, for completely transparent, into the text box.

SimTalk:
_3D.MaterialTransparency
.topic 0x93c514c4
Enter a value between 0.0, for opaque, and 1.0, for completely transparent, into the text box.

SimTalk:
_3D.MaterialTransparency
.topic 0x93c514b7
To set the Shininess, i.e., how sharp light is reflected by the object, drag the slider. A billiard ball has a large shininess, making for small and sharp highlights. You can enter a value between 0.0, for a very dull surface, and 1.0, for a highly polished surface, into the text box.

SimTalk:
_3D.MaterialShininess
.topic 0x93c514af
Enter a value between 0.0, for a very dull surface, and 1.0, for a highly polished surface, into the text box.

SimTalk:
_3D.MaterialShininess
.topic 0x93c514b5
Click this to copy the current material settings you selected. You can then paste these settings into another object. The command also copies the corresponding SimTalk code to the clipboard. You can then paste this code into a Method object to set the material of another graphic.

.topic 0x93c514b6
Click this to paste the material settings that you copied to the graphic of the object, click.
You also paste the source code, which the command Copy the Current Material Settings copied, into a Method object to set the material of the selected graphic.

.topic 0x93c514bb
Click this to remove the materials in nested graphics, i.e., the materials of the graphics contained within this object.

SimTalk:
_3D.removeGraphicMaterial
.topic 0x93f214e2
Enter the name of the alternative animation object of the object. This applies for each and every 2D-object which can accept MUs.

SimTalk:
_3D.AnimationObject

.topic 0x93f214e6
Select the side on which the loaded MU will be attached to the object.

Bottom: Attaches the loaded MU to the object from the bottom, i.e., from the negative z-direction to this object.

Booking point: Attaches the loaded MU to the object from the bottom, i.e., from the local position (0, 0, 0) to this object. Set the local position on the tab Attributes in the dialog of the MU.

Top: Attaches the loaded MU to this object from the top, i.e., from the positive z-direction.

Front: Attaches the loaded MU to this object from the front, i.e., from the positive x-direction.

Back: Attaches the loaded MU to this object from the back, i.e., from the negative x-direction.

Left: Attaches the loaded MU to this object from the left hand side, i.e., from the negative y-direction.

Right: Attaches the loaded MU to this object from the right hand side, i.e., from the positive y-direction.

Center bottom: Places the loaded MU with the middle of the base plate of its dimensions onto the animation path of the transporting object.

Front bottom: Combines the two settings Front and Bottom.

Back bottom: Combines the two settings Back and Bottom.

Left bottom: Combines the two settings Left and Bottom.

Right bottom: Combines the two settings Right and Bottom.

SimTalk:
_3D.MUSideToAttach

.topic 0x93f214da
To create an new animation path, click this.
Select a Path type in the dialog Create Path.
Enter a Path name. This only applies to animation paths.

.topic 0x93e11478
Enter a meaningful name for the animation or rotation path that you are creating.

.topic 0x93f3152f
Enter the angle where the rotation starts. The start angle has to differ from the End angle, otherwise 3D does not rotate the object. You can enter a value greater than +360 degrees and less than -360 degrees.

.topic 0x93f31530
Enter the angle where the rotation ends. The end angle has to differ from the Start angle, otherwise 3D does not rotate the object. You can enter a value greater than +360 degrees and less than -360 degrees.

.topic 0x93f31522
Enter the radius of the rotation path.

.topic 0x93f31533
Select X to rotate the animated object around the X-axis.

.topic 0x93f31534
Select Y to rotate the animated object around the Y-axis.

.topic 0x93f31535
Select Z to rotate the animated object around the Z-axis. We defined the Z-axis in a way that a greater end angle than a start angle rotates clockwise.

.topic 0x93f31536
Enter a value for the x-position of the center of the rotation.

.topic 0x93f31537
Enter a value for the y-position of the center of the rotation.

.topic 0x93f31538
Enter a value for the z-position of the center of the rotation.

.topic 0x93f214db
To add a new anchor point to the path, thus making it longer, click this. Then click the left mouse button at the position, where you would like to insert the anchor point. Repeat this as often as needed.
To terminate Extend path mode, click the right mouse button.

.topic 0x93ef15cd
The list shows the settings for the position, the rotation, and the time of the selected path anchor point. Instead, double-click the row of the anchor point, whose values you want to change, in the list.

.topic 0x93f214dc
To edit the anchor points of the path you selected in the list, click this.

.topic 0x93ef15ce
To add a new anchor point to the object, click this. The list window shows these settings. You can then edit the individual values.

.topic 0x93ef15cf
To insert a new anchor point before the anchor point, which you selected in the list window, click this.

.topic 0x93ef14d7
To delete the selected anchor point from the list, click this.

.topic 0x93ef15d0
To move the selected anchor point one position up in the list, click this.

.topic 0x93ef15d1
To move the selected anchor point one position down in the list, click this.

.topic 0x93ef15d2
To duplicate the settings of the selected anchor point and to insert the duplicate below the original in the list, click this.

.topic 0x93ef15d3
To edit the values of the anchor point which you selected in the list, click this. Instead, double-click the row of the anchor point, whose values you want to change, in the list.

You can edit these settings for the different path types:

Position for Lines, Polycurves, Splines

Rotation for Lines and Polycurves

Segments for Polycurves

Velocity for Lines and Splines

.topic 0x93db160d
To set the axis around which to rotate the anchor point, enter a value for the x- component of the rotation axis.

.topic 0x93db160e
To set the axis around which to rotate the anchor point, enter a value for the y- component of the rotation axis.

.topic 0x93db160f
To set the axis around which to rotate the anchor point, enter a value for the z- component of the rotation axis.

.topic 0x93e11605
Enter the angle of rotation.

.topic 0x93db1619
To activate Velocity settings, select this.

.topic 0x93db161b
The text box length shows the length of the anchor point.

.topic 0x93db161e
Enter the time, which is required for point-oriented movements, such as rotating around or remaining on the selected anchor point.

.topic 0x93db1617
Enter the velocity, which is required for point-oriented movements, such as rotating around or remaining on the selected anchor point.

.topic 0x93e11605
Enter the angle of rotation for the common offset into the text box.

.topic 0x93f214dd
To delete the path you selected in the list to the left, click this.

.topic 0x93f214f3
To prevent the parts to be placed flush on the surface of length-oriented object but with an offset to this surface, click this.

SimTalk:
_3D.ExtConfiguration
.topic 0x93f214e8
Enter the offset of the animation path to the surface of the object along the X direction or click the spin buttons to set a positive or a negative offset.

.topic 0x93f214ec
Enter the offset of the animation path to the surface of the object along the Y direction or click the spin buttons to set a positive or a negative offset.

.topic 0x93f214f0
Enter the offset of the animation path to the surface of the object along the Z direction or click the spin buttons to set a positive or a negative offset.

.topic 0x93f214fe
To activate gravity mode, select this. To deactivate it, clear the check box. In gravity mode the part is always placed perpendicular to the floor, either hanging from a rail or standing up on a rail.

.topic 0x93f214f5
Select the graphic of any of the MU prototypes which 3D uses as the test object, which moves on the selected animation path.

.topic 0x93f214f8
To start the animation, click this. 3D creates a test object of the selected graphic and animates it on the path you selected with the speed you entered. The test object pauses at the end of the animation path.

.topic 0x93f214f9
To pause animation of the test object, independent of the simulation, click this.

.topic 0x93f214fa
To stop the animation of the test object, independent of the simulation, click this. This also deletes the test object.

.topic 0x93f214f7
Select this if you want the selected graphic to move backwards towards the starting point of the animation path, instead of forwards towards the end point of the animation path.

.topic 0x93f21500
Enter a value for the x-dimension of the axis around which to rotate the object.

SimTalk:
_3D.AniRotationAxis

.topic 0x93f21502
Enter a value for the y-dimension of the axis around which to rotate the object.

SimTalk:
_3D.AniRotationAxis

.topic 0x93f21504
Enter a value for the z-dimension of the axis around which to rotate the object.

SimTalk:
_3D.AniRotationAxis

.topic 0x93f21506
Enter a value for the position of the center on the X-axis around which to rotate the object.

SimTalk:
_3D.AniRotationCenter

.topic 0x93f2150a
Enter a value for the position of the center on the Y-axis around which to rotate the object.

SimTalk:
_3D.AniRotationCenter

.topic 0x93f2150e
Enter a value for the position of the center on the Z-axis around which to rotate the object.

SimTalk:
_3D.AniRotationCenter

.topic 0x93db1619
To activate Velocity settings, select this.

.topic 0x93ef15d4
To add a common offset to the selected anchor point, click this.

.topic 0x93ef15d5
To define the viewing direction of the anchor point which you selected in the list, click this.

.topic 0x93ef15d6
To show the selected camera settings in the active 3D window, click this.

.topic 0x93e01555
Select this to make the viewing direction points backwards.

.topic 0x93e01554
Select the direction type, i.e., where the X-axis of the animated object points to for the selected anchor point.

Look along the path on the selected object.

Look towards an object. Then, select an object in the active scene from the list target object.

Look towards a position. Then, select the target position on the X-axis, the Y-axis, or the Z-axis.

Look in a direction. Then, enter the direction on the X-axis, the Y-axis, or the Z-axis.

.topic 0x93e0153e
Select the object in the active scene from the list target object to which the viewing direction points.

.topic 0x93e01541
Select or enter the target position of the viewing direction of the selected path anchor point on the X-axis.

.topic 0x93e01545
Select or enter the target position of the viewing direction of the selected path anchor point on the Y-axis.

.topic 0x93e01549
Select or enter the target position of the viewing direction of the selected path anchor point on the Z-axis.

.topic 0x93e0154e
Enter the viewing direction of the selected path anchor point on the X-axis or click the spin buttons.

.topic 0x93e01550
Enter the viewing direction of the selected path anchor point on the Y-axis or click the spin buttons.

.topic 0x93e01552
Enter the viewing direction of the selected path anchor point on the Z-axis or click the spin buttons.

.topic 0x93c815f1
Select this to add the content of the object to its external representation. Then not only the external graphic groups and the states group represent the selected object towards the outside, but also its internal graphic groups and the external representations of the objects, which are contained within the selected object. This means that the external graphic groups and the states group of all objects, which are located one level lower in the hierarchy than the selected object, are also visible one level higher in the hierarchy than the selected object.

SimTalk:
_3D.ShowContent
.topic 0x93c815f2
To add a new graphic group to the object, click this.

.topic 0x93c815f3
To delete the selected graphic group from the selected object, click this.

SimTalk:
_3D.deleteGraphicGroup

.topic 0x93fa17b1
Enter the name of the new graphic of the object.

SimTalk:
_3D.addGraphicGroup

.topic 0x93fa15da
To make the graphic only visible within its object, select this. The graphic will then only be used for its internal decoration. The external graphics on the other hand represent its object towards the outside.

SimTalk:
_3D.InternalGraphics, _3D.setGraphicGroupInternal
.topic 0x93fa17af
To use the new graphic for representing the object in the 3D scene window, select this. This graphic will be visible in the scene window.

SimTalk:
_3D.VisibleGraphics, _3D.isGraphicGroupVisible, _3D.setGraphicGroupInternal

.topic 0x939516f5
To select how the state graphics for the selected object are displayed, click this.

Off: Default for objects, which cannot have any states, such as the Frame. You cannot change this setting for objects of this type. 3D does not create any state graphics.

Horizontal: Default for objects, which have predefined states. 3D creates the state graphics as cubes and arranges them along the top border of the picture of the object.

Vertical: To arrange the LEDs vertically on a pole, select this. 3D creates the state graphics as cylinders and arranges them on a pole.

SimTalk:
_3D.StatesOrientation

.topic 0x93c815f4
The toggle button Visibilities sets if the graphic groups of the object inherit their visibility from the parent object or not. It also shows the state of the attribute _3D.VisibleGraphics.

SimTalk:
_3D.InheritGraphics
.topic 0x93c815f6
To prevent that the external representation of the object will be displayed together with the external representation of the location of the object, when Show content is activated, select this. Then the representing graphics of the object is only visible within its location. This makes sense for abstract objects, such as the Method, TableFile, EventController, etc., which are required to define and to control the simulation but not to illustrate the simulated scene.

SimTalk:
_3D.ExcludeFromShowContentOfLocation
.topic 0x93c815e3
To show the sensors which you defined for length-oriented object, select this. To hide the sensors, clear the check box.

SimTalk:
_3D.ShowSensors
.topic 0x93c815e2
Select if the object is an obstacle for the Worker who is moving about freely within space:

(None)

The object is no obstacle for the Worker. He can walk through it or across it. This applies to the Informationflow objects, such as the Method, the TableFile, etc.

Bounding box

The bounding box of the entire object is an obstacle for the Worker which he has to avoid and walk around. This applies to the MaterialFlow objects, such as the Station, the ParallelStation, etc. and for graphics.

Graphics

This applies to the length-oriented objects, such as the Conveyor, the Converter, the Track, etc.

Sides (for Stairs only)

This calculates the obstacle for the stairway so that:

An additional entrance or exit from or to which the stairway leads will not be covered by the obstacle.

The obstacle is being limited to the relevant area for the respective simulation-relevant height.

SimTalk:
_3D.ObstacleForWorker
.topic 0x973313ba
To apply your settings and leave the dialog open, click this.

.topic 0x93f01751
To open the Segments table, which shows information about the starting point and the curved and straight segments of the curved object, which you inserted, click this.
You can edit the tangential angle, the length, the curve angle, the radius, the vertical curve and the z-difference of a segment, while Plant Simulation computes the remaining, grayed out values.
If the curved object is an animation polycurve in 3D, you can also define a tangential angle and a length in addition to also place this starting point outside of the zero point of the object in the x-direction and the y-direction.

SimTalk:
_3D.getExtSegments, _3D.setExtSegments
.topic 0x93f0174d
Enter the distance of the object from the floor. The base height can be inherited, meaning that you can define it once in the class instead of having to define it for each instance individually. The z-coordinate defines the floor of the installation and the base height defines the distance of the legs from the floor. By changing the setting DeltaZ in the Segments table, you can add an additional offset. The setting DeltaZ also affects the simulation time in 2D.

SimTalk:
_3D.BaseHeight
.topic 0x93f017a5
Enter the width of the length-oriented object. The width only applies when the setting Transfer length in 2D is activated.

.topic 0x93f0173c
The toggle button activates or deactivates inheritance of the configuration settings of the conveyor. To deactivate inheritance, click the button again.

SimTalk:
_3D.ExtConfiguration
.topic 0x93f017a3
Select the type of conveyor you want to use in your simulation model. Depending on the type you select, the dialog shows the settings pertaining to that type.
Click Apply to insert the configured extrusion object into the scene.

.topic 0x93df147c
Select the extrusion profile you want to edit, rename, or delete.

.topic 0x93f01749
To create a new extrusion profile, click New. Then enter a name of the path. 3D adds this path to the bottom of the list next to profile name.

.topic 0x93df1479
To rename the selected extrusion profile, click this. Enter the new name into the dialog Rename.

.topic 0x93df147a
To delete the selected extrusion profile, click this.

.topic 0x93f017a5
Enter the width of the conveyor.

.topic 0x93f0173f
Select the type of legs which support your conveyor.

.topic 0x93f01743
Click this and select the material of the legs of the conveyor.

.topic 0x93f01741
Select where the legs are placed along the length of the inserted conveyor:

On the anchor points of the inserted suspension track.

With a single pair of legs along the entire length.

With a repeated fixed distance from each other, i.e., equidistant.

.topic 0x93f01747
Enter the distance between the individual pairs of legs.

.topic 0x93f01745
Enter the diameter of the legs.

.topic 0x93f0178f
Click this and select the material of the lanes of the conveyor.

.topic 0x93f01791
Enter the height of the lanes of the conveyor.

.topic 0x93f01799
Click this and select the material of the frame around the conveyor.

.topic 0x93f0179b
Enter the height of the frame around the conveyor.

.topic 0x93f01745
Enter the diameter of the legs.

.topic 0x93f01773
Enter how many rail bars you want to insert over the length of the rail.

.topic 0x93f01775
Enter the width of the rail bars.

.topic 0x93f01776
To insert crossbars for additional stability of your conveyor, select this.

.topic 0x93f01779
Click this and select the material of the crossbars that stabilize the rail bars of the rail conveyor.

.topic 0x93f01778
Enter the distance of the crossbars that stabilize the rail bars against each other.

.topic 0x93f01785
Select the type of chute of the chute conveyor.

.topic 0x93f01789
Enter the thickness of the chute proper.

.topic 0x93f0178b
Enter how many rails make up the chute of the rail conveyor.

.topic 0x93f01787
Click this and select the material of the chute.

.topic 0x93f01753
Select the type of the suspension that suspends the track from the ceiling.

.topic 0x93f01755
Select where the legs are placed along the length of the inserted conveyor:

On the anchor points of the inserted suspension track.

With a single pair of legs along the entire length.

With a repeated fixed distance from each other.

.topic 0x93f0175b
Enter the distance between the individual pairs of the suspension device.

.topic 0x93f01757
Click this and select the material of the suspension device that suspends the suspension track from the ceiling of the installation.

.topic 0x93f01759
Enter the diameter of the suspension track.

.topic 0x93f0175d
Enter the ceiling height of the suspension track. This is the distance between the suspension track and the ceiling of the installation.

.topic 0x93f01779
Click this and select the material of the rail bars of the conveyor.

.topic 0x939014a0
To assign a background color to the Frame, select this. This activates the other settings on the tab.
If you do not want to assign a background color to the selected Frame/scene, deactivate the checkbox. 3D then uses the background color of the parent Frame.

SimTalk:
_3D.BackgroundColor
.topic 0x939014a2
Select the base color for the background of the Frame. Then you can define a color gradient by dragging the sliders.

SimTalk:
_3D.BackgroundColor
.topic 0x939014a6
Drag the slider to set the brightness of the top left corner of the Frame window.

This way you can define a color gradient from top to bottom and from left to right.

SimTalk:
_3D.BackgroundBrightness
.topic 0x939014ac
Drag the slider to set the brightness of the bottom left corner of the Frame window.

This way you can define a color gradient from top to bottom and left to right.

SimTalk:
_3D.BackgroundBrightness
.topic 0x939014a9
Drag the slider to set the brightness of the top right corner of the Frame window.

This way you can define a color gradient from top to bottom and left to right.

SimTalk:
_3D.BackgroundBrightness
.topic 0x9390149f
Drag the slider to set the brightness of the bottom right corner of the Frame window.

This way you can define a color gradient from top to bottom and left to right.

SimTalk:
_3D.BackgroundBrightness
.topic 0x93c815f4
The toggle button sets if the object inherits the visibilities of its graphic groups from the origin object or not. As soon as you activate or deactivate the check box Visible of one of the graphics groups, 3D changes the state of the Visibilities to non-inheriting. Or you can set inheritance of Visibilities by clicking the toggle button.

SimTalk: _3D.VisibleGraphics
.topic 0x93aa1598
To add a rotation angle to the axis that you select, click this.

.topic 0x93aa13f5
To add the rotation angle you entered to the X-axis, click this.

.topic 0x93aa13f6
To add the rotation angle you entered to the Y-axis, click this.

.topic 0x93aa13f7
To add the rotation angle you entered to the Z-axis, click this.

.topic 0x97d417d5
The dialog only shows the visually depicting elements of the selected animatable object in a tree structure, i.e., the following elements defined for the animatable object:
Graphic groups, i.e., default graphics or graphic groups.
Graphics , i.e., geometries that describe the shape of their graphic group.
Plain animatable objects, i.e., children of the animatable object which do not have a counterpart in 2D.

.topic 0x97d417d6
To find an object, enter its name into the text box next to the Find button, and click this. Plant Simulation searches the list and highlights the object it found. Click Find again to find additional instances of the search term.

.topic 0x97d417d7
To find an object, enter its name into the text box, and click Find.

.topic 0x93f01795
Enter the count, i.e., the number of lanes that you want to insert.

.topic 0x93f0177d
Enter the thickness of the material of the tube proper.

.topic 0x93c31495
To activate auto graphics mode, select this, and click OK or Apply. Plant Simulation then uses the color of the 2D vector graphic. In this case 3D uses the color of the vector graphic as the Diffuse color.
To define a color of your own with the settings of the tab, select Override 2D vector graphics color and then select the settings of your choice.

SimTalk:
_3D.AutoGraphicsActive
.topic 0x93c31496
To define a color of your own with the settings of the tab, select this. Then, 3D activates the settings for defining the material.

SimTalk:
_3D.MaterialActive
.topic 0x9396144f
Click this and select the point cloud file that you want to import. To remove the point cloud from the Frame, delete its name from the text box.

SimTalk:
_3D.PointCloudPath
.topic 0x93961450
Enter a value or click the spin buttons to move the position of the point cloud on the X-axis.

SimTalk:
_3D.PointCloudPosition
.topic 0x93961452
Enter a value or click the spin buttons to move the position of the point cloud on the Y-axis.

SimTalk:
_3D.PointCloudPosition
.topic 0x93961454
Enter a value or click the spin buttons to move the position of the point cloud on the Z-axis.

SimTalk:
_3D.PointCloudPosition
.topic 0x93961441
To move the selected point cloud (with the center of its base area) to the point of origin of the Frame it belongs to, click Move to Zero. This is especially handy when you import graphics, such as .wrl files, which 3D might not place at the position you expected.

.topic 0x93961443
Enter a value for the x-component of the rotation axis.
Instead, you can click on the button to the right of the axis, to set this component of the rotation axis. This enters the respective values into the text boxes.

SimTalk:
_3D.PointCloudRotation
.topic 0x93961445
Enter a value for the y-component of the rotation axis.
Instead, you can click on the button to the right of the axis, to set this component of the rotation axis. This enters the respective values into the text boxes.

SimTalk:
_3D.PointCloudRotation
.topic 0x93961447
Enter a value for the y-component of the rotation axis.
Instead, you can click on the button to the right of the axis, to set this component of the rotation axis. This enters the respective values into the text boxes.

SimTalk:
_3D.PointCloudRotation
.topic 0x9396144a
Enter the rotation angle of the point cloud in the Frame. 3D interprets the rotation angle as a rotation around the negative Z-axis. This corresponds to the rotation angles in 2D.

SimTalk:
_3D.PointCloudRotationAngle
.topic 0x93961444
Click this to set the x-component of the rotation axis. This enters the respective values into the text boxes.

.topic 0x93961446
Click this to set the y-component of the rotation axis. This enters the respective values into the text boxes.

.topic 0x93961448
Click this to set the z-component of the rotation axis. This enters the respective values into the text boxes.

.topic 0x93b01438
Define the way in which the Worker walks in a relaxed posture without carrying anything. In this posture the Worker swings his arms back and forth.
The Worker shows the individual graphic groups in the sequence which you enter here when he walks on a FootPath.

SimTalk:
_3D.GraphicsWhenEmpty
.topic 0x93b0143a
To add a new graphic group to the Worker, click this. The list window then shows the name of this graphic group. The graphic group defines part of a walking pose.

.topic 0x93b0143b
To insert an existing graphic group before the selected graphic group, click this. Then, select the graphic group which you want to insert before the selected graphic group and click OK.
The drop-down list shows all graphic groups which are defined on the tab Graphics.

.topic 0x93b0143c
To delete the selected graphic group from the list, click this.

.topic 0x93b0143d
To move the selected graphic group one position up in the list, click this.

.topic 0x93b0143e
To move the selected graphic group one position down the list, click this.

.topic 0x93b0143f
Define the way in which the Worker walks while carrying a part in his hands or on his arms.
The Worker shows the individual graphic groups in the sequence which you enter here when he walks on a FootPath.

SimTalk:
_3D.GraphicsWhenCarrying
.topic 0x93b0143f
To add a new graphic group to the Worker, click this. The list window then shows the name of this graphic group. The graphic group defines part of a walking and carrying pose.

.topic 0x93b01441
To add a new graphic group to the Worker, click this. The list window then shows the name of this graphic group. The graphic group defines part of a walking and carrying pose.

.topic 0x93b01434
To insert an existing graphic group before the selected graphic group, click this. Then, select the graphic group which you want to insert before the selected graphic group and click OK.
The drop-down list shows all graphic groups which are defined on the tab Graphics.

.topic 0x93b01435
To delete the selected graphic group from the list, click this.

.topic 0x93b01436
To move the selected graphic group one position up in the list, click this.

.topic 0x93b01437
To move the selected graphic group one position down the list, click this.

.topic 0x852a0f1b
To create the model consisting only of the 2D part, select this.
If you need to create the 3D part at a later point in time, you can click Open 2/3D on the Home ribbon tab.

.topic 0x852a0f1c
To create the model consisting of a 2D part and a 3D part, select this.

.topic 0x852a0f1d
To create the model consisting only of the 3D part, select this.

.topic 0x852a0499
The check box denies the current model to access your computer. This is the standard setting. Clear the check box to allow the model access to your computer.
Plant Simulation generates a unique trust ID for each and every user. Models, which you save, are signed with this ID. If you load a model, which permits access to the computer and when this model is not signed with your ID, Plant Simulation asks you if you want to grant the model access to the computer.

SimTalk:
isComputerAccessPermitted
.topic 0x85360570
The check box denies the methods of this library access your computer. This is the default setting. Clear the check box to allow the methods of the library access to your computer.

If an attempt is made to execute a potentially dangerous command, Plant Simulation checks from which Method the source code is inherited and if this Method is located within a library before it checks the Model setting > Prohibit access to the computer. In this case the library setting applies instead of the model setting.

.topic 0x852a084d
To always ask with which parts you want to create a model, select this.

.topic 0x8f220f23
Enter the position of the sensor. You can enter a value between 0 and 1, i.e., between 0 percent and 100 percent.

SimTalk:
Position
.topic 0x8f220f25
Select this if the sensor is to triggered when the amount of material in the Tank has exceeded, i.e., is located above the sensor position.

SimTalk:
Exceeded
.topic 0x8f220f26
Select this if the sensor is to triggered when the amount of material in the Tank has underrun, i.e., is located below the sensor position.

SimTalk:
Underrun
.topic 0x8f220f24
Click this and select the Method object, which the sensor calls, in the dialog Select Object. To open the dialog of the object, whose name you entered into the text box, click in the text box, and press the F2 key.

As soon as the sensor calls this Method, it passes the Sensor-ID as an optional parameter. When the Method expects a parameter of data type integer, the sensor passes the Sensor-ID to the Method; if you do not enter an integer parameter, the Method will be called without a parameter. The second optional parameter of data type boolean shows the user if the front or the rear of the part triggers the control.

SimTalk: sensorID(ID).Ctrl.
.topic 0x9d9d15ff
Enter the number of objects you would like to paste into the active scene here. Or use the up and down arrows of the spin button to increase or decrease the number.
When you enter the number 5, for example, 3D pastes 5 objects. Enter an integer greater than zero. Enter 1 to have 3D perform the default paste operation, i.e., paste the object from the clipboard once.

.topic 0x939d15f8
To paste multiple copies of the object and to close the dialog, click Paste. 3D uses the number and the Offset you selected.

.topic 0x93d8140b
Enter the tread width. This is the width of the steps and thus the width of the entire stairway.

.topic 0x93d8140d
Enter the rise. This is the height of the entire stairway from the current floor to the ceiling of the next floor.

.topic 0x93d8140f
Click into the color box next to Stringer material and select the material of the stringer. The stringer borders the steps and the handrail laterally.

.topic 0x93d81410
Click into the color box next to Tread material and select the material of the steps between the stringers.

.topic 0x93e8141b
Select the Form of the barred area: Rectangular, Rectangular with hatching, or Round.

.topic 0x93e7145f
Click into the color box next to Material and select the material of the barred area.

.topic 0x85730f47
Shows the average traveled distance shows the average distance which the Worker traveled from the WorkerPool to the Workplaces attached to the stations and between the stations.

SimTalk
statAverageTraveledDistance
.topic 0x93a2145e
Shows the width of the graphic. The width is twice the radius.

.topic 0x93f915e4
Shows the minimum distance of the border of the graphic from the origin (zero point) of the scene on the X-axis.

.topic 0x93f915ea
Shows the maximum distance of the border of the graphic from the origin (zero point) of the scene on the X-axis.

.topic 0x93a2145d
Shows the depth of the graphic. The depth is twice the radius.

.topic 0x93f915e6
Shows the minimum distance of the border of the graphic from the origin (zero point) of the scene on the Y-axis.

.topic 0x93f915ec
Shows the maximum distance of the border of the graphic from the origin (zero point) of the scene on the Y-axis.

.topic 0x93f914db
Shows the width of the graphic. The width is twice the radius.

.topic 0x93f914dd
Shows the depth of the graphic. The depth is twice the radius.

.topic 0x93f914df
Shows the height of the graphic.

.topic 0x93a2145c
Shows the height of the graphic.

.topic 0x93f915e8
Shows the minimum distance of the floor of the graphic from the origin (zero point) of the scene on the Z-axis.

.topic 0x93f915ee
Shows the maximum distance of the floor of the graphic from the origin (zero point) of the scene on the Z-axis.

.topic 0x93fa17af
To use the new graphic group for visually representing the object in the 3D windows, select this.

.topic 0x88a10ee1
To create sensors in the Tank, click Sensors. This opens the dialog Sensor List, where you create new sensors or modify or delete existing sensors.

SimTalk:
createSensor
.topic 0x8ec30f2c
For a Pipe that is located directly after a FluidSource, a Tank, or a Mixer, you can enter the outflow rate with which the material flows out of the Pipe to the next object in the flow of materials. The default value -1 denotes that the Pipe uses the same outflow rate as its predecessor.
With this setting you can create the effect that not all of the succeeding Pipes connected to a FluidSource, a Tank, or a Mixer, have to have the same outflow rate.
If the predecessor of the Pipe is another Pipe, Plant Simulation ignores the value.
The outflow rate is the amount of liters of the material that flows off in a second.

SimTalk:
OutflowRate
.topic 0x9409156d
Select the type of the Store:

Floorspace: 3D places the parts on a single flat surface, either on the floor (height close to 0) or elevated in space (height greater than 0).

Rack: 3D puts the parts onto shelfs.

SimTalk:
_3D.StoreType
.topic 0x9409156f
Enter the width of the Store.

SimTalk:
_3D.Dimensions
.topic 0x94091572
Enter the depth of the Store.

SimTalk:
_3D.Dimensions
.topic 0x94091569
Enter the height of the Store.

SimTalk:
_3D.Dimensions
.topic 0x94091576
Click into the color palette next to storage area material to assign a color to the storage area of the Store in the dialog Material. The settings are the same as on the Tab Material.

.topic 0x94091575
Click into the color palette next to post material to assign a color to the posts of the rack in the dialog Material. The settings are the same as on the Tab Material.

.topic 0x93e4147e
Select one of the provided paths. They show the connections via Connectors from the predecessor of the Robot and from the Robot to its successor in the model.

.topic 0x861c0cc5
To open the table of the angles, at which the robot picks the part up or at which it places it, click this.
You can view or fine-tune these settings:
The name of the predecessor at which the robot picks the part up or the name of the successor onto which the robot deposits the part.
The angle between the station in the column Name and the robot.

When you insert Connectors or when you drag an object onto the robot and drop it there, Plant Simulation adds the respective values to the angles table. When you delete a Connector, Plant Simulation does not delete the entry of the now unconnected object from the table. You have to delete the entry yourself, for example by right-clicking the respective row and selecting Delete Row on the context menu.
Or manually change values or names in the angles table or add new stations to it. This way you can, for example, request the robot in a sensor control.

SimTalk:
setAnglesTable, getAnglesTable
.topic 0x861c0cc7
To open the table of the rotation times, click this. These are the times, which the robot needs to rotate from the station in the leftmost column to the respective stations in the columns to the right and vice versa.
Or enter a Time factor with which all times in the table are multiplied. This way you can simulate the robot with different speeds without having to manually change the times in the table.
You can view or fine-tune these settings:
The names of all objects, which the robot is to serve and the Default angle to which the robot moves after it has deposited the part.
The times above the diagonal are the times during which the robot rotates Empty. The times below the diagonal are the times during which the robot rotates full, i.e., while a part is located on it. The diagonal in the table runs from the values in the topmost cell in the column default angle to the bottommost cell in the last column.

SimTalk:
setTimesTable, getTimesTable
.topic 0x861c0cc9
Select this, if you want the robot to rotate back to its default position after it has deposited the part.
Then, enter the Default angle at which the default position is located.

SimTalk:
GoToDefaultPosition
DefaultAngle
.topic 0x861c0e2f
Enter the time factor with which all times in the Times Table are multiplied. This allows to simulate the robot with different speeds without having to manually change the times in the table.

SimTalk:
TimeFactor
.topic 0x861c0ccb
Enter the angle to which the robot rotates when you selected Go to default position. If you would like the robot to rotate to the side on which the start position is located, add 180° to this angle. You can enter a value between 0° and 360°.
The default angle is also used as the start position after a Reset, no matter if Go to default position is activated or not.

SimTalk:
DefaultAngle
.topic 0x861c0cca
Enter the blocking angle which the robot cannot cross while rotating. This prevents the robot from taking the shortest way. The default setting -1 means that no blocking angle applies and that the robot thus takes the shortest way. You can enter an angle between 0 and 360 degrees.
The blocking angle only affects the animation, the simulation is controlled by the rotation times which you defined in the Times Table.

SimTalk:
BlockingAngle
.topic 0x861c0f65
Select a distribution, and enter the values, which that distribution requires, into the text box.
The loading time is the time it takes the robot for picking up a part at a station. When the robot is full, it rotates to the target station and places the part there.
When the delivering station is a point-oriented object, the part is booked on the robot while it picks it up. The delivering station is locked until the loading time has elapsed.
When the delivering station is a length-oriented object the part remains on the delivering station during the loading time and is then moved on to the robot.

SimTalk:
LoadingTime
.topic 0x861c0f64
Select a distribution, and enter the values, which that distribution requires, into the text box.
The unloading time is the time it takes the robot for placing the part he picked up at another station onto the target station.
When the target station is a point-oriented object, the part is booked on the robot while it places it. The target station is locked until the unloading time has elapsed.
When the target station is a length-oriented object, the part is moved on to the length-oriented object before the unloading time starts.

SimTalk:
UnloadingTime
.topic 0x88ea0f5f
Select how the robot selects the target for the part that is to be moved:

Exit strategy or target control:

This is the default behavior of previous versions of the robot. You either set the target with the selected exit strategy or you define the target in the target control.

Load part onto MU at sensor:

Here you have to manually create a front-triggered sensor with light-barrier mode on the length-oriented target object. In addition you have to enter the target object and the target sensor ID. Note that stopping the Container/Transporter, loading and sending the Container/Transporter on only works automatically if you did not enter a control. If you use a control, you have to program stopping and sending the Container/Transporter on in this control.

Place part at sensor:

Here you have to manually create a rear-triggered sensor with light barrier mode on the length-oriented target object. In addition you have to enter the target object and the target sensor ID.

SimTalk:
TargetSelection
.topic 0x88ea0f61
Enter the path to the length-oriented object, at which the part is to be placed or loaded, into the text box. Or click the button and select the target object in the dialog Select Object.

SimTalk
TargetObject
.topic 0x88ea0f63
Enter the sensor ID of the target sensor at which the part will be placed or loaded.
Plant Simulation does not create the sensor automatically. You have to create it manually or use the drag-and-drop operation.

SimTalk
TargetSensorID
.topic 0x84180f27
To save the statements of often used SQL statements, click this. Then, enter the statement into the table that opens. You might, for example, enter select * from TestTable.
You can activate one of the saved statements with the method useStatement by specifying its row number in the table.

SimTalk:
executeStatement,
useStatement,
storeStatement
.topic 0x85360419
To set that this library requires 3D to display the objects it contains and to work correctly, select this.

When you load a library for which this setting is selected, and when 3D is not activated, you will be asked if you would like to activate 3D. When you click No, the library will not be loaded.
.topic 0x93b515af
To enable captions, which encompass the Name and the Label of the object, which you or Plant Simulation assigned in 2D, select the check box.
To disable captions, clear the check box.

SimTalk:
_3D.NameAndLabelEnabled
.topic 0x93b515b2
Enter a value or click the spin buttons to move the position of the caption of the object in the Frame on the X-axis.
The settings for the three axes are independent of each other.

SimTalk:
_3D.NameLabelPosition
.topic 0x93b515b6
Enter a value or click the spin buttons to move the position of the caption of the object in the Frame on the Y-axis.
The settings for the three axes are independent of each other.

SimTalk:
_3D.NameLabelPosition
.topic 0x93b515ba
Enter a value or click the spin buttons to move the position of the caption of the object in the Frame on the Z-axis.
The settings for the three axes are independent of each other.

SimTalk:
_3D.NameLabelPosition
.topic 0x93b515bd
Click this to move the captions, i.e., the Names and the Labels of the objects to their standard position.
The standard position is the bottom left corner of the graphic bounding box of the caption.

SimTalk:
_3D.NameLabelPosition
.topic 0x93b515a7
To set the axis around which to rotate the caption of the object, enter a value for each of the three components (x-y-z) that define the rotation axis.
The settings for the three axes are independent of each other.

SimTalk:
_3D.NameLabelRotation
.topic 0x93b515aa
To set the axis around which to rotate the caption of the object, enter a value for each of the three components (x-y-z) that define the rotation axis.
The settings for the three axes are independent of each other.

SimTalk:
_3D.NameLabelRotation
.topic 0x93b515ad
To set the axis around which to rotate the caption of the object, enter a value for each of the three components (x-y-z) that define the rotation axis.
The settings for the three axes are independent of each other.

SimTalk:
_3D.NameLabelRotation
.topic 0x93b515a8
Click this to set the rotation around the X-axis. This enters the respective values into the text boxes.

.topic 0x93b515ab
Click this to set the rotation around the Y-axis. This enters the respective values into the text boxes.

.topic 0x93b515ae
Click this to set the rotation around the Z-axis. This enters the respective values into the text boxes.

.topic 0x93b515a4
Enter the angle of rotation.

SimTalk:
_3D.NameLabelRotation

.topic 0x93b515be
To add a rotation angle to the axis that you select, click this.
Enter the angle which you would like to add to the axis that you select.
Select the axis to which you would like to add the angle.
Click OK to accept the values and to add the angle to the existing angle. Click Apply to show the result in the scene window.

.topic 0x93b515c6
To automatically enter this value into one text box into the remaining two text boxes for scaling the caption, select this. This way you do not have to manually enter the same value into each text box over again.
SimTalk:
_3D.NameLabelScale

.topic 0x93b515c0
Enter a value for scaling the caption on the X-axis. You can only enter positive values.

SimTalk:
_3D.NameLabelScale
.topic 0x93b515c2
Enter a value for scaling the caption on the Y-axis. You can only enter positive values.

SimTalk:
_3D.NameLabelScale
.topic 0x93b515c4
Enter a value for scaling the caption on the Z-axis. You can only enter positive values.

SimTalk:
_3D.NameLabelScale

.topic 0x84720468
To activate the PLCSIM Interface, select this. To deactivate it, clear it.

SimTalk:
Active
.topic 0x84730469
Enter the name of the virtual PLC with which the PLCSIM interface is to communicate.

SimTalk:
InstanceName
.topic 0x8473046a
To open the table into which you enter the PLCSIM items, click this. Each row in this table represents a group.
Enter the names of the groups into the cells below Group Name.
Select the type of signal, which the group is to contain, in the cells below Signal Type.
PLC In are input signals of the PLC. You can assign a value in a SimTalk Method to such an item.
PLC Out are output signals of the PLC. You can query the value of such an item in a SimTalk Method.
Enter the time in milliseconds into the cells below Interval. After at least this time has elapsed, Plant Simulation exchanges signals and data with the virtual PLC. If you enter 0 here, Plant Simulation exchanges signals and data after each cycle of the virtual PLC.

SimTalk:
getItems,
setItems
.topic 0x8473046b
To open a table that shows the values of the Items you defined, click this. Double-click a group name in the table that opens, so that Plant Simulation shows the values of the items of this group.

.topic 0x84730493
To import all items that the virtual PLC provides, click this. To do so, you first have to activate the connection. Plant Simulation then creates groups for these items.

SimTalk:
getItems,
setItems
.topic 0x847304bd
Enter the IP address and port of the Runtime Manager. Leave this field empty if you want to use the Runtime manager on your local computer.

SimTalk:
RemoteRuntimeManager
.topic 0x861c0f66
Select this, if you want the robot only to rotate back to its default position when its blocking list is empty, i.e., when no additional requests are registered for it.
You can only change the state of Only for empty blocking list when Go to default position is active.

SimTalk:
OnlyForEmptyBlockingList
.topic 0x847304bf
Enter the value of the data exchange interval. This is the time span in milliseconds in which the PLCSIM Interface exchanges data with the virtual PLC while the simulation model runs in real time.
When you enter 0, Plant Simulation sets the operating mode SingleStep in the virtual PLC and exchanges data after each cycle of the virtual PLC. During data exchange the virtual PLC is in Freeze mode. This ensures that all data is completely transmitted before the next cycle starts. This also causes the virtual time to stand still during data exchange. Thus the virtual time progresses slower than real time. Plant Simulation synchronizes the simulation time with the virtual PLC and thus the simulation model runs slower than real time.

SimTalk:
DataExchangeInterval
.topic 0x93f01764
Enter the width of the frame around the conveyor.

.topic 0x93f01780
To add a new extrusion profile, click this.

.topic 0x93f01781
To delete the extrusion profile that you selected in the list, click this.

.topic 0x93f01769
Enter the diameter of the rollers.

.topic 0x93aa159f
To adjust the size and positioning of the graphic of the MU to the measurements and the booking point of the MU in 2D, select this. 3D then hides the settings for scaling the MU.

SimTalk:
_3D.ScaleAutomatically
.topic 0x93aa157c
Select the respective check box to mirror/flip the selected object on this plane.
If your model also has a 2D part, the object will be mirrored there as well.

SimTalk:
_3D.Mirror
.topic 0x93aa157d
Select this to mirror/flip the selected object on the YZ-plane.

SimTalk:
_3D.Mirror
.topic 0x93aa157e
Select this to mirror/flip the selected object on the XZ-plane.

SimTalk:
_3D.Mirror
.topic 0x93aa157f
Select this to mirror/flip the selected object on the XY-plane.

SimTalk:
_3D.Mirror
.topic 0x93c815f7
To adjust the size of the MUs to their size in 2D, click this.

.topic 0x93aa158d
Click this to set the x-component of the rotation axis. This enters the respective values into the text boxes.

.topic 0x93aa158e
Click this to set the y-component of the rotation axis. This enters the respective values into the text boxes.

.topic 0x93aa158f
Click this to set the z-component of the rotation axis. This enters the respective values into the text boxes.

.topic 0x93f21518
The check box shows the settings for the animation area. This is the default setting. If you would like to show the settings for animation paths, clear the check box.
The animation area defines the size of the area on the object on which 3D places the MUs. By default 3D uses the bounding box of the selected simulation object.

Only the objects with matrix loading space ParallelStation, Store, PlaceBuffer, Transporter, Container, and Worker provide these settings.

SimTalk:
_3D.MUAnimationAreaEnabled
.topic 0x93f2151b
Select the orientation of the animation area on which 3D places the MUs:

XY-plane places the MU on the XY-plane, i.e., flat on the machine.

XZ-plane places the MU on the XZ-plane, i.e., perpendicular to the front or the back of the machine.

YZ-plane places the MU on the XZ-plane, i.e., perpendicular to the right or the left side of the machine.

SimTalk:
_3D.MUAnimationAreaOrientation
.topic 0x93f214fb
Enter the relative length of the animation area. You can enter a value between 0 and any size [0..1..]. This value is used for assignments in SimTalk.

SimTalk:
_3D.MUAnimationAreaSize
.topic 0x93f214fc
Enter the absolute length of the animation area in meters.

SimTalk:
_3D.MUAnimationAreaSize
.topic 0x93f214de
Enter the relative width of the animation area. You can enter a value between 0 and any size [0..1..]. This value is used for assignments in SimTalk.

SimTalk:
_3D.MUAnimationAreaSize
.topic 0x93f214df
Enter the absolute width of the animation area in meters.

SimTalk:
_3D.MUAnimationAreaSize
.topic 0x93f214cb
Enter the relative x-position of the center point of the animation area onto which 3D places the parts. The settings for the center point move the storage places that are spaced evenly across the animation area to adapt it to the 3D graphic.
You can enter any negative or positive value [..0..1..]. This value is used for assignments in SimTalk.

To move the center point to the right, type in a positive value into the text box X.

To move the center point to the left, type in a negative value.

To move the center point into several directions at the same time, type in the values into the respective text boxes.

SimTalk:
_3D.MUAnimationAreaCenter
.topic 0x93f214ce
Enter the relative y-position of the center point of the animation area onto which 3D places the parts. The settings for the center point move the storage places that are spaced evenly across the animation area to adapt it to the 3D graphic.
You can enter any negative or positive value [..0..1..]. This value is used for assignments in SimTalk.

To move the center point to the back, type in a positive value into the text box Y.

To move the center point to the front, type in a negative value.

To move the center point into several directions at the same time, type in the values into the respective text boxes.

SimTalk:
_3D.MUAnimationAreaCenter
.topic 0x93f214d1
Enter the relative z-position of the center point of the animation area onto which 3D places the parts. The settings for the center point move the storage places that are spaced evenly across the animation area to adapt it to the 3D graphic.
You can enter any negative or positive value [..0..1..]. This value is used for assignments in SimTalk.

To move the center point up, type in a positive value into the text box Z.

To move the center point down, type in a negative value.

To move the center point into several directions at the same time, type in the values into the respective text boxes.

SimTalk:
_3D.MUAnimationAreaCenter
.topic 0x93f214cc
Enter the absolute x-position in meters of the center point of the animation area onto which 3D places the parts. The settings for the center point move the storage places that are spaced evenly across the animation area to adapt it to the 3D graphic.

To move the center point to the right, type in a positive value into the text box X.

To move the center point to the left, type in a negative value.

To move the center point into several directions at the same time, type in the values into the respective text boxes.

SimTalk:
_3D.MUAnimationAreaCenter
.topic 0x93f214cf
Enter the absolute y-position in meters of the center point of the animation area onto which 3D places the parts. The settings for the center point move the storage places that are spaced evenly across the animation area to adapt it to the 3D graphic.

To move the center point to the back, type in a positive value into the text box Y.

To move the center point to the front, type in a negative value.

To move the center point into several directions at the same time, type in the values into the respective text boxes.

SimTalk:
_3D.MUAnimationAreaCenter
.topic 0x93f214d2
Enter the absolute z-position in meters of the center point of the animation area onto which 3D places the parts. The settings for the center point move the storage places that are spaced evenly across the animation area to adapt it to the 3D graphic.
You can enter the position as a relative or as an absolute value. Plant Simulation automatically converts the value to the respective other value.

To move the center point up, type in a positive value into the text box Z.

To move the center point down, type in a negative value.

To move the center point into several directions at the same time, type in the values into the respective text boxes.

SimTalk:
_3D.MUAnimationAreaCenter
.topic 0x93f21519
To show the animation area, click Show. To hide it again, click Hide.

.topic 0x93f21511
Enter the angle of the MU rotation, which you want to add to the rotation axis.

SimTalk:
_3D.MUAnimationAreaMURotation
.topic 0x93f21512
Enter a value for the x-component of the rotation axis.
Instead, you can click on the button to the right of the axis, to set this component of the rotation axis. This enters the respective values into the text boxes.

SimTalk:
_3D.MUAnimationAreaMURotation
.topic 0x93f21514
Enter a value for the y-component of the rotation axis.
Instead, you can click on the button to the right of the axis, to set this component of the rotation axis. This enters the respective values into the text boxes.

SimTalk:
_3D.MUAnimationAreaMURotation
.topic 0x93f21516
Enter a value for the z-component of the rotation axis.
Instead, you can click on the button to the right of the axis, to set this component of the rotation axis. This enters the respective values into the text boxes.

SimTalk:
_3D.MUAnimationAreaMURotation
.topic 0x93f21513
Click this to set the x-component of the rotation axis. This enters the respective values into the text boxes.
.topic 0x93f21515
Click this to set the y-component of the rotation axis. This enters the respective values into the text boxes.
.topic 0x93f21517
Click this to set the z-component of the rotation axis. This enters the respective values into the text boxes.

.topic 0x93e1147b
Select one of the available path types:

A Lines path consists of straight lines or a sequence of straight lines joined by vertices.

A Polycurve path consists of the vertices of a curved object, i.e., a sequence of curved and straight lines, on which MUs are animated, when they are transferred onto a material flow object.

A Spline path consists of the vertices, i.e., the anchor points of a spline curve.

A Rotation path (Lines) consists of straight lines or a sequence of straight line joined by vertices. These set the area, the axis, and the center of rotation of the MU.

.topic 0x861c0f67
Select the conveying direction of the MU when the Pick-and-Place robot passes the part on to its successor and places it there.

For the settings Retain, Rotate by 90° to the right, Rotate by 90° to the left, and Rotate by 180° the Pick-and-Place robot executes a relative rotation depending on the direction from which the MU arrives.

For the settings Forwards, Lateral right, Backwards, and Lateral left the rotation is an absolute rotation independent of the direction from which the MU arrives.

SimTalk:
MUConveyingDirection
.topic 0x8F6D0F6E
Type in the maximum width of the Sankey flows, which visualize the paths of the Workers in the Frame, who are moving freely within the area.

SimTalk:
MaximumWidth
.topic 0x8F6D0F6F
Select the color of the Sankey flows, which visualize the paths of the Workers in the Frame, who are moving freely within the area.

SimTalk:
Color
.topic 0x8F6A0F6B
To make the WorkerSankeyDiagram collect data, select this. To deactivate the collection of data, clear the check box.

SimTalk:
CollectData
.topic 0x8F6A0F6C
To show the Sankey flows in the Frame, click Show Diagram. To hide the Sankey flows, click Hide Diagram.
The WorkerSankeyDiagram is only shown in 3D, not in 2D.

SimTalk:
Active
.topic 0x9396144a
To add a rotation angle to the axis that you select, click this.
Enter the angle which you would like to add to the axis that you select.
Select the axis to which you would like to add the angle.
Click OK to accept the values and to add the angle to the existing angle. Click Apply to show the result in the scene window.

.topic 0x93961449
To add a rotation angle to the axis that you select, click this.
Enter the angle which you would like to add to the axis that you select.
Select the axis to which you would like to add the angle.
Click OK to accept the values and to add the angle to the existing angle. Click Apply to show the result in the scene window.

.topic 0x93961443
Enter a value for the x-component of the rotation axis.
Instead, you can click on the button to the right of the axis, to set this component of the rotation axis. This enters the respective values into the text boxes.

.topic 0x93961445
Enter a value for the Y-component of the rotation axis.
Instead, you can click on the button to the right of the axis, to set this component of the rotation axis. This enters the respective values into the text boxes.

.topic 0x93961447
Enter a value for the z-component of the rotation axis.
Instead, you can click on the button to the right of the axis, to set this component of the rotation axis. This enters the respective values into the text boxes.

.topic 0x93961444
Click this to set the x-component of the rotation axis. This enters the respective values into the text boxes.

.topic 0x93961446
Click this to set the y-component of the rotation axis. This enters the respective values into the text boxes.

.topic 0x93961448
Click this to set the z-component of the rotation axis. This enters the respective values into the text boxes.

.topic 0x93b71482
Clear this to hide this walking height of the Worker that Plant Simulation calculated.

.topic 0x93a9146e
Click this to activate the selected camera mark.

.topic 0x93a9146d
Click this to rename the selected camera mark. Type in a new name into the dialog that opens.

.topic 0x93a9146d
Type in a new name for the camera mark.

.topic 0x93a8146b
This field shows the scene path of the camera mark.

.topic 0x93a9146f
Click this to delete the selected camera mark.

.topic 0x93a91470
Click this to move the selected camera mark up in the list.

.topic 0x93a91471
Click this to move the selected camera mark down in the list.

.topic 0x93a9146c
The list in the dialog shows the defined camera marks. You can activate, rename, move up or move down, or delete the selected camera mark in the list.

.topic 0x93a21474
Enter the top radius of the cone you want to create.
A top radius of 0 creates the cone with a tip.
A top radius of greater than 0 cuts of the tip of the cone. This way you can, for example, model a bottle quickly and easily.

.topic 0x93a21476
Enter the bottom radius of the cone you want to create.
Type in a greater bottom radius than the top radius to create a funnel-type truncated cone.

.topic 0x93a2145c
Enter the Height of the cone you want to create.

.topic 0x93a21462
Enter the Wall thickness of the cone.

If you do not specify the wall thickness, Plant Simulation creates a closed cone.

If you specify a negative value, Plant Simulation interprets this as if you did not specify a value.

If you enter 0, Plant Simulation creates mantle without a thickness.

If you enter a positive value, Plant Simulation creates the cone with the specified wall thickness.

.topic 0x93a21473
Select Create covers to create the frustum with a top and a bottom. Clear Create covers to leave the top and the bottom of the cone open.

.topic 0x93db161f
Enter a value or click the spin buttons to move the position of the selected anchor point on the X-axis. The settings for the three axes are independent of each other.

.topic 0x93db1620
Enter a value or click the spin buttons to move the position of the selected anchor point on the Y-axis. The settings for the three axes are independent of each other.

.topic 0x93db1621
Enter a value or click the spin buttons to move the position of the selected anchor point on the Z-axis. The settings for the three axes are independent of each other.

.topic 0x93db161f
Enter a value for the position, or click the spin buttons to add a common offset to the position of the anchor point on the X-axis. The settings for the three axes are independent of each other.

.topic 0x93db1620
Enter a value for the position, or click the spin buttons to add a common offset to the position of the anchor point on the Y-axis. The settings for the three axes are independent of each other.

.topic 0x93db1621
Enter a value for the position, or click the spin buttons to add a common offset to the position of the anchor point on the Z-axis. The settings for the three axes are independent of each other.

.topic 0x93aa13b8
Enter a value or click the spin buttons to move the position of the object on the X-axis, the Y-axis, and the Z-axis. The settings for the three axes are independent of each other.

SimTalk:
_3D.Position
.topic 0x93aa1578
Enter a value or click the spin buttons to move the position of the object on the X-axis. The settings for the three axes are independent of each other.

To move the object by 0.01 meters, click the mouse into the respective text box, hold down the Ctrl key and roll the mouse wheel.

For MU instances the settings for the position show the local positions calculated by the animation.

SimTalk:
_3D.Position
.topic 0x93aa1579
Enter a value or click the spin buttons to move the position of the object on the Y-axis. The settings for the three axes are independent of each other.

To move the object by 0.01 meters, click the mouse into the respective text box, hold down the Ctrl key and roll the mouse wheel.

For MU instances the settings for the position show the local positions calculated by the animation.

SimTalk:
_3D.Position
.topic 0x93aa157a
Enter a value or click the spin buttons to move the position of the object on the Z-axis. The settings for the three axes are independent of each other.

To move the object by 0.01 meters, click the mouse into the respective text box, hold down the Ctrl key and roll the mouse wheel.

For MU instances the settings for the position show the local positions calculated by the animation.

SimTalk:
_3D.Position
.topic 0x93f214e4
Enter a number for the factor, which 3D uses for the animation on the test path.

When you select Backwards, 3D automatically enters a negative velocity, and the MU moves towards the starting point of the animation path.

.topic 0x93c815f0
Sets if the graphic groups of the object inherit their visibility from the origin object or not. It also shows the state of the attribute _3D.VisibleGraphics.

As soon as you activate or deactivate the check box Visible of one of the graphic groups, 3D changes the state of the Visibilities to non-inheriting. Or you can set inheritance of the visibility by clicking the toggle button.

SimTalk:
_3D.VisibleGraphics
.topic 0x88210f74
To stop the MU on a Conveyor, a Track, or a TwoLaneTrack, select this. To  makes it continue on its way, clear it.

You can use it to make an MU, which you want to load onto a pallet, stop and wait until the pallet arrives. Once the pallet has arrived, you can stop the MU, so that it can be loaded onto the pallet. Most often you will use the function within a driving control of the Transporter.

SimTalk:
Stopped
.topic 0x8f0a0f18
Shows the statistics table types that the selected object provides. The different objects provide different statistics table types. Select the statistics table that you want to show in the report.

.topic 0x8f0a0f16
Enter the column indexes of the columns of the statistics table that you want to show in the report. If you want to show several columns, separate them with a comma.

.topic 0x93f0172c
Enter the width of the legs of the conveyor.

.topic 0x93f01725
Click this and select the settings of the material of the belt proper of the conveyor.

.topic 0x93f01727
Click this and select the settings of the material of the carrier on which the belt of the conveyor moves.

.topic 0x93f017a7
Enter the height of the beltp proper of the conveyor.

.topic 0x93f017aa
Enter the width of the belt proper of the conveyor.

.topic 0x93f0179f
Enter the height of the carrier on which the belt of the conveyor moves.

.topic 0x93f01750
Click this and select the settings of the material of the guide rails of the conveyor.
.topic 0x93f01729
Enter the height of the guide rails of the conveyor. The height is measured starting at the top of the belt carrier.

.topic 0x93f0172f
Enter the diameter of the guide rails of the conveyor.

.topic 0x93f0176c
Enter the distance of the individual mounts from each other.

.topic 0x93951723
Select this to also scale the state graphics when scaling the object itself.
Clear it to not scale the state graphics when scaling the object. Here Plant Simulation still scales the position of the state graphics.

SimTalk:
_3D.StatesScaleWithObject
.topic 0x939516fa
Enter a value or click the spin buttons to move the position of the state graphics on the X-axis. The settings for the three axes are independent of each other.

.topic 0x93951700
Enter a value or click the spin buttons to move the position of the state graphics on the Y-axis. The settings for the three axes are independent of each other.

.topic 0x93951706
Enter a value or click the spin buttons to move the position of the state graphics on the Z-axis. The settings for the three axes are independent of each other.

.topic 0x9395170b
Select this to mirror/flip the state graphics on the YZ-plane.

.topic 0x9395170d
Select this to mirror/flip the state graphics on the XZ-plane.

.topic 0x9395170f
Select this to mirror/flip the state graphics on the XY-plane.

.topic 0x93951712
To automatically enter the value you enter into one text box into the remaining two text boxes to scale the state graphic, select this. This way you do not have to manually enter the same value into each text box over again.

SimTalk:
_3D.StatesScale

.topic 0x93951716
Enter a value or click the spin buttons to scale the state graphics on the X-axis. You can only enter positive values.

.topic 0x9395171b
Enter a value or click the spin buttons to scale the state graphics on the Y-axis. You can only enter positive values.

.topic 0x93951720
Enter a value or click the spin buttons to scale the state graphics on the Z-axis. You can only enter positive values.

.topic 0x93951722
Select this to also scale the state graphics when scaling the object itself.
Clear it to not scale the state graphics when scaling the object. Here Plant Simulation still scales the position of the state graphics.

SimTalk:
_3D.StatesScaleWithObject
.topic 0x939516f8
Enter a value or click the spin buttons to move the position of the state graphics on the X-axis. The settings for the three axes are independent of each other.

.topic 0x939516fe
Enter a value or click the spin buttons to move the position of the state graphics on the Y-axis. The settings for the three axes are independent of each other.

.topic 0x93951704
Enter a value or click the spin buttons to move the position of the state graphics on the Z-axis. The settings for the three axes are independent of each other.

.topic 0x9395170a
Select this to mirror/flip the state graphics on the YZ-plane.

.topic 0x9395170c
Select this to mirror/flip the state graphics on the XZ-plane.

.topic 0x9395170e
Select this to mirror/flip the state graphics on the XY-plane.

.topic 0x93951711
To automatically enter the value you enter into one text box into the remaining two text boxes to scale the state graphic, select this. This way you do not have to manually enter the same value into each text box over again.

SimTalk:
_3D.StatesScale

.topic 0x93951714
Enter a value or click the spin buttons to scale the state graphics on the X-axis. You can only enter positive values.

.topic 0x93951719
Enter a value or click the spin buttons to scale the state graphics on the Y-axis. You can only enter positive values.

.topic 0x9395171e
Enter a value or click the spin buttons to scale the state graphics on the Z-axis. You can only enter positive values.

.topic 0x84D20F7E
To make the die ParallelStation only start processing the parts when a part each is located on all processing stations, select this.

SimTalk:
StartProcessingWhenFull
.topic 0x892f0f7c
Shows the portion of the time in percent during which the Conveyor is blocked because no part can leave it because no successor can take the part.

SimTalk:
StatExitBlockedPortion,
StatExitBlockedTime

.topic 0x85aa05ab
To show the data, which the GanttChart collected in the display window, click this.

SimTalk:
Active
.topic 0x85aa05ac
To make the GanttChart collect data during the simulation run, select this. To deactivate data collection, clear the check box.

SimTalk:
CollectData
