# Latest fuzz run

`eb0f76de3b1c`, 2026-11-19T03:27:46+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/44441516491

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 4472273 | 241 | +0 | 432 | +0 | 42 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1657777067 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 319735273 | 303 | +0 | 389 | +15 | 360 | +1 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 227107692 | 339 | +0 | 618 | +0 | 588 | +6 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 12382148 | 1298 | +0 | 4434 | +3 | 12699 | +246 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 54538000 | 479 | +0 | 2582 | +0 | 6038 | +27 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1730781658 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1655810737 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 481474814 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 336293701 | 217 | +0 | 839 | +0 | 2153 | +21 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1115298585 | 212 | +0 | 504 | +0 | 2218 | +6 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 4241563 | 2057 | +1 | 4572 | +8 | 755 | +4 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1171808425 | 111 | +0 | 307 | +0 | 907 | +8 | 0 |
