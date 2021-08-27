---
title: Convert CFF2 to JPEG via Java 
url: /java/conversion/cff2-to-jpeg/ 
description: Try our On-Premise APIs for your document conversion on Java Runtime Environment for JSP/JSF Application and Desktop Applications.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert CFF2 to JPEG via Java" h2="Native Java Library to Read, Write & Export CFF2 to JPEG without needing Adobe." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cad/aspose_cad-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="Aspose.CAD" subTitlepfName="for Java" downloadUrl="" fileiconsmall1="JPEG" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="CFF2" >}}

{{< blocks/products/pf/main-container pfName="Aspose.CAD " subTitlepfName="for Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/cad/aspose_cad-for-java.svg" apiHomeLink="https://products.aspose.app/cad/family" codeSamplesLink="https://github.com/aspose-cad" liveDemosLink="https://products.aspose.app/cad/family" docsLink="https://docs.aspose.com/cad/java" installationsDocsLink="https://docs.aspose.com/cad/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/cad/java" learnAsLink="https://docs.aspose.com/cad/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cad" >}}

{{% blocks/products/pf/agp/content h2="How to Convert CFF2 to JPEG Using Java" %}}

In order to render CFF2 to JPEG, we’ll use <a href="https://products.aspose.com/cad/java">Aspose.CAD for Java</a> API which is a feature-rich, powerful and easy to use conversion API for Java platform. You can download its latest version directly from <a href="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-cad">Maven</a> and install it within your Maven-based project by adding the following configurations to the pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependency" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-cad</artifactId>
<version>version of aspose-cad API</version>
<classifier>jdk17</classifier>
</dependency>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Convert CFF2 to JPEG via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.CAD API makes it easy for the developers to convert CFF2 file to JPEG in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

1. Load CFF2 file with Image.load method
1. Set an object of CadRasterizationOptions with page height & width
1. Create an instance of JpegOptions class and set its VectorRasterizationOptions property
1. Call Image.save method while passing the resultant file path & object of JpegOptions



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.CAD for Java supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Convert CFF2 to JPEG - Java‎" offSpacer="" %}}

```cs
// load CFF2 in an instance of Image via its Load method
Image image = Image.load("template.cff2");

// create an instance of CadRasterizationOptions and set page height & width
CadRasterizationOptions rasterizationOptions = new CadRasterizationOptions();
rasterizationOptions.setPageWidth(1600);
rasterizationOptions.setPageHeight(1600);

// create an instance of JpegOptions
TiffOptions options = new TiffOptions();

// set the VectorRasterizationOptions property as CadRasterizationOptions
options.setVectorRasterizationOptions(rasterizationOptions);

// export CFF2 to JPEG
image.save("output.jpeg", options);   
  
  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="CFF2 to JPEG Conversion Live Demos" sectionDescription="[Convert CFF2 to JPEG](https://products.aspose.app/cad/conversion/cff2-to-jpeg) right now by visiting our Live Demos website.The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your CFF2 file, it will be converted instantly to JPEG." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.CAD is an AutoCAD conversion API. One can easily convert DWG, DWF, DGN and DXF documents to PDF, TIFF, JPEG, PNG and other image formats. Moreover, API provides conversion facility of specific layouts and layers from the AutoCAD documents. Its a standalone API and does not require AutoCAD or any other software installation. ‎ ‎



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="CFF2" readMoreLink="/{{cff2_url}}" >}}
{{cff2}}

        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="JPEG" readMoreLink="https://docs.fileformat.com/image/jpeg/" >}}
A JPEG is a type of image format that is saved using the method of lossy compression. The output image, as result of compression, is a trade-off between storage size and image quality. Users can adjust the compression level to achieve the desired quality level while at the same time reduce the storage size. Image quality is negligibly affected if 10:1 compression is applied to the image.  The higher the compression value, the higher the degradation in image quality. JPEG image file format was standardized by the Joint Photographic Experts Group and, hence, the name JPEG. The format has been the choice of storing and transmitting photographic images on the web. Almost all Operating systems now have viewers that support visualization of JPEG images, which are often stored with JPG extension as well. Even the web browsers support visualization of JPEG images.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}