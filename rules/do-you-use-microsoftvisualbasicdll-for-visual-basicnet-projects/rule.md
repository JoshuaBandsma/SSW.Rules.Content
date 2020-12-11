---
type: rule
archivedreason: 
title: Do you use Microsoft.VisualBasic.dll for Visual Basic.NET projects?
guid: b4257bbf-0e0b-471c-b0ba-6497fe1f25af
uri: do-you-use-microsoftvisualbasicdll-for-visual-basicnet-projects
created: 2009-04-28T02:53:36.0000000Z
authors:
- id: 1
  title: Adam Cogan
- id: 17
  title: Ryan Tee
related: []

---

The Microsoft.VisualBasic library is provided to ease the implementation of the VB.NET language itself. For VB.NET, it provides some methods familiar to the VB developers and can be seen as a helper library. It is a core part of the .NET redistribution and maps common VB syntax to framework equivalents, without it some of the code may seem foreign to VB programmers.   
<!--endintro-->


| Microsoft.VisualBasic  | .NET Framework  |
| --- | --- |
| CInt, CStr  | Convert.ToInt(...), ToString()  |
| vbCrLf  | Environment.NewLine, or "\r\n"  |
| MsgBox  | MessageBox.Show(...)  |