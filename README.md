<p align="center">
  <img width="250" src="https://github.com/SoupyzInc/CanvasDarkMode/blob/main/images/CanvasDarkModeIcon.png" alt="Canvas Dark Mode Logo">
</p>
<p align="center">
  <img src="https://img.shields.io/badge/version-1.3.6-green" alt="Version Badge">
  <img src="https://img.shields.io/github/license/soupyzinc/CanvasDarkMode" alt="MIT License">
  <img src="https://img.shields.io/github/issues-raw/soupyzinc/canvasdarkmode" alt="Open Issues Badge">
  <img src="https://img.shields.io/github/issues-closed-raw/soupyzinc/canvasdarkmode" alt="Closed Issues Badge">
</p>

A Stylus extension to give Canvas/myLearning a dark mode so your retinas don't have to burn out. 

### **Scroll down to see install instructions.**

*I do not have access to the administrative view; any APs/teachers wanting to use this may experience graphical bugs.*

<p align="left">
<img src="https://github.com/SoupyzInc/CanvasDarkMode/blob/main/images/Dashboardv1.1.5.png" alt="alt text" height="300">
</p>

## Installation
1. Install the Stylus browser extension for [Chrome/Brave](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), [Opera](https://addons.opera.com/en-gb/extensions/details/stylus/), or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/).
2. Install the style through [UserCSS](https://raw.githubusercontent.com/SoupyzInc/CanvasDarkMode/main/CanvasDarkMode.user.css) (reccomended) or [userstyles.org](https://userstyles.org/styles/191622/mylearning-dark-mode) (May not be up to date. For me, this website takes 30 mins for anything to load, so updates may be behind)
3. This style looks best when High Contrast UI is disabled.

## Bugs/Suggestions
- If you find a bug that isn't already known, please submit it to the [issue tab](https://github.com/SoupyzInc/CanvasDarkMode/issues) and flag it with the bug tag. Please provide a photo and description clearly showing the bug. *Be careful not to leak any of your or others personal information: such as grades, names, private messages, etc.*
- If you would like to suggest a feature that isn't already suggested, please submit it to the [issue tab](https://github.com/SoupyzInc/CanvasDarkMode/issues) and flag it with the enhancement tag.
- Canvas is used by a lot of schools around the country, some outside the US; and because of that, each school will probably need its own tweaks to function well. Unfortunately, changes made to one school's Canvas may affect another school's Canvas. So feel free to fork this repo and work off of it as a template, I try to put good comments on everything we touch to make it easy to know what's happening.

## Contribution
If you would like to contribute to this repository directly, feel free to open a pull request! Try to generally follow the formatting that is currently being used for the colors and actual code itself.
Code is formatted as so:
```css
/*Description of what is being changed*/
thing-you-are-changing {
  color: var(--text) !important; 
  /*Make sure to flag the element you're changing as important!*/
  /*Otherwise nothing will happen*/
 }
```
Ex:
```css
/*General Text*/
body {
  color: var(--text) !important;
 }
```

and these are the colors we are using (please use these variables):
```css
:root {
    --dark-grey: #1d1e21 !important; /*Darker Background Color*/
    --grey: #23272A !important; /*Normal Bakground Color*/
    --light-grey: #2C2F33 !important; /*Light Color to show that you can interact*/
    --white-grey: #99AAB5 !important; /*Lighter Color to show even more interactivity*/
    --text: #d7d7d7 !important; /*Text Color & Highlights*/
    --sub-text: #a7a7a7 !important; /*Sub Text Color*/
}
```
You can get a feel for what things are colored what colors by looking around the code and Canvas it self.

## Fix List
Stuff I plan to fix next in order of priority (not absolute).

- [Reogranizing the code so that each section of Canvas has its own style sheet.](https://github.com/SoupyzInc/CanvasDarkMode/issues/12)
- [All other known issues.](https://github.com/SoupyzInc/CanvasDarkMode/issues)


<p align="right">
<img src="https://github.com/SoupyzInc/CanvasDarkMode/blob/main/images/CanvasDarkModeQRCode.png" alt="alt text" height="200">
</p>

<!-- -->
