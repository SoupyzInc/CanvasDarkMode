# Contributing Guidelines
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
