# C#
```js
// Path for input and output documents directory.
String dirPath = "D:/Download/";

// Load the sample Microsoft Visio document inside the Aspose.Diagram.Diagram object.
Aspose.Diagram.Diagram dg = new Diagram(dirPath + "SampleConvertMicrosoftVisioDocumentToBMP.vsd");

// Specify Image Save Options - set the resolution of your choice.
Aspose.Diagram.Saving.ImageSaveOptions imgOpts = new Aspose.Diagram.Saving.ImageSaveOptions(SaveFileFormat.BMP);
imgOpts.Resolution = 200;

// Save the Diagram object into BMP format with specified ImageSaveOptions.
dg.Save(dirPath + "OutputConvertMicrosoftVisioDocumentToBMP.bmp", imgOpts);
```

# Java
```js
// Path for input and output documents directory.
String dirPath = "D:/Download/";

// Load the sample Microsoft Visio document inside the com.aspose.diagram.Diagram object.
com.aspose.diagram.Diagram dg = new Diagram(dirPath + "SampleConvertMicrosoftVisioDocumentToBMP.vsd");

// Specify Image Save Options - set the resolution of your choice.
com.aspose.diagram.ImageSaveOptions imgOpts = new ImageSaveOptions(SaveFileFormat.BMP);
imgOpts.setResolution(200);

// Save the Diagram object into BMP format with specified ImageSaveOptions.
dg.save(dirPath + "OutputConvertMicrosoftVisioDocumentToBMP.bmp", imgOpts);
```