---
title: Java CAD Files Conversion
url: /java/conversion/
description: Convert AutoCad formats DWG DXF STL CF2 DWF IGES DGN STL FBX OBJ with few lines of Java code via Java library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="CAD Formats Conversion Via Java" h2="Convert CAD document formats to DWG, DXF, DGN, PDF and other Vector and Raster Images to build cross-platform Java applications." >}}

{{% blocks/products/pf/feature-page-summary %}}
AutoCad files can be viewed within webpages or desktop application after rendering to images or PDF as well as some more cases to view the CAD files without requiring AutoCAD or any other rendering workflow. **Java CAD library** facilitates to process and render CAD drawings and conversion procedures are highly configurable due to its [CadRasterizationOptions class](https://apireference.aspose.com/java/cad/com.aspose.cad.imageoptions/CadRasterizationOptions).

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert CAD to Images" %}}

To convert the AutoCad formats, Load the source format via [Image.load](https://apireference.aspose.com/cad/java/com.aspose.cad/image). Create the  CadRasterizationOptions class object and developers can use it to set optional features for rendering process according to the application requirement. Set the relevant settings such as width, height, background color and more. Create the relevant PDF or images options for assigning the setting in previous step. Check the list from the sub classes list of [ImageOptionsBase class](https://apireference.aspose.com/cad/java/com.aspose.cad.class-use/ImageOptionsBase) for relevant target file options. Finally call the save method with output file and image or PDF options as parameters. 

{{% blocks/products/pf/feature-page-code h3="Java Code for CAD to Images" %}}

{{< gist "aspose-com-gists" "2789628881df93e0012cfad00bbc73e1" "convert-dxf-to-png.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="Java Code for DXF to JPG Conversion" %}}

{{< gist "aspose-com-gists" "49c1b75d9a84e149ecf374ece2c2597d" "Examples-src-main-java-com-aspose-cad-examples-CADConversion-ConvertCADLayerToRasterImageFormat-.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="dgn-to-bmp dwf-to-jpeg dwfx-to-png dxf-to-gif ifc-to-tiff igec-to-pdf stl-to-bmp" >}}