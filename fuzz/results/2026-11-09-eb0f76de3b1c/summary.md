## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/42548815100

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 3381458 | 1877 | 241 | 432 | 42 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1663974717 | 923917 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 246542932 | 136892 | 301 | 355 | 356 | 0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 226048942 | 125513 | 339 | 618 | 539 | 4 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 12336945 | 6850 | 1286 | 4350 | 8543 | 538 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 82179094 | 45629 | 479 | 2582 | 5635 | 83 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1874095978 | 1040586 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1258923742 | 699013 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 340317089 | 188960 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 456870592 | 253676 | 217 | 829 | 1882 | 64 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 998546498 | 554440 | 212 | 504 | 1927 | 55 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 3830052 | 2126 | 2047 | 4502 | 712 | 17 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 903876883 | 501875 | 111 | 307 | 741 | 26 | 0 |
