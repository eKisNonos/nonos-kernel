## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/45098055297

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 3373973 | 1873 | 241 | 432 | 42 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1265479967 | 702654 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 255539871 | 141887 | 303 | 406 | 375 | 0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 249472213 | 138518 | 339 | 618 | 598 | 2 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 10996074 | 6105 | 1303 | 4455 | 13515 | 142 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 54473388 | 30246 | 479 | 2582 | 6127 | 24 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1955118968 | 1085574 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1278677537 | 709981 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 331074709 | 183828 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 321335499 | 178420 | 217 | 848 | 2216 | 13 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 1296956786 | 720131 | 212 | 506 | 2263 | 12 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 3837932 | 2131 | 2058 | 4585 | 774 | 3 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 702501871 | 390062 | 111 | 307 | 960 | 3 | 0 |
