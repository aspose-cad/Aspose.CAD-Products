---
title: Convert DWFX to PDF via .NET 
url: /net/conversion/dwfx-to-pdf/ 
description: Try our On-Premise APIs with your document on .NET Framework, .NET Core, and PHP, VBScript, Delphi, C++ via COM Interop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert DWFX to PDF via C#" h2="Instantly convert DWFX to PDF without needing AutoCAD® or any other rendering software." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cad/aspose_cad-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="Aspose.CAD" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="CAD" fileiconsmall4="XML" fileiconsmall5="DWFX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.CAD " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cad/aspose_cad-for-net.svg" apiHomeLink="https://products.aspose.app/cad/family" codeSamplesLink="https://github.com/aspose-cad" liveDemosLink="https://products.aspose.app/cad/family" docsLink="https://docs.aspose.com/cad/net" installationsDocsLink="https://docs.aspose.com/cad/net" nugetLink="https://www.nuget.org/packages/aspose.cad" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cad/net" learnAsLink="https://docs.aspose.com/cad/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Convert DWFX to PDF Using C#" %}}

In order to convert DWFX to PDF, we’ll use <a href="https://products.aspose.com/cad/net">Aspose.CAD for .NET</a> API which is a feature-rich, powerful and easy to use document manipulation and conversion API for C# platform. Open <a href="https://www.nuget.org/packages/aspose.cad">NuGet</a> package manager, search for <b>Aspose.CAD</b> and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Aspose.CAD" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.CAD

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Convert DWFX to PDF via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.CAD makes it easy for the developers to load & convert DWFX files to PDF in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

1. Load DWFX file with Image.Load method
1. Set an object of CadRasterizationOptions with page height & width
1. Create an instance of PdfOptions class and set its VectorRasterizationOptions property
1. Call Image.Save method while passing the resultant file path & object of PdfOptions


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.CAD for .NET is supported on all major operating systems. Just make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, .NET Core, and PHP, VBScript, Delphi, C++ via COM Interop.
-  Development environment like Microsoft Visual Studio.
-  Aspose.CAD for .NET DLL referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="" %}}

```cs
// load DWFX in an instance of Image via its Load method
using (var image = Aspose.CAD.Image.Load("template.dwfx"))
{
    // create an instance of CadRasterizationOptions and set page height & width
    var rasterizationOptions = new Aspose.CAD.ImageOptions.CadRasterizationOptions()
    {
        PageWidth = 1600,
        PageHeight = 1600
    };

    // create an instance of PdfOptions
    var options = new Aspose.CAD.ImageOptions.PdfOptions();

    // set the VectorRasterizationOptions property as CadRasterizationOptions
    options.VectorRasterizationOptions = rasterizationOptions;

    // export DWFX to PDF
    image.Save("output.pdf", options);
} 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Free App to Convert DWFX to PDF" sectionDescription="Check our live demos for [DWFX to PDF conversion](https://products.aspose.app/cad/conversion/dwfx-to-pdf) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DWFX file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PDF file." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

A standalone CAD File Processing Library with the ability to convert DWG, DWF and DXF files to high-quality PDF and raster images. Developers can select and convert specific layouts and layers from AutoCAD files as well as track the file conversion process with ease.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DWFX" readMoreLink="https://docs.fileformat.com/cad/dwfx/" >}}
A DWFx (Design Web Format XPS) is a a formatted representation of 2D/3D drawing as XPS document. It contains graphics and text as part of design data. It is the newest version of DWF file format and can be viewed and printed with the Microsoft XPS Viewer. The XPS nature of these files lets you share the design data with reviewers without requiring them to install Autodesk Design Review. Similar to DWF, DWFx is developed by Autodesk in compressed format to make transmission over the internet suitable. A single DWFx file can contain one or multiple drawings and sheet sets.

        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="pdf" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
Portable Document Format (PDF) is a type of document created by Adobe back in 1990s. The purpose of this file format was to introduce a standard for representation of documents and other reference material in a format that is independent of application software, hardware as well as Operating System. PDF files can be opened in Adobe Acrobat Reader/Writer as well in most modern browsers like Chrome, Safari, Firefox via extensions/plug-ins. Most of the commercially available software suites also offer conversion of their documents to PDF file format without the requirement of any additional software component. Thus, PDF file format has full capability to contain information like text, images, hyperlinks, form-fields, rich media, digital signatures, attachments, metadata, Geospatial features and 3D objects in it that can become as part of source document.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}