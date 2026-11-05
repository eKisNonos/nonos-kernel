# Latest fuzz run

`eb0f76de3b1c`, 2026-11-05T03:06:18+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/41952739513

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 4481101 | 241 | +0 | 432 | +0 | 40 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1360268102 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 340186044 | 301 | +0 | 355 | +0 | 356 | +15 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 221280927 | 339 | +0 | 599 | +0 | 499 | +29 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 13218719 | 1261 | +0 | 4175 | +16 | 6145 | +706 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 70542359 | 479 | +0 | 2556 | +0 | 5161 | +198 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1266446938 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1278774037 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 388199419 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 319452154 | 217 | +0 | 829 | +0 | 1622 | +114 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1023142494 | 212 | +0 | 487 | +0 | 1740 | +93 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 3240224 | 2041 | +1 | 4459 | +6 | 663 | +4 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 746580528 | 111 | +0 | 307 | +1 | 625 | +36 | 0 |
