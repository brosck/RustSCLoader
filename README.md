<h1 align="center">「🔄」About RustSCLoader</h1>

<p align="center"><img src="https://prathamai.com/wp-content/uploads/2022/06/rust.png" widght="250" height="200"></p>

RustSCLoader is a simple code that has the intention of loading a shellcode directly into RAM memory in a new process that will be created, called notepad.exe. The library used in the code is known as [winapi](https://docs.rs/winapi/latest/winapi/), which allows the programmer to make calls to Windows API's.

## Build

```
git clone https://github.com/Brosck/RustSCLoader
cd RustSCLoader
cargo build --release
.\target\release\rustscloader.exe
```
