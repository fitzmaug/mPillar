mPillar
=======

Demonstration iOS application - Auto layout constraints playground.


Features:
---------

* Simple UIView constraints using Visual Formatting.
    intrinsicContentSize
    
* Simple UILabel constraints using Visual Formatting.
    preferredMaxLayoutWidth

* Simple UIButton constraints using Visual Formatting.
    setContentHuggingPriority

* iOS7 topLayoutGuide.

* Simplification category for adding visual constraints.

* Simple helper MACRO MXDictionaryOfVariableBindings.

* Simple example of UIScrollView and Autolayout.


Usage:
------

Build and run using Xcode5 (or later), targeting iOS7 (or later).

You can optionally add the custom runtime argument `-UIViewShowAlignmentRects YES`, via the scheme editor.
This will render the Auto layout bounding boxes in a yellow wireframe.

This application has also been built to make use of Reveal App (See the Application delegate).
Read their most excellent integration guide to find how to use the Reveal Dynamic Library.
You will need to copy the libReveal.dylib file across to this project folder.

See http://revealapp.com/


Support:
--------

Not much I'm afraid. This is really an experimental playground, have fun.

* Twitter: [@molescat](http://twitter.com/molescat)


Collaboration:
--------------

If you have any feature requests/bug-fixes etc. feel free to help out and send a pull request, or create a new issue.


License:
--------

mPillar is Copyright (c) 2013 Myles Abbott and released open source
under a MIT license:

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.
    