

WSL:
    curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh

Extension (VSC):
    rust-analyzer, rust-lang.org

Docs (with XServer, VcXsrv):
    sudo apt install firefox
    rustup doc

Commands:
    (compile): rustc <path>
    (format): rustfmt <path>

Cargo:
    (new): cargo new <project>
    (build, default is debug): ./target/debug/<project>
    (build and run): cargo run
    (build without binary): cargo check
    (build with optimization): cargo build --release