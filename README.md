# RGB schemata registry

Registry of known RGB schemata.

## Basic instructions

To add a schema to the registry just submit PR to the repository.

Schemata are classified according to their API conformance; each root schema is 
put into a separate directory with directory name being a CRC32-based mnemonic
generated out of schema id. To generate mnemonic, use the following commands:

```bash
$ cargo install crc32mnemo
$ crc32mnemo --bech32 $SCHEMA_ID
```

## Registry

| Mnemonic            | Standards | Author | # of schemata |
|---------------------|-----------|--------|---------------|
| topic-tripod-alien  | RGB20     | LNP/BP | 2             |
