# Rock, Paper, Scissors!
"Rock, Paper, Scissors!" is a website for people who want to play the famous Rock, Paper, Scissors game against a computer.

The purpose of "Rock, Paper, Scissors!" is to be a short distraction from the daily lives of their users.
This is achieved by presenting a very easy to follow webpage with an attractive design.

Visit the deployed page here: [https://85rhrl.github.io/PP2/index.html](https://85rhrl.github.io/PP2/index.html)

![Rock, Paper, Scissors! in different screen sizes](docs/images/amiresponsive.png)

## Design
A minimalistic but attractive design was chosen, there is no need for a substancial layout change based on the device where it is viewed.
- __Wireframes__
    - Wireframe was generated by hand to show the planned layout.
    
    Homepage
    ![Homepage](docs/images/wireframe-home.png)

- __Colors__
    - The colors used for "Rock, Paper, Scissors!" were inspired by the 1980s with flashy colors that are easy on the eyes. The Background color of the "Ties" box is the combination of the background colors of Player and CPU and is considered an Easter Egg.

## Features

### Existing Features

- __Header__
    - At the top of the page the user will find the header of the page "Rock, Paper, Scissors!" next to the hand gesture for scissors, this header also works as a link to refresh the webpage if the user wants to reset the scores.

    ![Header](docs/images/01-header.png)

- __Selection Area__
    - To start playing "Rock, Paper, Scissors!" the user must chose either Rock, Paper or Scissors, this can be done by clicking either of the options which are presented as images of the Rock, Paper or Scissors hand gestures respectively.
    - Under every option there is a text describing the hand gesture for those who haven't played the game.

    ![Selection Area](docs/images/02-choices.png)

- __Results Area__
    - The Results Area is located under the Selection Area and displays the option chosen by the user and CPU.
    - At the game start the Results Area displays a placeholder image showing the 3 possible options and all scores sets to zero.

    ![Game Start](docs/images/03-results-start.png)

    - As the game progresses the Results Area displays the latest option chosen by the user and CPU, their respectives scores, the number of Ties and the result of the latest game.

    ![Game End](docs/images/04-results-end.png)