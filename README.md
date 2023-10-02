### Hi there 👋
1. Previous coding experience
- A few survey courses. Nothing all too-in-depth
2. Reasons for taking this class
- To become more familiar with the realm of coding
3. Other interests (academic or otherwise)
- Finance: evaluation of the stock market
4. Goals you have for this class and/or projects you'd like to complete
- Programming a video game 

*Recursive Art (10/1)*
My recursive art project is based on the idea of Sierpiński's triangles
 The project details a filled-in black triangle that, from its initial level change from 0 to 1, adds a white triangle (inscribed and connected by the larger triangle's
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

*IDP #1 (Connect 4 10/1)*

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
