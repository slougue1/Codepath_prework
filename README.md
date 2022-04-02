# Pre-work - **Memory Game**

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Sakina Lougue**

Time spent: 4 hours spent in total

Link to project: https://glitch.com/edit/#!/shard-familiar-close?path=README.md%3A1%3A0

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/GwbYsNRDRT.gif)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
Based on the guidance and instructions provided, I was able to have a stronger understanding of HTML, CSS, and JavaScript. Therefore, I did not use any outside resources to successfully create this project.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
What helped me in completing the project was having a basic yet strong and useful understanding of JavaScript. However, I slightly encountered some difficulties in understanding the content of the playSingleClue function. I understood the purpose of the function is to set a time in which the sound of the button will play, but not quite the content. However, thanks to the expanded box titled setTime reference, I was able not only to have a deeper understanding of the function, but also to understand better the inner fucntions, lightButton, playTone, and setTime function . Thus, I made sure to read very carefully the instructions including every expended box not to get stuck in building the Memory game.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
  The first question I have is how to build a website? I have always wondered how can one go from writing a Java, or C program to building a website with sound, color, and videos... Then, I was introduced to JavaScript, and I had a better understanding of how JavaScript libraries and codes take care of the dynamic behavior and the designed interactive sites in a website. However, some questions are still unclear to me: where does one start? is a website builder needed? if yes, which ones are the most recommended.
  Another question I have is with regards to web design. I learned from this project that CSS steps in more when it comes to colors, fonts, sizes... However, is the only language used in designing a website? if not, what are the others?
  Lastly, what are the keys essential in building a website?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
    If I had more time to work on this project, I would have changed the tries every time the start button is pressed. For instance on every try, the current game start with 1 blue, 2 blues, 2 blues + 1 yellow... I would have made the tries different and randomly chosen by the computer. If on the first try, the pattern is 1 green, 2 greens, 3 greens... then an example of the second try's pattern will be 1 yellow, 1 yellow + 1 blue, 1 yellow + 2 blues... 
    Also, the number of patterns would be randomly chosen between 4 and 8. Therefore, the user can win after 4, 5, 6, 7, or 8 patterns.
    In addition, I would add a feature giving a unique second chance to the users. For example, if the button to be pressed is yellow, and the user presses green, then all the buttons would light up, vibrate and allow the user to press the correct button. 
    Lastly, I would have added a for loop in the guess function asking users (who won or lost) if they would like to play another round. If the user presses "Yes", the stop button remains the same, and a new pattern is displayed. However, if the user presses "No", the stop button automatically changes to the start button



## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/nF5z91oWuBw)


## License

    Copyright [Sakina Lougue]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
