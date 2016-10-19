# userinfo
This is a sample project. Its content does not reflect the actual file structure.

### General documentation guidelines
1.	In the docu/files directory, create a tutorial file. Files displayed in the left menu in the Dev Portal are ordered by the file name. To obtain the desirable order, use the following naming convention:
- *10_first_filename.html*
- *20_another_file.html*
2.	Add content in your file and save your changes.
3.	Commit and push the file to the repository.

#### Metadata
The metadata is required in order for the document to display properly on the Dev Portal. The metadata varies, depending upon the document type. It is very important to have the exact format, as shown in the template (see below).

#### Content
The content is usually written in the HTML syntax. In addition, the Dev Portal embedded plugin enables composition in Markdown (MD), and even a mix between the two. The composition choice is usually a personal preference.

However, there are some known advantages to using HTML:
*	It is easier because it is more commonly known, for example, when attaching images.
*	Not all MD code is read correctly, for example, HTML is needed for images, not MD.

You can also verify the syntax from one of these sources:
*	HTML: http://www.w3schools.com/html/default.asp
*	Markdown: http://daringfireball.net/projects/markdown/syntax

#### Images
Put image files in this directory:
 * docu/files/img

The Graphic Standards agreed upon by Information Developers are the following:
*	Make or capture your images using any number of tools that output images of high quality. The desired image format is SVG (vector), but PNG and JPG (raster) are acceptable.
*	Use an online tool, such as TinyPNG, to compress images and limit the size of each image to 1MB, or smaller.
*	By default, images are sized automatically. If you want to control the size of the image relative to the screen size, use one of these standard percentages: 100%, 75%, 50%, or 25%.
*	Most images are left-aligned, unless it is a special case, such as wireframe images in a table.
*	Do not include the mouse pointer in your screenshots, unless it is showing a function related to the content.
*	To highlight certain areas of an image, crop the image to show the desired area, or use red arrows or boxes with 5-point line width.
*	Most images do not need borders, unless there is a specific reason to add them.
*	The padding around the image is controlled by the style sheet, or when you create the screenshot, such as how much of the background you capture with the frame grab itself.

The following are code examples for images:

||HTML|MD|
|--------|--------|--------|
|image | `<img src=/"img/img.png">`   |`![Alt text](img/img.png)`   |
|image (width):    | `<img style="width:200px;" src="img/img.png">`      |not supported     ||

### Tutorial guidelines

The tutorials are targeted at developers with different amount of experience with YaaS. For that reason, structure the tutorials so that a beginner can follow the most basic steps, and more experienced developers can learn more fine-grained details, such as troubleshooting or more use cases.

This shows a template for the Tutorial document:

`---` <br />
`title: 'Your tutorial title'`<br />
`type: Tutorial`<br />
`--- ` <br />
`Content of your tutorial.`

To fill out the metadata above:
* *title: Title of your tutorial.*
* *type: The value must be “Tutorial”*.

Include the following in the content of your tutorial:
* Title – Give the tutorial a descriptive title, without the words, "How To".
* Introduction – Create an introduction to explain the purpose and flow of each tutorial, or create one document to introduce all of the tutorials as a whole. State the objective of the tutorials, and any important introductory details or prerequisites.
* Step-by-Step – Create detailed interactive steps.
* Optional Troubleshooting - Give tips on how to troubleshoot the problem after receiving an error.
* Optional Use Cases – Show more than one use case to highlight different features.
