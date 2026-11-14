## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/43544196706

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 3335553 | 1852 | 241 | 432 | 42 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1630355887 | 905250 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 347825809 | 193129 | 303 | 367 | 358 | 1 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 267680006 | 148628 | 339 | 618 | 569 | 9 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 18129467 | 10066 | 1295 | 4413 | 11148 | 546 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 55068326 | 30576 | 479 | 2582 | 5897 | 38 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1187225263 | 659203 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1644407292 | 913052 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 400751249 | 222515 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 203504711 | 112995 | 217 | 838 | 2048 | 23 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 805211630 | 447091 | 212 | 504 | 2197 | 40 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 3121239 | 1733 | 2051 | 4549 | 740 | 3 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 1131258033 | 628127 | 111 | 307 | 844 | 49 | 0 |
