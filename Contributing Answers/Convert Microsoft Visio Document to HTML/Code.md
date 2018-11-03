# C#
```js
// Path for input and output documents directory.
String dirPath = "D:/Download/";
 
// Load the sample Microsoft Visio document inside the Aspose Diagram object.
Aspose.Diagram.Diagram dg = new Diagram(dirPath + "SampleConvertMicrosoftVisioDocumentToHTML.vsdx");
 
// Save Diagram object into HTML format.
dg.Save(dirPath + "Output.html", SaveFileFormat.HTML);
```

# Java
```js
// Path for input and output documents directory.
String dirPath = "D:/Download/";
 
// Load the sample Microsoft Visio document inside the Aspose Diagram object.
com.aspose.diagram.Diagram dg = new Diagram(dirPath + "SampleConvertMicrosoftVisioDocumentToHTML.vsdx");
 
// Save Diagram object into HTML format.
dg.save(dirPath + "Output.html", SaveFileFormat.HTML);
```