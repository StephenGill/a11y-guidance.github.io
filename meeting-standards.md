# Meeting accessibility standards

Your service or website must meet level AA of the Web Content Accessibility Guidelines (WCAG 2.0) as a minimum.

Check if your organisation has other requirements you need to meet. If you’re creating a service or website for central government in the UK, you’ll also need to:

* test your service or website on the most commonly used [assistive technologies](https://www.gov.uk/service-manual/technology/designing-for-different-browsers-and-devices#testing-with-assistive-technologies) - including screen magnifiers, screen readers and speech recognition tools
* include people with disabilities in [user research](https://www.gov.uk/service-manual/user-research)

## Understanding WCAG 2.0

WCAG 2.0 is based on 4 principles:

- perceivable
- operable
- understandable
- robust

By focusing on principles, not technology, they emphasise the need to think about the different ways that people interact with content. For example, users might:

* use a keyboard instead of a mouse
* change browser settings to make content easier to read
* use a screen reader to ‘read’ (speak) content out loud
* use a screen magnifier to enlarge part or all of a screen
* use voice commands to navigate a website

The principles apply to all aspects of your service (including code, content and interactions), which means all members of your team need to understand and consider them.

## Applying WCAG 2.0 guidelines

The WCAG 2.0 design principles are supported by 12 guidelines. Each of these is broken down into specific requirements (or ‘success criteria’).

### Principle 1: Perceivable

To meet [WCAG 2.0 Principle 1: Perceivable](https://www.w3.org/TR/WCAG20/#perceivable) you need to make sure users can recognise and use your service with the senses that are available to them.

This means you need to do things like:

- provide text alternatives (‘alt text’) for non-text content
- provide transcripts for audio and video
- provide captions for video
- make sure content is structured logically and can still be read if stylesheets are disabled
- use the proper markup for every feature
- not use colour as the only way to explain or distinguish something
- use text colours that show up clearly against the background colour
- make sure every feature can be used when text size is increased by 200%
- not use images of text

### Principle 2: Operable

To meet [WCAG 2.0 Principle 2: Operable](https://www.w3.org/TR/WCAG20/#operable), you have to make sure users can find and use your content, regardless of how they choose to access it (for example, using a keyboard or voice commands).

This means you need to do things like:

- make sure everything works with a keyboard
- let people play, pause and stop moving content
- not use blinking or flashing content
- provide a ‘skip to content’ link
- use descriptive titles for pages and frames
- make sure keyboard users can move through content in a way that makes sense
- use descriptive links so users know where a link will take them
- use meaningful headings and labels
- make it easy for keyboard users to see where they are on a page

### Principle 3: Understandable

To meet [WCAG 2.0 Principle 3: Understandable](https://www.w3.org/TR/WCAG20/#understandable), you have to make sure people can understand your content and how the service works.

This means you need to do things like:

- use [simple language](https://www.gov.uk/guidance/content-design/writing-for-gov-uk)
- keep sentences short
- not use words and phrases that people won’t recognise - or provide an explanation if you can’t avoid it
- explain all abbreviations and acronyms, unless they are well known and in common use - for example UK, EU, VAT
- make it clear what language the content is written in, and indicate if this changes
- make sure features look consistent and behave in predictable ways
- make sure all form fields have visible and meaningful labels
- [make it easy to identify and correct errors in forms](https://govuk-elements.herokuapp.com/errors/)

### Principle 4: Robust

To meet [WCAG 2.0 Principle 4: Robust](https://www.w3.org/TR/WCAG20/#robust), you must make sure your content can be interpreted reliably by a wide variety of user agents (including reasonably outdated, current and anticipated browsers and assistive technologies).

This means you need to do things like:

- use valid HTML so user agents, including assistive technologies, can accurately interpret and parse content
- make sure your code lets assistive technologies know what every feature is for and what state it’s currently in

## Accessibility statements

You will need to publish an accessibility statement at a prominent place in your service, website or mobile app. For example, digital services on GOV.UK should add a link to the footer of each page. The accessibility statement should be published as an HTML page. 

The accessibility statement must say:

- which parts of your service meets accessibility standards and which parts don't
- if parts of the service don't meet accessiblity standards, why that's the case
- how people with access needs can use parts of the service that don't meet accessibility standards
- how to report accessibility problems with the service

The EU will publish a model accessibility statement by December 2018.

There's a legal requirement to publish your accessibility statement by:

- September 2019 for new services and websites
- September 2020 for services and websites created before 23 September 2018
- June 2021 for mobile apps

## Testing your service or website for accessibility

Create a test plan to check that your service or website is accessible.

To meet the digital service standard for UK central government services, your test plan must include:

- [recruiting people who have disabilities or use assistive technologies to participate in your user research](https://www.gov.uk/service-manual/user-research/find-user-research-participants)
- [testing your technology](https://www.gov.uk/service-manual/technology/testing-for-accessibility)

<p style="color:red;">[QUESTION: do we want to advocate expert review without providing advice on how to find someone with the right expertise?]</p>

### Getting an accessibility audit

You can get experts to review your website or service against accessibility standards by [commissioning an accessibility audit](https://stephengill.github.io/a11y-guidance.github.io/audit.html).

To meet the digital service standard for UK central government services, you’ll need to carry out an audit during the beta phase.

## Services and content that don't have to meet accessibility standards

There’s no legal requirement to meet the accessibility standards if you’re creating a service for a school, nursery or kindergarten.

And there's no general legal requirement to make content accessible if it's:

- live video
- third party content that’s under someone else’s control
- part of a heritage collection - for example, scanned manuscripts
- <span style="color:red">[content published on mobile closed systems - need to clarify what this means]</span>

But you may still need to make it accessible if you're aiming to meet the digital service standard for central government services.

If you think that your service (or any part of it) can’t be made accessible, contact the Government Digital Service (GDS) accessibility team for advice at <accessibility@digital.cabinet-office.gov.uk>.

## More about WCAG 2.0

Read the following resources for more information about meeting the WCAG guidelines:

- [WebAIM’s WCAG 2.0 checklist](https://webaim.org/standards/wcag/checklist)
- [University of Washington’s IT accessibility checklist](http://www.washington.edu/accessibility/checklist/)
- [WCAG is not scary anymore - a progressive approach to website accessibility](https://www.linkedin.com/pulse/wcag-scary-anymore-progressive-approach-website-herin-hentry/) - you’ll need a LinkedIn account to view this article
- [bitsofcode’s accessibility cheatsheet](https://bitsofco.de/the-accessibility-cheatsheet/)
