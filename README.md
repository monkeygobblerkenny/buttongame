# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Kenny Xia

Time spent: 3 hours spent in total

Link to project: https://glitch.com/edit/#!/sandy-truth-thursday?path=README.md%3A32%3A118

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
- [x] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [x] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![button](https://i.imgur.com/8wjoIk3.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

   The only outside source I used was the website w3schools.com.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

   One challenge I encountered was implementing the guess function. On my first attempt, I did something wrong and kept getting the error where I was
   trying to read the property of a null element. I had to google the error to understand what the problem was, but after figuring it out and takingn a look
   at the example guess solution, I figured out how to fix it.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

   A question about web development would be how people keep their code organized especially on larger projects. On this project that is as simple
   as just 4 buttons, the code was quite long even with 3 different files that held parts of the information.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

I did start this project a bit late, but if I had more time, I would try to do more of the additional features. The timer for the player
s turn seemed the most time consuming and hardest to implement, so I would definitely try to see if I could figure it out. I also think
adding different options the player can choose can make the game more interesting and fun rather than just the same game over and over again with different patterns.

## License

    Copyright Kenny Xia

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
