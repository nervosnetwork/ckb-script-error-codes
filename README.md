## CKB Script Error Codes

Please use Pull requests to submit error codes for your CKB scripts.

## Disclaimer

The content of this repository is contributed by the community. Nervos Foundation will not verify that the content submitter is the author of the CKB script. Please use the information carefully, and restrict the usage in development debugging.

## How to Add New Script

This repository is organized by script hash type and code hash. When a script is referenced by data hash:

```
{
  "hash_type": "data",
  "code_hash": "0x12..90",
  ...
}
```

The corresponding error codes page is `by-data-hash/12..90.md`. Pay attention that the prefix `0x` is not included in the file name.

When a script is referenced by type hash

```
{
  "hash_type": "type",
  "code_hash": "0xab..ef",
  ...
}
```

The corresponding error codes page is `by-type-hash/ab..ef.md`. Pay attention that the prefix `0x` is not included in the file name.

## Error Code Anchors

Please use HTML anchors for error codes. For example, the erorr message will link to `#-1` for error code `-1`. Since GitHub Pages automatically create anchors for or headers, just add the title for each error code.
