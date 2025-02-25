# os
This project is meant as a learning project and as such I am mainly following the series [blog_os](https://os.phil-opp.com/freestanding-rust-binary/) by Phillip Oppermann.

# Progression 
## Day 1 - Freestanding binary
I followed the first part of the tutorial. This included modifying the main.rs file, disabling use of std and main, providing a panic function and writing an entrypoint to our program.  
Also through cargo.toml the panic behavior was modified to abort on panic.

One more thing that happened was to solve a linker error we added a bare metal environment namely an  embedded ARM system as build target.  

To run this first version we can run
'''cargo build --target thumbv7em-none-eabihf'''

Which does obviously nothing yet :)
