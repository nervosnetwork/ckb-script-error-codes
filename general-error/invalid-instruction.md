# Invalid Instruction Error in CKB-VM

## Supported RISC-V Extensions

The CKB-VM supports the following RISC-V extensions:

- I (Base Integer Instruction Set)
- M (Integer Multiplication and Division)
- B (Bit Manipulation)
- C (Compressed Instructions)

## Identifying Invalid Instructions

When an `InvalidInstruction` error occurs, it indicates that the instruction is
not part of the supported instruction sets listed above.

### Using CKB-Debugger for Analysis

You can analyze the problematic instruction using the
[ckb-debugger](https://github.com/nervosnetwork/ckb-standalone-debugger) tool:

```bash
ckb-debugger --mode decode-instruction <instruction>
```

#### Example

```bash
$ ckb-debugger --mode decode-instruction 336213423
       Assembly = lr_d a1,s4,zero
         Binary = 00010100000010100011010110101111
    Hexadecimal = 140a35af
Instruction set = A
```

## Resolving Atomic Instructions

If the instruction set is identified as `A`, it means it's an atomic
instruction. These are not supported by default in CKB-VM. To resolve issues
with atomic instructions, refer to the [CKB Script Templates
repository](https://github.com/cryptape/ckb-script-templates/tree/main?tab=readme-ov-file#molecule-uses-bytes-crates).

## Additional Resources

- [ckb-std](https://github.com/nervosnetwork/ckb-std)
- [CKB-VM Documentation](https://github.com/nervosnetwork/ckb-vm)
- [RISC-V Specification](https://riscv.org/technical/specifications/)
