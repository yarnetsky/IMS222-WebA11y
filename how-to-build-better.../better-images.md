# Better Images

## The Interaction

{% hint style="info" %}
A person using a screen reader has no means of "seeing" an image. Instead, they will hear the alternative text \(or alt-text\) from the image tag read aloud when encountering an image on a webpage. Without alt-text, the images become invisible to the reader.
{% endhint %}

## Solution: Use Alternative Text to describe your images

Screen readers will read alt text in the place of the image to convey its intended meaning. The `alt` attribute would appear in an image tag like this...

**`<img src="/images/image-title.jpg" alt="description of image content">`**

### What should be included in the alt text?

* Ask yourself what information or site functionality you intend to convey with the image's use. This is also what you to convey with your alt text. 
* The wording could change depending on the image's context. For example, if a magnifying glass is being used as an icon for a search button, the intent is not "magnifying glass", but rather "search."
* Keep your alt-text brief. If brief is not possible, consider including more explanation in your text.
* You can skip using an introductory phrases such as "image of...." as the screen reader will announce it encountered an an image by default before it reads the alt text.

### When is alt text _not_ needed?

* If the image or graphic is purely decorative.
* If the alt text would be repetitive information.
  * For example, the alt text for a book cover might be its title. But if you've already given the title of the book, repeating it is not needed.

Even for decorative images we still need alt attribute , but it would be empty like this... **`<img src="images/decorative.jpg" alt="" />`**

## Testing

* Click "Image alt-text" in Tota11y.
* The error window will report if there are any images requiring alt text.
* Next to the error message you'll see a small magnifying glass. You can click this icon to see which image caused the error.
* Accessibility testing requires human verification. 
  * For example, an "empty" alt tag `alt=""` is used for decorative images. This often comes up as an error in accessibility tests. If the image is indeed decorative, don't worry about the error.

## Read more...

For best practices on creating alternative text, please consult the links below.

* [WebAIM Alternative Text Guide](http://webaim.org/techniques/alttext/)
* [Image ALT Tag Tips from Penn State](http://accessibility.psu.edu/images): Gives helpful examples of Alt Text descriptions for different situations.

