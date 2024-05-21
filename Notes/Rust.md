The Rust programming language helps you write faster, more reliable software.

Why Rust?
1. Rust is used for performance, safety and memory management.
2. If you want to write language with low-level access to system and low latency, rust is most used ones.
3. Also it is the only language which is used to write Smart Contracts on Solana blockchain.

Rust vs. Node.js

1. Node.js does not have 'Type-safety' 
   Type-safety is prevention of type-errors, which occur when an operation is performed on the wrong type of data. A type-safe language ensures that data of one type cannot be mistakenly treated as another type, reducing bugs.
   ```
   let x = 2;
   let y = 3;
   let sum = x + y;
   console.log(sum)
   // Output - 5
   ```
   ```
   let x = 2;
   let y = "3";
   let sum = x + y;
   console.log(sum)
   // Output - 23   // JS concatenated the number and string, resulting in sum 23 instead of 5. 
   ```
   The reason for such output is JS implicitly converts the number of string and concatenates them. 
