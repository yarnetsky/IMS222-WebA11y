# Better Images

## The Interaction

{% hint style="info" %}
A person using a screen reader has no means of _seeing_ an image. Rather, they hear a reading of the alt text \(alternative text\) embedded in our image tag. Without alt text, the image become invisible to the reader.
{% endhint %}

## Solution: Use Alt Text to describe your images

Alt text comes from the `alt=""` attribute embedded in your image tag like this...

`<img src="/images/image-title.jpg"` **`alt="description of image content goes here"`**`>`

### What to include in your alt text

* Ask what information or site functionality you intend to convey with the image. This same intent must also be conveyed with your alt text.
* Keep your alt text brief. If that's not possible, consider including more explanation in your text.
* Skip introductory phrases such as "image of...." because the screen reader will automatically announce the element an an image/graphic by default before it reads the alt text.
* Note: Alt text wording could change depending on the image's context. For example, if a magnifying glass icon is being used to signify a search button, the intent is not "magnifying glass", but rather "search."

### When is alt text _not_ needed?

* If the image or graphic is purely decorative.
* If the alt text would be repetitive information.
  * For example, the alt text for a book cover might be its title. But if you've already given the title of the book, repeating it is not needed.

However, even for decorative images we still need alt attribute, but it would be empty like this... `<img src="images/decorative.jpg"` **`alt=""`** `/>`

## Testing

* Click "Image alt-text" in Tota11y.
* The error window will report if there are any images missing alt text.
* Click the magnifying glass icon next to the error listing to see which image caused the error.
* Accessibility testing often requires human verification. 
  * For example, an empty alt attribute used for decorative images can come up as an error in accessibility tests. If the image is indeed decorative, don't worry about the error.

## Read more...

For best practices on creating alternative text, please consult the links below.

* [WebAIM Alternative Text Guide](http://webaim.org/techniques/alttext/)
* [Image ALT Text Tips from Penn State](http://accessibility.psu.edu/images): Gives helpful examples of Alt Text descriptions for different situations.

