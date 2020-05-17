# do-addition

This project expects the `*.wasm` binary to be located within the `www/`
directory, next to the `index.html` file. To ensure that is the case, execute
the following code:

```console
make build
cp target/wasm32-unknown-unknown/release/hello_raw.wasm www/
```