## Reduce HTML errors in Publisher

In Publisher all of your templates are written in HTML and sometimes errors 
may occur. Having lots of HTML errors in your template and document may affect your
deliverability. It is advised to reduce errors as much as possible.

To see if your template and/or document has any HTML errors, click on
the warnings button in the lower toolbar of the screen.

This check provides some information on the found error and how you
could solve it.

Some HTML errors may only come up when the document is
**personalized**. Set the preview version to personalized in the lower left
corner to validate the personalized document using the [test destination](./what-is-the-test-destination.md).

![](../images/htmlerrors.png)

Common HTML errors are
----------------------

**Warning: <img\> lacks "alt" attribute**
The image has no alt attribute. You should solve this, because not
everyone is able to see your images. The alt attribute provides an
alternative description for when the image is not loaded.

`<img src="car.png"  alt="Picture of a car" />`

**Warning: <*table*\> lacks "summary" attribute**
You can remove this warning by adding summary="" attribute to table
tags in your template and document.

**Warning: trimming empty <*span*\>**
Most HTML tags have opening and closing tags. If you see this warning,
the closing tag is missing.

`<span>Content goes here</span>   Some HTML tags are self closed: <br  />`

**Warning: discarding unexpected </td\>**
Most HTML tags have opening and closing tags. If you see this warning,
the opening tag is missing.

`<td>This is a table cell</td>`**
 
**Error: <dfgsdfg\> is not recognized!**
 The tag does not exist. Check for misspellings.
 
**Warning: missing <!DOCTYPE\> declaration**
The HTML doctype is missing in the template. You may ignore this
warning.

**Warning: <html element\> proprietary attribute "*attribute name*"**
The HTML element has an non-existing attribute. Remove the attribute or
check for spelling errors.

## More information

* [Templates in Publisher](./templates-and-documents)
