# RAD Studio 10.3.3 - FixIDEScrollBar package
Fixes the Code Complete dangling scroll bar issue.

When you're in a Delphi project, and press Ctrl Spacebar to activate Code Completion, followed by Ctrl F9, the scrollbar from the Code Completion window will be left dangling system-wide. Even if you switch to another application, it will still dangle there, until you close the IDE.

After installing this package, the dangling scrollbar will no longer be an issue.

The video below demonstrates the issue. Watch the right side of the code completion window, and look there when the progress dialog has been closed. It will pop right out again.
![FixIDEScrollBar bug](https://github.com/chuacw/10_3_3-FixIDEScrollBar/blob/master/10-3-3CodeCompleteScrollBarBug.gif)

# Installation instructions
Download the BPL, and place it in C:\Users\Public\Documents\Embarcadero\Studio\20.0\Bpl or a location accessible to the IDE. Install the BPL using [Component, Install Package](http://docwiki.embarcadero.com/RADStudio/Rio/en/Installing_Component_Packages).
