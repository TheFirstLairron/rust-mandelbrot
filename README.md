# rust-mandelbrot

A mandelbrot image plotter written in rust.

# Build
    * Ensure Rust is installed
    * move into the mandelbrot directory
    * For Debug: cargo build
    * For Release: cargo build --release

# Usage
    * Move into the mandelbrot directory
    * Run Debug build(takes a long time to plot image): cargo run mandel.png 4000x3000 -1.20,0.35 -1,0.20
    * Run Release build (Found in ./target/release, quickest plot time): ./mandelbrot mandel.png 4000x3000 -1.20,0.35 -1,0.20
    * To view results: View mandelbrot.png (<filename>.png)
