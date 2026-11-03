## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/41563796047

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 3354266 | 1862 | 241 | 432 | 40 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1397882367 | 776170 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 337652885 | 187480 | 301 | 355 | 340 | 1 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 266085531 | 147743 | 339 | 596 | 444 | 52 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 16869971 | 9367 | 1258 | 4109 | 4675 | 945 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 76272815 | 42350 | 479 | 2556 | 4646 | 524 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1928745753 | 1070930 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1661271577 | 922416 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 483977774 | 268727 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 312845823 | 173706 | 217 | 829 | 1258 | 362 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 846515981 | 470025 | 212 | 477 | 1551 | 72 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 4853857 | 2695 | 2038 | 4442 | 641 | 57 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 784951362 | 435841 | 111 | 305 | 522 | 76 | 0 |
