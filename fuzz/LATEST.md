# Latest fuzz run

`eb0f76de3b1c`, 2026-11-17T03:40:06+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/44000229790

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 4643368 | 241 | +0 | 432 | +0 | 42 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1718237722 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 191390235 | 303 | +0 | 374 | +0 | 359 | +0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 232982085 | 339 | +0 | 618 | +0 | 577 | +3 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 13154365 | 1298 | +0 | 4425 | +1 | 12183 | +344 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 69377807 | 479 | +0 | 2582 | +0 | 5981 | +26 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1175175313 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1924129402 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 339107254 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 324815507 | 217 | +0 | 839 | +0 | 2116 | +22 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 4847348 | 2056 | +2 | 4563 | +4 | 750 | +3 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 731815668 | 111 | +0 | 307 | +0 | 890 | +9 | 0 |
