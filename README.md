monkey.textwrangler
===================

This codeless language module lets you to use the Mac OS X editor [TextWrangler](http://www.barebones.com/products/textwrangler/) as an IDE for the [monkey programming language](http://www.monkeycoder.co.nz).

Created by Matt Sephton, [http://www.gingerbeardman.com/monkey/](http://www.gingerbeardman.com/monkey/)

## Features

**Syntax Colouring**  
Easily see the difference between keywords, constants, strings and comments

**Easy Source Navigation**  
Navigate around your source using the index of functions, classes and methods

## Installation
Copy or move the `MonkeyCodelessLanguageModule.plist` file to the folder at:

	~/Library/Application Support/TextWrangler/Language Modules/

You may need to restart TextWrangler for the changes to take effect.

## BBEdit

I have also created a package for BBEdit which does everything this TextWrangler one can do, plus more!

[https://github.com/gingerbeardman/monkey.bbedit](https://github.com/gingerbeardman/monkey.bbedit)

If you own BBEdit, you probably want to use that one instead.

## License
monkey.textwrangler is made available under a [Creative Commons Attribution-Share Alike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0).

## Support
You can talk about the package on the [official monkey forum](http://www.monkeycoder.co.nz/Community/posts.php?topic=1320)

## Requirements
- TextWrangler [http://www.barebones.com/products/textwrangler/](http://www.barebones.com/products/textwrangler/)
- monkey [http://www.monkeycoder.co.nz](http://www.monkeycoder.co.nz)

## Changelog

2012-05-04  
- Added DrawPoint (v50)  

2011-10-08  
- Added FirstNode, LastNode, NextNode, PrevNode, Exp (v45c)  
- Added DisableKeyboard, EnableKeyboard (v45)  
- Added ACosr, ASinr, ATan2r, ATanr, Cosr, Sinr, Tanr (v44)  
- Added DrawPoly (v43)  
- Added App: UpdateRate  
- Added Audio: music commands (v35), Discard  
- Added Graphics: DeviceHeight, DeviceWidth, Frames, HandleX, HandleY, Height, Width  
- Added Lang: Print, Length, Resize, Compare, ToLower, ToUpper, Trim  
- Added List: Backwards, Clear, Count, First, IsEmpty, Last, LastNode, ObjectEnumerator, RemoveFirst, RemoveLast, Value, ToArray  
- Added Map: Set, Values, Key  
- Added Random: Seed  
- Added Set: Insert  
- Added Stack: Insert, Pop, Push, Top  
