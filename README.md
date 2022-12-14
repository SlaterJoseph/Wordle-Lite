# Android Project 1 - *Wordle-Lite*

Submitted by: **Joseph Slater**

*Wordle-Lite* is an android app that recreates a simple version of the popular word game [Wordle](https://www.nytimes.com/games/wordle/index.html). 

Time spent: **17** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] **User has 3 chances to guess a random 4 letter word**
- [x] **After 3 guesses, user should no longer be able to submit another guess**
- [x] **After each guess, user sees the "correctness" of the guess**
- [x] **After all guesses are taken, user can see the target word displayed**

The following **optional** features are implemented:

- [ ] User can toggle betweeen different word lists
- [x] User can see the 'correctness' of their guess through colors on the word 
- [ ] User sees a visual change after guessing the correct word
- [x] User can tap a 'Reset' button to get a new word and clear previous guesses
- [x] User will get an error message if they input an invalid guess
- [x] User can see a 'streak' record of how many words they've guessed correctly.

The following **additional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='Wordle.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with Licecap  
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

I encountered a few challenegs creating this app. First I wanted each letter to be its own square, so figuring out a system to cleanly edit all squares took some time. Second, setting up the button to respond to both submit and reset took a while. Finally building components like the border for the tiles and the different tiles for the different outcomes took a while.

I planned on adding a feauture to toggle between light and dark modes, but I ran into many issues so I scrapped it for now. I plan to work on this later and implemenet it at that time.

## License

    Copyright [2022] [Joseph Slater]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
