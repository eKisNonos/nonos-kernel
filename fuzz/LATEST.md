# Latest fuzz run

`eb0f76de3b1c`, 2026-11-01T04:12:25+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/41263648005

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 4313396 | 241 |  | 432 |  | 40 |  | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 2104166317 | 81 |  | 83 |  | 86 |  | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 289301932 | 301 |  | 355 |  | 331 |  | 0 |
| `userland/admission_proofs` | `manifest` | pass | 185451245 | 339 |  | 596 |  | 339 |  | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 8381554 | 1252 |  | 4010 |  | 2805 |  | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 69590713 | 478 |  | 2536 |  | 2844 |  | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1285774352 | 177 |  | 178 |  | 42 |  | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1664883027 | 35 |  | 36 |  | 6 |  | 0 |
| `userland/market_proto` | `linux_policy` | pass | 398557404 | 107 |  | 110 |  | 13 |  | 0 |
| `userland/net_proofs` | `dns` | pass | 180655593 | 213 |  | 812 |  | 691 |  | 0 |
| `userland/net_proofs` | `net_packets` | pass | 775014429 | 203 |  | 441 |  | 1063 |  | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 2670814 | 1986 |  | 4266 |  | 543 |  | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 932228369 | 110 |  | 293 |  | 360 |  | 0 |
