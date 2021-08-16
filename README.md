# RUST: first steps
### 1. Configuration
#### In order to run a rust program you have to install rustup Toolchain management.
From Linux or mac you can run:
```curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh```
#### If you have already installed rustup in the past you have probably upgrade it
so execute this:
```rustup update```
#### If you are tired and you want to uninstall rust:
```rustup self uninstall```

### 2. Compile and run
On Linux or macOS, enter the following commands to compile and run the file:
to compile
```rustc <filename>.rs```
to run:
```./<filename>```

### CARGO: build system and package manager
check if cargo is installed:
```cargo --version```
#### Create a new project
```cargo new <projectName>```
!!! Git files won’t be generated if you run cargo new within an existing Git repository so you can run:
```cargo new <projectName> --vcs=git```
Now you can build
```cargo build```
The compiled file is created in target directory, so to run it:
```./target/debug/<filename>```