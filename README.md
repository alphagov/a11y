a11y
====

A collection of accessibility resources for developers building GOV.UK

What follows is a quick "first pass" for what you should be thinking about when checking the accessibility of the things we're building for GOV.UK. There will be additional work beyond this to provide accessibility documentation for the Digital by Default Standard in 2013, but these will get you thinking about building accessibly from the beginning.


## Layout

* When you zoom in/out of the page, does the layout, design and/or content break visually? Increase text size in browser at least 200%, or use Zoom on a Mac.
* Does the source order of the page (irrespective of visual layout) present information in a logical sequence?</li>


## Content
* Is the page broken down into sections with a logical heading structure?
* Does your content use straight forward language, expand acronyms the first time they’re used, and provide explanations for necessary jargon?
* Does your link text make sense, especially when taken out of the context of the surrounding paragraph/page?
* When using a <code>&lt;table&gt;</code>, are table headers included and marked up appropriately?


## Contrast
* Do the foreground/background colour combinations you’re using pass the 4.5:1 ratio? Useful tool here: <a href="http://juicystudio.com/services/luminositycontrastratio.php">http://juicystudio.com/services/luminositycontrastratio.php</a>
* Have you checked with <a href="http://michelf.ca/projects/sim-daltonism/">Sim Daltonism</a> to make sure it works across vision ranges for those who are colourblind?
* [More resources on color contrast](https://accessibility.civicactions.com/guide/tools#color).


## Focus & Keyboard Access
* When you navigate using the tab key, can you easily identify your current position on the page?
* Can everything on the page be accessed or activated without a mouse?


## Forms
* Does every form field have a correctly associated <code>&lt;label&gt;</code>?
* Are associated form items grouped in a fieldset?
* Does your form have a clear call to action (submit button etc.)?


## Alternative tools

* Try the site in a screen reader? VoiceOver on the Mac and NVDA on Windows are both free, as is the ChromeVox Chrome extension. Does the content make sense when read through? Can you understand the function of the page and complete your task?
* Try the site using a text-only browser such as Lynx - is the site structure still understandable?
