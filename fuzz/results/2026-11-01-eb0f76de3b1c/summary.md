## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/41263648005

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 4313396 | 2395 | 241 | 432 | 40 | 9 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 2104166317 | 1168332 | 81 | 83 | 86 | 10 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 289301932 | 160634 | 301 | 355 | 331 | 102 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 185451245 | 102971 | 339 | 596 | 339 | 113 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 8381554 | 4653 | 1252 | 4010 | 2805 | 1744 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 69590713 | 38640 | 478 | 2536 | 2844 | 2619 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1285774352 | 713922 | 177 | 178 | 42 | 1 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1664883027 | 924421 | 35 | 36 | 6 | 1 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 398557404 | 221297 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 180655593 | 100308 | 213 | 812 | 691 | 325 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 775014429 | 430324 | 203 | 441 | 1063 | 865 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 2670814 | 1482 | 1986 | 4266 | 543 | 156 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 932228369 | 517617 | 110 | 293 | 360 | 276 | 0 |
