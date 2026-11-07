## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/42327299630

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 5632933 | 3127 | 241 | 432 | 42 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1659618732 | 921498 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 247493612 | 137420 | 301 | 355 | 356 | 0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 355735105 | 197520 | 339 | 599 | 526 | 15 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 13343700 | 7409 | 1267 | 4289 | 7461 | 526 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 82260873 | 45675 | 479 | 2558 | 5449 | 132 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 2106518208 | 1169638 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1270642107 | 705520 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 322115949 | 178853 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 337499240 | 187395 | 217 | 829 | 1761 | 66 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 686671378 | 381272 | 212 | 495 | 1839 | 57 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 4529200 | 2514 | 2047 | 4497 | 690 | 19 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 906113233 | 503116 | 111 | 307 | 703 | 33 | 0 |
