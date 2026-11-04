# Latest fuzz run

`eb0f76de3b1c`, 2026-11-04T04:09:07+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/41758257173

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 5338201 | 241 | +0 | 432 | +0 | 40 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1265337092 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 236046372 | 301 | +0 | 355 | +0 | 341 | +1 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 242628268 | 339 | +0 | 599 | +3 | 470 | +26 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 10815553 | 1261 | +3 | 4159 | +50 | 5439 | +764 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 69422228 | 479 | +0 | 2556 | +0 | 4963 | +317 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1164188398 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1354987097 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 387621089 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 369615920 | 217 | +0 | 829 | +0 | 1508 | +250 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 858166169 | 212 | +0 | 487 | +10 | 1647 | +96 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 3080256 | 2040 | +2 | 4453 | +11 | 659 | +18 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1158841599 | 111 | +0 | 306 | +1 | 589 | +67 | 0 |
