---
layout: post
title: "Web accessibility for designers pt1- Perceivable"
date: 2021-09-12 10:26:13 +1300
---

As more governments are adopting the WCAG as part of their policies for digital content, it’s becoming more important for designers to understand what this means, and how to build it into their products. The good news is, an accessible website is good for everybody, not just those with disabilities.

Accessibility is something that ideally, is considered from the inception of a digital product. While it is possible and definitely worthwhile to retroactively adopt websites and apps to be more accessible, it is much more difficult and will require extensive rework for both the design and development.

There are some simple practicle steps you can take to get started. The main branches of accessible websites are that they are Perceivable, Operable, Understandable, and Robust. For designers, it is a little more subjective than developers, and in this post I'm going to go over how to make web content more easily perceivable.

## Perceivability

“Make it easier for users to [see and hear content.](https://www.w3.org/WAI/standards-guidelines/wcag/glance/)”  

Designers can contribute to creating a digital experience more perceivable right from the get go. In practical terms, a lot of this comes down to user interface design. 

### Make font sizes larger

It can be tempting to put secondary text such as a date or order numbers in a smaller size than the text around it. It’s also tempting to reduce font size in order to fit more information on a page. This can make it difficult for those with vision difficulties, those with reduced sight but not blind, to use the website. A user may zoom in on a page to read small information, which may make it difficult for them to complete their task if the page elements don’t resize well. For this I like to suggest the squint test. Look at a design and squint your eyes so everything goes a little blurry, and increase the font size until it’s ledgible.

### Check colours for contrast 

If the colours of text or a graphic element do not have enough contrast with their backgrounds, it will be difficult for people to see and understand easily. As well as those with vision difficulties, this is also important for people who are colourblind, which is thought to be as high as 1 in 12 men, and 1 in 200 in women. Good news everybody, WebAIM has a great handy tool for this. Simply put in the hex codes of the colours you’re using and it will show you the contrast values. If the contrast isn’t high enough, there’s not a lot your user can do to try to fix it, or they may not even know there’s something there they can’t see. 

### Don’t rely on icons for meaning

Ever had the problem where you’re on a new website, and trying to find your way around, but nothing has a label? This creates problems for everybody, not just those with visual impairments. Depending on where you’re from, or how old you are, a symbol that denotes one thing for one person may denote something completely different for someone else. Icons should have corresponding labels. It’s also highly suggested to use a useful hover label to further explain the action that will happen when the icon is clicked or tapped. 

### Don't rely on colour alone for meaning

Relying on colour alone to denote meaning is risky business. I see this most commonly on form error states, where the only visual indicator something has gone wrong is that the border has changed from black to red. If there is no other indication something has changed, it can make it very difficult to spot the errors. It's best to pair a colour change with another visual indicator, such as increasing border size, adding a message, or an icon. 

### Have clear page text hierarchy 

Web content should have a clear top heading element, usually a page title. Other headings should each decrease in font size, and be easily distinguishable from regular page text. Headings should be consistent across different pages, so users can easily identify the headings and subheadings, and don’t have to re-learn a new pattern on each page. Don’t be afraid to have a decent amount of breathing room between text elements, this will help people with reading difficulties be able to take in your content. 

That's all my hot tips for increasing perceivability. A lot of these seem simple, and they are, isn't that great? Stay tuned to learn about the next area of accessibility that relates closely to design, making websites more understandable.

There are heaps of resources on the web on accessibility. Check these out to get started:

- [Web Accessibility In Mind](https://webaim.org/)
- [W3 Web Accessibility Inititive](https://www.w3.org/WAI/)
- [Gov.UK Accessibility in Government](https://accessibility.blog.gov.uk/)
