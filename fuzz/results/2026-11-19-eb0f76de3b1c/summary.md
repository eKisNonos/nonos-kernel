## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/44441516491

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 4472273 | 2483 | 241 | 432 | 42 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1657777067 | 920475 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 319735273 | 177532 | 303 | 389 | 360 | 1 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 227107692 | 126100 | 339 | 618 | 588 | 6 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 12382148 | 6875 | 1298 | 4434 | 12699 | 246 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 54538000 | 30282 | 479 | 2582 | 6038 | 27 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1730781658 | 961011 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1655810737 | 919384 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 481474814 | 267337 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 336293701 | 186726 | 217 | 839 | 2153 | 21 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 1115298585 | 619266 | 212 | 504 | 2218 | 6 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 4241563 | 2355 | 2057 | 4572 | 755 | 4 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 1171808425 | 650643 | 111 | 307 | 907 | 8 | 0 |
