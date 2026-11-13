# Latest fuzz run

`eb0f76de3b1c`, 2026-11-13T03:57:31+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/43349424421

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 3366368 | 241 | +0 | 432 | +0 | 42 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1519388297 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 337621013 | 303 | +0 | 362 | +0 | 357 | +0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 268136515 | 339 | +0 | 618 | +0 | 560 | +3 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 11688736 | 1295 | +2 | 4405 | +6 | 10602 | +446 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 89161334 | 479 | +0 | 2582 | +0 | 5859 | +54 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1747835533 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1663159642 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 511300964 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 393447241 | 217 | +0 | 830 | +0 | 2025 | +79 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 806859700 | 212 | +0 | 504 | +0 | 2157 | +39 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 3536711 | 2050 | +0 | 4547 | +3 | 737 | +3 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 722599701 | 111 | +0 | 307 | +0 | 795 | +15 | 0 |
