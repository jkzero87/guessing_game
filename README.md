# Guessing Game 🎯

A command-line number guessing game built in Rust, following Chapter 2 of [The Rust Programming Language Book](https://doc.rust-lang.org/book/).

## How to Play

The program generates a random number between 1 and 100. Your goal is to guess it.

- If your guess is too low → `Too small!`
- If your guess is too high → `Too big!`
- If you guess correctly → `You win!`

Invalid inputs (letters, symbols) are ignored and the game continues.

## How to Run

Make sure you have [Rust installed](https://www.rust-lang.org/tools/install), then:

```bash
git clone https://github.com/jkzero87/guessing_game.git
cd guessing_game
cargo run
```

## Concepts Practiced

- Variables and mutability
- Data types (`u32`, `String`)
- User input with `std::io`
- Random number generation with the `rand` crate
- Control flow (`loop`, `break`, `continue`)
- Pattern matching with `match` and `Ordering`
- Error handling with `Result`, `Ok`, and `Err`

## Learning Context

This project is part of my journey transitioning into software development.
Currently studying Rust through The Rust Programming Language Book.