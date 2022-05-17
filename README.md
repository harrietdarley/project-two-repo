# An Ultimate General Knowledge Quiz - Project Two

## About
This is my creation of a General Knowledge quiz. The aim of the game is for the player to attempt to answer the questions 
correctly about a variety of subjects in order to get a high score. 

### Why this project?
I built this game for an Interactive Frontend Development project. The purpose was to create a game using HTML, CSS & JavaScript,
however mainly focusing on JavaScript to develop functionality. 
I chose to build a quiz rather than any other game because it enabled me to improve areas of JavaScript that I didn't understand 
such as processing data. The project has definitely helped me learn a lot and strengthen my knowledge of JavaScript.

## UX

### User Stories 
As a player I want to:
- Be able to be able to read how to play, before and whilst playing the game
- Be able to listen to music and turn if off, before and whilst playing the game.
- Have the choice of difficulty
  - Playing on 'easy' mode means one has more time (one minute) to answer the question. 
  - Playing on 'hard' mode means one has less time (30 seconds) to answer the question.
- Be able to return home and stop the game. 
- Be able to pause and play the game. 
- Have four options to pick from. 
- After choosing an answer, be told which answer is correct by the answer turning green & be told which answer is incorrect by the answer turning red. 
- Move onto the next question if I can't answer. 
- Be told my score at the end of the game. 

### Research
Before starting to design my project, I looked at lots of versions of quizes to give me a good understanding of other designs 
and the range of functions they were using, helping me to start plan my game. 

One of my main focuses was to create a highly responsive and intuitive user interface to ensure a seamless experience for users. 

### Style Rationale 
The majority of quizes I looked at online had quite basic designs and layouts, and all the questions were on one 
page, therefore I decided that my game would be more responsive and look cleaner if each question had an individual page.

I chose a bright colour scheme, a basic background and engaging and creative fonts to attract users to play the game and
to make the game more enjoyable. 

### Wireframes 
I created my designs using Abode XD, I displayed two different aspects; one from a laptop and one from a phone, to ensure my webpage would be responsive from a variety of technology.

![iPhone 12, 12 Pro – 1](https://user-images.githubusercontent.com/82885562/168827984-a8f31404-fa0c-4bc9-9b0c-407a82c14bcb.jpg)
![Artboard – 1](https://user-images.githubusercontent.com/82885562/168828082-669a69ee-bfcf-47c2-80aa-30ac77dcc3e9.jpg)
![Artboard – 2](https://user-images.githubusercontent.com/82885562/168828137-c52019ca-151d-442c-9291-e55b9efd4ded.jpg)
![iPhone XR, XS Max, 11 – 1](https://user-images.githubusercontent.com/82885562/168828255-2fc7c840-cb8b-4ac3-afd3-b5e0d5f60c83.jpg)
![iPhone XR, XS Max, 11 – 2](https://user-images.githubusercontent.com/82885562/168828288-2fbca802-eb1d-4d67-9c35-02c5466d470a.jpg)
![iPhone X, XS, 11 Pro – 1](https://user-images.githubusercontent.com/82885562/168828315-0e34c78f-67fd-4de5-8147-99e89463a584.jpg)

## Features

### Functionality
- The user is required to choose whether to turn volume on or off. 
- To understand how to play the game, the user should click on the button and read instructions. 
- The user should then choose whether to play on 'easy' (they need to answer the question in one minute) or 'hard' mode ((they need to answer the question in 30 seconds). 
- When the game starts, the user should click on the answer they believe is correct before the timer runs out. They should not be able to move onto the next question if they haven't chosen an answer and the timer is running.
- When their answer has been chosen, the button will either turn green or red depending on whether the answer is correct or incorrect. If it is incorrect then the correct button will turn green as well. 
- The user is then required to click on the next button to move onto the next question. 
- If the user fails to answer the question in time, the game will automatically move onto the next question. 
- Whilst the game is being played, the user can turn the volume on and off and play and pause the game. 
- They can also read the instructions which explain how to play and decide whether to end the game, when the modal appear the timer will be paused and when they return to the game it will continue.
- When the user gets to the end of the game their results will be shown and then they can return to the home page by clicking on the home button. 

### Existing Features
#### Home Page
- **Title** - Main title 'Ultimate' fades in. 
- **Volume Button** - Users can turn on and off the music by clicking the volume icon. The icon will change depending on the sound.
- **Play Easy Mode** - By clicking on the Play Easy button the user is choosing the easier way to play the game as well as starting the game. The user will have 1 minute to answer each question. 
- **Play Hard Mode** - By clicking on the Play Hard button the user is choosing the harder way to play the game as well as starting the game. The user will have 30 seconds to answer each question. 
- **'How to Play' Button** - When the user clicks the 'How to Play' Button, a modal will appear 

#### Game Page

