*This template is under development and ready for people to test it out. 
Exciting! If you'd like help test it, please let me know 
(phoebe.woodworth-jefcoats@noaa.gov).*

# PIFSC Tech Memo Template
This repository is designed to allow you to prepare a PIFSC Tech Memo
in R. It does this by rendering the report as a Quarto book. The
rendered report will still need some additional formatting, so only a
Word document is rendered (no pdf or HTML documents).

## Getting started
You can use this template to create your own repository for your tech memo. 
To do this, click on the green button in the upper left that says "Use this
template": ![](ExampleContent/UseThisTemplate.png)
\
Follow the steps to create a new repository with whatever name makes sense to 
you.  You can learn about this in GitHub's [guide](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) 
to creating a repository from a template.  

Once you've created the new, independent repository, you can do whatever you'd like
with it and it will not mess up this template.  To use the new repo in RStudio,
you'll start online in your newly created repo.  Click the green button that says, 
"< > Code": ![](ExampleContent/CodeButton.png)
\
Copy the URL that from the box that opens. Then, go to RStudio and create a new 
project, with version control, using Git and paste the URL for your repo as the
repository URL.  You can learn more about this in Jenny 
Bryan's [guide](https://happygitwithr.com/existing-github-first) to creating an
R project from a GitHub repo.  

That's it.  You are good to go!

*One exception to these instructions is if you'd like to contribute to this 
template.  Then, you should fork the repo so that you can submit pull requests.
If I lost you with that last sentence, fear not.  You can also contribute to 
the template by opening issues or via email (see below)*

## What's in the repository?
This repository contains a few categories of files.

#### Files you should edit
For the most part, all the files you need to work with end in `.qmd`.
Their file names match what they are with the exception of `index.qmd`.
Quarto requires a book to have a file by this name. Here, it's used to
generate the front matter of the tech memo. There are some fields
you'll need to edit. Follow the instructions in the file. Ask questions
as they arise—you are almost certainly not the only one with your
question, so asking it will help others, too.

Every file that ends with `.qmd` will appear in your tech memo unless
you take steps to prevent this. First, follow the instructions in each
document. After that, update the chapters listed in `_quarto.yml` to include only
the files you want to use and in the order you want to use them. Again,
please reach out with questions.

#### Files you should NOT edit
There are a few files you should not edit. These include the graphic for
the DoC seal, the Citation Style Language (csl) file, and the template
Word doc.

#### Files you'll end up ignoring
The files in `ExampleContent` are used in the Quarto template examples
and by this ReadMe. Once you're working with your actual tech memo,
you can safely delete them from your computer if you want.

## Rendering the tech memo
You can render the tech memo from any `.qmd` file that's used in the
memo. The rendered memo will be in a folder named `_book`. Quarto will create 
this in your R project the first time you render the book, and subsequent 
renderings will overwrite the existing version.

When you open the document in Word, you'll be confronted with two
dialogue boxes:  
The first asks if you want to update fields in the document.  Click "Yes".  
![](ExampleContent/UpdateFields.png)
\
The second asks how you want to update the Table of Contents.  Select "Update 
entire table" and click "OK".  I'm not sure it really matters which you select, 
though.  
![](ExampleContent/UpdateTOC.png)


There are instructions in the rendered document (also in `index.qmd`) to guide
you through some formatting you'll need to do in Word.  While this template does
let you work collaboratively with your coauthors, it doesn't handle all the detailed
formatting as well as I'd like.  If you know how to improve any of these steps, 
please let me know, submit a pull request with the proposed changes, or open an 
issue.

Finally, you'll need to add the cover page manually.  Our editor extraordinaire
can help you with this.

## Questions? Comments? Corrections?

Please open an issue or email Phoebe.Woodworth-Jefcoats\@noaa.gov

------------------------------------------------------------------------

### Disclaimer

This repository is a scientific product and is not official
communication of the National Oceanic and Atmospheric Administration, or
the United States Department of Commerce. All NOAA GitHub project code
is provided on an ‘as is’ basis and the user assumes responsibility for
its use. Any claims against the Department of Commerce or Department of
Commerce bureaus stemming from the use of this GitHub project will be
governed by all applicable Federal law. Any reference to specific
commercial products, processes, or services by service mark, trademark,
manufacturer, or otherwise, does not constitute or imply their
endorsement, recommendation or favoring by the Department of Commerce.
The Department of Commerce seal and logo, or the seal and logo of a DOC
bureau, shall not be used in any manner to imply endorsement of any
commercial product or activity by DOC or the United States Government.

### License

This repository uses the Creative Commons Zero v1.0 Universal (CC0 1.0
Universal) license.\
Additionally, Software code created by U.S. Government employees is not
subject to copyright in the United States (17 U.S.C. §105). The United
States/Department of Commerce reserves all rights to seek and obtain
copyright protection in countries other than the United States for
Software authored in its entirety by the Department of Commerce. To this
end, the Department of Commerce hereby grants to Recipient a
royalty-free, nonexclusive license to use, copy, and create derivative
works of the Software outside of the United States. See LICENSE for
further details.
