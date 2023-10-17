### Hi there 👋
1. Previous coding experience
- A few survey courses. Nothing all too-in-depth
2. Reasons for taking this class
- To become more familiar with the realm of coding
3. Other interests (academic or otherwise)
- Finance: evaluation of the stock market
4. Goals you have for this class and/or projects you'd like to complete
- Programming a video game 

**Recursive Art (10/1)**
My recursive art project is based on the idea of Sierpiński's triangles
 The project details a filled-in blue triangle that, from its initial level change from 0 to 1, adds a white triangle (inscribed and connected by the larger triangle's
 midpoints). Each white triangle from that point forward is drawn outside the interior white triangle's boundaries to each specific midpoint.

 Project development: The project development commenced with the ideation of a visually engaging program to recursively create triangle shapes. Below is a step-by-step documentation of the developmental process. 

 1. Initial Setup:
    - The 'main' function was established as the launching point of the program.
    - Here, a preliminary call to 'makeBackgroundBlack' was utilized to set a uniform background for our visual output
 2. User Interaction:
    - 'Scanner' was incorporated to facilitate user interaction, prompting users to input the number of recursive steps desired for the triangle creation.
    - The obtained input determined the complexity and depth of the triangles drawn, offering a customizable experience to the user.
 3. Conditional Handling:
    - Conditional statements were set up to address the user input and invoke the 'TriangleMake' function with the appropriate parameters based on the provided number of steps.
    - These conditions also handled the special case of a single step, drawing just one triangle in the middle.
 4. Recursive Drawing:
    - The 'triangleMake' function was developed to handle the recursive drawing of the triangles, managing the position and size of the triangles based on the user-defined steps.
    - The function incorporated three calls to 'drawLine' to create the triangles and three recursive calls to itself to generate the nested triangles.
 5. Drawing and Coloring:
    - The 'drawLine' function was implemented to color the pixels from the start point to the end point black and fill the resulting triangle white
    - This function was paramount in visually representing the triangles, ensuring the clarity and accuracy of the shapes drawn.
    
Reflection on learning (things I'm proud of /takeaways)
  - Realized the importance of modular coding; it not only makes code readable but more manageable
  - Grasped the essence of recursion; it's like solving a puzzle, breaking it into smaller pieces to see the whole picture more clearly

Potential for enhancement (things I would incorporate/refine)
  - Implement full user interaction: the code could prompt the user more interactively, possibly asking for different sizes or points to draw the triangle. It will allow users to create more customized shapes.
  - Enhance error handling: The code can be made more robust by adding more appropriate error-handling mechanisms, for instance, checking if the user input is a valid integer 

**IDP #1 (Connect 4 10/1)**

Developing this project involved multiple key steps, with the core goal of creating an interactive, grid-based console application. Below is a detailed documentation of the developmental process.  
1. Initialization and Setup:
    - A 2D char array 'grid' of size [6][7] was initialized to represent the grid structure.
    - A nested loop was employed to fill the grid with '-' to represent empty spaces and to print the initial state of the grid
2. User interaction:
    - A while loop was implemented to continually accept user inputs, allowing perpetual interaction
    - Utilizing 'Scanner', the program prompts the user to input an integer corresponding to the grid column where they wish to place an 'X'.
3. Grid Manipulation:
    - For the selected column, the program traverses each row to determine the appropriate position for 'X', ensuring it's placed in the lowest available row within the chosen column.
    - Special cases, such as when a column is fully occupied or when placing 'X' in the last row, are handled with conditional statements to avoid errors.
4. Grid update and Display:
    - After placing 'X' based on the user's input, the grid is updated.
    - The updated grid is then printed to the console, giving users a visual representation of the current state of the grid.
    - The process repeates indefinetly due to the enclosing while(true) loop, allowing users to continue placing 'X' in the grid
5. Debugging and Validation:
    - Throughout the development, several print statements were employed to print variable values and intermediate states, aiding in debugging and validating the program logic.
    - These print statements helped in confirming the proper functioning of the user input, grid updates, and special condition handling
  
**Password generator (Project 11)**

Documentation of Process
1. The application preloads a word list
2. On setup, it initializes the word list and prepares the canvas for drawing
3. When a key is pressed, a random dice roll is simulated
4. After 5 dice rolls, the sequence of numbers corresponds to an index in the word list, fetching a word
5. These words are then displayed on the screen

Documentation of Code: 
Variables: 
- 'strings': An array to load words from "eff_large_wordlist.txt"
- 'wordList': An array to store words after processing 
- 'dieRolls': Stores the dice rolls
- 'listOfWords': List of generated words from dice rolls
- 'passphrase': Stores the current passphrase 
- 'dieFaces': Array reprensenting die faces

Functions
- 'preload ()': Preloads the word list
- 'setup ()': Initializes canvas and word list
- 'draw ()': Draws the canvas, including dice rolls and passphrase
- 'keyPressed ()': Handles the event when a key is pressed, generating a dice roll and updating the passphrase
- 'getWordForKey (key)': Returns word for a specific dice roll sequence 
- 'isValidKey (key)': Validates if a key (dice roll sequence) is valid 
- 'initializeWordList ()': Initializes the word list
- 'loadStringIntoList ()': Processes and load strings into word list 

Two things I'm proud of:
1. Efficiency and Key Validation: The 'isValidKey' fuction ensures that only valid dice roll sequences are used. This guarantees the reliability of the passphrase generation.
2. Memory management: After the word list is loaded and processed, the 'strings' array is set to null to free up memory

Two Areas for Improvement
1. Hard-Coded Values: There are hard-coded values in the draw fucntion for positioning text. These could be defined as constants or variables for better readbility and flexibility.
2. Debugging Logs: There are console.log statements (like "Asss" and "hi") which might have been used for debugging. It's better to remove or comment them out in the final version of the code. 

  


<!--
**Dshin24/Dshin24** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
