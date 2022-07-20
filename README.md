# Information About Website
This website lets you play a game of Nim either against a friend, or the computer.
The game was written using React. Each button in the game is rendered as a React function component, and the game itself is 
implemented as a React class component, mainting the state of the game at each turn.
The React and JavaScript code is contained within main.html, inside the div tag with the id of "mainContainer."

# How to run
To view the website, download the contents of the repository to your machine. This includes the main.html file as well as the styles folder and all its contents. Then, the main.html file can be opened using the web browser of your choice.

Alternatively, visit https://htmlpreview.github.io/?https://github.com/matt-marko/nim/blob/main/main.html for a preview of the website. Although this preview uses the pure JavaScript version of the website which is contained within my GitHub repository called "website," it functions identically to the React version contained in this repository.

# Rules
In Nim, two players take turns removing matches set up in five rows.
On their turn, a player can remove any number of matches provided they all come from the same row. You can remove matches by clicking on them. 
The player who is forced to remove the last match loses. After pressing play, choose "Two players" to take turns playing with a friend, or choose "One player" to play against the computer.
