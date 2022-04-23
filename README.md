# redis-playground

📚 Learning and exploring Redis.

> The open source, in-memory data store used by millions of developers as a database, cache, streaming engine, and
> message broker.
>
> --<cite>https://redis.io/</cite>


## Description

**NOTE**: This project was developed on macOS. It is for my own personal use.

Redis is awesome. I need to learn it.


## Instructions

Follow these instructions to build and run the demo:

1. Install Redis:
   * ```shell
     brew install redis
     ```
1. Start the Redis server:
   * ```shell
     redis-server --loglevel warning
     ```
1. Connect to it from the Redis REPL (Read Eval Print Loop):
   * ```shell
     redis-cli
     ```
1. Write some data using the REPL
   * ```redis-cli
     LPUSH redis-playground "Hello from the redis-playground!"
     ```
   * Instead of copy/pasting the command. Try writing it by hand. Notice how the REPL has a nice auto-suggestion
     and auto-completion user experience.   
1. Read the data:
   * ```redis-cli
     RPOP redis-playground
     ```


## Reference

[Redis: "Getting Started"](https://redis.io/docs/getting-started/)
