# The core principles of a universally accessible website

Web accessibility relies on several components that work together. 

* **Your content** - This can be any content in your website from text to images and multimedia.
* **The "user agent"** - this is the software people use to access web content— be it a desktop, tablet, and mobile browsers, multimedia players, plug-ins, and assistive technologies such as screen readers that read aloud web pages for people who cannot read the text or screen magnifiers for people with some types of low vision.
* **Authoring tools** - any software or services you use to create content for the web. Examples could include our code editor, a PDF creator, or a web content manager such as WordPress. This could also include assistive tools such as voice recognition.

These components interrelate and support each other. For instance, **web content** needs to include text alternatives for images. This information needs to be processed by **web browsers** and then conveyed to **assistive technologies**, such as screen readers. To create such text alternatives, authors need **authoring tools** that support them to do so. More background is provided in [Essential Components of Web Accessibility](https://www.w3.org/WAI/fundamentals/components/).

Standards play a vital role in defining accessibility requirements for each of these components. Some accessibility requirements are easy to meet, yet understanding the basics of how people with disabilities use the Web helps implement them more effectively and efficiently. Some aspects of accessibility require more technical skills or advanced knowledge of how people use the Web. In all cases, [involving users early and throughout your web projects](https://www.w3.org/WAI/test-evaluate/involving-users/) will make your work better and easier.

### Perceivable

This means any person using any device can read the intended content of the page. Here's what this means for your websites...

#### text alternatives for non-text content

A good example is closed captioning and/or transcripts for spoken material \(be it a video or podcast\). This would also include description of images and charts and labels for interactive elements of your site \(such as forms and search buttons\).

#### Text alternatives for non-text content including images and multimedia <a id="alternatives"></a>

Text alternatives are equivalents for non-text content. Examples include:

* Short equivalents for images, including icons, buttons, and graphics
* Description of data represented on charts, diagrams, and illustrations
* Brief descriptions of non-text content such as audio and video files
* Labels for form controls, input, and other user interface components.

Think about all the places we use icons as a substitution for words. We need to include 

Text alternatives convey the purpose of an image or function to provide an equivalent user experience. For instance, an appropriate text alternative for a search button would be “_search_” rather than “_magnifying lens_”.

Text alternatives can be presented in a variety of ways. For instance, they can be read aloud for people who cannot see the screen and for people with reading difficulties, enlarged to custom text sizes, or displayed on braille devices. Text alternatives serve as labels for controls and functionality to aid keyboard navigation and navigation by voice recognition \(speech input\). They also act as labels to identify audio, video, and files in other formats, as well as applications that are embedded as part of a website.

#### Content can be presented in different ways <a id="adaptable"></a>

For users to be able to change the presentation of content, it is necessary that:

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

Meeting this requirement helps separate foreground from background, to make important information more distinguishable. This includes considerations for people who do not use assistive technologies and for people using assistive technologies who may observe interference from prominent audio or visual content in the background. For instance, many people with color blindness do not use any particular tools and rely on a proper design that provides sufficient color contrast between text and its surrounding background. For others, audio that is automatically played could interfere with text-to-speech or with [assistive listening devices \(ALDs\)](http://www.w3.org/WAI/training/accessible#ald).

### Operable  <a id="operable"></a>

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

#### information and user interface

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

#### content and reliable interpretation

#### Content is compatible with current and future user tools <a id="compatible"></a>

Robust content is compatible with different browsers, assistive technologies, and other user agents. Examples of how this can be achieved include:

* Ensuring markup can be reliably interpreted, for instance by ensuring it is valid
* Providing a name, role, and value for non-standard user interface components

Meeting this requirement helps maximize compatibility with current and future user agents, including assistive technologies. In particular, it enables assistive technologies to process the content reliably, and to present or to operate it in different ways. This includes non-standard \(scripted\) buttons, input fields, and other controls.

Adapted from [Accessibility Principals](https://www.w3.org/WAI/fundamentals/accessibility-principles/) by W3C Web Accessibility Initiative

