# May 2024 Shareholder Meeting - Build Practice Area Breakout Session

## Sudoku Solver

### What is Sudoku
From the [Wikipedia article](https://en.wikipedia.org/wiki/Sudoku):
> Sudoku is a logic-based,[2][3] combinatorial[4] number-placement puzzle. In classic Sudoku, the objective is to fill a 9 × 9 grid with digits so that each column, each row, and each of the nine 3 × 3 subgrids that compose the grid (also called "boxes", "blocks", or "regions") contains all of the digits from 1 to 9. The puzzle setter provides a partially completed grid, which for a well-posed puzzle has a single solution.

A typical puzzle might look like this:
![Unsolved](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Sudoku_Puzzle_by_L2G-20050714_standardized_layout.svg/2560px-Sudoku_Puzzle_by_L2G-20050714_standardized_layout.svg.png)

And the solution for that puzzle:
![Solved](https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/Sudoku_Puzzle_by_L2G-20050714_solution_standardized_layout.svg/2560px-Sudoku_Puzzle_by_L2G-20050714_solution_standardized_layout.svg.png)

### Objectives
Today, we will be working in pairs to solve this puzzle with two different approaches. You can use each of the given inputs ([easy.json](easy.json), [medium.json](medium.json), and [hard.json](hard.json)) as a starting unsolved puzzle. Like the images above, they are 9x9 grids with cells containing digits 1-9, and with 0 representing an unfilled cell in the grid. Each of the inputs contains a JSON object, with a `puzzle` property containing a 2D array of the puzzle input, and a `solution` property containing a 2D array with the expected solution. You can use the `solution` to verify that your code is finding the right answer to the puzzle.

#### Part 1
In the first 40 minutes or so, each pair will code a solution to the puzzle in whatever language they choose, but the requirement is that we wil NOT use any form of AI to solve the problem, and we will NOT search for "sudoku solver insert_language_here" to get a solution. This The problem can be solved in a number of ways, and there are some fairly straightforward (even if brute-force) solutions when you start thinking through it. Do not worry about coming up with the fastest or most elegant solution, just try to get as far into the solution as you can with without referencing any "prior art". Also, this next requirement may be convroversial, but do not consider TDD as part of this exercise. If you want to write unit tests to confirm that a particularly complex piece of logic is working, or that your final solution is correct, that is acceptable. Just please don't approach this from a TDD mindset and try to follow TDD. This particular problem is a difficult one to break down into testable units, and we want pairs to make good progress on the problem itself, not spend most of the time trying to break down the problem into testable units.

#### Part 2
In the next 30 minutes or so, we will discard any previous work we've done, switch pairs, and solve the problem again. However, this time we want pairs to use AI to guide a solution. Whether this is something built into an IDE like GitHub Copilot, or JetBrains AI Assistant, or simply OpenAI ChatGPT, we want to use AI as much as we can to solve the problem.

#### Final Discussion
In the last 15 minutes or so, we will come back together in the large group and discuss what we learned. As you are working through Part 1, take note of what challenges you are facing. If the Sudoku puzzle is new to you, think about the challenges of understanding the problem to even start to come up with a programming solution to it. If you are familiar with the puzzle and have done it in the past, think about how you have solved it "by hand", what strategies you have used, and how you are translating that into your code.

As you are working through Part 2, think about how AI is helping you (or not helping you), and note what ideas you find with AI that you may or may not have thought of in Part 1. Also think about if/how AI is helping you understand the problem better, especially if the puzzle is new to you.

Our goal from this is to emphasize that AI is rapidly becoming a part of our lives in many ways, and as developers, it can be a powerful tool to help us work more efficiently. But we also need to be able to use it wisely, and understand that it is still largely building on "prior art", so there are limitations to what it can do. For a problem like this one that has been solved in many different ways, it will probably help you come up with a very elegant solution. It may even give you a complete and optimized solution depending on the prompts you use. But for other problems we face daily, we need to be able to ask the right questions and give the right prompts in order to eventually land on a solution, and even then, we have a responsibility to make sure these solutions are correct and really do solve the problem at hand. 