# chat-tokio-stream

This is a toy project to build out a chat server in Rust using Tokio async primitives.

This work is based on the tutorial "Creating a Chat Server with async Rust and Tokio" by Lily Mara published as a Manning liveVideo. Any copyright claims on that code still hold, and I don't make any claims to it. I'm just doing this to start learning the Tokio library.

## To run it locally

You'll need a few shells. The server will run in one shell, and clients will connect via telnet on other shells.

To run the server:

```{bash}
cargo run
```

To connect a client:

```{bash}
telnet localhost 8080
```

## To deploy it somewhere

Don't. This is a toy project. You shouldn't do that.
