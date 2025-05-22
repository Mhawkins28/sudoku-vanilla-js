## Gameplay Guidlines and Rules
1. Main board is 9x9 grid
2. The board has 3x3 sub-grids
3. The solution:
    - Each row contains all numbers from 1 to 9.
    - Each column contains all numbers from 1 to 9.
    - Each 3x3 sub-grid contains all numbers from 1 to 9.
    - There are no repeating numbers within any row, column, or sub-grid.
4. The game starts with some cells pre-filled with numbers.

## Pseudocode 

### Board Setup
> 🥅 Setup a 9x9 board where a user can interact with each cell by inputing a number 1-9. 
1. Create the board structure in memory
    - initilize and empty array to repeat the board. `let board = []`
   - Use loop to create the rows:
        - initialze row array
        - for each column, add placeholder to represent an empty cell
    - push the row array to the board arry
2. Build the board in DOM
    - For each row:
        - Create a new DOM element to represent a row.
        - For each column:
            - Create an input element for the cell
            - Set it to accept only one character
            - Add any necessary classes or data attributes to identify its position
            - Append the cell to the row element
        - Append the row element to the board container
3. Style the board
    - make the cells all same lxh
    - make all sub-grids stand out
4. Trigger the board to get created on page load
    
### User Interactivity
> 🥅  User can use on-screen keys or keyboard to add numbers 1-9 in each cell. User can also remove numbers. 
1. 

### Winning Logic

### Randomized Solutions with Difficulty Levels