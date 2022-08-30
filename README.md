# Beamer Template for Rockefeller College affiliates
This provides a template and example set of slides for Rockefeller College faculty and students who prefer to use Beamer for presentations. The advantage of writing in R Markdown is you can call LaTeX to create the slides (allowing for the use of LaTeX commands, packages and code) while also using the simplified Markdown code for most other things (sections, defining slides with simple headers, using dashes to create bulleted lists, etc.)

R Markdown also provides integration with your Zotero library for adding citations to a slide and automatically creating a set of references slides at the end of the presentation (see example slides for the setup).

This template provides the basic code you need to replicate the look of the slides (UAlbany colors with a Rockefeller College logo on the title slide). Everything in the front matter (everything between the three dashes in line 1 and line 31) sets the template. Simply edit the author, title, subtitle, and date information accordingly.

Software needed:
- LaTeX (MikTeX for Windows)
- R Studio
- Pandoc
- R

To use:
1. Save the .Rmd file and logo in the location you would like to be saving your slides.
2. Use the template to get a sense for how slides are defined and replace the content with your own.
3. Save the edited document. 

NOTE: if you plan on using the citation function, save the document in your folder first, then in Visual mode, add citations. Once the .Rmd is saved, R Studio will create a references.bib bibtex file in the same directory when you add your first citation. Every citation added from there will automatically be imported into the references.bib file in the project folder. The template here includes some citations to demonstrate how they look, but when doing your own work from scratch, this order of operations for citations is important because R Studio has to create the references.bib file for your project and import the citation information for each citation before it can actually add the citations in the document. Let my trial and error figure this bit out be your guide.

