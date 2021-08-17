---
description: Headings give our content structure and a hierarchy.
---

# Better Headings

## Screen reader interaction

{% hint style="info" %}
* A person using a screen reader can quickly skim the contents of our page by listening to the page headings. 
* They can also jump to those points on the page. 
* Your page will be described in a linear fashion so we cannot rely entirely on visual organization. Thus, even a three-column page is heard as a single column starting with the first column.
{% endhint %}

## Solution: Headings give your content logical hierarchy.

Use headings to outline your content— not unlike a bulleted page outline or table of contents. Use the headings in order and don't skip headings.

Best practice is to use Heading 1 `<h1>` for page titles and Heading 2 `<h2>` for page section titles. For the content within these sections, we use headings 3 to 6. Here's an example of how to keep headings in good order.

* **`<h1>` Page Title**
  * **`<h2>` Section Title**
    * **`<h3>`** sub-section title
      * **`<h4>`** next level heading within sub-section
      * **`<h4>`** next level heading within sub-section
    * **`<h3>`** Sub-section title
  * **`<h2>` Section Title**
    * **`<h3>`** Sub-section title
    * **`<h3>`** Sub-section title

### Additional best practices

* Don't use a font-size change alone to signify headings. Font size changes are missed by screen readers.
* Don't change the heading level simply to make your text larger or smaller. This can alter your page outline and make it difficult to understand.
* If you need to change a heading's font size, do so in your CSS.

## Testing

### Using Tota11y

* When you click the Tota11y icon and select the headings button, a window will pop up explaining any errors. The most common errors are headings skipped and headings out of order. 
* This window also has a summary tab which shows the sequential and nesting order of your headings. It is easy to see where errors may occur and if your nesting order makes sense.
* On your page, you will also see small heading notations next to each header so you can see which elements on the page are headings.

### **Check your page on your cellphone**

Another way to visualize the organization of your page is to view it with a phone browser. Your content will become linear in much the same way it does on a screen reader. If the page does not make sense on a phone, a re-ordering of content will be needed.

