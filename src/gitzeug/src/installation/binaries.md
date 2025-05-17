## Build from source
1. Ensure you have [Rust](https://rustup.rs/) installed.
2. Clone this repository:
   ```sh
   git clone https://github.com/thaemisch/gitzeug.git
   ```
3. Navigate to the project directory:
   ```sh
   cd gitzeug
   ```
4. Build the project:
   ```sh
   cargo build --release
   ```
5. Add the binary to your PATH for easy access:
   ```sh
   export PATH=$PATH:$(pwd)/target/release
   ```
