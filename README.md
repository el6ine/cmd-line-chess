# cmd-line-chess

This project was created by Elaine Zhao, Peiran Tao and Martin Tang as part of coursework at the University of Waterloo. 

In line with Academic Integrity Policies, source code for this project cannot be publicly posted.

The following is a demo of how this chess game would work:

### Game Setup
<img width="1437" alt="Screen Shot 2024-01-11 at 4 09 39 PM" src="https://github.com/el6ine/cmd-line-chess/assets/110880989/e031e527-06fc-4ad6-a24e-28c0b5b70113">
The game is a program written in C++ with graphics generated with Xwindow.

Commands are entered through terminal. The command game followed by arguments specifying the type of player (human or one of three computer players), after which a game starts. The chessboard is displayed through the graphics display as well as outputted to the terminal in a grid.

Example of starting a game with two human players:
<img width="1440" alt="game human human" src="https://github.com/el6ine/cmd-line-chess/assets/110880989/ca71ed9c-3637-433e-a4d2-7452d07e4888">


Example of starting a game with a computer player:
<img width="1440" alt="chess comp:human start" src="https://github.com/el6ine/cmd-line-chess/assets/110880989/2ea57bce-34d5-4319-821c-8c48b7493700">

By usual chess rules, the white player starts first.

Another unique feature is the ability to set custom chessboard configurations. 
<img width="1440" alt="chess begin setup" src="https://github.com/el6ine/cmd-line-chess/assets/110880989/6eb4cb2a-9612-4a8c-ae1e-94551e40bb8e">


Here, the chessboard starts empty and the user is able to setup the board how they want it. The commands "+ [piece] [coordinate]" and "- [piece] [coordinate]"
<img width="1440" alt="chess-setup" src="https://github.com/el6ine/cmd-line-chess/assets/110880989/1d1e9bf1-3318-4e2e-859b-0f963af50304">

