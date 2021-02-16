# Rust STM32 experiment

Code is cloned from here: https://cgit.pinealservo.com/BluePill_Rust

To flash the STM32, run this from working directory: cargo flash --release --chip STM32F103C8 (Builds the code and flashes the chip)

To flash and see the debug console: cargo embed --release

