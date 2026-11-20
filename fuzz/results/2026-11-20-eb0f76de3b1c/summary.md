## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/44658086388

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 3358198 | 1864 | 241 | 432 | 42 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1669440072 | 926951 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 281627579 | 156372 | 303 | 406 | 375 | 15 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 328240612 | 182254 | 339 | 618 | 591 | 3 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 11428155 | 6345 | 1298 | 4436 | 12823 | 124 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 56352697 | 31289 | 479 | 2582 | 6067 | 29 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1715146803 | 952330 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1653290062 | 917984 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 332908504 | 184846 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 248667030 | 138071 | 217 | 848 | 2171 | 18 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 814999438 | 452526 | 212 | 504 | 2238 | 20 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 4729105 | 2625 | 2058 | 4585 | 765 | 10 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 707455138 | 392812 | 111 | 307 | 912 | 5 | 0 |
