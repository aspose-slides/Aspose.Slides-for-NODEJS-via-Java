# Node.js Library for PowerPoint File Formats

Aspose.Slides for Node.js via Java is a PowerPoint API for presentations manipulation and management. It allows developers to read, write, convert and manipulate PowerPoint presentations using Node.js. All document elements such as slides, tables, text, charts, shapes, images and SmartArt diagrams are accessible for manipulation, supports exporting presentations to PDF, PDF/A, HTML, XPS and image formats. The PowerPoint API includes many extended PPT and PPTX features as: merge, clone, split, compare presentations.

## Node.js PowerPoint Library Features

- Create or clone existing slides from templates.
- Save & open files to & from streams.
- Generate presentations from database.
- Create shapes and add text to shapes on slides.
- Work with PowerPoint tables.
- Handle text & shape formatting.
- Remove or apply the protection on shapes.
- Embed Excel charts as OLE objects in slides.
- Work with ActiveX component.

## Read & Write PowerPoint Files
**Microsoft PowerPoint:** PPT, PPTX, PPS, POT, PPSX, PPTM, PPSM, POTX, POTM
**OpenOffice:** ODP, ODS
**Text:** CSV, Tab-Delimited, TXT, JSON
**Web:** HTML, MHTML

## Save PowerPoint Files As 
**Fixed Layout:** PDF, XPS
**Images:** JPEG, PNG, BMP, SVG, TIFF, GIF, EMF
**Text:** CSV, Tab-Delimited, JSON, SQL, XML
**Web:** HTML

## Getting Started with Aspose.Slides for Node.js via Java

Aspose.Slides for Node.js via Java consists of 2 individual parts, the javascript wrapper (aspose.slides.js) and Aspose.Slides for Node.js via Java (aspose-slides-xx.x-nodejs.jar). These components communicate via https://www.npmjs.com/package/java whereas both require separate environments & processes for execution.

### Prerequisites
1. JDK8 or newer.
2. https://www.npmjs.com/package/java
3. Node.js

### Installation

From the command line:
```npm
npm install aspose.slides.via.java
```

Please use the following [article](https://docs.aspose.com/slides/nodejs-java/troubleshooting-installation/) if you encounter compilation errors during installation of Aspose.Slides for Node.js via Java.

### Convert Presentation to Multiple Formats using Node.js

```javascript
var aspose = aspose || {};

aspose.slides = require("aspose.slides");

var pres = new aspose.slides.Presentation();
var slide = pres.getSlides().get_Item(0);
slide.getShapes().addAutoShape(aspose.slides.ShapeType.Line, 50, 150, 300, 0);
pres.save("template.pptx", aspose.slides.SaveFormat.Pptx);
```

### Convert Presentation to PDF using Node.js

```javascript
var aspose = aspose || {};

aspose.slides = require("aspose.slides");

var pres = new aspose.slides.Presentation("template.pptx");
pres.save("output.pdf", aspose.slides.SaveFormat.Pdf);
```

[Product Page](https://products.aspose.com/slides/nodejs-java/) | [Documentation](https://docs.aspose.com/slides/nodejs-java/) | [API Reference](https://reference.aspose.com/slides/nodejs-java/) | [Code Examples](https://github.com/aspose-slides/Aspose.Slides-for-Java) | [Blog](https://blog.aspose.com/category/slides/) | [Free Support](https://forum.aspose.com/c/slides) | [Temporary License](https://purchase.aspose.com/temporary-license/)
