# Latest fuzz run

`eb0f76de3b1c`, 2026-11-07T04:07:58+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/42327299630

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 5632933 | 241 | +0 | 432 | +0 | 42 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1659618732 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 247493612 | 301 | +0 | 355 | +0 | 356 | +0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 355735105 | 339 | +0 | 599 | +0 | 526 | +15 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 13343700 | 1267 | +2 | 4289 | +66 | 7461 | +526 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 82260873 | 479 | +0 | 2558 | +2 | 5449 | +132 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 2106518208 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1270642107 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 322115949 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 337499240 | 217 | +0 | 829 | +0 | 1761 | +66 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 686671378 | 212 | +0 | 495 | +3 | 1839 | +57 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 4529200 | 2047 | +3 | 4497 | +28 | 690 | +19 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 906113233 | 111 | +0 | 307 | +0 | 703 | +33 | 0 |
