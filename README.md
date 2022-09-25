# Tauri + Yew

This template should help get you started developing with Tauri and Yew.

# Dependencies

```bash
rustup target add wasm32-unknown-unknown
cargo install trunk
cargo install wasm-bindgen-cli
cargo install tauri-cli
```

# Running
Do ``cargo taur dev`` to run and ``cargo tauri build`` to create a
standalone app.

# TODO Items
 - read codebase in more detail
 - test out window no decorations
 - test out rendering with alpha value
 - test bluring

# Initial Template Generation
To generate the template used to initially create this repository, do the
following and make sure to select ``yew`` for the framework when running 
``cargo create-tauri-app``.

```bash
cargo install create-tauri-app
cargo create-tauri-app
```

## Recommended IDE Setup

[VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer).
