## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/44220483149

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 3298208 | 1831 | 241 | 432 | 42 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1661243742 | 922400 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 209974185 | 116587 | 303 | 374 | 359 | 0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 226240739 | 125619 | 339 | 618 | 582 | 5 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 15929979 | 8845 | 1298 | 4431 | 12453 | 270 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 87254122 | 48447 | 479 | 2582 | 6011 | 30 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1261991688 | 700717 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1862704457 | 1034261 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 450716644 | 250259 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 413475827 | 229581 | 217 | 839 | 2132 | 16 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 1097975812 | 609647 | 212 | 504 | 2212 | 5 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 5309395 | 2948 | 2056 | 4564 | 751 | 1 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 735914349 | 408614 | 111 | 307 | 899 | 9 | 0 |
