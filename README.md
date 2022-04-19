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
![](http://g.recordit.co/JXAo18caNu.gif) Player loses (after three chances)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
For additional functionalities like implementing the Math.random() function (to pick a different pattern for each game) and working with arrays, I referred to the JavaScript section of w3schools. I also used a website to obtain the frequencies of music notes. 
https://www.w3schools.com/js/js_random.asp
https://mixbutton.com/mixing-articles/music-note-to-frequency-chart/

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
In terms of the required functionalities, I did not run into any problems since the guide provided very clear step-by-step instructions. The biggest challenge was implementing extra features - since this was my first time coding in JavaScript, I was unfamiliar with the syntax. To overcome this, I read through each section of the instruction document to learn more about the language itself and the purpose of different code snippets/functions. I also referred to the website w3schools, a resource I have used extensively in the past, to learn more about JavaScript. From there, I was able to refer to the existing code and write more on my own; for example, I created a helper function that randomizes the pattern of clues using the Math library. This function is then called in the main startGame() function, enabling a different pattern every game and providing a more interesting user experience. At first, I defined the randomization function under global variables - I quickly realized that the pattern was the same even when I hit the stop/start button and would only change if I refreshed the page. Once I called the function within startGame(), the randomization worked every round as intended. This ensured that the player would get a unique pattern of clues each turn. Additionally, I was not satisfied with my code layout itself, so I created helper functions and added comments to enhance readability. 
Another challenge was the submission of the project - I spent a substantial amount of time exploring and “debugging” the GIF recording tool. Since the allotted time for a GIF is quite small, I had to iterate and eventually came up with a winning formula: I split the recording into three different clips of equal timing (first four clues, next three clues, last clue). I was satisfied with the ending result.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I was able to successfully complete this program using the thorough step-by-step directions. However, without the instructions, I would definitely be more hesitant - I am unsure of which file (script.js, index.html, style.css) to start with. I would like to learn more about the development process, especially for full-stack programming. For example, do programmers start from the front (user) end or the back end, or does it differ for different goals? When tasked with a complex objective, what’s the first step a programmer should do to lay out the different files? I have used wireframing to plan out website design/flow - is this a good strategy to start every project? Additionally, how much open-source software should be referred to for each assignment? I am aware of the benefits of open-source code, but is it an industry standard for programmers to incorporate it often? Furthermore, what portions of program development is individual versus collaborative? Overall, I would like to gain more insight into the day-to-day functions and planning of software developers. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had more time to work on this project, I would focus on enhancing the user interface to make it more “aesthetically” pleasing and sleek. The platform is indeed simple and straightforward for the user to play the game, but I would change or add more elements on the front end. For example, I would add a progress bar (x out of 8 clues) so that the user is aware of how far they are in the game. If I added a feature where the user would have a limited amount to enter their guess each turn, then I would add a graphic of a timer for the user to track how much time they have left to guess. Another interesting feature to implement on the user side would be to track each player’s score and display a “global” average once the player wins/loses, allowing individuals to compare their memory capability to others. However, I understand that such a feature would require a database of sorts to store the player scores, which would significantly escalate the scope of the project. From the back-end perspective, I think that the existing code is satisfactorily condensed and efficient with a good use of functions. 



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/495bc96aac624fd0916645a1c4b935e3)


## License

    Copyright [SHU WEN ONG]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
