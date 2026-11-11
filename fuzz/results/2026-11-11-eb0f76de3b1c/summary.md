## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/42943367951

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 3263668 | 1812 | 241 | 432 | 42 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1647219782 | 914613 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 280461214 | 155725 | 303 | 362 | 357 | 1 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 226070605 | 125525 | 339 | 618 | 551 | 7 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 11747663 | 6522 | 1291 | 4390 | 9575 | 458 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 70507854 | 39149 | 479 | 2582 | 5734 | 49 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1550486553 | 860903 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1646496387 | 914212 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 323073679 | 179385 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 334775913 | 185883 | 217 | 829 | 1932 | 24 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 821323255 | 456037 | 212 | 504 | 2073 | 85 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 4153286 | 2306 | 2050 | 4536 | 728 | 5 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 732734191 | 406848 | 111 | 307 | 770 | 7 | 0 |
