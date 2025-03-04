﻿# Back Office Editor Viewer for Umbraco
The Umbraco package to let you see who is also looking at the same content as you.  

![Editor view](https://github.com/Rockerby/BackOfficeEditorView/raw/main/BackOfficeEditorView/img/overview.png)
  
## How to install
The easiest way is to install from [NuGet](https://www.nuget.org/packages/Arjo.UmbracoBackOfficeEditorView/) using:

`dotnet add package Arjo.UmbracoBackOfficeEditorView`
  
## How to use
After installing the package you will see an icon next to the name bar of the content. You'll be immediately notified when another user is viewing that content,
either before the start or during your session. Simply click the icon to see who the other editors are.  

To add a locking feature so that other editors can't edit the content while you are, add the following to your appSettings.json:  

```
{
  ...
  
  "BackOfficeEditorView": {
    "canLockContent": true
  }
}
```
  
If you have any issues or questions, reach out to me over on GitHub - https://github.com/Rockerby/BackOfficeEditorView  
  
Tested and working on:  
 - v10.x

Shout out to [@lssweatherhead](https://github.com/lssweatherhead) for the locking feature 👍
