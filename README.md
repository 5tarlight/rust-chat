# rust-chat

Real time CLI chatting made of Rust!

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

You can use your own WebSocket URL instead of `ws://localhost:8008`

3. Chat
