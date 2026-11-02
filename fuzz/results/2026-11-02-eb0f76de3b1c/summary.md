## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/41375710305

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 3430801 | 1904 | 241 | 432 | 40 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1263492477 | 701550 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 279591843 | 155242 | 301 | 355 | 339 | 8 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 337951603 | 187646 | 339 | 596 | 392 | 53 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 8347550 | 4634 | 1255 | 4056 | 3730 | 925 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 94544965 | 52495 | 479 | 2550 | 4122 | 1278 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1186551188 | 658829 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1361448722 | 755940 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 399255094 | 221685 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 371527004 | 206289 | 217 | 829 | 896 | 205 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 1020239889 | 566485 | 210 | 468 | 1479 | 416 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 3264489 | 1812 | 2000 | 4319 | 584 | 41 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 712375018 | 395544 | 111 | 304 | 446 | 86 | 0 |
