# RP Pico Template

Template repo for the [Raspberry Pi Pico](https://www.raspberrypi.com/products/raspberry-pi-pico/) board projects using [Rust](https://www.rust-lang.org/) and the [Embassy framework](https://github.com/embassy-rs/embassy/tree/main).

The template is based on the Embassy RP multicore example. 

The starter code is a simple `blink` example in the `src/main.rs` file and takes care of booting up the process and configuring the second core (core_1) with a shared channel for inter-core communication.
