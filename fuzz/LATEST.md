# Latest fuzz run

`eb0f76de3b1c`, 2026-11-23T03:35:11+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/45098055297

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 3373973 | 241 | +0 | 432 | +0 | 42 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1265479967 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 255539871 | 303 | +0 | 406 | +0 | 375 | +0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 249472213 | 339 | +0 | 618 | +0 | 598 | +2 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 10996074 | 1303 | +3 | 4455 | +5 | 13515 | +142 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 54473388 | 479 | +0 | 2582 | +0 | 6127 | +24 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1955118968 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1278677537 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 331074709 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 321335499 | 217 | +0 | 848 | +0 | 2216 | +13 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1296956786 | 212 | +0 | 506 | +2 | 2263 | +12 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 3837932 | 2058 | +0 | 4585 | +0 | 774 | +3 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 702501871 | 111 | +0 | 307 | +0 | 960 | +3 | 0 |
