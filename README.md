# Module2-ProfessionalPortfolio
This is the UCF Module 2 Professional Portfolio challenge. 
This website contains some information about myself and will serve as a place for me to showcase my future work.
It also contains multiple ways to contact me.

## Live Link
https://hfrancis7.github.io/Module2-ProfessionalPortfolio/

## User Story
```
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position
```

## Acceptance Criteria
```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
*WHEN I am presented with the developer's first application
*THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```
*Images in the work section currently all same size

## Issues / Future Changes
- Sections of my style.css are directly targetting tags, which created multiple unexpected behaviors and overrides of the style sheet. On this and future projects, will try not to html tags directly in favor of using classes and IDs for easier to read/write UI
  - Border line on "About Me", "Work", and "Contact Me" will line up
  - Work images will flex properly, with the size of the first image being larger than the others (likely 50% larger) in a grid layout
