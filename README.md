# userinfo
This is a sample project. Its content does not reflect the actual file structure.

### General documentation guidelines
1.	In the docu/files directory, create a tutorial file. Files displayed in the left menu in the Dev Portal are ordered by the file name. To obtain the desirable order, use the following naming convention:
  - *10_first_filename.html*
  - *20_another_file.html*
2.	Add content in your file and save your changes.
3.	Commit and push the file to the repository.

#### Content
The content is usually written in the HTML syntax. In addition, the Dev Portal embedded plugin enables composition in Markdown (MD), and even a mix between the two. The composition choice is usually a personal preference.

However, there are some known advantages to using HTML:
*	It is easier because it is more commonly known, for example, when attaching images.
*	Not all MD code is read correctly, for example, HTML is needed for images, not MD.

You can also verify the syntax from one of these sources:
*	HTML: http://www.w3schools.com/html/default.asp
*	Markdown: http://daringfireball.net/projects/markdown/syntax

#### Images
You need to have special permissions if you want to add image files in this repository. Send and email with your github username to piotr.oszenda@sap.com and request access to this repository. Put image files in this directory:
 * docu/files/img

The following are code examples for images:

||HTML|MD|
|--------|--------|--------|
|image | `<img src=/"img/img.png">`   |`![Alt text](img/img.png)`   |
|image (width):    | `<img style="width:75%;" src="img/img.png">`      |not supported     ||

### Tutorial guidelines

The tutorials are targeted at developers with different amount of experience with YaaS. For that reason, structure the tutorials so that a beginner can follow the most basic steps, and more experienced developers can learn more fine-grained details, such as troubleshooting or more use cases.

This shows a template for the Tutorial document:

`---` <br />
`title: 'Your tutorial title'`<br />
`type: 'Tutorial'`<br />
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
