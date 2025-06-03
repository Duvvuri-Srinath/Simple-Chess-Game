# Simple Chess Game

A simple chess program written in C++ using SFML.

## Features

* Interactive chessboard with piece movement.
* Pawn promotion.
* Castling and En Passant.
* Move validation and check detection.
* Highlights for selected pieces, last moves, and check.
* Sound effects for moves and captures.
* FEN string loading for board setup.

## Compiling

You will need the following to compile this project:

* **SFML 2.5+**: Development headers and library.
* **C++17 compliant compiler**: Such as GCC, Clang, or MSVC.
* **CMake build system**: For generating build files.

### Compilation Steps

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/HueFlux/chess.git](https://github.com/HueFlux/chess.git)
    ```
2.  **Navigate into the cloned directory:**
    ```bash
    cd chess
    ```
3.  **Create a build directory and navigate into it:**
    ```bash
    mkdir build && cd build
    ```
4.  **Run CMake to configure the project (ensure `CMAKE_BUILD_TYPE` is set to `Release`):**
    ```bash
    cmake -DCMAKE_BUILD_TYPE=Release ..
    ```
5.  **Compile the project using make (or your platform's equivalent build tool):**
    ```bash
    make
    ```

## How to Play

1.  Run the compiled executable.
2.  Click on a piece to select it.
3.  Drag the selected piece to its desired destination.
4.  Release the mouse button to drop the piece.
5.  If a pawn reaches the opposite end of the board, a promotion menu will appear, allowing you to choose the promoted piece.


## Dependencies

* [SFML](https://www.sfml-dev.org/): Used for graphics, audio, and window management.
