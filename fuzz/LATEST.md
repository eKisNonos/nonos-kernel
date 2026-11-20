# Latest fuzz run

`eb0f76de3b1c`, 2026-11-20T04:14:16+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/44658086388

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 3358198 | 241 | +0 | 432 | +0 | 42 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1669440072 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 281627579 | 303 | +0 | 406 | +17 | 375 | +15 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 328240612 | 339 | +0 | 618 | +0 | 591 | +3 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 11428155 | 1298 | +0 | 4436 | +2 | 12823 | +124 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 56352697 | 479 | +0 | 2582 | +0 | 6067 | +29 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1715146803 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1653290062 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 332908504 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 248667030 | 217 | +0 | 848 | +9 | 2171 | +18 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 814999438 | 212 | +0 | 504 | +0 | 2238 | +20 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 4729105 | 2058 | +1 | 4585 | +13 | 765 | +10 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 707455138 | 111 | +0 | 307 | +0 | 912 | +5 | 0 |
