# DiagramControl - How to create custom shapes with connection points


The Diagram control supports a special language for defining shapes. The main element that contains shape description is <em>ShapeTemplate</em>. This element describes a shape contour and may contain several segments

* <em>Start</em>. Specifies the start point
* <em>Line</em>. Defines a line with start and end points
* <em>Arc</em>. Defines an arc with start and end points<br><br>To specify connection points, use the <em>ShapeTemplate.ConnectionPoints</em> property.<br>Shapes may contain parameters. Parameters may be used to dynamically calculate an end point, row height, and other properties. To specify parameters, use the <em>ShapeTemplate.Parameters</em> property.<br>To register custom shapes, create a stencil with the <em>DiagramStencil.Create</em> method and pass it to the <em>DiagramToolboxRegistrator.RegisterStencil</em> method.<br><br><br><strong>Note:</strong> <em>Starting with version 16.1, it is recommended to use XML to describe custom shapes. If you prefer to use XAML instead, take a look at the following example: <a href="https://www.devexpress.com/Support/Center/p/T381372">T381372 - DiagramControl - How to create custom shapes with connection points using XAML markup</a>.</em>

<br/>


