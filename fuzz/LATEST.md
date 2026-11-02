# Latest fuzz run

`eb0f76de3b1c`, 2026-11-02T04:10:19+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/41375710305

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 3430801 | 241 | +0 | 432 | +0 | 40 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1263492477 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 279591843 | 301 | +0 | 355 | +0 | 339 | +8 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 337951603 | 339 | +0 | 596 | +0 | 392 | +53 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 8347550 | 1255 | +3 | 4056 | +46 | 3730 | +925 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 94544965 | 479 | +1 | 2550 | +14 | 4122 | +1278 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1186551188 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1361448722 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 399255094 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 371527004 | 217 | +4 | 829 | +17 | 896 | +205 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1020239889 | 210 | +7 | 468 | +27 | 1479 | +416 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 3264489 | 2000 | +14 | 4319 | +53 | 584 | +41 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 712375018 | 111 | +1 | 304 | +11 | 446 | +86 | 0 |
