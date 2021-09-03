# Better Hyperlinks

## Interactions

{% hint style="info" %}
* When a screen reader encounters a link, it will be announced as a "link" followed by the link's text. For example... "Link: Directions to Miami University"
* Listening to all the links on a page is another method people using a screen reader for quickly skimming the content of a webpage.
* As such, links are often heard outside of their context.
{% endhint %}

## Solutions

* Link wording should clearly and concisely explain the link's destination and/or its intent.
* Avoid using introductory phrases, such as "click here," in a link. 
* Never use "click here" as a link on its own.
* Avoid using long, raw web addresses in links. Screen readers will try to read the entire url aloud, which can sound both awful and confusing. However, short primary urls like [miamioh.edu](https://miamioh.edu) are fine.

### Examples

* **Poor**: [Click here](https://miamioh.edu/about-miami/visiting-miami/directions/index.html) for directions to Miami University.
* **Better**: [Directions to Miami University](https://miamioh.edu/about-miami/visiting-miami/directions/index.html) are available online.

  `<p><a href="https://miamioh.edu/about-miami/visiting-miami/directions/index.html">Directions to Miami University</a> are available online.</p>`

* **Poor**: Learn more about accessibility [here](http://webaim.org/standards/wcag/).
* _**Better:**_ Learn more about [accessibility standards from WebAIM](https://www.w3.org/WAI/intro/wcag).`<p>Learn more about <a href="https://www.w3.org/WAI/standards-guidelines/wcag/">accessibility standards from WebAIM</a>.</p>`

## Testing

* Read your links out of context to insure they will make sense when they stand alone as read by a screen reader.
* Tota11y's "Link Text" option will try to identify any links that appear unclear. 
  * On this page for instance it identified the poorly written link examples above.

