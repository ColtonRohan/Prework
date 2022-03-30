# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Colton Rohan

Time spent: 10 hours spent in total

Link to project: https://glitch.com/edit/#!/light-lightning-domain?path=PreWork%2Findex.html%3A1%3A0  I initially had some issues with glitch but learned how to use its softwate better and got my program to upload 

## Required Functionality

The following **required** functionality is complete:

* [*] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [*] "Start" button toggles between "Start" and "Stop" when clicked. 
* [*] Game buttons each light up and play a sound when clicked. 
* [*] Computer plays back sequence of clues including sound and visual cue for each button
* [*] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [*] User wins the game after guessing a complete pattern
* [*] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [*] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [*] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [*] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [*] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
(https://recordit.co/qcRFiecTW1)
(https://recordit.co/Go5xWhBxJ9)
(https://recordit.co/GiPUOIkCao)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
one of the biggest helpers i used when creating this app was the JQuery framework. Also when working through this asignment i ran into some topics i hadnt used in a while and had to refresh on them using websites like www.w3schools.com , www.stackoverflow.com , and www.geeksforgeeks.org

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
one of the best and most important steps with computer programing is debugging, creating this program made me go over my code and debug it more then once. when i created the game i didnt realize there was step by step help in the directions, i watched the youtube video and used the information i knew to try and rebuild what i saw in the video. Doing this i ran into a fair bit of issues i had to overcome alone, one of the biggest ones being the colors of my buttons instead of playing one after the other they would all display at one time. the way i solved this was to include an if statement inside my nextsequence function that increments the index of my game_RNG while flashing the color each iteration of the function. Another big issue i was having was with the sounds, when the colors were flashing through each cycle the audio was not aligned with the flash. My sound is declared and played through a playsound function and was being called in my main nextsequence function, i found out after creating the if statement for the colors of my buttons that if i include the playsound call above the incrementation that the sound would align perfectly with my color sequence.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
after completing my submission, it got me thinking about the different ways i could have done my project to complete the same task. the different types of function implementation in more efficient ways trying to cut down on website latency. this might be a small game now but if it were to grow into something much larger im afraid my functions would not be able to keep up and would begin to lag the browser.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
one of the things i would do if i had more time would be making the game go on forever instead of ending at 8 turns and have a level counter to see how far the user can go in a uncapped game. another thing i would of dont to work on this app would be looking into function refactoring in an attempt to make sure they dont conflict with each other. one of the last things i would try to implement is IOS compatibility so the game could be easily played on mobile devices.



## Interview Recording URL Link

[My 5-minute Interview Recording] https://www.youtube.com/watch?v=j-n8pujnX3g i uploaded my video to an unlisted youtube video please let me know if there is an issue with the link i used


## License

    Copyright [Colton Rohan]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
