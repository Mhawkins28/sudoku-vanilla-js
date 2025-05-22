## Gameplay Guidlines and Rules
1. Main board is 9x9 grid
2. The board has 3x3 sub-grids
3. The solution:
    - Each row contains all numbers from 1 to 9.
    - Each column contains all numbers from 1 to 9.
    - Each 3x3 sub-grid contains all numbers from 1 to 9.
    - There are no repeating numbers within any row, column, or sub-grid.

### Sample Board
| 5 | 3 |   ||   | 7 |   ||   |   |   |
| 6 |   |   || 1 | 9 | 5 ||   |   |   |
|   | 9 | 8 ||   |   |   ||   | 6 |   |
|===|===|===||===|===|===||===|===|===|
| 8 |   |   ||   | 6 |   ||   |   | 3 |
| 4 |   |   || 8 |   | 3 ||   |   | 1 |
| 7 |   |   ||   | 2 |   ||   |   | 6 |
|===|===|===||===|===|===||===|===|===|
|   | 6 |   ||   |   |   || 2 | 8 |   |
|   |   |   || 4 | 1 | 9 ||   |   | 5 |
|   |   |   ||   | 8 |   ||   | 7 | 9 |


|🔒R1C1:5|🔒R1C2:3|✏️R1C3: | |✏️R1C4: |🔒R1C5:7|✏️R1C6: | |✏️R1C7: |✏️R1C8: |✏️R1C9: |
|🔒R2C1:6|✏️R2C2: |✏️R2C3: | |🔒R2C4:1|🔒R2C5:9|🔒R2C6:5| |✏️R2C7: |✏️R2C8: |✏️R2C9: |
|✏️R3C1: |🔒R3C2:9|🔒R3C3:8| |✏️R3C4: |✏️R3C5: |✏️R3C6: | |✏️R3C7: |🔒R3C8:6|✏️R3C9: |
|=======|=======|=======| |=======|=======|=======| |=======|=======|=======|
|🔒R4C1:8|✏️R4C2: |✏️R4C3: | |✏️R4C4: |🔒R4C5:6|✏️R4C6: | |✏️R4C7: |✏️R4C8: |🔒R4C9:3|
|🔒R5C1:4|✏️R5C2: |✏️R5C3: | |🔒R5C4:8|✏️R5C5: |🔒R5C6:3| |✏️R5C7: |✏️R5C8: |🔒R5C9:1|
|🔒R6C1:7|✏️R6C2: |✏️R6C3: | |✏️R6C4: |🔒R6C5:2|✏️R6C6: | |✏️R6C7: |✏️R6C8: |🔒R6C9:6|
|=======|=======|=======| |=======|=======|=======| |=======|=======|=======|
|✏️R7C1: |🔒R7C2:6|✏️R7C3: | |✏️R7C4: |✏️R7C5: |✏️R7C6: | |🔒R7C7:2|🔒R7C8:8|✏️R7C9: |
|✏️R8C1: |✏️R8C2: |✏️R8C3: | |🔒R8C4:4|🔒R8C5:1|🔒R8C6:9| |✏️R8C7: |✏️R8C8: |🔒R8C9:5|
|✏️R9C1: |✏️R9C2: |✏️R9C3: | |✏️R9C4: |🔒R9C5:8|✏️R9C6: | |✏️R9C7: |🔒R9C8:7|🔒R9C9:9|




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