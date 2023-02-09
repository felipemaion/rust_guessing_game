# Simple Rust Guessing Game
<h2><strong>RUST 101</strong></h2>
<br>
Studying Rust from <a href="https://doc.rust-lang.org/stable/book/">The Rust Book </a>
<br>
Build and run with default Rust installation

```$ cargo run ```     

Example Output:
```Shell
$ cargo run
Compiling guessing_game v0.1.0 (/Users/user/Projects/guessing_game)
    Finished dev [unoptimized + debuginfo] target(s) in 0.82s
     Running 'target/debug/guessing_game'
Guess the number!
Please input your guess.
50
You guessed: 50
Too big!
Please input your guess.
25
You guessed: 25
Too big!
Please input your guess.
12
You guessed: 12
Too big!
Please input your guess.
6
You guessed: 6
Too small!
Please input your guess.
8
You guessed: 8
Too big!
Please input your guess.
7
You guessed: 7
You win!
```
<p>
After that, you may run the executable located at target folder.
</p>

```Batchfile
$ ./target/debug/guessing_game
```

<br>

Note: 
    To build release: 

```Batchfile
$ cargo build --release
$ ./target/release/guessing_game
```

<br>