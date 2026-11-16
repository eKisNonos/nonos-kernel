# Latest fuzz run

`eb0f76de3b1c`, 2026-11-16T03:28:44+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/43789910514

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 5346288 | 241 | +0 | 432 | +0 | 42 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1199252177 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 213894255 | 303 | +0 | 374 | +0 | 359 | +0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 274726063 | 339 | +0 | 618 | +0 | 574 | +2 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 12945158 | 1298 | +3 | 4424 | +7 | 11839 | +349 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 66343382 | 479 | +0 | 2582 | +0 | 5955 | +28 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1513136388 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1263029262 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 485003859 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 188555174 | 217 | +0 | 839 | +1 | 2094 | +20 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 793656590 | 212 | +0 | 504 | +0 | 2207 | +6 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 5103741 | 2054 | +3 | 4559 | +7 | 747 | +4 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 722347882 | 111 | +0 | 307 | +0 | 881 | +18 | 0 |
