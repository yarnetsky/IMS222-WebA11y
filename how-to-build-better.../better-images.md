# Better Images

## The Interaction

{% hint style="info" %}
A person using a screen reader has no means of _seeing_ an image. Rather, they hear a reading of the alt text \(alternative text\) embedded in our image tag. Without alt text, the image become invisible to the reader.
{% endhint %}

## Solution: Use Alt Text to describe your images

Screen readers will read alt text in the place of the image to convey its intended meaning. The `alt=""` attribute would appear in an image tag like this...

**`<img src="/images/image-title.jpg" alt="description of image content">`**

### What should you include in alt text?

* Ask yourself what information or site functionality you intend to convey with the image's use. This is also what you to convey with your alt text. 
* The wording could change depending on the image's context. For example, if a magnifying glass is being used as an icon for a search button, the intent is not "magnifying glass", but rather "search."
* Keep your alt text brief. If brief is not possible, consider including more explanation in your text.
* You can skip using an introductory phrases such as "image of...." as the screen reader will announce it encountered an an image by default before it reads the alt text.

### When is alt text _not_ needed?

* If the image or graphic is purely decorative.
* If the alt text would be repetitive information.
  * For example, the alt text for a book cover might be its title. But if you've already given the title of the book, repeating it is not needed.

However, even for decorative images we still need alt attribute, but it would be empty like this... **`<img src="images/decorative.jpg" alt="" />`**

## Testing

* Click "Image alt-text" in Tota11y.
* The error window will report if there are any images missing alt text.
* Click the magnifying glass next to the error to see which image caused the error.
* Accessibility testing requires human verification. 
  * For example, an empty alt attribute used for decorative images can come up as an error in accessibility tests. If the image is indeed decorative, don't worry about the error.

## Read more...

For best practices on creating alternative text, please consult the links below.

* [WebAIM Alternative Text Guide](http://webaim.org/techniques/alttext/)
* [Image ALT Text Tips from Penn State](http://accessibility.psu.edu/images): Gives helpful examples of Alt Text descriptions for different situations.

