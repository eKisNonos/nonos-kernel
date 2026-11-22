# Latest fuzz run

`eb0f76de3b1c`, 2026-11-22T03:54:35+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/44974326717

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 3375898 | 241 | +0 | 432 | +0 | 42 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1259149122 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 193921856 | 303 | +0 | 406 | +0 | 375 | +0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 322735264 | 339 | +0 | 618 | +0 | 596 | +5 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 12524934 | 1300 | +0 | 4450 | +3 | 13373 | +202 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 55025726 | 479 | +0 | 2582 | +0 | 6103 | +15 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1538143368 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1290861417 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 503592019 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 392244333 | 217 | +0 | 848 | +0 | 2203 | +19 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1113599461 | 212 | +0 | 504 | +0 | 2251 | +2 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 3888792 | 2058 | +0 | 4585 | +0 | 771 | +0 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1027944436 | 111 | +0 | 307 | +0 | 957 | +19 | 0 |
