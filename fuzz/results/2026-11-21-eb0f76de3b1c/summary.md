## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/44853744321

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 3344498 | 1857 | 241 | 432 | 42 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1844117817 | 1023941 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 201574246 | 111923 | 303 | 406 | 375 | 0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 394473657 | 219030 | 339 | 618 | 591 | 0 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 17939369 | 9960 | 1300 | 4447 | 13171 | 348 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 69585187 | 38636 | 479 | 2582 | 6088 | 21 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 2051314083 | 1138986 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 2003659467 | 1112526 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 337022489 | 187130 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 324108559 | 179960 | 217 | 848 | 2184 | 13 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 1206742555 | 670040 | 212 | 504 | 2249 | 11 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 5408596 | 3003 | 2058 | 4585 | 771 | 6 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 750822833 | 416892 | 111 | 307 | 938 | 26 | 0 |
