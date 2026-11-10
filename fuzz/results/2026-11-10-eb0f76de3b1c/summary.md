## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/42740135993

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 3314148 | 1840 | 241 | 432 | 42 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1641152067 | 911244 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 267711537 | 148646 | 301 | 355 | 356 | 0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 350567660 | 194651 | 339 | 618 | 544 | 5 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 12043418 | 6687 | 1289 | 4377 | 9117 | 574 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 60380855 | 33526 | 479 | 2582 | 5685 | 50 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 2021527583 | 1122447 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1630949757 | 905580 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 332673639 | 184716 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 534792430 | 296941 | 217 | 829 | 1908 | 26 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 802221050 | 445430 | 212 | 504 | 1988 | 61 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 4627407 | 2569 | 2050 | 4532 | 723 | 11 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 736060953 | 408695 | 111 | 307 | 763 | 22 | 0 |
