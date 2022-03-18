# std::io

std -> standard library

io -> input/output

std::io -> standard library for input and output

# fn main() 

main function, look in chapter one for more information

# print content

```rust
    println!("Guess the number!");

    println!("Please input your guess.");
```

it is printing out the statements


```rust
    Guess the number!

    Please input your guess.
```

# let mut guess = String::new()

```rust
let apples = 5; // creates variable apples and gives it a value of 5
````

so with basic brain usage we can see that

let mut guess = ... 

creates a variable guess

## mut 

will go in more detail in chapter 5

but it makes it muttable

```rust
let apples = 5; // immutable
let mut bananas = 5; // mutable
```

# user input

```rust
    io::stdin()
        .read_line(&mut guess)
```

since we imported the io library at the beginning we can use io::stdin(), but nevertheless we could still use the library with `std::io::stdin` 

the next line `.read_line(&mut guess)` calls the read_line method from the standard input to get the input from the user.

&mut guess is the arguement for the `.read_line()` to tell it what string to store the input in

# //

// is comments in [rust](rust)
