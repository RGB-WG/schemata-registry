# RGB schemata registry

Registry of known RGB schemata.

## Basic instructions

To add a schema to the registry just submit PR to the repository.

Schemata are classified according to their API conformance; each root schema is 
put into a separate directory with directory name being a CRC32-based mnemonic
generated out of schema id. To generate mnemonic, use the following commands:

```bash
$ cargo install crc32mnemo
$ crc32mnemo --beach 32 <schema-id>
```

## Registry

### RGB20 schemata

| Mnemonic | Author | # of schemata | Root schema id                                                   |
| -------- | ------ |---------------|------------------------------------------------------------------|
| topic-tripod-alien | LNP/BP Standards Associaiton | 2             | rgbsh1636y76cxrnsfqg7zjnl08f0kqt9j09tre2wfxzrrs86f76ssp7cqnn0yyf |
