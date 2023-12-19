# Welcome!

Write the following C++ code in Rust:
```
// Compute greatest common divisor
uint8_t gcd(uint8_t a, uint8_t b) {
   if (b != 0) {
          return gcd(b, a % b);
    } else {
        return a;
    }
};

int main()
{
    uint8_t gcdResult = gcd(10,25); 
    printf("%i",gcdResult);
    assert(gcdResult == 5);
    return 0;
}
```

```rust runnable
fn main() {
    println!("Hello World!");
}
```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced Rust template](https://tech.io/select-repo/596)
