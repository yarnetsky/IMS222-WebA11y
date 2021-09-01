---
description: Headings give our content structure and a hierarchy.
---

# Better Headings

## Screen reader interaction

{% hint style="info" %}
* A person using a screen reader can quickly skim our page contents by listening to the page headings. 
* They can also jump to those points on the page. 
* Screen readers read a page in a linear fashion so we cannot rely entirely on visual organization. For example, a three-column layout is read as a single column starting with the first column.
{% endhint %}

## Solution: Headings give your content logical hierarchy.

Use headings to outline your content— not unlike a bulleted page outline or table of contents. In your outline, keep headings in order and don't skip heading levels.

Best practice is to use Heading 1 `<h1>` for page titles and Heading 2 `<h2>` for page section titles. For the content within these sections, we use heading levels 3 to 6. 

Here's a sample outline that keeps headings in good order...

* **`<h1>` Page Title**
  * **`<h2>` Section Title**
    * **`<h3>`** Sub-section title
      * **`<h4>`** Next level heading within sub-section
      * **`<h4>`** Next level heading within sub-section
    * **`<h3>`** Sub-section title
  * **`<h2>` Section title**
    * **`<h3>`** Sub-section title
    * **`<h3>`** Sub-section title

### Additional best practices

* Don't use a font-size change alone to signify headings. Font size changes are missed by screen readers.
* Don't change a heading level simply to make your text larger or smaller. This can alter your page outline and make your content difficult to understand.
* You have a lot of control over a heading's appearing in your CSS.

## Testing

### Using Tota11y

* When you click the Tota11y icon and select the headings button, a window pops up explaining any errors. The most common errors are heading levels skipped and headings out of order. 
* This window also has a summary tab which shows the sequential and nesting order of your headings. It is easy to see where errors may occur and if your nesting order makes sense.
* On your page, you will also see small heading notations next to each header so you can see which elements on the page are headings.

### **Check your page on your cellphone**

Another way to visualize the organization of your page is to view it with a phone browser. Your content will become linear in much the same way it does on a screen reader. If the page does not make sense on a phone, a re-ordering of content will be needed.

