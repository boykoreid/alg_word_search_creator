# Word Search Creator

A Python application that automatically generates printable word search puzzles and solution keys in PDF format.

Each execution creates a new set of randomized puzzles by shuffling word placement and letter layouts, ensuring that every generated puzzle is unique. Words are organized into categories, making it easy to produce themed puzzle books or worksheets.


## Real-World Application
This generator was used to produce the puzzles for my published Amazon KDP word search book.

**Book:** *Word Search for Active Seniors*

[Click Here to View on Amazon](https://www.amazon.ca/dp/B0H5797WLQ)


## Features
- Generate multiple word search puzzles automatically
- Create corresponding solution pages
- Export puzzles and solutions as a formatted PDF
- Randomized puzzle generation for unique outputs each run
- Category-based word lists
- Automatically generated puzzle images using Pillow
- Configurable puzzle size and word lists (where applicable)


## Example Output
<img width="662" height="852" alt="Screenshot 2026-06-16 144459" src="https://github.com/user-attachments/assets/025852ec-12ec-4c74-a82d-8a758184ef93" />
<img width="654" height="852" alt="Screenshot 2026-06-16 144431" src="https://github.com/user-attachments/assets/018905b1-b585-4121-abb6-bdc51b86c304" />


## Technologies Used
- Python
- Pillow (PIL)


## How It Works
1. Words are grouped into categories.
2. A word list is selected for each puzzle.
3. Words are randomly placed into the puzzle grid.
4. Remaining empty spaces are filled with random letters.
5. Puzzle and solution images are generated using Pillow.
6. All pages are compiled into a printable PDF.


## Future Improvements
- Reducing hard-coded layout values (margins, spacing, sizing)
- Optimizing the puzzle generation algorithm to reduce unnecessary looping
- Better automation of word list filtering to reduce manual preprocessing
- Adding support for different puzzle sizes and page layouts
- Refactor grid and drawing calculations using vector-based coordinate transformations rather than manually computing pixel locations throughout the code.


## What I Learned
This project gave me experience working with:

- Algorithmic problem solving
- Image generation with Pillow
- 2D grid manipulation
- PDF creation and document formatting

