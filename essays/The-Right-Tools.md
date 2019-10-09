---
layout: essay
type: essay
title: The Right Tools
# All dates must be YYYY-MM-DD format!
date: 2019-10-08
labels:
  - Software Engineering
  - Semantic UI
  - HTML
---
## Initial Anxiety
When I found out we would be covering html in ICS 314, I could not help but feel intimidated. In ICS 101, I learned basic HTML that allowed me to create sites on the same level as those made in the early 90’s. I was concerned about the amount of learning that would need to be done before I can reach the level of “modern website design”. I was unaware of the power that UI Frameworks had, I thought it would take me years of experimenting with CSS and hundreds of projects to figure out how to implement my vision of website through trial and error. Little did I know that I would love html development once I was exposed to the right tool (Semantic UI).

## What is a UI Framework?
Let us start by covering what exactly a UI framework is: for our purposes, we can define a UI framework as a package of files and standardized code that allow a user to develop an html website with greater ease.  It’s not uncommon for a beginner html programmer (such as myself) to have a clear vision of what they are trying to accomplish, but not have the necessary knowledge to implement it. A UI framework such as Semantic UI provides many pre-written modules and elements that are easy to implement, from buttons and icon elements, to organizational tools like menus, tables and grids. These elements may have proven daunting to create on your own, but by using the power provided within the Semantic UI library even a novice html coder can create modern looking websites.

## Practical Uses
As previously mentioned, Semantic UI simplifies the UI design process, cutting down the amount of code needed to create specific layouts or realize your vision for a website. For example, creating 3 columns of text would require making 3 separate div containers and playing around with widths and heights in the style sheet to achieve the desired effect, whereas we can simply use Semantic UI to write the following:

```html
<div class=”ui three column grid container”>
<div class=”ui column”></div>
<div class=”ui column”></div>
<div class=”ui column”></div>
</div>
```

## Ease of Use
Semantic UI is very aptly named because most modules or elements can be used simply by writing out semantically what you need in the class line. If I needed a large button for my website, instead of going into the CSS, setting an ID for that button and then setting the size to a pixel value, I can simply say:

```html
<a class=”ui large button”>
```

I find myself needing to refer to the Semantic UI documentation less and less as I do more practice WODS and sample projects, sometimes I elect to just try element names out in the class field before trying to search the documentation, simply because they are named so well and I can usually “guess” the correct syntax.

While some may say learning a UI Framework is like learning a whole new programming language, I disagree and would argue that it’s like going from Windows 7 to Windows 10. At first it’s rather jarring needing to switch to new methods and get used a different environment, but all the new functionalities more than make up for the initial learning required.

## Conclusion
Semantic UI is an amazing tool and I look forward to working with it more this semester, in my previous experiences I did not like html as I didn’t know how to actualize the image I had in my head due to my lack of skills. But now with Semantic UI, I feel like my horizons have definitely been broadened and a whole new world of html programming has opened up to me. It’s like my whole life I’ve been using a screwdriver, and someone just introduced me to the electric drill, while they both get the job done, one makes it significantly easier to get it done the way you intend. 
