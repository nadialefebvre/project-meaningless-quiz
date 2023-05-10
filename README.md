# Project Meaningless Quiz

Weekly project for Technigo's bootcamp, week 13: build a quiz (April 2022)

## Tech stack

- JavaScript
- React
- Redux
- HTML
- CSS
- Styled components

## The problem

This week's project was a group project where we had to build a multiple choice quiz using Redux.

We set up the structure and the needed components in a Jamboard first. We aimed for styled components to practice them more.

In the end, we didn't even create branches for the repo because we worked all together for the whole project. We used useSelector to access the Redux store. We added an image to each question object to make our quiz look richer. We added validation to the buttons so the user has to choose an option, and can't choose more than one or change their choice. When the user chooses an option, they can see if it was right or wrong with the border changing its color. If wrong, the real answer is revealed only in the summary. The summary also contains the score along with a grade (letter), which depends on the score. We used React Router so the start page is on / path and the quiz is on /quiz path.

If we had more time, we would have implemented a progress bar, but we are really proud of what we achieved: the code, but also the styling and the content.

## View it live

Project deployed here: [Meaningless Quiz](https://meaningless-quiz.netlify.app/)

Group project: Joanna Ringqvist, Laura Sjölander, Mauricio Urra, Nadia Lefebvre, Rijad Ilijazagic

<div align="center">
  <img src="screenshot.jpg" />
</div>
