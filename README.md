# Project 2 - *Wordle*

Submitted by: **Shaisab Mistry**

**Wordle** is an app that allows users to play the classic Wordle game with customizable settings including word length, number of guesses, themes, and a unique "alien wordle" mode where the target word changes after each guess. 

Time spent: **1** hour spent in total

## Required Features

The following **required** functionality is completed:

- [x] User can change the number of letters per row (the length of the goal word)
- [x] User can change the numbers of rows on the board (how many guesses allowed)
- [x] User can select a new themed set to pull the goal word from
- [x] User can select "alien wordle", causing the goal word to change after each guess

The following **optional** features are implemented:

- [x] App displays a reset button on the top left to reset the game (but make no changes to the settings)


## Video Walkthrough

Here is a reminder on how to embed Loom videos on GitHub. Feel free to remove this reminder once you upload your README. 

[Click](https://www.awesomescreenshot.com/video/37351851?key=0ef7c51273768b27c63ea5b876ffc05a)

## Notes

Describe any challenges encountered while building the app.

While building the Wordle app, I encountered several challenges:

1. Understanding the existing codebase structure and how different components interact with each other, particularly the relationship between BoardController and ViewController.

2. Implementing the settings functionality required careful consideration of type casting and optional handling to safely unwrap dictionary values.

3. The "alien wordle" mode implementation needed special attention to ensure the goal word changes correctly after each guess without affecting other game mechanics.

4. Adding the reset button functionality required understanding of UIKit's navigation bar system and proper method delegation between controllers.

5. Ensuring the board properly resets while maintaining the current settings without changing the goal word required careful state management.

These challenges provided valuable learning experiences in iOS development, particularly in areas of UIKit, delegation patterns, and state management.

## License

    Copyright [2025] [Shaisab Mistry]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
