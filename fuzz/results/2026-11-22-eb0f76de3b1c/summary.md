## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/44974326717

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 3375898 | 1874 | 241 | 432 | 42 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1259149122 | 699138 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 193921856 | 107674 | 303 | 406 | 375 | 0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 322735264 | 179197 | 339 | 618 | 596 | 5 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 12524934 | 6954 | 1300 | 4450 | 13373 | 202 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 55025726 | 30552 | 479 | 2582 | 6103 | 15 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1538143368 | 854049 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1290861417 | 716747 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 503592019 | 279618 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 392244333 | 217792 | 217 | 848 | 2203 | 19 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 1113599461 | 618322 | 212 | 504 | 2251 | 2 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 3888792 | 2159 | 2058 | 4585 | 771 | 0 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 1027944436 | 570763 | 111 | 307 | 957 | 19 | 0 |
