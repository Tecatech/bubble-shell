# Custom shell implementation

```
$ cd bubble-shell/
$ ls
Cargo.lock  Cargo.toml  README.md  src
$ cargo build
   Compiling bubble-shell v0.1.0 (/mnt/c/Users/Admin/bubble-shell)
    Finished dev [unoptimized + debuginfo] target(s) in 1.05s
$ cargo run
    Finished dev [unoptimized + debuginfo] target(s) in 0.01s
     Running `target/debug/bubble-shell`
> ls
Cargo.lock  Cargo.toml  README.md  src  target
> cd target/
> ls
CACHEDIR.TAG  debug
> cd debug/
> ls
bubble-shell  bubble-shell.d  build  deps  examples  incremental
> cd scripts/
No such file or directory (os error 2)
> cd ../../src
> ls
main.rs
> exit
$ cargo check
    Checking bubble-shell v0.1.0 (/mnt/c/Users/Admin/bubble-shell)
    Finished dev [unoptimized + debuginfo] target(s) in 0.15s
```