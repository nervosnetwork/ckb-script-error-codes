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

## Index

* TYPE\_ID
    * By type hash [00000000000000000000000000000000000000000000000000545950455f4944](by-type-hash/00000000000000000000000000000000000000000000000000545950455f4944.md)
* DAO
    * By type hash [82d76d1b75fe2fd9a27dfbaa65a039221a380d76c926f378d3f81cf3e7e13f2e](by-type-hash/82d76d1b75fe2fd9a27dfbaa65a039221a380d76c926f378d3f81cf3e7e13f2e.md)
    * By data hash
        * [32064a14ce10d95d4b7343054cc19d73b25b16ae61a6c681011ca781a60c7923](by-data-hash/32064a14ce10d95d4b7343054cc19d73b25b16ae61a6c681011ca781a60c7923.md) (the latest version)
* secp256k1-blake160-sighash-all
    * By type hash [9bd7e06f3ecf4be0f2fcd2188b23f1b9fcc88e5d4b65a8637b17723bbda3cce8](by-type-hash/9bd7e06f3ecf4be0f2fcd2188b23f1b9fcc88e5d4b65a8637b17723bbda3cce8.md)
    * By data hash
        * [709f3fda12f561cfacf92273c57a98fede188a3f1a59b1f888d113f9cce08649](by-data-hash/709f3fda12f561cfacf92273c57a98fede188a3f1a59b1f888d113f9cce08649.md) (the latest version)
* secp256k1-blake160-multisig-all
    * By type hash [5c5069eb0857efc65e1bca0c07df34c31663b3622fd3876c876320fc9634e2a8](by-type-hash/5c5069eb0857efc65e1bca0c07df34c31663b3622fd3876c876320fc9634e2a8.md)
    * By data hash
        * [43400de165f0821abf63dcac299bbdf7fd73898675ee4ddb099b0a0d8db63bfb](by-data-hash/43400de165f0821abf63dcac299bbdf7fd73898675ee4ddb099b0a0d8db63bfb.md) (the latest version)

* RGB++
    * By type hash [bc6c568a1a0d0a09f6844dc9d74ddb4343c32143ff25f727c59edf4fb72d6936](by-type-hash/bc6c568a1a0d0a09f6844dc9d74ddb4343c32143ff25f727c59edf4fb72d6936.md)
* BTC Time lock
    * By type hash [70d64497a075bd651e98ac030455ea200637ee325a12ad08aff03f1a117e5a62](by-type-hash/70d64497a075bd651e98ac030455ea200637ee325a12ad08aff03f1a117e5a62.md)
* Omnilock
    * By type hash [9b819793a64463aed77c615d6cb226eea5487ccfc0783043a587254cda2b6f26](by-type-hash/9b819793a64463aed77c615d6cb226eea5487ccfc0783043a587254cda2b6f26.md)
* xUDT
    * By data hash [50bd8d6680b8b9cf98b73f3c08faf8b2a21914311954118ad6609be6e78a1b95](by-data-hash/50bd8d6680b8b9cf98b73f3c08faf8b2a21914311954118ad6609be6e78a1b95.md)

