# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Shehab Mohsen**

Time spent: **10** hours spent in total

Link to project: https://glitch.com/edit/#!/valuable-kindly-captain-memory-game

Website: https://valuable-kindly-captain-memory-game.glitch.me/

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

Win game:
![Winning game](https://raw.githubusercontent.com/ShehabMohsen/light-sound-game/main/walkthrough_win_game.gif)
Losing game:
![Losing game](https://raw.githubusercontent.com/ShehabMohsen/light-sound-game/main/walkthrough_lose_game.gif)
Stop and Start buttons:
![Stop and Start buttons](https://raw.githubusercontent.com/ShehabMohsen/light-sound-game/main/walkthrough_start_stop.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here:

  [Math.random()](https://www.w3schools.com/js/js_random.asp)  
  [CSS Color Names List](https://www.w3.org/wiki/CSS/Properties/color/keywords)

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
    The most notable challenge I've faced was learning how to create a randomized pattern. Firstly, I searched online for Math.random() and learned how to use 
    it specifically for this project. I wasn't exactly sure how I would go about using a randomly generated number between 0 (inclusive) and 1 (exclusive)
    to get a value capable of running the sound buttons in the game. Turns out the solution to that was to simply multiply the random number by n (where n is some integer number)
    in order to get a range of numbers from 0 to n-1. The problem with this is that: (1) the labels of the frequencies and buttons range from 1-n and some functions in the project
    are designed around the idea that the buttons are within that range. (2) as it stands, the numbers generated are decimals So rather than readjusting the project to fit the Math.random() function, I simply used the built in ceiling function
    in order to round    
[YOUR ANSWER HERE]


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[ While implementing optional features to the pre-work, I found myself constantly going back and forth to play the game to make sure that everything is working properly as intended. Because of this, one thing I'm curious about is for projects of great magnitude, what kind of tests do developers create to ensure that their work is foolproof? In addition, I have now become increasingly curious about web development. This is because I find it intriguing how can a combination of a few lines of code from JS, HTML, and CSS are able to make their mark on the web, as well as reflect what we see and use in our daily lives.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[For starters, I would learn how to make the page look aesthetically pleasing. With some reading on color theory, I would like to add the options to pick themes (including dark mode) for the start/stop, sound buttons, as well as the background of the page. Another thing I would like to try is to add music notes from various instruments for the sounds. An example of such an instrument is the piano. Additionally, given lots of time and knowledge in music theory, I would like to attempt making an algorithm capable of generating unique melodies to make the page more than just a memory game. Lastly, adding the ability to choose the number of buttons to play with would make the game more accessible. This would make the game enjoyable for a wider audience since everyone can play at their own ability and capacity. I believe these ideas would work great as an extension of the project.]



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Shehab Mohsen]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
