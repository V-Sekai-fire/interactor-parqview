# interactor-parqview

A local web viewer for a directory of Parquet files, showing relations as paged tables and embedded images as thumbnails.

## What it is for

It lets a person look through a Parquet dataset in a browser without writing a query or loading it into a notebook. A release bundles the runtime, so the machine that runs it needs nothing else installed.

## Build and run

```sh
mix setup
PARQVIEW_DIR=/path/to/parquet mix phx.server
```

Without `PARQVIEW_DIR` it browses the directory it was started in. `mix release` builds the self-contained release for the platform it runs on.

## Licence

MIT; see `LICENSE`.
