# blog-actix

This project uses `diesel` to manage database migrations, and sqlite as a
light-weight backing database. To set up the database, install the `diesel`
CLI:

```console
cargo install diesel_cli --no-default-features --features sqlite
```

and then execute the following command to generate a sqlite database with the
correct schema.

```console
diesel migration run
```