---
layout: post
title: "Web accessibility for designers - Understandable"
date: 2021-09-19 10:26:13 +1300
---

In my [last post](https://lauramunro.nz/2021/09/11/web-accessibility-for-designers-perceivable.html) we looked at how to make websites more perceivable. The next aspect of web accessibility that relates closely to design is making them more understandable. 

## Understandable

“Make text readable and understandable.”  
“Make content appear and operate in predictable ways.”  
“Help users avoid and correct mistakes.”  
From [WCAG at a glance](https://www.w3.org/WAI/standards-guidelines/wcag/glance/)

This is where user experience and user interface design cross paths. These aspects of accessibility relate more to how the user interprets what a website is trying to say or asking them to do. Having a website that is easy to understand helps people with learning and reading difficulties like dyslexia, as well as those for which English is a second language. But just like I mentioned in my last post on perceivability, making a website more easily understandable helps everyone on the internet.

### Write in plain terms

Not every team has dedicated content and copywriters, and it’s often left up to the designers to write copy, espcially micro-copy like form labels and help text. If you're in this position there's a few things that are worth remembering. Avoid using jargon, and when introducing a term or acronym for the first time, explain what it means. There's also a trend I've seen, most often I’ve seen this on menus, where a normal label is replaced with something more fancy or on-brand, which makes it near impossible to find what you're looking for the first time. 

#### Not helpful:

- Emporium
- Our Specialities
- Pantry

#### Helpful:

- Store
- Shop

While it might be on brand, if someone can’t find your store, they can’t buy what you’re selling. When in doubt, remember the age-old design principle, Keep It Simple Stupid (KISS). 

### Be up front with field requirements

Ever tried to create a password for a website, only to be given an error message, which changes on each attempt? It can be a frustrating experience. This comes down to helping users avoid mistakes. If the design up front lets the user know what the password requirements are, they can avoid triggering the error message at all. Relying on error messaging to convey requirements is a dark pattern that should be avoided. In user experience design we are often trying to limit the information shown to the user to help make their experience easy, but if we aren’t giving them enough information to succeed on their first try, it isn’t enough information. 

#### Not helpful:

- Choose a password
- Make it a strong one

#### Helpful:

- Choose a password
- Must have upper and lowercase characters, and a number or symbol

### Have specific and helpful error messaging 

If a website needs to show an error, it should guide the user to understand exactly what it is they need to do to correct the problem. Don’t rely on colour alone to signify an error state, if someone is colour blind it may not look any different to them. It’s best to have a short message that is phrased as how to solve the problem. 

#### Not helpful:

- Incorrect date


#### Helpful:

- Date must be before today

### Button behaviour should be predictable 

Buttons with the same label should behave in the same way, no matter what area of a site they are on. If a button that says "back" on one page goes back to the previous page in one area, but on another area goes back to the homepage no matter where you came from, that can create a negative user experience when the site doesn't behave in the way people expect. 

One area which can be particularly important to get right in this aspect is multi-page forms or steppers. In these situations, it should be very obvious when the user is on the last step and about to send the form. It would be very confusing to the user if every step in the form the primary button said "next" and the user hits "next" expecting another page, but the form has been sent and now there's no chance to go back.

## In Summary 

Web accessibility for designers is a lot more subjective than the technical requirements for developers, but that doesn’t make it less worthwhile or valuable. Making a website more understandable is good for all users, and can have a measurable impact on your bottom line as well. Taking the guess work out of navigating and interacting with your website will drastically improve the user experience. Having an understanding of what types of things to consider when it comes to improving accessibility is half the battle, otherwise we don’t know what we don’t know. 

There are heaps of resources on the web on accessibility. Check these out to get started:

- [Web Accessibility In Mind](https://webaim.org/)
- [W3 Web Accessibility Inititive](https://www.w3.org/WAI/)
- [Gov.UK Accessibility in Government](https://accessibility.blog.gov.uk/)
