# Simple Sudoku

Sudoku is a logic-based, combinatorial number-placement puzzle. The objective is to fill a 9×9 grid with digits so that each column, each row, and each of the nine 3×3 subgrids that compose the grid (also called "boxes", "blocks", or "regions") contains all of the digits from 1 to 9. The puzzle setter provides a partially completed grid, which for a well-posed puzzle has a single solution.

Completed games are always a type of Latin square with an additional constraint on the contents of individual regions. For example, the same single integer may not appear twice in the same row, column, or any of the nine 3×3 subregions of the 9x9 playing board.

French newspapers featured variations of the puzzles in the 19th century, and the puzzle has appeared since 1979 in puzzle books under the name Number Place. However, the modern Sudoku only started to become mainstream in 1986 by the Japanese puzzle company Nikoli, under the name Sudoku, meaning "single number". It first appeared in a US newspaper and then The Times (London) in 2004, from the efforts of Wayne Gould, who devised a computer program to rapidly produce distinct puzzles.

Thanks in advance for your Sudoku!

*Try your hand at the following exercise:*

The classic Sudoku game involves a grid of 81 squares. The grid is divided into nine blocks, each containing nine squares. The rules of the game are simple: each of the nine blocks has to contain all the numbers 1-9 within its squares. Each number can only appear once in a row, column or box.

Create a simple Sudoku game, aka console game. That's mean it should be Ruby script anyone can launch into interactive ruby console via `irb -r ./sudoku.rb` command or `require_relative 'sudoku.rb'` within `irb`.

Acceptance criteria:

1. Initialize gaming field/grid (could be with static values each launching) and show it to user (print in console) via e.g. `game = Sudoku.new`

2. Make a move via public method `:move` e.g. `game.move(x, y, value)`

2. After a successful move print updated grid (below of previous, cleaning of previous grid and/or notification is not necessary).

3. Notify user if x/y/val is out of range (each of them could be within [1..9])

4. Notify user if val is prohibited by rules (is already taken by horizontal, vertical, or within block)

5. Allow user to do a move into the same cell (change its value)

6. *[Optional]* Allow user to clear a cell by passing `val` as 'x'

### Things we are looking for

- A working script, launchable under `irb` console
- Clean code
- Clear method naming
- Nice to use access modifiers

### Things we are not looking for

- Impeccable and complicated app

### Timebox

Spend no more than an 2 hours on this in total. It is perfectly valid to call out the things that you would have done, had you more time.
