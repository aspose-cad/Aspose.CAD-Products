---
title: C# CAD Files Conversion
url: /net/conversion/
description: Convert CAD formats DWG DXF STL CF2 DWF IGES DGN STL FBX OBJ with few lines of C# code via .NET library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="CAD Formats Conversion Via C#" h2="Convert CAD document formats to DWG, DXF, DGN, PDF and other Vector and Raster Images to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

For any AutoCAD formats processing application, **.NET CAD API** facilitates the conversion processes easily to view or display CAD designs within the web or desktop applications. API not only loads main AutoCad formats including DWG, DXF, DGN, IFC, IGES, DWF, DWFx, STL, PLT but also converts to PDF and raster images such as PNG, JPG, BMP, TIFF, and GIF with ease.  

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert CAD to Images" %}}

As it is not possible to view or embed CAD formats directictly within in web applications or desktop solutions, so there is need of conversion. Process of conversion is simple, Load the source CAD file via API [Image.Load](https://apireference.aspose.com/cad/net/aspose.cad.image/load/methods/2) method. Create the [CadRasterizationOptions](https://apireference.aspose.com/cad/net/aspose.cad.imageoptions/cadrasterizationoptions) instance and set the related parameters such as page width and height. API provides the [ImageOptionsBase](https://apireference.aspose.com/cad/net/aspose.cad/imageoptionsbase) abstract class for setting relevant image options object like [BmpOptions](https://apireference.aspose.com/cad/net/aspose.cad.imageoptions/bmpoptions), [GifOptions](https://apireference.aspose.com/cad/net/aspose.cad.imageoptions/gifoptions), [JpegOptions](https://apireference.aspose.com/cad/net/aspose.cad.imageoptions/jpegoptions),[SvgOptions](https://apireference.aspose.com/cad/net/aspose.cad.imageoptions/svgoptions) for **CAD to SVG Conversion**, [PngOptions](https://apireference.aspose.com/cad/net/aspose.cad.imageoptions/pngoptions) and more listed within [ImageOptions Namespace](https://apireference.aspose.com/cad/net/aspose.cad.imageoptions).

{{% blocks/products/pf/feature-page-code h3="C# Code for CAD to Images" %}}

{{< gist "aspose-com-gists" "fa9ce3c2849df7748c9043e827afecf1" "convert-dwg-dxf-to-bmp-gif-tiff.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="dgn-to-bmp dwf-to-jpeg dwfx-to-png dxf-to-gif ifc-to-tiff igec-to-pdf stl-to-bmp" >}}