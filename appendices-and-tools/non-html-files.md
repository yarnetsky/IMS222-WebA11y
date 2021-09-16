# Better \(non-HTML\) Files

The concepts from web documents can also apply to other documents. However, the implementation may differ. Here are links for tips on making additional file types accessible

* [PDF files](http://webaim.org/techniques/acrobat/)
* [Microsoft Word](http://webaim.org/techniques/word/) documents
* [PowerPoint](http://webaim.org/techniques/powerpoint/) presentations
* [Adobe Flash](http://webaim.org/techniques/flash/) content.

Recommendations for most of these formats echo those for webpages such as using headings to convey logical flow for a Word document and PDFs.

If you're using an application that creates HTML for you, be very careful on how you paste content into the application

## The hidden problem with copy/paste

When copying and pasting from another source, such as Word, hidden style code can be copied along with the content. These hidden styles can break an otherwise accessible document.

### Solution: How to avoid these hidden styles

#### Many rich text editors have these useful tools: ![Rich text editor toolbar screenshot of buttons used for removing hidden text formatting](http://s3.amazonaws.com/libapps/accounts/3908/images/lg-richtexteditor-toolbar.png)

* ![Button to use for removing hidden styles from copied text.](http://s3.amazonaws.com/libapps/accounts/3908/images/lg-pasteplainbutton.png) The "clipboard-T" \(Paste as Plain Text\) button will show a paste box that strips out all text formatting and leave behind plain text. Best for simple text.
* ![Button to use for leaving the original formatting as in the Word document.](http://s3.amazonaws.com/libapps/accounts/3908/images/lg-pastewordbutton.png) The "clipboard-W" \(Paste from Word\) button will show a paste box that keeps the formatting structure from the source, but strips out extra styling. 
* ![Button to use for removing all formatting from selected text in the rich text editor.](http://s3.amazonaws.com/libapps/accounts/3908/images/lg-clearformattingbutton.png) This button will remove all formatting from selected text inside the rich text editor. This will generally solve strange formatting issues you may find from copied text. This button will also remove hard-coded widths from tables that may overflow your guide.

**Extra tip**: You can also use the "Paste from Word" button with data from Excel.  
When you paste in a series of cells, the resulting paste will be a simple and clean HTML table in your guide!

**Source**: [Boston College LibGuides Accessibility Guide](http://libguides.bc.edu/guidestandards/accessibility)

