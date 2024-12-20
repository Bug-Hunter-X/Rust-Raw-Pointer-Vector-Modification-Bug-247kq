This repository demonstrates a common error in Rust when working with raw pointers and vectors. The `bug.rs` file shows the problematic code, attempting to modify a vector element via a raw pointer.  The risk of reallocation invalidating the pointer is explained in detail, demonstrating undefined behavior.  The solution, in `bugSolution.rs`, provides a safe alternative using standard vector indexing.