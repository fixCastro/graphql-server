# Graphql Server Rust

Learning Rust with real life projects. This time, a Graphql Server with MongoDB.

## Database

Create a `.env` file and add those variable on it

```bash
MONGO_ROOT_USERNAME="root"
MONGO_ROOT_PASSWORD="password"
```

Then on the project root path run the commando below

```bash
docker-compose up -d
```

## Dependencies

As mentioned before we're going to use [Rust] and some os it's dependencies like:

```bash
async-graphql = "6.0.7"
tokio = "1.32.0"
warp = "0.3.6"
```

[Rust]: https://www.rust-lang.org/tools/install