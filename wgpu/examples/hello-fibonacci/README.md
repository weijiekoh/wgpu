# hello-fibonacci

Runs a compute shader to determine the n-th Fibonacci number.

e.g. the 0th Fibonacci number is 0, followed by 1, 1, 2, 3, 5, and so on.

## To Run

```
# Pass in values for n as arguments
RUST_LOG=hello_fibonacci cargo run --example hello-fibonacci 0 1 2 3 4 5
```

## Example Output

```
Fibonacci numbers: [0, 1, 2, 3, 5, 8]
```
