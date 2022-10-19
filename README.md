# rusty_strawberry

Rusty Strawberry is an application built with web assembly and wasm in mind.

Currently it is at its barebones. We will try to fill it up as we go.

## What can it do at the moment ?

At the moment it can only print to the console.


## Getting Started

### Why `web assembly` and what is its use case ?

Web assembly is a type of byte code that can be generated from variety of languages that can be compilied by the brower and ran natively at native speeds. This is a FEAT because prior to this, only JS could be run in the browser. For a variety of problems javascript is totally fine for the application. but as we venture more in the depth of WEB, we come to notice its usage and importance. 

This is NOT INTENDED to replace JS. The main reason web assembly is used is because it can offloading computation task to some other langage and get output. `GO`, `RUST`, `C` and other languages also use the `Web Assembly`.

### Installation

`Note:` Before you continue, please make sure you have the following installed - 

```
1. Rust
2. Cargo
3. wasm
```

1. Create a new library by - `cargo init --name calculator --lib`
2. Install a dependency - `cargo install wasm-pack`
3. Build the wasm file everytime we change values - `wasm-pack build --target web` ( should have written code by now )
4. Finally, just serve your `index.html` and you should see your console.log