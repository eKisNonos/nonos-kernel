## Fuzz run `eb0f76de3b1c` (push)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/41228050090

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 120 | 255265 | 2109 | 240 | 427 | 31 | 31 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 120 | 83673416 | 691515 | 81 | 83 | 76 | 58 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 120 | 22044637 | 182187 | 301 | 355 | 229 | 64 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 120 | 16027050 | 132454 | 330 | 502 | 226 | 61 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 120 | 2065948 | 17073 | 1164 | 3499 | 1061 | 1061 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 120 | 7997626 | 66096 | 429 | 1419 | 225 | 225 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 120 | 83555362 | 690540 | 177 | 178 | 41 | 41 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 120 | 85784980 | 708966 | 35 | 36 | 5 | 5 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 120 | 20555214 | 169877 | 107 | 110 | 13 | 10 | 0 |
| `userland/net_proofs` | `dns` | pass | 120 | 20668762 | 170816 | 213 | 786 | 366 | 366 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 120 | 54844242 | 453258 | 203 | 424 | 198 | 198 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 120 | 355076 | 2934 | 1759 | 3884 | 387 | 370 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 120 | 67133621 | 554823 | 103 | 227 | 84 | 84 | 0 |
