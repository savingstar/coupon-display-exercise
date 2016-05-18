# Coupon Display Exercise for SavingStar
A short, open-ended exercise of designing and implementing a coupon using HTML &amp; CSS (JS optional).

From an information architecture perspective, a coupon "cell" consists of a header section (title), body section (image &amp; description) and a footer section (actions, links, etc). The below image illustrates this with a wireframe.

### Coupon Cell

![Example Coupon](/coupon_example.png)

You can consider the exercise mostly complete when you have the below working:
* Accommodate for text that does not fit in its container (title &amp; description for example). At a minimum an ellipsis should appear when there is more text than fits in the container, and no ellipsis when the entire text does fit. If an ellipsis appears, provide a way to view the entire text.
* Display an image for the coupon in the body section, as well as the description. Bonus points for a creative approach to this.
* Design for the eventuality that the body section (between footer and header) can range in height, while allowing the image and description text to remain vertically centered. (See 'Vertical Alignment Example' Below)
* Display a button to activate the coupon in the footer section.

### Vertical Alignment Example

![Example Coupon With Vertical Alignment Guides](/coupon_example_w_guides.jpg)
![Example Coupon With Larger Body Area](/coupon_example_stretched_w_guides.jpg)

### Additional Considerations

Now that you have a decent example of your front-end skills, take a moment to consider the below before sending it over:
* Have you taken a responsive design approach to presenting the coupon optimally on both small screen devices (iPhone, Android, etc.) and large screen devices (laptops, desktops, TVs, etc.)?
* Have you considered some "outside the box" approaches to the coupon cell layout? For instance, how can the coupon's image and offer description be laid out in an interesting and useful way?
* Have you considered how colors can aid in the visual design and usability?
* Did you use any JS to accomplish something which a modern browser can accomplish using only CSS?

### Bonus :)

And of course nothing makes an exercise more interesting than a bonus task!
* How would you approach displaying more than one of the coupon "cells" you just implemented on a single page? See SavingStar.com, ibotta.com/rebates, or coupons.com for some live examples.
* How could the layout change if viewed on a small screen (phone) vs. a large screen (desktop, TV)?


To get you started there are 2 key files already committed as a starting point, index.html &amp; style.css, which you can use as a working starting point to add the HTML needed for the coupon's structure and add CSS to control the visual design.
