# C#
```js
// Path for input and output documents directory.
String dirPath = "D:/Download/";
 
// Load the sample Microsoft Visio document inside the Aspose.Diagram.Diagram object.
Aspose.Diagram.Diagram dg = new Diagram(dirPath + "SampleVisioDiagram.vsdx");
 
// Save the Diagram object into PDF format.
dg.Save(dirPath + "OutputVisioDiagram.pdf", SaveFileFormat.PDF);
```
 
# Java
```js
// Path for input and output documents directory.
String dirPath = "D:/Download/";
 
// Load the sample Microsoft Visio document inside the com.aspose.diagram.Diagram object.
com.aspose.diagram.Diagram dg = new Diagram(dirPath + "SampleVisioDiagram.vsdx");
 
// Save the Diagram object into PDF format.
dg.save(dirPath + "OutputVisioDiagram.pdf", SaveFileFormat.PDF);
```
