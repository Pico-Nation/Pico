## Description

The `db_size_api_plugin` retrieves analytics about the blockchain.

* free_bytes
* used_bytes
* size
* indices

<!--
## Usage

```console
# Not available
```
-->

## Options

None

## Dependencies

* [`chain_plugin`](../chain_plugin/index.md)
* [`http_plugin`](../http_plugin/index.md)

### Load Dependency Examples

```console
# config.ini
plugin = picoio::chain_plugin
[options]
plugin = picoio::http_plugin
[options]
```
```sh
# command-line
nodpico ... --plugin picoio::chain_plugin [operations] [options]  \
           --plugin picoio::http_plugin [options]
```
