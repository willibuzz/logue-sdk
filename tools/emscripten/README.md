## Installing Emscripten

_Required EMSDK version: 1.38.45 (other versions untested)_

### OSX

Run `./get_emscripten_osx.sh` to download and unpack gcc automatically.

### Linux

#### Native System or VM _(untested)_

Run `./get_emscripten_linux.sh` to download and unpack gcc automatically.

#### Windows Subsystem for Linux

Status unknown.

### Windows

#### MSYS2

Unfortunately the Emscripten install scripts do not work properly in the MSYS2 environment. However, it can be installed following the manual procedure below. 

#### Manual Procedure (via Command Prompt)

_Note: Requires Git and Python_

1. Clone the [Emscripten SDK repository](https://github.com/emscripten-core/emsdk) in this folder:

```
> git clone https://github.com/emscripten-core/emsdk.git
```

2. Run the Emscripten SDK installation procedure:
```
> emsdk install 1.38.45
```

3. Activate Emscripten for the current environment:
```
> emsdk activate 1.38.45
```
