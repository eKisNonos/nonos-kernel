## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/43349424421

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 3366368 | 1869 | 241 | 432 | 42 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1519388297 | 843635 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 337621013 | 187463 | 303 | 362 | 357 | 0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 268136515 | 148882 | 339 | 618 | 560 | 3 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 11688736 | 6490 | 1295 | 4405 | 10602 | 446 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 89161334 | 49506 | 479 | 2582 | 5859 | 54 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1747835533 | 970480 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1663159642 | 923464 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 511300964 | 283898 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 393447241 | 218460 | 217 | 830 | 2025 | 79 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 806859700 | 448006 | 212 | 504 | 2157 | 39 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 3536711 | 1963 | 2050 | 4547 | 737 | 3 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 722599701 | 401221 | 111 | 307 | 795 | 15 | 0 |
