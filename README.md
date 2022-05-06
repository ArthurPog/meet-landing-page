# My ninth project and solution to the meet landing page challenge over at [Frontend Mentor](https://www.frontendmentor.io/challenges)

## Table of contents
- [The challenge](#the-challenge)
- [Goals](#goals)
- [Assignment design](#this-was-the-design)
- [My solution with live page link](#this-is-my-solution)
- [What I learned](#what-i-learned)
- [Tools used](#tools-used)


## The challenge

My challenge is to build out this landing page and get it looking as close to the design as possible.

I can use any tools I like to help me complete the challenge. So if I've got something I'd like to practice, I can feel free to give it a go.

My users should be able to:

View the optimal layout depending on their device's screen size
See hover states for interactive elements

## Goals

My goals for this project were, apart from the increased difficulty when compared to the projects that I've tackled before, to:

- [x] Use a mobile first approach for the first time
- [x] Do cleaner coding
- [x] Comment my code
- [x] Use CSS Variables
- [x] Use CSS grid for the first time

I used this opportunity to further practice clean coding, CSS grids, CSS variables and most importantly a mobile first approach meaning I started coding the CSS by coding the style for the mobile version first then moving up to the desktop design with conditional CSS.

## This was the design

![](./assets/desktop-design.png)

## This is my solution

[Click here to see the live page](https://arthurpog.github.io/meet-landing-page/)

![](./assets/my-solution.png)

## <a name="#what-i-learned"></a>What I learned

Apart from using `display: grid;` for the first time and playing with it a little bit to mainly centre my page and display some illustrative images, I designed my first mobile-first approach website and realized that this is the more intuitive way to build sites, because it's so much more simpler than a desktop first approach.

I learned that I can put a negative padding on elements to make them overflow when at 100% width.

Courtesy of [Vanza Setia](https://github.com/vanzasetia) and his advice I learned to use `em` units in media queries instead of pixels (such as @media (min-width: 64em) because it is simply the more reliable way to set these conditions across all devices as per [this article](https://zellwk.com/blog/media-query-units/).

Also courtesy of [Vanza Setia](https://github.com/vanzasetia) and his code I learned that there are such things as `::before` and `::after` pseudo-elements and I'm looking forward to using them in my future project.

And one last thing regarding learning from the best. Vanza's comment lead me to read up more in-depth regarding the use of anchors and buttons and I realized the destinction between them better. Buttons should be used when carrying out a function within the site, like an in-page calculator, basically things using JavaScript and anchors should be used to navigate around and they often lead to downloads, external links and so on.

## Tools used

- **VS Code** with a few extensions:
  - **CSS Peek** - To immediately see what certain variables that I set mean and their values by holding CRTL + hovering over the value
  - **HTML to CSS Autocompletion** - Quickly autocomplete classes and ID names in CSS based on what I created in HTML
  - **Live Preview** - Right-clicking the index.html offers to view a live and constantly auto-updated version of the web-page for a quick live view of one's work
- **Greenshot** - A fantastic little open-source tool that is like a screenshot on steroids. After pressing PrtScrn it lets one exactly measure the width and height of an element on a screen basically making it very easy to calculate how big certain margins, paddings, containers and font-sizes are in a design without having access to a wire-frame.



- **Microsoft PowerToys** - A nifty little program from Microsoft adding a *plethora* of UI functionality to Windows. What I use most for coding is CTRL+WIN+C it brings up a colour picker, and when I hover over something or click something it shows me the HEX, RGB, HSL and CMYK values of the colour that can instantly be copied to the clipboard and in addition to this it keeps a history of all the colours picked. Amazing!
