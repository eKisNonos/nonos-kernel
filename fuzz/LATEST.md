# Latest fuzz run

`eb0f76de3b1c`, 2026-11-14T03:35:12+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/43544196706

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 3335553 | 241 | +0 | 432 | +0 | 42 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1630355887 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 347825809 | 303 | +0 | 367 | +5 | 358 | +1 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 267680006 | 339 | +0 | 618 | +0 | 569 | +9 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 18129467 | 1295 | +0 | 4413 | +8 | 11148 | +546 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 55068326 | 479 | +0 | 2582 | +0 | 5897 | +38 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1187225263 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1644407292 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 400751249 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 203504711 | 217 | +0 | 838 | +8 | 2048 | +23 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 805211630 | 212 | +0 | 504 | +0 | 2197 | +40 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 3121239 | 2051 | +1 | 4549 | +2 | 740 | +3 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1131258033 | 111 | +0 | 307 | +0 | 844 | +49 | 0 |
