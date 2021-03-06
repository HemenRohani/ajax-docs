---
title: Telerik.Web.UI.ExportInfrastructure.Image
page_title: Telerik.Web.UI.ExportInfrastructure.Image
description: Telerik.Web.UI.ExportInfrastructure.Image
---

# Telerik.Web.UI.ExportInfrastructure.Image

EI Image object

## Inheritance Hierarchy

* System.Object
* Telerik.Web.UI.ExportInfrastructure.Image

## Properties

###  Width `Int32`

Internal pixel width

###  Height `Int32`

Internal pixel height

###  ImageData `Byte[]`

Byte array containing the image data. This property has higher priority compared to ImageUrl.

###  ImageUrl `String`

Image URL string

###  ImageRange `Range`

Image range. This property has lower priority compared to ImageData.

###  AutoSize `Boolean`

Boolean property. Will resize the image automatically if set to true. False by default.

## Methods

###  GetImage

Generate a System.Drawing.Image object from the current EI Image object

#### Returns

`System.Drawing.Image` System.Drawing.Image object

###  GetImageFromByteArray

Generate an Image object from byte array

#### Returns

`System.Drawing.Image` System.Drawing.Image object

###  GetImageFromByteArray

Generate an Image object from byte array

#### Returns

`System.Drawing.Image` System.Drawing.Image object

###  GetImageFromUrl

Generate an Image object from URL

#### Returns

`System.Drawing.Image` System.Drawing.Image object

