## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/43665988405

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 4483403 | 2489 | 241 | 432 | 42 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1854562532 | 1029740 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 241172649 | 133910 | 303 | 374 | 359 | 1 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 223666966 | 124190 | 339 | 618 | 572 | 3 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 11596582 | 6438 | 1295 | 4417 | 11490 | 342 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 57225353 | 31774 | 479 | 2582 | 5927 | 30 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1167781263 | 648407 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1283968157 | 712919 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 329410229 | 182904 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 326918071 | 181520 | 217 | 838 | 2074 | 26 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 799818588 | 444096 | 212 | 504 | 2201 | 4 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 4033267 | 2239 | 2051 | 4552 | 743 | 3 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 754559384 | 418966 | 111 | 307 | 863 | 19 | 0 |
