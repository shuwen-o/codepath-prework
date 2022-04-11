# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **SHU WEN ONG**

Time spent: **2** hours spent in total

Link to project: https://glitch.com/edit/#!/held-continuous-era

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/EM9tF3MNGp.gif) Part 1: First four clues
![](http://g.recordit.co/nTt8YeYplX.gif) Part 2: Next three clues
![](http://g.recordit.co/5kIA823mkS.gif) Part 3: Last clue, player wins
![](http://g.recordit.co/YYTl65SDZk.gif) Player loses (after three chances)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
For additional functionalities like implementing the Math.random() function (to pick a different pattern for each game) and working with arrays, I referred to the JavaScript section of w3schools. I also used a website to obtain the frequencies of music notes. 
https://www.w3schools.com/js/js_random.asp
https://mixbutton.com/mixing-articles/music-note-to-frequency-chart/

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
In terms of the required functionalities under the step-by-step instructions, I did not run into any problems since the guide was very clear and specific. The biggest challenge was implementing extra features - since this is my first time coding in JavaScript, I was unfamiliar with the syntax and functionalities. To overcome this, I read through each section on the Prework instruction document to learn more about the language itself and the purpose of different code snippets, such as the functions under script.js. From there, I was able to refer to the existing code and write more on my own; for example, I created a helper function that randomizes a pattern of clues using the Math library. This function is then called in the main startGame() function, enabling a different pattern every game and providing a more interesting user experience. I referred to the website w3schools, which I have used for Python and SQL, to learn more about JavaScript. at first, defined randomization under global variables - realized that pattern was the same. then put under startgame function to change it up - created function to simplify readibility
Another challenge was during the submission itself - I spent quite a while figuring out and "debugging" my GIF recorded tool. Since the . Iterations (split into two, equal timing)

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[YOUR ANSWER HERE]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[YOUR ANSWER HERE] 



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
