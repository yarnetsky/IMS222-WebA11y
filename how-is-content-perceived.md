# How is content perceived with assistive technologies?

Universal access to our web content relies on several components working together...

* **Content**: It all starts with our content— from text to images and multimedia.
* **Authoring tools:** These are tools we use to create web content. This could be anything from our code editor to a web content manager such as WordPress. It's also the content we embed in our websites from sources such as Instagram, YouTube, or Twitter.
* **User agents:** Finally, user agents are the hardware-software people use to access our content. This could be any device including a desktop or mobile web browsers, ebook readers, multimedia players, browser plug-ins, and assistive technologies such as screen readers that read aloud web pages. 

If **any** of these fail, your reader can miss the intended meaning of your content. Your reader loses and so do you because the failure prevents your ability to communicate.

Let's look at user agents. While there are many types of assistive technology, we will focus on screen readers which communicate the structure and content of web pages via simulated speech or a Braille readout. Many of the best practices that will allow your content to be understood via a screen reader will also help with other assistive technologies.

[Additional types of assistive technologies include](https://webaccess.berkeley.edu/resources/assistive-technology)...

* Screen magnifiers which can dramatically enlarge text and graphics on the screen.
* Text readers that focus on reading specified chunks of text.
* Speech input software to help people who would have difficulties with typing.
* Alternative input devices for folks who might not have the dexterity/ability to use a mouse or keyboard. Examples include eye tracking, head pointers, cursor controlled-on screen keyboards.

## Try this experiment

Look at the [_New York Times_ website](https://www.nytimes.com) and think aloud about what you are looking at as you go through the homepage.

What are you reading to understand the page? Are you reading every word on the page? Are you skimming the headlines? Looking at the photos? The navigation? Which methods help you understand the page the easiest and/or fastest?

The answer, accordingly to [eye-tracking studies](https://www.nngroup.com/articles/f-shaped-pattern-reading-web-content/), is that we skim pages looking for content that interests or serves us best. In that scan, we focus in on things like headings and key text such as phone numbers.

A person can use a screen reader in much a similar manner as they aim to understand the structure and content of a webpage. Just as we visually scan for headlines on nytimes.com, a screen reader can accomplish the same by reading the page headings, links, and regions of the page \(such as the navigation and main content\).

But what would happen if the computer had no way of telling which is which? That is where you, as the content creator, can help.

## Making the web visible to a screen reader

Screen readers cannot communicate page content and structure based on what can only be seen by eye. Rather, they rely on how our page is coded and organized. If not done properly, content can go missing or its intent can be lost.

For example, a screen reader relies on headings coded into the page to communicate article headlines or section titles within an article. For example, `<h1>` is for a top level heading, `<h2>` for second level, etc.

With our headline labeled as a heading, our screen reader can indeed see it as a headline.

```markup
<h2>Article headline</h2>
<p>This is the first paragraph of content.</p>
```

On the other hand, what if we only make the words bold? It will stand out visually, but a screen reader has no means of knowing if we intend for this text to be a headline or simply emphasized.

```markup
<p><strong>These words are bold, but is it a headline?</strong></p>
<p>This is the first paragraph of the article.</p>
```

When used correctly, a content management system, such as Wordpress, can handle most of these simple coding needs. However, as we write content within them, we can still introduce many errors. These errors, in turn, can make reading the pages with a screen reader difficult at best. When we're marking up our content in HTML from scratch, than the entire process is in our control. 

To get a feel how this works, here is a screen reader demonstration

{% embed url="https://www.youtube.com/watch?v=dEbl5jvLKGQ" %}

## Read more...

* [How People with Disabilities Use the Web](https://www.w3.org/WAI/people-use-web/)
* [I Used The Web For A Day Using A Screen Reader](https://www.smashingmagazine.com/2018/12/voiceover-screen-reader-web-apps/)

### **Simulations from WebAIM**

* [Screen reader Simulation](https://webaim.org/simulations/screenreader)
* [Low-vision Simulation](https://webaim.org/simulations/lowvision)
* [Dyslexia Simulation](https://webaim.org/simulations/dyslexia)
* [Distractability Simulation](https://webaim.org/simulations/distractability)

