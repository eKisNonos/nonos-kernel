## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/41952739513

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 4481101 | 2488 | 241 | 432 | 40 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1360268102 | 755284 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 340186044 | 188887 | 301 | 355 | 356 | 15 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 221280927 | 122865 | 339 | 599 | 499 | 29 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 13218719 | 7339 | 1261 | 4175 | 6145 | 706 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 70542359 | 39168 | 479 | 2556 | 5161 | 198 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1266446938 | 703190 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1278774037 | 710035 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 388199419 | 215546 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 319452154 | 177374 | 217 | 829 | 1622 | 114 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 1023142494 | 568096 | 212 | 487 | 1740 | 93 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 3240224 | 1799 | 2041 | 4459 | 663 | 4 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 746580528 | 414536 | 111 | 307 | 625 | 36 | 0 |
