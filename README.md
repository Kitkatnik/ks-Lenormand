# RoboFriends Rolodex

<div align="center">

![screely-1668830784027](https://user-images.githubusercontent.com/5871075/202834090-0f5cd4a5-ceb2-4d75-8e63-46161998ef98.png)

</div>

## Description

### 💼 About this project

- Shuffle the deck of cards
- Pick two cards
- Read the meaning of your cards - [Learn how to read Lenormand Cards here](https://www.alittlesparkofjoy.com/lenormand-cards/)
- Click "Reset: New Reading" to to put your cards back in the deck and re-shuffle


### 🖥 About the tech stack

![HTML5 Badge](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=fff&style=for-the-badge) ![CSS3 Badge](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=fff&style=for-the-badge) ![JavaScript Badge](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000&style=for-the-badge) ![React Badge](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=000&style=for-the-badge) ![Create React App Badge](https://img.shields.io/badge/Create%20React%20App-09D3AC?logo=createreactapp&logoColor=fff&style=for-the-badge) 

Forked from the amazingly talented [@adrianpowers](https://github.com/adrianpowers/lenormand) who originally built this project to practice async and await.


### 🧠 What I learned

- How to use componentDidMount to shuffle the deck of cards when the page loads for the first time
- How to randomize (shuffle) objects in an array using the object's id (card number). 
    - *Initially I was going to have a random number generate when the user picks the card, and just show the card that has the matching number (like most web-based card readers do), instead of assigning each card image a number. I felt like that would take the fun out of shuffling and picking a card though, so I built it with the cards already assigned and truly randomized/shuffled on the page. The only downside to this is that it's easy to cheat by inspecting the code and looking at the ID, which is the number of the card.*
- How to randomize the rotation of the cards and animate the card on hover
- How to use state to store the two cards picked by the user and show it in their hand
- How to hide the chosen card in the deck after it's picked by the user
    - *Thoughts: I realize now I could've used .filter after the card was picked to remove it from the deck, but I actually like that using visibility: hidden leaves a gap in the deck rather than pushing all the cards together.*
- How to disable all card images so that no more than 2 cards can be picked at a time
- How to reset the state after a button press, so that users can start a new reading
- How to make the app mobile responsive, especially with showing the deck of cards and making it easy to pick a card *(there were initially issues with cards being too close together, which made it difficult to select the cards underneath)*
- How to compress & optimize images for loading speed
