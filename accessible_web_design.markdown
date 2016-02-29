slidenumbers: false

# Web Accessibility

## All the Basics[^*]

[^*]: <https://github.com/JacobR/accessible_web_presentation/>

---

# About Me

* My name is **Jacob Reed**
* Work as a **web developer/project manager** at the **Marriott Library**
* Working with websites for ~15 years
* My email address is <jacob.reed@utah.edu>

---

# What is Web Accessibility?

---

## Web accessibility is simply making sure **every one** visiting your website or using your app can **understand**, **navigate**, and **use** your stuff.

^ The chapter of Head First Web Design Prof. Gehl gave you makes this point as well. Accessibility really isn't just about "disabled" people, it's about designing "correctly."

---

# Why Design with Accessibility in Mind?

* It's the **right** thing to do
* Sites built with accessibility in mind are **more flexible** and benefit **all users**
* A level of accessibility is **legally obligated** in some countries
* Accessible designs help with **search engine optimization**

^ A certain base-level of accessibility for some services is the law in some countries.

^ In the U.S., Section 508 of the Workforce Rehabilitation Act mandates the accessibility requirements for Federal agencies.

^ Google's web crawler is a type of screen reader

---

# The Numbers

* ~1/5th of America has some disability[^1]
* 10.8% for ages 21 to 64[^2]
* 25.8% for ages 65 to 74[^2]
* 50.7% for ages 75+[^2]

[^1]: Nearly 1 in 5 People Have a Disability in the U.S. (2012, July 25). Retrieved September 16, 2015, from <https://www.census.gov/newsroom/releases/archives/miscellaneous/cb12-134.html>

[^2]: Erickson, W. Lee, C., & von Schrader, S. (2014). 2013 Disability Status Report: United States. Ithaca, NY: Cornell University Employment and Disability Institute (EDI).

^ The U.S. Census estimates that almost 20% of Americans experience some form of disability

^ Disabilities become a bigger and bigger issue as you age

^ If you live long enough, chances are **you** will most-likely have a disability

---

# What does Web Accessibility Look to Address?

---

# Vision Issues

* Blindness
* Low vision
* Color blindness
* Poor lighting conditions

![](https://upload.wikimedia.org/wikipedia/commons/6/65/Eye_iris.jpg)

^ So, for instance, when you build your site with adequate color contrast, you're not only helping people with vision problems, you're also helping people read your content on their cell phone in the sun.

---

# Hearing Issues

* Deafness
* Hard-of-hearing
* Situational inability to hear

![fit](https://upload.wikimedia.org/wikipedia/commons/b/bf/Tidens_naturl%C3%A6re_fig40.png)

---

# Cognitive Issues

* Learning disabilities
* Distractibility
* Situational inability to focus
* Vestibular disorders

![](https://upload.wikimedia.org/wikipedia/commons/9/90/A_Special_Olympics_%28SO%29_athlete_crosses_the_finish_line_after_completing_the_last_leg_of_a_400_meter_relay_race_during_the_Kadena_Air_Base_SO_event_in_Okinawa%2C_Japan%2C_Nov_111105-F-FL863-002.jpg)

^ Motion sickness was a major problem when Apple released iOS 7, and Apple had to release a fix with iOS 7.1

---

# Changing or Temporary Issues

* The effects of age
* Temporary disabilities or injuries

![](https://upload.wikimedia.org/wikipedia/commons/e/ef/Cast_off.JPG)

^ Broken wrist from skiing
^ Recovering from surgery

---

# Technological Issues

* Slow internet connection
* Small or low resolution screens
* Older technology

![fit](https://upload.wikimedia.org/wikipedia/commons/8/84/C64c_system.jpg)

---

# Crisis[^3]

* Vague or unclear thinking
* Stress
* In a hurry

![](http://images-cdn.moviepilot.com/image/upload/c_fill,h_827,w_1600/t_mp_quality/alien_128pyxurz-1-last-survivor-of-the-nostromo-signing-off-what-ever-happened-to-the-alien-cast-jpeg-140214.jpg)


[^3]: Eric Meyer gives a good summary this on The Web Ahead podcast (<http://5by5.tv/webahead/91>).

^ Lately, Eric Meyer, well-known web-designer and author of *Eric Meyer on CSS*, *Cascading Style Sheets: The Definitive Guide*, and *CSS2.0 Programmer's Reference*, has been talking about designing for those in crises. 

^ When his family experienced some pretty extreme medical problems, he noticed that many of the hospital websites they used were not well suited for finding the exact sort of information they needed on their websites, and this was exacerbated by his state of mind while visiting them.

^ This doesn't have to just apply to medical emergency information though. I'm sure a few of you have experienced going to a website in a semi-paniced, stressed-out state and having a hard time locating exactly what you needed.

^ Eric has made the case that important information that needs to be found in a hurry should be easily found on sites that offer these sorts of services.

---

# Accessibility is About Everyone

* Not just about long-term physical disabilities
* Short-term & situational/environmental disabilities
* Technological limitations and alternative devices
* Convenience & Usability

^ Accessibile designs aren't just for people with permanent disabilities.

^ Everyboy benefits from websites and apps built with accessible designs.

^ By building accessibility features into your sites, you are giving your users more ways of interacting with your information.

---

# Accessibility Isn't Just About Code
### Designing with Accessibility in Mind

---

## Poor planning = :clock4: + :dollar:

^ The key to accessiblity web design really is planning.

^ People and organizations often have the mistaken idea that making things accessible means spending more time and money. A good demonstration of this is given in your Head First text. But, if accessibility is part of the initial planning and design process, this is almost never really the case.

^ Retro-fitting existing, poorly planned projects, however, is often extremely costly, and I think this is where the "accessibility is expensive" myth comes from.

---

# Planning Your Design[^4]

* Determine your goals & gather support
* Develop & implement policies
* Make sure someone is "in charge" of accessibility
* Review your tools & resources before use

[^4]: <http://www.w3.org/WAI/impl/>

^ If you're working on a project by yourself you want to make sure you know ahead of time what your project goals will be, and if a project is being managed by a group accessibility goals need to be understood by the group.

^ Actual accessibility policies should be understood. These can be simplified by simply making sure your group is inline with some of the already cotified guidelines out there, such as the W3Cs WCAG standard.

^ Everybody involved in design and development should take responsibility for making sure things are accessible, but having someone "in charge" of this is a good way to make sure things stay on track.

^ If you're using specific frameworks, make sure these don't have accessibility issues. If the tool is fairly well known, Google will yield good information on this and may point you towards a competing product or tweaks and tools to make the tool work with a broader group of people.

^ A good example of a cautionary tale is Prezi, who's over-reliance on Flash seems to have not only severely hampered their ability to be ADA/508 compliant.

---

# Design Empathetically

Don't just check off an "accessibility to-do"

Put yourself in the mind of your users

Make your website a **great experience for all** your visitors

^ In their book *The Persona Lifecycle: Keeping People in Mind Throughout Product Design*, Pruitt and Adlin recommend creating personas of different types of users.

^ They note that "Personas put a face on the user — a memorable, engaging, and actionable image that serves as a design target. They convey information about users to your product team in ways that other artifacts cannot." (p. 11)

---

## Responsive Design is an Accessibilty Concern

---

## What is Responsive Design?

> "[A]n approach to web design aimed at crafting sites to provide an optimal viewing and interaction experience ... across a wide range of devices"[^5]

[^5]: <https://en.wikipedia.org/wiki/Responsive_web_design>

^ Rather than creating a different site for each device, designers now have their content respond to the dimensions of their users device. Responsive design is extremely common now, and I'm sure most of you have noticed responsiveness when viewing websites with your phones or tablets.

---

# Build Responsively

Responsive design has become a *must*

Many developers use responsive designs without knowing they are making things more accessible

There are many frameworks available <br> (e.g. Bootstrap, Skeleton, and YAML 4)

^ When learning HTML 101, it may not be important for you to create fully fleshed-out responsive sites, but as you develop you'll want to start to integrate responsiveness into your designs.

---

# Typograhy

---

# Font Size

* Body text should be designed around 16px-20px
* Relative sizing is better than absolute
* Browsers will adjust to absolutes
* Absolutes tend to be less flexible, can break designs on resize

^ Designing with relative values provide more design flexibility, but really browsers will adjust this for your user either way. 

^ However, you probably want the body text to be between 16px and 20px to provide a satisfying user experience.

---

# Font Contrast


* The difference between Headings & body text should be obvious

* Same goes for **bold** vs. normal text

---

# Line Length

Not too long (>75 characters)

Not too short (<45 characters)

**Just right! (*~66 characters*)**

(Especially an issue with responsive designs)

---

# Line Spacing

* Line spacing should be at least ½ the height of the text

* Paragraph spacing should be set to ~1.5 x line height

^ This can vary by the font size and type

---

# Avoid Text Justification

* Creates "rivers" that make reading difficult
* Especially bad for people with cognitive disabilities such as dyslexia

---

# Justified vs. Left Aligned

![inline](https://dl.dropboxusercontent.com/u/1709778/justified_v_left.png)

---

# Color

![](http://2.bp.blogspot.com/-Ji27uJ3C_x0/UQWq7GEb5BI/AAAAAAAAD4o/-qYLYq5Ak1s/s1600/wheel.png)

---

# Color & Context

You shouldn't rely **solely** on color to convey meaning[^6]

This mistake used to happen *a lot* with forms

[^6]: <http://webaim.org/intro/>

^ When designing, make sure the context of your site isn't dependent on color alone.

^ Color obviously gives very little information to the blind.

---

# Color Blindness Types[^7]

![inline](https://upload.wikimedia.org/wikipedia/commons/a/af/Color_blindness.png)

[^7]: <https://en.wikipedia.org/wiki/Talk:Color_blindness/Archive_1#/media/File:Color_blindness.png>

^http://webaim.org/resources/contrastchecker/

---

# Color Perception[^8]

![inline](http://understandinggraphics.com/wp-content/uploads/2009/10/color-blind-chart.png)

[^8]: <http://understandinggraphics.com/design/designing-for-color-blindness/>

---

# Color Contrast

* Make sure colors have enough contrast
* W3C recommends a contrast ratio ≥ 4.5:1[^9]
* There are a lot of tools available to test this


[^9]: <http://www.w3.org/TR/WCAG20/>

---

# Color Contrast

Proper use of color addresses many issues:

* Vision problems
* Technological issues
* Poor lighting

^ The colors you do choose should also have enough contrast to be readable by the widest audience.

^ This not only helps people with vision problems; it also helps make sites more readable for everyone.

---

# In Doubt?

* WebAIM's Color Contrast Checker[^10]

* Colour Contrast Analyser[^11]

[^10]: Available at <http://webaim.org/resources/contrastchecker/>

[^11]: Available at <https://www.paciellogroup.com/resources/contrastanalyser/>

---

# In Summary

* You should design with empathy for your user
* Accessibility should be part of your initial planning
* Responsive design is a must
* Both color and typography play vital roles in accessible designs

---

# Coding with Accessibility in Mind

---

## Document Structuring

---

# Structuring Is Where Accessible Designs Start

* HTML should be logically organized.

* If your page has **no css**, it should still make sense and have valid hierarchy.

---

# HTML Headings provide the Assistive Technology Outline

When scanning your site, assistive technologies use your heading structure to map out the page.

<h2>s should be underneath <h1>s, etc.

Avoid skipping heading levels.

Use CSS to make your headings look appropriate.

---

# Floats

Write content in the order you want the material read and float accordingly

```html
<section id="main_content">
Lorem ipsum dolor sit amet, quo et tollit maluisset, enim 
assentior eu ius. His amet probo ubique an, falli sensibus 
corrumpit est id. Prodesset efficiendi in vis, his et aeque 
ludus. Ne vix oblique quaerendum, ei dicat epicuri abhorreant 
eum.
</section>
<section class="side_content" style="float:left;">
Quem perfecto mea ei, wisi voluptaria qui at. Id aperiri labores 
neglegentur has. Esse nibh semper usu at, vivendum urbanitas pri ne. 
</section>
```

---

# Image Alternative Text[^12]

[^12]: Most of these examples were derived from WebAIM (<http://webaim.org/techniques/alttext>). <br> Check out their article for additional information.

---

* Typically the first accessibility tool learned
* Used improperly a lot of the time
* Plan your "alts" around **context**

^ Alternative text is usually the first thing a developer hears about when learning about web accessibility, but it's often poorly implemented on the web.

^ When using alternative text it's important to keep in mind its purpose -- context. Alternative text is not something you check off your accessibility "to-do," it's a means to make your site usable to the broadest possible audience.

---

### Providing Context[^13]

![right](http://vignette1.wikia.nocookie.net/poohadventures/images/7/70/Ellen_Ripley_1.png)

```html
<section class="bio">
  <img src="ripley.png" alt="Ellen Ripley">
  <p>
  Beginning her career as a warrant officer with 
  Weyland-Yutani's commercial freight operations, 
  Ellen Louise Ripley was assigned to the USCSS 
  Nostromo in 2122 when it encountered a single 
  Xenomorph unintentionally collected from the 
  planetoid LV-426.
  </p>
</section>
```

[^13]: [http://avp.wikia.com/wiki/Ellen_Ripley](http://avp.wikia.com/wiki/Ellen_Ripley)

---

### Context Given or Unneccessary[^14]

![right](http://vignette2.wikia.nocookie.net/avp/images/c/c9/Dallas.png/revision/latest?cb=20140918003116)

```html
<section class="bio">
  <img src="dallas.png" alt="">
  <strong>Arthur Dallas</strong>
  <img src="decorative_line.gif" alt="">
  <p>
  After attending high school in his home town, 
  Arthur Dallas studied engineering at Beilecki 
  University's Martian campus, eventually 
  graduating with a Bachelors degree.
  </p>
</section>
```

[^14]: [http://avp.wikia.com/wiki/Arthur_Dallas](http://avp.wikia.com/wiki/Arthur_Dallas)

^ An "alt" tag attribute is always necessary, but if adding content to it doesn't appropriately add context, it's appropriate to leave the attribute value blank.

^ Context can be **directly** addressed by the text around the image, or the image may be purely decorative.

---

### "Alts" and Links

![left](http://image.toutlecine.com/photos/a/l/i/alien-1979-29-g.jpg)

```html
<!-- Context Needed -->
<p>
<a href="https://en.wikipedia.org/wiki/Harry_Dean_Stanton">
  <img src="stanton.png" alt="Wikipedia entry for Harry Dean Stanton">
</a>
</p>

<!-- Context Present -->
<p>
<a href="https://en.wikipedia.org/wiki/Harry_Dean_Stanton">
  <img src="stanton.png" alt="">
  <strong>Harry Dean Stanton</strong>
</a>
</p>
```

^ When an image is providing a link, your alternative text should describe the function of the image.

^ Normally an image like this may have an "alt" value of Harry Dean Stanton or Samuel Brett, but given the context of the html giving your visitors information about what clicking on the image **does** would trump further details about the image.

^ If the context of the link is described by the text around your image, the "alt" should be used as is appropriate to put the image in context. In this case, the context is also being handled by the text below.

^ Avoid using using the words like "link to" or "click here for" in your "alt" values.

---

# Other Cases

* The "alt" on form-submit images should describe the form action, not the image.

```html
<input type="image" src="right-arrow-submit.gif" alt="Submit">
```

* Background images should not provide context.

---

# Other Cases (cont.)

* If an image has been broken up into multiple parts, "alt" content should be included on the most prominent part.
* alt="[COMPANY NAME]" is usually considered appropriate for a company logo in the top banner.

^ If you **have** to use an image map, the alt tag should describe the image as a whole, not individual components.

---

# Long Descriptions

* The "longdesc" attribute is a great tool for adding detailed information, **HOWEVER**...
* Support for this attribute is not great
* Primarily used by JAWS and NVDA on IE and Firefox[^15]

[^15]: Support testing information available at <http://webaim.org/techniques/alttext/longdesctestcases.htm>.

---

# Make Long Descriptions Work for Everyone

When using this attribute, provide a link to the description so that it's available to all.[^16]

```html
<img src="sales.jpg" alt="Line chart of 
annual sales data" longdesc="salesdata.htm"><br>
<a href="salesdata.htm">View sales data</a>

```

[^16]: Sample code provided by WebAIM (<http://webaim.org/techniques/alttext/>).

^ Using "longdesc" in this way will dramatically increase this informations user availability and make it a useful bit of information for all your users

---

# WAI-ARIA
## Web Accessibility Initiative – Accessible Rich Internet Applications

---

# What's that!?

ARIA is a set of attributes, created by the W3C, to help assistive technologies.

Web applications utilize AJAX, HTML, and JavaScript in ways that screen readers often don't understand.

ARIA attempts to bridge that gap.

---

# How does it work?

ARIA uses "roles," "states," and "properties" to give browsers and assistive technologies *additional information*

---

# "Roles," "States," and "Properties"

"Roles" tell a browser that an HTML element is functioning in a specific, non-traditional manner 

"States" and "properties" define the state of a current element (e.g. checked, hidden, collapsed)

---

# ARIA and Forms (Required Fields)

```html
<label for="email">
  Email Address <span class="req">*</span>
</label>
<input id="email" type="email" aria-required="true">
```

---

# ARIA and Forms (Labelling)[^17]

![inline](https://dl.dropboxusercontent.com/u/1709778/Screenshot%202015-10-15%2015.20.18.png)

```html
<th id="officenum" scope="col">Office Number</th>
The HTML for the first text field within the table is:
<input type="text" name="office1" aria-labelledby="cyndi officenum">

```

[^17]: <http://webaim.org/techniques/forms/advanced>

---

# ARIA and Forms (Describing)[^18]

![inline fit](https://dl.dropboxusercontent.com/u/1709778/Screenshot%202015-10-15%2015.34.37.png)

```html
<label for="resetpass">Reset Password:</label>
<input type="password" name="resetpass" id="resetpass" aria-describedby="newpass">
<br>
<span id="newpass">New password must be 8-15 characters and include 
letters and numbers</span>

```

[^18]: <http://webaim.org/techniques/forms/advanced>

---

# Random Form

![inline](http://uxmovement.com/wp-content/uploads/2010/08/Picture-111.png)

---

# What ARIA isn't

ARIA is a toolset for adding accessibility **information**; it's not a silver bullet.

ARIA doesn't influence browser behavior.

Accessibility first should still be your goal.

^ Giving a **<div>** a "button" role will not allow it to function as a **<button>**. Keyboard/device functionality will need to be programmed seperately.

^ Applying accessibility techniques to an unusable site is like putting lipstick on a pig. No matter how much you apply, it will always be a pig.
-- Jared Smith, WebAIM

---

## Make sure your applications are designed to function accessibly

^ Jörn Zaefferer mentions using [JQuery UI](https://jqueryui.com/), which is a great resource. It's important to keep in mind that your sites and applications can benefit from already written code and that you can take advantage of a lot of the work that has already been done to solve problems.


---

### Always Set the Language Attribute

```html
<!-- For the page itself... -->
<html lang="en">
  ...

  <!-- and for alternate languages within a page. -->
  <blockquote lang="fr">
    Il faut réfléchir avant d'agir. Vaut mieux prévenir que guérir.
  </blockquote>
  ...

</html>
```

^ It's important to define the language of your document so that screenreaders can properly interprate the page.

---

# :focus & :active

Keyboard and assistive technology users rely on the CSS :focus & :active attributes .

Browsers will handle these attributes properly if the attributes haven't been disabled.

Feel free to style :focus and :active to make them match your design and create cross-platform consistency.

^ Many users with assistive technologies rely heavily on the CSS focus and active attributes to navigate the form elements and links in a page. 

^ The good news is that, without interference, browsers will handle this functionality fine. However, it's important that you don't disable this functionality as part of your design, and if you are using a content management system such as Drupal or Wordpress you want to make sure any templates you choose don't do this either.

^ You can test this out by simply navigating through your page using the tab and enter buttons on your keyboard.

^ You may actually be able to *improve* the default browser behavior using CSS. Common techniques for this are increasing the contrast or setting the :focus and :active attributes to the same value as :hover. You want to make sure, however, that you don't change these attributes so they rely solely on color.

---

### Avoid Generic Text in Links

```html
<!-- Screen readers will state "Read More" repeatedly for each instance. -->
Lorem ipsum dolor sit amet, quo et tollit maluisset, enim assentior eu ius. His 
amet probo ubique an, falli sensibus corrumpit est id. Prodesset efficiendi 
in vis, his et aeque ludus. Ne vix oblique quaerendum, ei dicat epicuri 
abhorreant eum. Pro dissentias interesset ad, no error nominavi pri.
<a href="services.html">
  Read More
</a>

<!-- Instead use descriptive text -->
<a href="services.html">
  Read More About Our Services
</a>
```

---

### You Can Use CSS to Obscure Details[^19]

```html
<!--index.html-->
<a href="#">
  Read More <span class="offscreen">About NC State</span>
</a>
```

```css
/*my_style.css*/
.offscreen {
position:absolute;
left:-9999px;
width:1px;
height:1px;
top:auto;
}
```

[^19]: <http://accessibility.oit.ncsu.edu/blog/2012/01/12/accessible-read-more-links>

^ You'll want to note a few things here. You'll always want to move items to the left when using this technique. If you used "up" or "down," some browsers will scroll to these on keyboard focus. 

^ Also, you want to always use absolute positioning for this because it will prevent the browser from highlighting items when tabbing through with the keyboard. In this case, that's not much of a problem, but you can use this technique for a lot of different content.

---

# Another Example of Hidden Content Usage

```html
<!-- Assistive technology options -->
<div class="offscreen">
  <!-- Skip to main option -->
  <a href="#main_content">Skip to Main Content</a>
  <!-- Navbar labeling -->
  <h1>Main Navigation Bar</h1>
</div>
<!-- Main navigation bar -->
<nav class="navbar navbar-default">
```

^ These sorts of techniques should be used with some discretion. They aren't a bandaid, but they can be used to make your site a bit more friendly. Your site should be appropriate for all users even without these add-ons.

---

# Audio-visual

* Proper captioning is an important step when creating video content.[^20]
* Having a transcript of your content **will** come in handy.

[^20]: Accessify YouTube Caption Creator is a great tool for YouTube content. <br> (<http://accessify.com/tools-and-wizards/accessibility-tools/easy-youtube-caption-creator/>)

---

# Guidelines & Regulations

---

# Web Content Accessibility Guidelines <br> (WCAG 2.0)[^21]

WCAG is a set of guidelines, created by the W3C, meant to determine wether a website is accessible to people with disabilities.

WCAG isn't a law, but it's usually sets the context for accessibility discussions

[^21]: Overview of WCAG available at <http://www.w3.org/WAI/intro/wcag>

---

# Section 508

Section 508 Amendment to the Rehabilitation Act of 1973 are a set of regulations that bar the Federal government from buying electronic and goods and services that aren't accessible to people with disabilities.

---

# Non-U.S. Regulations

Many other governments are starting to mandate levels of accessability for online content. 

Almost all of these regulations closely mirror WCAG 2.0 guidelines.

---

# Accessibility Testing


* Remove CSS and see if your site makes sense
* Navigate your site with just your keyboard
* Download the JAWS demo or NVDA (Windows)
* Turn on VoiceOver (Mac or iOS)
* Checkout the many tools available to audit and automate testing
* W3C or WebAIM Checklists

^ As Jörn Zaefferer notes in one of the videos Prof. Gehl gave you, the JAWS demo is only available for a brief time and then your machine needs to be rebooted, so a virtual machine that can be paused may be a good option here.

---

# Useful Tools

* TinyPNG – <https://tinypng.com>
* WebAIM Color Contrast Checker – <http://webaim.org/resources/contrastchecker/>
* WAVE accessibility tool - <http://wave.webaim.org/>

---

# More Useful Tools

* Colour Contrast Analyser - <https://www.paciellogroup.com/resources/contrastanalyser/>
* Bootstrap Responsive Framework – <http://getbootstrap.com/>
* Bootstrap Accessibility Plugin – <https://paypal.github.io/bootstrap-accessibility-plugin/>

---

# Even More Useful Tools

* Accessibility Developer Tools – <https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb/>
* Accessify YouTube Caption Creator – <http://accessify.com/tools-and-wizards/accessibility-tools/easy-youtube-caption-creator/>


---

# [fit] Questions?
