# Rustpass

Rustpass is a Webapplication to Read and Edit Keepass2.x Databases.
It uses WASM (Web Assembly) to achieve native performance on de-/encryption tasks.
To achieve high security while keeping a good development experience, we use RUST as programming language.
This project was built with the [yewstack](https://yew.rs/docs).

## Run Project
Ensure you have installed ```wasm-pack``` with cargo
Next you need to install all node modules by running:
```
npm i
```
Just use the npm task to start the development server with hot reloading:
```
npm run start:dev
```