---
title: Convert IGEC to BMP via .NET 
url: /net/conversion/igec-to-bmp/ 
description: Try our On-Premise APIs with your document on .NET Framework, .NET Core, and PHP, VBScript, Delphi, C++ via COM Interop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert IGEC to BMP via C#" h2="Instantly convert IGEC to BMP without needing AutoCAD® or any other rendering software." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cad/aspose_cad-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="Aspose.CAD" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="CAD" fileiconsmall4="XML" fileiconsmall5="IGEC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.CAD " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cad/aspose_cad-for-net.svg" apiHomeLink="https://products.aspose.app/cad/family" codeSamplesLink="https://github.com/aspose-cad" liveDemosLink="https://products.aspose.app/cad/family" docsLink="https://docs.aspose.com/cad/net" installationsDocsLink="https://docs.aspose.com/cad/net" nugetLink="https://www.nuget.org/packages/aspose.cad" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cad/net" learnAsLink="https://docs.aspose.com/cad/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Convert IGEC to BMP Using C#" %}}

In order to convert IGEC to BMP, we’ll use <a href="https://products.aspose.com/cad/net">Aspose.CAD for .NET</a> API which is a feature-rich, powerful and easy to use document manipulation and conversion API for C# platform. Open <a href="https://www.nuget.org/packages/aspose.cad">NuGet</a> package manager, search for <b>Aspose.CAD</b> and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Aspose.CAD" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.CAD

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Convert IGEC to BMP via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.CAD makes it easy for the developers to load & convert IGEC files to BMP in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

1. Load IGEC file with Image.Load method
1. Set an object of CadRasterizationOptions with page height & width
1. Create an instance of BmpOptions class and set its VectorRasterizationOptions property
1. Call Image.Save method while passing the resultant file path & object of BmpOptions


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
// load IGEC in an instance of Image via its Load method
using (var image = Aspose.CAD.Image.Load("template.igec"))
{
    // create an instance of CadRasterizationOptions and set page height & width
    var rasterizationOptions = new Aspose.CAD.ImageOptions.CadRasterizationOptions()
    {
        PageWidth = 1600,
        PageHeight = 1600
    };

    // create an instance of BmpOptions
    var options = new Aspose.CAD.ImageOptions.BmpOptions();

    // set the VectorRasterizationOptions property as CadRasterizationOptions
    options.VectorRasterizationOptions = rasterizationOptions;

    // export IGEC to BMP
    image.Save("output.bmp", options);
} 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Free App to Convert IGEC to BMP" sectionDescription="Check our live demos for [IGEC to BMP conversion](https://products.aspose.app/cad/conversion/igec-to-bmp) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your IGEC file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant BMP file." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

A standalone CAD File Processing Library with the ability to convert DWG, DWF and DXF files to high-quality PDF and raster images. Developers can select and convert specific layouts and layers from AutoCAD files as well as track the file conversion process with ease.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="IGEC" readMoreLink="/{{igec_url}}" >}}
{{igec}}

        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="bmp" readMoreLink="https://docs.fileformat.com/image/bmp/" >}}
Files having extension .BMP represent Bitmap Image files that are used to store bitmap digital images. These images are independent of graphics adapter and are also called device independent bitmap (DIB) file format. This independency serves the purpose of opening the file on multiple platforms such as Microsoft Windows and Mac. The BMP file format can store data as two-dimensional digital images  in both monochrome as well as color format with various colour depths.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}