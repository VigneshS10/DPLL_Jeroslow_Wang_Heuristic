# DPLL with Jeroslow-Wang Heuristic: SAT Solver

**Author:** Vignesh Subramanian  
**Course:** CS 8803: Logic in Computer Science

## Introduction

This project revolves around the implementation of the DPLL (Davis-Putnam-Logemann-Loveland) algorithm with an integration of the Jeroslow-Wang heuristic. The Jeroslow-Wang heuristic is a particular method used to guide the search in SAT solvers, giving preference to variables appearing in shorter clauses. By efficiently choosing the next literal to branch upon, this heuristic tends to improve the performance of SAT solvers.

## File Instructions

### solvers.ipynb

- **Verbose Setting:** You can choose a 'verbose' value which should be a multiple of number 100 (1, 2, 5, 10, 20, 50, 100). This determines the frequency of the output logs.
  
- **Output Handling:** While the detailed outputs of the sat solvers are not directly shown in the output block, they are saved to a text file in a relative folder. This text file allows you to monitor the SAT-solving process in real-time.
  
- **Execution:** Press 'RUN ALL' on the menu panel or run all the cells sequentially to derive the required results. The results will be stored in dictionary format within a `.txt` file. **WARNING:** Ensure that all cells have completely executed before moving on to `plots.ipynb`.

### plots.ipynb

- **Purpose:** Use this notebook to visualize the data and numerical results.
  
- **File Paths:** Before running this file, remember to modify the file paths specified in the 2nd code cell to match your directory structure.
  
- **Disclaimer:** This notebook won't generate any graphs if the `solvers.ipynb` file hasn't finished its execution.

## Running Instructions

1. Execute all cells in `solvers.ipynb`.
2. Once that completes, open `plots.ipynb` and modify the file paths.
3. Run all cells in `plots.ipynb` to view the results.

## Feedback

Feel free to open issues for any feedback to improve the project.



