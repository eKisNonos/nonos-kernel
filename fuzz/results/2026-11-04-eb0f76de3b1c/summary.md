## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/41758257173

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 5338201 | 2964 | 241 | 432 | 40 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1265337092 | 702574 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 236046372 | 131064 | 301 | 355 | 341 | 1 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 242628268 | 134718 | 339 | 599 | 470 | 26 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 10815553 | 6005 | 1261 | 4159 | 5439 | 764 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 69422228 | 38546 | 479 | 2556 | 4963 | 317 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1164188398 | 646412 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1354987097 | 752352 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 387621089 | 215225 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 369615920 | 205228 | 217 | 829 | 1508 | 250 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 858166169 | 476494 | 212 | 487 | 1647 | 96 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 3080256 | 1710 | 2040 | 4453 | 659 | 18 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 1158841599 | 643443 | 111 | 306 | 589 | 67 | 0 |
