# Rusty Chess Engine

Rusty Chess Engine is a simple chess engine I am working on in my free time.
So far not many things are implemented, howewer the journey is quite enjoyable.

## Features

- **Game States**: Full implementation of game states.
- **FEN Processor**: Parse and process FEN strings to initialize the board state.
- **Board Display**: Nicely formatted board display in the console.

- **Rayon**: Engine uses paralellisation whenever it is possible
- **Thiserror**: Engine has extensive error processing


## Getting Started

### Prerequisites

- [Rust](https://www.rust-lang.org/tools/install) - Make sure you have Rust installed on your system.

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/TymDrogin/rusty-chess-engine/
    ```
2. Navigate to the project directory:
    ```sh
    cd rusty-chess-engine
    ```
3. Build the project:
    ```sh
    cargo build
    ```

### Running the Engine

After building the project, you can run the chess engine using:
```sh
cargo run
```

Unit test can be run using:
```sh
cargo test
```

Becnhmarks are not yet implemented, howewer it is planed.


     0100 
0000 1000 
1000 0000