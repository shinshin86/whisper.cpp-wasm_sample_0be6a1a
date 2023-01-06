# whisper.cpp-wasm_sample_0be6a1a
This is the source code for trying to run the WASM version of whisper.cpp in a local.  
It contains source code built with reference to the following page.

[whisper.wasm](https://github.com/ggerganov/whisper.cpp/tree/master/examples/whisper.wasm)

I built using the version of the commit hash [here](https://github.com/ggerganov/whisper.cpp/commit/0be6a1afd9d6e7848ffc5917c2a66a3cd4eba53e) in whisper.cpp.

This project has been realized up to the point where it is started on a local server, but it does not function properly as a web application.  
Barely, the text is output only to the console on the browser's developer tools.

## Running app

Start the local server with the following model files stored in the root of the project.  
We also use [superstatic](https://github.com/firebase/superstatic) for local server startup.

* tiny.en
* tiny
* base.en
* base

```sh
# install
yarn install

# start local server
yarn dev
```

Access `localhost:3000`.
