# wasm2merkle

small tool for converting hashing wasm bytecode into a merkle tree

needs to be used alongside *wat2wasm* and *wasm2wat* tools in the [webassembly binary toolkit](https://github.com/WebAssembly/wabt)

for example, provided you have a wasm text (.wat) file: 
```
/path/to/wat2wasm test.wat -o test.wasm
cat test.wasm | wasm2merkle
```
