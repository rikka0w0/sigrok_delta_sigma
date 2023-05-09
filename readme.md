Delta-Sigma Decoder Plugin for Sigrok

# Features
1. Multiple filters available (sinc1, sinc2, sinc3).
2. Configurable oversampling factor (also known as down sampling ratio).
3. Support bit right shifting to give the desired resolution.
4. Provide a scalar to convert code into actual value.

# TODO
1. Support sinc_fast filter.
2. Support Manchester decoding.

# Usage
On Linux, clone this repository into `~/.local/share/libsigrokdecode/decoders/` and launch Pulseview.
