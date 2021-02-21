[original README.md](./original_README.md)

change
-----
wamrcc/wamrc++ becomes available.

notice
-----
wasi-sdk must be located @ `/opt/wasi-sdk`

wamr builtin libc must be located @ `~/wasm-micro-runtime/wamr-sdk`

build
-----
requirements: python3 and pip3

```
git clone --depth=1 https://github.com/FailFish/wasienv.git
cd wasienv
make
```

usage
-----
```
wasiconfigure ./configure linux-x32 -static {flags}
wasimake make {flags}
```
