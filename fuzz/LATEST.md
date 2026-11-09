# Latest fuzz run

`eb0f76de3b1c`, 2026-11-09T04:11:25+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/42548815100

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 3381458 | 241 | +0 | 432 | +0 | 42 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1663974717 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 246542932 | 301 | +0 | 355 | +0 | 356 | +0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 226048942 | 339 | +0 | 618 | +0 | 539 | +4 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 12336945 | 1286 | +10 | 4350 | +34 | 8543 | +538 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 82179094 | 479 | +0 | 2582 | +1 | 5635 | +83 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1874095978 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1258923742 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 340317089 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 456870592 | 217 | +0 | 829 | +0 | 1882 | +64 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 998546498 | 212 | +0 | 504 | +9 | 1927 | +55 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 3830052 | 2047 | +0 | 4502 | +2 | 712 | +17 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 903876883 | 111 | +0 | 307 | +0 | 741 | +26 | 0 |
