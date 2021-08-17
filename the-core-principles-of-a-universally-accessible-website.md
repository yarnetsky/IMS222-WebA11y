# The four principles of universally accessible websites \(POUR\)

Universal access to your web content relies on several components working together.

* **Your content** - It all starts with your content— from your text to images and multimedia. If your content is not written or coded correctly, your reader will not be able to comprehend your content.
* **User agents** - A user agent is the software people use to access your web content. This could be any device including a desktop or mobile/tablet web browsers, ebook readers, multimedia players, browser plug-ins, and assistive technologies such as screen readers that read aloud web pages.
* **Authoring tools** - We often use tools to create web content. This could be anything from our code editor to a web content manager such as WordPress. It's also the content we embed in our websites such as Instagram, YouTube, or Twitter. 

If any of these fail, your reader can miss the intended meaning of your content. Your reader loses and so do you because the failure prevents your ability to communicate.

To help you navigate what is required to make your work accessible, there are four principles which go by the acronym POUR— _perceivable_, _operable_, _understandable_, and _robust_. These principals each cover a lot of ground, but come together to outline what's needed to make your site universally accessible.

Note: There are official national and international standards that play a vital role in the requirements for each of these components. Some of these requirements are easy to meet and others require technical skills or advanced knowledge of how people use the Web. In all cases, [involving users early and throughout your web projects](https://www.w3.org/WAI/test-evaluate/involving-users/) will make your work better and easier.

### Perceivable

Everyone should be able to gain the knowledge you intend to share with your site. All content should have a means of conveyance to the reader. Here's what this means for your websites...

"Perceivability means the user can identify content and interface elements by means of the senses. For many users, this means perceiving a system primarily visually, while for others, perceivability may be a matter of sound or touch. New and emerging technologies may include sensory cues for smell and taste; these would also be considered examples of "perceivable" technology."

#### text alternatives for non-text content such as images and multimedia

A good example is closed captioning and/or transcripts for spoken material \(be it a video or podcast\). This would also include description of images and charts and labels for interactive elements of your site \(such as forms and search buttons\).

These text alternatives can be presented in a variety of ways. They could be read aloud for people who cannot see the screen and for people with reading difficulties, enlarged to custom text sizes, or displayed on braille devices.

#### Content can be presented in different ways <a id="adaptable"></a>

Structuring your HTML properly, such as headings, lists, tables, and content structures, will help a variety of user agents— from browsers to assistive technologies — properly display your content.  

* Headings, lists, tables, input fields, and content structures are marked-up properly
* Sequences of information or instructions are independent of any presentation
* Browsers and assistive technologies provide settings to customize the presentation

Meeting this requirement allows content to be correctly read aloud, enlarged, or adapted to meet the needs and preferences of different people. For instance, it can be presented using custom color combinations, text size, or other styling to facilitate reading. This requirement also facilitates other forms of adaptation, including automatic generation of page outlines and summaries to help people get an overview and to focus on particular parts more easily.

#### Content is easier to see and hear <a id="distinguishable"></a>

Distinguishable content is easier to see and hear. Such content includes:

* Color is not used as the only way of conveying information or identifying content
* Default foreground and background color combinations provide sufficient contrast
* When users resize text up to 400% or change text spacing, no information is lost
* Text reflows in small windows \(“viewports”\) and when users make the text larger
* Images of text are resizable, replaced with actual text, or avoided where possible
* Users can pause, stop, or adjust the volume of audio that is played on a website
* Background audio is low or can be turned off, to avoid interference or distraction

Meeting this requirement helps separate foreground from background, to make important information more distinguishable. This includes considerations for people who do not use assistive technologies and for people using assistive technologies who may observe interference from prominent audio or visual content in the background. For instance, many people with color blindness do not use any particular tools and rely on a proper design that provides sufficient color contrast between text and its surrounding background. 

### Operable  <a id="operable"></a>

"Operability means that a user can successfully use controls, buttons, navigation, and other necessary interactive elements. For many users, this means identifying an interface control visually, and then clicking, tapping, or swiping. For other users, using a computer keyboard or voice commands may be the only means by which they can operate and control the interface."

#### Your site needs to be functional from a keyboard

Many people do not use the mouse and rely on the keyboard to interact with the Web. This requires keyboard access to all functionality, including form controls, input, and other user interface components.

Keyboard accessibility includes:

* All functionality that is available by mouse is also available by keyboard
* Keyboard focus does not get trapped in any part of the content
* Web browsers, authoring tools, and other tools provide keyboard support

Meeting this requirement helps keyboard users, including people using alternative keyboards such as keyboards with ergonomic layouts, on-screen keyboards, or switch devices. It also helps people using voice recognition \(speech input\) to operate websites and to dictate text through the keyboard interface.

#### Users have enough time to read and use the content <a id="time"></a>

Some people need more time than others to read and use the content. For instance, some people require more time to type text, understand instructions, operate controls, or to otherwise complete tasks on a website.

Examples of providing enough time include providing mechanisms to:

* Stop, extend, or adjust time limits, except where necessary
* Pause, stop, or hide moving, blinking, or scrolling content
* Postpone or suppress interruptions, except where necessary
* Re-authenticate when a session expires without losing data

#### Content does not cause seizures and physical reactions <a id="safe"></a>

Content that flashes at certain rates or patterns can cause photosensitive reactions, including seizures. Flashing content is ideally avoided entirely or only used in a way that does not cause known risks. Also animations and moving content can cause discomfort and physical reactions.

Examples of avoiding causing seizures and physical reactions:

* Do not include content that flashes at particular rates and patterns
* Warn users before flashing content is presented, and provide alternatives
* Provide mechanisms to switch off animations, unless they are essential

#### Users can easily navigate, find content, and determine where they are <a id="navigable"></a>

Well organized content helps users to orient themselves and to navigate effectively. Such content includes:

* Pages have clear titles and are organized using descriptive section headings
* There is more than one way to find relevant pages within a set of web pages
* Users are informed about their current location within a set of related pages
* There are ways to bypass blocks of content that are repeated on multiple pages
* The keyboard focus is visible, and the focus order follows a meaningful sequence
* The purpose of a link is evident, ideally even when the link is viewed on its own

Meeting this requirement helps people to navigate through web pages in different ways, depending on their particular needs and preferences. For instance, while some people rely on hierarchical navigation structures such as menu bars to find specific web pages, others rely on search functions on websites instead. Some people may be seeing the content while others may be hearing it or seeing and hearing it at the same time. Some people may be using the content with only a mouse or a keyboard, while others may be using both.

#### Users can use different input modalities beyond keyboard <a id="modalities"></a>

Input modalities beyond keyboard, such as touch activation, voice recognition \(speech input\), and gestures make content easier to use for many people. Yet not everyone can use each of these input modalities, and to the same degree. Particular design considerations maximize the benefit of these input modalities. This includes:

* Gestures that require dexterity or fine movement have alternatives that do not require high dexterity
* Components are designed to avoid accidental activation, for example by providing undo functionality
* Labels presented to users match corresponding object names in the code, to support activation by voice
* Functionality that is activated by movement can also be activated through user interface components
* Buttons, links, and other active components are large enough to make them easier to activate by touch

Meeting this requirement makes the content easier to use for many people with a wide range of abilities using a wide range of devices. This includes content used on mobile phones, tablet computers, and self-service terminals such as ticketing machines.

### Understandable  <a id="understandable"></a>

"Understandable technology is consistent in its presentation and format, predictable in its design and usage patterns, concise, multimodal, and appropriate to the audience in its voice and tone. Users should be able to comprehend the content, and learn and remember how to use the interface."

#### Text is readable and understandable <a id="readable"></a>

Content authors need to ensure that text content is readable and understandable to the broadest audience possible, including when it is read aloud by text-to-speech. Such content includes:

* Identifying the primary language of a web page, such as Arabic, Dutch, or Korean
* Identifying the language of text passages, phrases, or other parts of a web page
* Providing definitions for any unusual words, phrases, idioms, and abbreviations
* Using the clearest and simplest language possible, or providing simplified versions

Meeting this requirement helps software, including assistive technology, to process text content correctly. For instance, this requirement helps software to read the content aloud, to generate page summaries, and to provide definitions for unusual words such as technical jargon. It also helps people who have difficulty understanding more complex sentences, phrases, and vocabulary. In particular, it helps people with different types of cognitive disabilities.

#### Content appears and operates in predictable ways <a id="predictable"></a>

Many people rely on predictable user interfaces and are disoriented or distracted by inconsistent appearance or behavior. Examples of making content more predictable include:

* Navigation mechanisms that are repeated on multiple pages appear in the same place each time
* User interface components that are repeated on web pages have the same labels each time
* Significant changes on a web page do not happen without the consent of the user

Meeting this requirement helps people to quickly learn the functionality and navigation mechanisms provided on a website, and to operate them according to their specific needs and preferences. For instance, some people assign personalized shortcut keys to functions they frequently use to enhance keyboard navigation. Others memorize the steps to reach certain pages or to complete processes on a website. Both rely on predictable and consistent functionality.

#### Users are helped to avoid and correct mistakes <a id="tolerant"></a>

Forms and other interaction can be confusing or difficult to use for many people, and, as a result, they may be more likely to make mistakes. Examples of helping users to avoid and correct mistakes include:

* Descriptive instructions, error messages, and suggestions for correction
* Context-sensitive help for more complex functionality and interaction
* Opportunity to review, correct, or reverse submissions if necessary

Meeting this requirement helps people who do not see or hear the content, and may not recognize implicit relationships, sequences, and other cues. It also helps people who do not understand the functionality, are disoriented or confused, forget, or make mistakes using forms and interaction for any other reason.

### Robust  <a id="robust"></a>

If you do the above, your content becomes more compatible with current and future tools. It ensures your markup is compatible with different browsers, assistive technologies, and other user agents. 

"Robust I.T. is standards-compliant, and designed to function on all appropriate technologies. Users should be able to choose the technology they use to interact with websites, online documents, multimedia, and other information formats."

In accessibility circles, we often talk about compatibility with assistive technologies, but we also need to keep our content usable for the future "Internet of Things." Will your refrigerator be able to read a recipe and compare it to the contents of your refrigerator? If you recipe is marked up properly today, then it should be robust enough to succeed.

"POUR principles were developed to describe web accessibility, but they can be applied to almost any accessibility question. Technology providers must ensure that their users all can perceive, operate, and understand their technology, and that the technology is robust enough to work across a spectrum of technologies, including assistive technology."

Web accessibility has a set of standards called the [Web Content Accessibility Guidelines \(WCAG 2.1\)](https://www.w3.org/TR/WCAG21/). It has dozens of specifications on topics from headers and links to colors and images. To better understand the intent of these specifications, let's group them into three goals.

## Goal 1: Page structure outlined

When first visiting a webpage, a reader want to quickly gain an outline of the page's purpose and content. As noted, headings can provide our users with the page headlines. Headings can also provide an outline of the content's proper order. Thus, a webpage is understandable if the page's headings, content order, and links are well written. A poorly constructed page, on the other hand, could be perceived as out of order or missing content.

## Goal 2: Content meaning explained

All meaning that would be visually gained from illustrated webpages should also be readily understood by patrons using assistive technologies. As screen readers cannot "see" our photos, alternative text is needed to explain a photo's purpose and content. Similarly, warnings are often color-coded red. These warnings should be understandable as a warning even without the use of color. Incorporating best practices as you write, and a little help from our content management systems, make these tasks easier.

## Goal 3: Interactive tools enabled and described

In addition to perceiving a webpage's structure and content, a person also needs to properly interact with the page. It's worth noting at this point that screen readers are most often controlled by keyboard commands. As such, we need to enable our site to be accessible by keyboard as well as by mouse or tap.

For example, a webpage may have a floating window that pops-up asking if the user wants to sign up for a newsletter. With a screen reader, mousing to the close button is not an option. If the floating window is correctly coded, the cursor will be captured so the reader can easily keyboard over to the close button. If the window is incorrectly coded, the reader could be stuck behind a window that cannot be closed.

Interactive tools also needs to be properly described. For example, if there are four tabs of content, the site needs to describe to the screen reader which of the four tabs is visible. Without this description, the screen reader simply cannot navigate these interactive features.

Fortunately, much of this functionality is built into modern website management systems such as LibGuides. However, as content creators, we need to be alert to this issue so we use these interactive elements effectively and correctly coded.

**Credits**: Content adapted from [Accessibility Principles](https://www.w3.org/WAI/fundamentals/accessibility-principles/) by W3C Web Accessibility Initiative

