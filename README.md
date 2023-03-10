# Melody Mastermind

Melody Mastermind is a full-stack game testing music knowledge across multiple genres

## Contents
1. [Project Engineer](#projectengineer)
2. [Technologies Used](#techused)
3. Features <br />
	i. [Main Menu](#mainmenufeatures) <br />
	ii. [Settings](#settingsfeatures) <br />
	iii. [In Game](#ingamefeatures) <br />
	iv. [Game Over](#gameoverfeatures) <br />
	v. [Tutorial](#tutorialfeatures) <br />
	vi. [Leaderboard](#leaderboardfeatures) <br />
4. [Installation](#installation)

## Project Engineer <a name="projectengineer"></a>
### Erin Antoine
* https://github.com/erinantoine1
* https://www.linkedin.com/in/erin-antoine/

## Technologies Used <a name="techused"></a>

<img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E"/> <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/Material%20UI-007FFF?style=for-the-badge&logo=mui&logoColor=white"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/Canva-%2300C4CC.svg?&style=for-the-badge&logo=Canva&logoColor=white"/>
<br/>
<img src="https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=Webpack&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=white"/>
<img src="https://img.shields.io/badge/Babel-F9DC3E?style=for-the-badge&logo=babel&logoColor=white"/>
<img src="https://tutorialzine.com/media/2016/08/15_howler.png" width=100 height=28/>
 <img src="https://yggdrasill-7c9.gallerycdn.vsassets.io/extensions/yggdrasill-7c9/axios-snippets/1.0.0/1547542460873/Microsoft.VisualStudio.Services.Icons.Default" width=75 height=28/>
<img src="https://img.shields.io/badge/Ant%20Design-1890FF?style=for-the-badge&logo=antdesign&logoColor=white"/>

## Main Menu <a name="mainmenufeatures"></a>

<img src="https://i.imgur.com/NzgEqnC.png" width=75% height=75%/>
-Navigation
<ul>
	<li><b>New Game:</b> To settings page (to create a new game)</li>
	<li><b>How to Play:</b> To game tutorial</li>
	<li><b>Leaderboard:</b> To scores/times</li>
</ul>

## Settings <a name="settingsfeatures"></a>

<img src="./GIF/settings.gif" width=75% height=75% />
-Users are prompted to choose various settings for their new game <br />
<ul>
	<li><b>Name:</b> Name/nickname/username, limited to 20 characters (special chars/spaces allowed)</li>
	<li><b># of Songs:</b> The total number of songs to be quizzed on in your game (10, 20, 30)</li>
	<li><b>Difficulty:</b> The difficulty of your game (Easy, Medium, Hard)</li>
	<li><b>Genre:</b> The genre of the songs in your game (Random, Pop, Alt/Rock)</li>
</ul>
-Navigation
<ul>
	<li><b>x:</b> To main menu</li>
	<li><b>i:</b> To game tutorial</li>
</ul>

## In Game <a name="ingamefeatures"></a>

<img src="./GIF/gameStart.gif" width=75% height=75%/>
-The left panel contains important info for the user that remains visible/updated throughout the game
<ul>
	<li><b>Current Song #</b></li>
	<li><b>Performance Info:</b> Total game time, points scored, # correct/partially correct/incorrect</li>
	<li><b>Settings Info:</b> Game difficulty, song genre, total # of songs in game</li>
</ul>
-Navigation
<ul>
	<li><b>How to Play:</b> To game tutorial</li>
	<li><b>Leaderboard:</b> To scores/times</li>
	<li><b>Main Menu:</b> To main menu</li>
</ul>
-Animations in the center of the screen draw attention to where the user will directly interact with game <br /><br />
<img src="./GIF/guesses.gif" width=75% height=75%/>
 -Making A Guess
 <ul>
        <li>Type the song title and/or artist, then click 'Guess!' button or "Enter" key to submit guess</li>
        <li><b>Spelling counts, but punctuation/capitalization do not</b></li>
        <li><b>Unlimited guesses for each song</b> (until 'Give Up' button is pressed, or both song and artist correct)</li>
 </ul>
  -Scoring <b>(Easy Difficulty)</b>
        <ul>
          <li>Two points for correct song and artist</li>
          <li>One point for having either song title OR artist</li>
          <li>Zero points if neither are correct</li>
        </ul>
  -Scoring <b>(Medium Difficulty)</b>
        <ul>
          <li>Two points for correct song and artist</li>
          <li>Zero points if neither are correct</li>
        </ul>
  -Scoring <b>(Hard Difficulty)</b>
        <ul>
          <li>Two points for correct song and artist</li>
          <li>Zero points if neither are correct</li>
          <li>Limited to 3 lives (will be shown in left sidebar)</li>
          <li>Score is not added to leaderboard if you run out of lives</li>
        </ul>

## Game Over <a name="gameoverfeatures"></a>

<img src="./GIF/gameOver.png" width=75% height=75%/>
-A performance summary is provided once game has ended
        <ul>
          <li>Summary includes average time per song calculation</li>
	  <li>Info about final song also provided</li>
        </ul>
-Navigation
<ul>
	<li><b>Leaderboard:</b> To scores/times (will now include your score!)</li>
	<li><b>Main Menu:</b> To main menu</li>
</ul>

## Tutorial <a name="tutorialfeatures"></a>

<img src="./GIF/tutorial.gif" width=75% height=75%/>
-Quick tutorial that simulates layout of the game while explaining step-by-step
        <ul>
          <li>Press the "Next" button to progress through the tutorial</li>
	  <li>Relevant elements of the game will be highlighted in each step</li>
        </ul>

## Leaderboard <a name="leaderboardfeatures"></a>

<img src="https://i.imgur.com/aZnUvgN.png" width=75% height=75%/>
-Scores can be searched be genre, difficulty, or # of songs
        <ul>
		<li>Click on the corresponding dropdown to change the scores displayed</li>
		<li>To reset search criteria, press the "Reset" button</li>
        </ul>
-Navigation
<ul>
	<li><b>x:</b> To main menu</li>
	<li><b>i:</b> To game tutorial</li>
</ul>

## Installation <a name="installation"></a>
1. From command line, navigate to desired directory and enter the following command to download the app:

	`git clone https://github.com/erinantoine1/Melody-Mastermind.git`
	
2. Navigate to the newly downloaded folder with the following command: 

	`cd 'Melody-Mastermind'`

3. Install dependencies using the following command:

	`npm install`

4. Start the server by entering into command line:

	`npm start`

5. Open project in web browser at:

	`http://localhost:3000`
