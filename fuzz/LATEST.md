# Latest fuzz run

`eb0f76de3b1c`, 2026-11-03T04:11:16+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/41563796047

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 3354266 | 241 | +0 | 432 | +0 | 40 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1397882367 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 337652885 | 301 | +0 | 355 | +0 | 340 | +1 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 266085531 | 339 | +0 | 596 | +0 | 444 | +52 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 16869971 | 1258 | +3 | 4109 | +53 | 4675 | +945 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 76272815 | 479 | +0 | 2556 | +6 | 4646 | +524 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1928745753 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1661271577 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 483977774 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 312845823 | 217 | +0 | 829 | +0 | 1258 | +362 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 846515981 | 212 | +2 | 477 | +9 | 1551 | +72 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 4853857 | 2038 | +38 | 4442 | +123 | 641 | +57 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 784951362 | 111 | +0 | 305 | +1 | 522 | +76 | 0 |
