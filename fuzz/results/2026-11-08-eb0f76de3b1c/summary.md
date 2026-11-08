## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/42436908869

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 4461558 | 2477 | 241 | 432 | 42 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1649677392 | 915978 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 267553177 | 148558 | 301 | 355 | 356 | 0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 259156002 | 143895 | 339 | 618 | 535 | 9 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 10504158 | 5832 | 1276 | 4316 | 8005 | 544 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 70260503 | 39011 | 479 | 2581 | 5552 | 103 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1173089123 | 651354 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1577358192 | 875823 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 484126234 | 268809 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 332025291 | 184356 | 217 | 829 | 1818 | 57 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 797868020 | 443013 | 212 | 495 | 1872 | 33 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 3411126 | 1894 | 2047 | 4500 | 695 | 5 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 683132457 | 379307 | 111 | 307 | 715 | 12 | 0 |
