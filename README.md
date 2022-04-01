# Pre-work - *Memory Game*

**Light and Sound Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Emma Lawton**

Time spent: **4.5** hours spent in total

Link to project: (https://glitch.com/edit/#!/fuzzy-rumbling-lion)

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
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!
- [x] Added a button linking to a rules page
- [x] Added option for dark mode

## Video Walkthrough (GIF)
![](https://i.imgur.com/CvNuwgc.gif)
![](https://i.imgur.com/zxy27MJ.gif)
![](https://i.imgur.com/UUjLt3U.gif)
![](https://i.imgur.com/zVHw8px.gif)
![](https://i.imgur.com/FHheU6d.gif)
If you recorded multiple GIFs for all the implemented features, you can add them here:


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[I used multiple websites. I used W3 schools, stack overflow, and glitch's help page.]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[To further build on the website's framework I wanted to add a rules page. I thought this would help inform a user of all of the game's settings especially since many are not obvious. 
For example, the game offers multiple chances or speeds up each round. I really wanted to embed a link to a rule page instead of listing the rules somewhere on the game play page. 
This was a struggle for me as I am relatively inexperienced with html and javascript. I knew that the anchor tag is what linked something to a given url, however, I did not understand how to execute this. I started by trying to go off my own knowledge which did not get me very far. I then turned to reading about anchor tags and how they worked. This was helpful, but it did not fully solve my problem. This is because I was not fully understanding the website’s instructions. This led me to trying to find example code. This took a while as many of the examples posted on help forums had many other elements making it difficult to read through. I finally found a helpful example and noticed that when the websites said to put the URL in the anchor tag it meant in the brackets not between the open and close tags. I also had trouble stylizing buttons and getting them to line up. To try and overcome this problem I changed variables one by one to see how it affected the button. For example, changing the padding changed the distance from the next element. I had an idea of what I wanted the button to look like going in and was by taking the time to understand each component I was mostly able to reach that goal.]


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[While completing this project one of the main problems I ran into was with formatting and designing the website. I struggled to get things to align and make the design more compelling. This has led me to wonder how web developers create more complex formats and make websites look so much more polished. My project looks much more similar to how websites looked when the internet was first introduced than to websites now. This disparity reinforces my question of what tools designers now have available to design such intricate sites. I also was wondering about code reuse. When I was creating my dark mode button I was trying to reuse code from another class and realized I was not able to because that button wasn’t part of that class. I know there are rules to overriding descriptive code in css, but I am not familiar with them. As a result, I am interested in learning more about overriding code to be able to reuse other parts of the code.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had a few more hours to work on this project I would want to stylize my game a little bit more. I would like to work on positioning things better on the page and making it more visually appealing. One way that I started to make it more visually appealing is with the dark mode option. By clicking on the dark mode button it switches the background and font color. I think it would be cool to extend this to the buttons and have them change color as well. The problem with this being time, I could not think of a way to efficiently change all of the color settings for the buttons. If I could figure that out I think it would be cool to have it randomize the colors of the buttons each new game. I would also like to implement a timer. I think that was an interesting suggestion to enhance game play. Additionally, I would spend time looking for a way for the page to automatically refresh after each game. This is because it uses a pseudo random number generator and the seed changes only when the page reloads so if the page doesn't reload the same pattern will be used because the generator will generate the same random numbers. By forcing the page to automatically refresh that would make it much closer to truly random.]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/OFzh2-X-xUM)


## License

    Copyright Emma Lawton

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
