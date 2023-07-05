# rust-webserver
# statically link executable

RUSTFLAGS='-C target-feature=+crt-static' cargo build