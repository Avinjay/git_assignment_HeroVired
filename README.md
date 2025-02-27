# CalculatorPlus

## Overview

CalculatorPlus is a Python application that provides basic arithmetic operations, such as addition, subtraction, multiplication, and division. Additionally, a new feature for calculating the square root of a number has been implemented.

The project also includes a **Geometry Calculator**, which provides functionalities for calculating the area of a circle and a rectangle. Furthermore, **Git LFS (Large File Storage)** has been integrated to efficiently manage large binary files, in this case a .msi file which is binary in nature.

## Repository Information

- **Repository Name:** git\_assignment\_HeroVired
- **Branches:**
  - `main`
  - `dev`
  - `feature/sqrt`
  - `lfs`
  - `geometry-calculator`
  - `feature/circle-area`
  - `feature/rectangle-area`

## Features

- Addition
- Subtraction
- Multiplication
- Division (with zero-division error handling)
- Square Root Calculation (new feature added in `feature/sqrt` branch)
- Large File Storage (Git LFS setup)
- Geometry Calculations (circle area and rectangle area implemented in `geometry-calculator` branch)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Avinjay/git_assignment_HeroVired.git
   ```
2. Navigate to the project directory:
   ```sh
   cd git_assignment_HeroVired
   ```
3. Install required dependencies (if any):
   ```sh
   pip install -r requirements.txt
   ```

## Implementation Details

### Version 1: Initial Release
- Implemented basic arithmetic operations: addition, subtraction, multiplication, and division.
- Created the `Calculator` class and provided an interface for calculations.
- Released as `Version 1.0`.

### Square Root Feature
- Implemented in the `feature/sqrt` branch.
- Added a new function to calculate the square root using `math.sqrt()`.
- Merged into `dev` and later into `main` as part of `Version 2` release.

### Bug Fix: Division by Zero Handling
- Implemented in the `dev` branch.
- Fixed `divide` method to raise an error when dividing by zero.
- Merged into `main`.

### Git LFS Integration
- Implemented in the `lfs` branch.
- Added a large file (over 200MB), a jdk msi installer for windows and tracked it using Git LFS.
- Pushed changes and verified correct downloading on a cloned repository.

### Geometry Calculator
- Implemented circle area and rectangle area calculations.
- Used `git stash` to manage unfinished work between features.
- Features merged into `dev` and then into `main`.

## Try It Yourself

If you'd like to experiment with the project, you can fork the repository:

1. Click the **Fork** button on the top right of the repository page.
2. Clone your forked repository:
   ```sh
   git clone https://github.com/yourusername/git_assignment_HeroVired.git
   ```
3. Follow the installation steps above.


## Releases

- **Version 1.0**: Initial release with basic arithmetic operations.
- **Version 2.0**: Added square root function and bug fix for division.


## Output

1. **CalculatorPlus**:

<img width="557" alt="image" src="https://github.com/user-attachments/assets/6eaa4d5c-09ab-4b6a-94d2-ea9f6d0c4509" />

   
2. **GIT LFS**:
   Tested through other machines

<img width="560" alt="image" src="https://github.com/user-attachments/assets/7144a7e2-04ab-4a43-8c61-82e24e9a6b97" />

  
3. **Geometry Calculatory**:

<img width="494" alt="image" src="https://github.com/user-attachments/assets/cb39993f-10b0-474c-807a-a94149164ec5" />

 

## Releases

- **Version 1.0**: Initial release with basic arithmetic operations.
- **Version 2.0**: Added square root function and bug fix for division.


## Contact

For any questions, feel free to reach out via GitHub Issues.



