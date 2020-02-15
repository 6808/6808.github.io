# 6.808-website

This is the web page for MIT 6.808, starting from the Spring 2019 offering.

## Editing
Info pages (index, calendar, notes, answers) are based on [jemdoc](https://jemdoc.jaboc.net/).
Edit `*.jemdoc` and run `make`, which will auto update the corresponding HTML files.
If HTML files are edited directly, those changes will be overwritten by the next time `make` is called.
See this [cheat sheet](https://jemdoc.jaboc.net/cheatsheet.html) for jemdoc's syntax.

Lab pages only have an HTML version.
Edit HTML files directly to update those pages.

## To-dos
Some codes will need updating.
- **Swift**: Xcode has an internal migration tool to automatically update from one version of Swift to another. However, a specific version of Xcode may have to be downloaded, and some further manual debugging may be required. For example, Swift 3.0 can be migrated to Swift 4.2 using Xcode 10.1. Older versions of Xcode can be downloaded from [this page](https://developer.apple.com/download/more/?=xcode).
- **Lab 4 (python)**: The OpenCV library used in the current code in 2.4 (`import cv`), but should be changed to 3.x or 4.x (`import cv2`), which is much easier to install. However, there are certain functions that cannot be changed directly and require manual edits.
