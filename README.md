# rust-basic-microservice

Basic CRUD microservices built with Rust. ORM used is Diesel and database used is Postgresql.2

## Crates used:
- Url 
- Diesel (ORM)
- env_logger
- hyper
- maud (Basic Frontend)
- serde_json
- futures

Run microservice with this:
`DATABASE_URL="postgresql://<username>:<password>@localhost" RUST_LOG="microservice=debug" cargo run`