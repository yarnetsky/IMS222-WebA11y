# Better Hyperlinks

## The Interaction

{% hint style="info" %}
* When a screen reader encounters a link, it will be announced as a link followed by it's link text. "Link: Directions to Miami University"
* Listening to all the links on a page is another method used for skimming a webpage using a screen reader is to listen to all of the links on the page. Before reading the link text, the screen reader will state they've encountered a link.
{% endhint %}

## The Solution

* Link wording should clearly explain its destination and/or intent. Ambiguous phrasing can obscure a link's purpose.
* Read your links out of context to insure they will stand alone as a screen reader presents them in order.
* Avoid introductory phrases such as "click here" for a link. 
* Definitely do not use "click here" as a link on its own.
* Do not use raw web addresses in links as the screen reader will read it aloud the entire URL.

### Examples

* **Poor**: [Click here](https://miamioh.edu/about-miami/visiting-miami/directions/index.html) for directions.
* **Better**: [Directions to Miami University](https://miamioh.edu/about-miami/visiting-miami/directions/index.html) are available online.

  `<p><a href="https://miamioh.edu/about-miami/visiting-miami/directions/index.html">Directions to Miami University</a> are available online.</p>`

* **Poor**: Learn more about accessibility [here](http://webaim.org/standards/wcag/).
* _**Better:**_ Learn more about [accessibility standards from WebAIM](https://www.w3.org/WAI/intro/wcag).`<p>Learn more about <a href="https://www.w3.org/WAI/standards-guidelines/wcag/">accessibility standards from WebAIM</a>.</p>`

## Testing

* Tota11y's "Link Text" option will identify any link that appear unclear. 
  * On this page for instance it identified the poorly written link examples above.
* Tip: If the overlays hide the errors, click the annotate checkbox in the errors window. Without the annotations, you can hover over each error and it will be highlighted on the page. If the error is not visible, click the magnifying glass icon to zoom to the error.

