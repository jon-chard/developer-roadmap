# Vector

A `Vector` in Rust, often referred to as `Vec`, is a growable, or dynamically-sized, array-like data structure that can store homogeneous types. It stores elements of the same type in a contiguous block of memory, with the count of elements and capacity managed automatically by Rust. Unlike arrays, vectors do not need to have a predetermined size at compile time and their size can be increased or decreased at runtime. The `Vec<T>` holds its data on the heap. It maintains a pointer to the data, a length, and a capacity. The length is the number of elements currently stored in the vector, while the capacity is the total allocation in the memory. The key methods for a `Vec<T>` include `push()`, `pop()`, and `len()`, among others.

Learn more from the following links:

- [@article@Storing Lists of Values with Vectors](https://doc.rust-lang.org/book/ch08-01-vectors.html?highlight=vector#storing-lists-of-values-with-vectors)