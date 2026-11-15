# Latest fuzz run

`eb0f76de3b1c`, 2026-11-15T04:00:37+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/43665988405

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 4483403 | 241 | +0 | 432 | +0 | 42 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1854562532 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 241172649 | 303 | +0 | 374 | +7 | 359 | +1 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 223666966 | 339 | +0 | 618 | +0 | 572 | +3 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 11596582 | 1295 | +0 | 4417 | +4 | 11490 | +342 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 57225353 | 479 | +0 | 2582 | +0 | 5927 | +30 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1167781263 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1283968157 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 329410229 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 326918071 | 217 | +0 | 838 | +0 | 2074 | +26 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 799818588 | 212 | +0 | 504 | +0 | 2201 | +4 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 4033267 | 2051 | +0 | 4552 | +3 | 743 | +3 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 754559384 | 111 | +0 | 307 | +0 | 863 | +19 | 0 |
