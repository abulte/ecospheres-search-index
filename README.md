# ecospheres-search-index

## Install

```
poetry install
```

## Usage

Launch [Meilisearch](https://www.meilisearch.com) locally.

```
docker-compose up
```

### Build index from data.gouv.fr's API

```
poetry run ecospheres-search index --config={path/to/ecospheres-front/config.yaml}
```

## See also

[Deploy a Meilisearch instance on Dokku](https://github.com/abulte/meilisearch-dokku).
