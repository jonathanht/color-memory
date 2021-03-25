# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Jonathan Thai**

Time spent: **3** hours spent in total

Link to project: https://glitch.com/edit/#!/glimmer-cooked-honeysuckle

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

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!
- [x] Added scorekeeping 
## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](your-link-here)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
 https://www.w3schools.com/cssref/css_colors.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

One challenge that I faced was implementing the decreasing duration for sound cues as the player progressed through the game. In order to properly address this feature I had to keep the value of progress in mind. I eventually discovered an optimal timing interval that was not too difficult to play with but not too easy through play-testing the game myself a couple of times. I implemented this interval by adding an extra statement to the game-logic loop, decrementing the duration of the sound cue by a fixed amount after every iteration of the user passing a level. I also had trouble with finding colors I wanted to use for my CSS code, and to overcome that I referred to w3school's CSS reference page, which helped me a lot. Having the color previews in front of me saved me a lot of time as I didn't have to manually test out every single color and wait for it to update on my project to see what it looked like. I have been on and have used W3School before but had no idea that they have so many references for web-dev related technologies. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After completing this submission I would say that it helped garnered my interest for front-end web development. How does CSS and HTML translate into the fully developed user interfaces that webdevs create for their websites? I am very interested in learning more about what goes into the design of vibrant ui spaces and how I can go about generating designs like that for my own personal websites or projects. This submission has also allowed me to have even more respect for front end developers, who have to take both the aesthetics of the interface and its functionality into account when designing. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had more time to work on this project, I would dedicate my time to adding a couple additional features I had in mind. One thing I would attempt to do is implement a high-score system of sorts, which stores the user's past scores between each instance of playing the game and displays them at the end screen. A difficulty setting would be fun to create as well, with higher difficulties consisting of "levels" with more buttons. I was also thinking of increasing the difficulty by making the tones less discernible from one another, which would also test how accurate the player's hearing is. 


## License

    Copyright Jonathan Thai

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
