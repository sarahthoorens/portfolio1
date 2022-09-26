# portfolio1

Deployment date: 9/26/22</br>
Deployed address: https://sarahthoorens.github.io/portfolio1/</br>
Topics applied: Flexbox, image overlays, responsive code, HTML page layout with containers</br>
Project goal: Recreate a pre-existing portfolio page using my personal information

## Project Description

This was an HTML and CSS coding challenge to recreate a portfolio page without existing code.  The information provided for this challenge is as follows:

### User Story

```
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position
```
### Acceptance Criteria

```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```

## Project review

#### Full-size version

<img src="/assets/images/fullsize.png" alt="full-size page rendering">

#### Responsive version

<img src="/assets/images/smallsize.png" alt="small-size page rendering">

**Challenges**

I'm still learning how to approach HTML and CSS projects like this, ie those with a specified layout to match. I realized I started this project without responsiveness in mind, and when it came time to address that part of the acceptance criteria, I was limited with how I could make those modifications with my existing code. In the end, I had to scrap my nav links when reaching 568px to accomodate for my lack of foresight.

I also struggled with how to organize my containers that allowed automatic size adjustments; I eventually settled on using percentages to help with width and height adjustments, although I'm still unsure if that was the best method to apply. 

**Lessons learned**

I see some area of improvement by incorporating a very specific wireframing to map my containers, including wireframing responsive versions to assist with planning out HTML when resized. It's clear I need more practice with manipulating flexboxes and organizing HTML containers. These are areas of focus for me going forward while learning CSS. 