# Bitmap Flood Fill Algorithm

This project implements a **flood fill algorithm** for filling regions in a bitmap. The algorithm starts from a given point and recursively fills connected pixels with a specified color.

## Usage

1. **Input**: The input is a 2D array representing the bitmap. Each cell contains either a `.` (empty) or `*` (filled).

2. **Starting Point**: The algorithm starts from a specific point (in this case, `(8, 7)`).

3. **Flood Fill**: It recursively fills connected empty cells with `*`.

4. **Output**: The updated bitmap is displayed.

## Example Bitmap

................**********........................\
...............*..........*.......................\
..........*****............*........*.............\
.........*.................*.......*.*....*****...\
........*................***......*...*.**.....**.\
....****.................*.......*.....*.........*\
..**......................*******................*\
.*...............................................*\
.*...............................................*\
*...........****.............................****.\
*..........*....*.........................***.....\
.*.........*....*.......................**........\
..***.......****.......................*..........\
.....****......................******..*..........\
.........**********************.....****..........\


## How to Run

1. Clone this repository.
2. Open the `index.js` file.
3. Modify the `bitmap` array or starting point as needed.
4. Run the script using Node.js: `node index.js`.

Feel free to customize and adapt this algorithm for your specific use case! 🚀
