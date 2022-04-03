# MIPSView

MIPSView is a web-based interactive simulator of the MIPS R2000 architecture. It
was created to be an educational tool for beginners to computer architecture, serving
as a jumping point to learning more about how computers work on a microarchitectural
level.

## Features

MIPSView features an interactive diagram of an implementation of the MIPS R2000
architecture and features a number of sample programs that can be loaded into the simulator.
The internal state of the different portions of the datapath can be inspected during 
execution which allows for an intuitive visualization of the flow of data and control
signals.

## In progress

The following features/improvements will be implemented in later updates to MIPSView

- User-written code execution
- Source code view during execution
- User interface redesign


## Project layout 

## Build instructions

Ensure that `wasm-pack` and `npm` have been installed on your local system and
run:

```bash
./build
```

To run the development server:

```bash
cd www
npm run start
```
