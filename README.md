# Connect Four

Table of Contents
1. [About this Project](#about)
   - [Demo](#demo)
   - [Built With](#built)
   - [AI Opponent](#AI)
   - [Mediapipe Hand Landmark Model](#model)
2. [Running the Application](#runapp)
3. [Contact](#contact)

<a name=about></a>
## About this Project:

<a name=demo></a>
### Demo:

https://user-images.githubusercontent.com/93673736/149860871-1004f907-a141-45dd-9919-4b202b419855.mp4

<a name=built></a>
### Built With:
  - [Pygame](https://www.pygame.org/news)
  - [Mediapipe](https://google.github.io/mediapipe/)

<a name=AI></a>
### AI Opponent

Three levels of difficulty were deveoped for this game. 
1. **Easy**: Discs dropped randomly at any of the columns.
3. **Medium**: Discs dropped based on the best heuristic sccore from searching through one ply or a depth of one.
4. **Hard**: Employs the minimax algorithm. 

<a name=model></a>
### Mediapipe Hand Landmark Model

  <img width="737" alt="Screen Shot 2022-01-17 at 5 10 57 PM" src="https://user-images.githubusercontent.com/93673736/149842240-b8425f9e-e59e-4fa6-8683-6a0d22f0c9bb.png">
  
  For more information: https://google.github.io/mediapipe/solutions/hands.html
  
  Three gestures were implemented for this game:
  1. Peace Sign - Move discc to the left.
  
     <img width="391" alt="Screen Shot 2022-01-17 at 5 26 35 PM" src="https://user-images.githubusercontent.com/93673736/149843775-6945f400-c02c-4c5f-8e87-4fe208b4dadb.png">
  
  2. Okay Sign - Move disc to the right.
  
     <img width="319" alt="Screen Shot 2022-01-17 at 5 26 45 PM" src="https://user-images.githubusercontent.com/93673736/149843811-abc8606f-4f3c-4232-a1db-86798b517803.png">

  3. Thumbs Down Sign - Drop disc into column.
 
     <img width="242" alt="Screen Shot 2022-01-17 at 5 28 40 PM" src="https://user-images.githubusercontent.com/93673736/149843827-70f0a8b3-f45a-44f5-a3ae-15e9300cfa70.png">

<a name=runapp></a>
## Running the Application

The game can be ran using terminal with the following commands:

- Easy: python3 main.py -- easy
- Medium: python3 main.py -- medium
- Hard: python3 main.py -- hard
- Quit: q

<a name=contact></a>
## Contact

Work email: kelvinsiu8888work@gmail.com

School email: siu.ka@northeastern.edu

Github Link: https://github.com/kelvin8888siu/

Linkedin: https://www.linkedin.com/in/kelvin-siu-7b6297160/


