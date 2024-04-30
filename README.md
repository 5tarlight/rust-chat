# rust-chat

Real time CLI chatting made of Rust!



https://user-images.githubusercontent.com/45203447/232058729-c1fa460b-7739-4e74-87e0-85e926b991fe.mov



## Requirements

Love of Rust

## Execution

1. Start server

```bash
cd chat_server
cargo run
```

2. Start client and connect

```bash
cd chat_client
cargo run ws://localhost:8080
```

You can use your own WebSocket URL instead of `ws://localhost:8080`

3. Chat
