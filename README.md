<!-- @format -->

**debugging**

```shell
 ./target/debug/hello_cargo
```

**creating new project**

```shell
cargo new <project_name>
```

**Building and Running a Cargo Project**

**-Buildin**

```shell
 cargo build
```

**-Running**

```shell
cargo run
```

**This command quickly checks your code to make sure it compiles but doesn’t produce an executable:**

```shell
cargo check
```

# summary

<ul>
<li>We can create a project using<b> <i>cargo new</i></b> .</li>
<li> We can build a project using <b> <i>cargo build</i></b>.</li>
<li>We can build and run a project in one step using <b> <i>cargo run</i></b>.</li>
<li>We can build a project without producing a binary to check for errors using <b> <i>cargo check</i></b>.</li>
</ul>    
- Instead of saving the result of the build in the same directory as our code, Cargo stores it in the target/debug directory.
<br/>
<br/>

**Run for specific file**<br/>
example file named _hello_world.rs_

```shell
rustc hello_world.rs
./hello_world
```

[**Installing Rust**](https://www.digitalocean.com/community/tutorials/install-rust-on-ubuntu-linux)
