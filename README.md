# esp-rust-firmware

this project was generated from cargo-pio.
``` bash
cargo pio new esp-rust-firmware --platform espressif32 --frameworks arduino --board esp32-s3-devkitc-1
```

to set rustc toolchain, this must be installed toolchain from `espup`
``` bash
rustup override set esp
```

### building the firmware
``` bash
cargo pio build
```
