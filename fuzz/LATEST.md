# Latest fuzz run

`eb0f76de3b1c`, 2026-11-10T03:31:28+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/42740135993

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 3314148 | 241 | +0 | 432 | +0 | 42 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1641152067 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 267711537 | 301 | +0 | 355 | +0 | 356 | +0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 350567660 | 339 | +0 | 618 | +0 | 544 | +5 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 12043418 | 1289 | +3 | 4377 | +27 | 9117 | +574 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 60380855 | 479 | +0 | 2582 | +0 | 5685 | +50 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 2021527583 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1630949757 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 332673639 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 534792430 | 217 | +0 | 829 | +0 | 1908 | +26 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 802221050 | 212 | +0 | 504 | +0 | 1988 | +61 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 4627407 | 2050 | +3 | 4532 | +30 | 723 | +11 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 736060953 | 111 | +0 | 307 | +0 | 763 | +22 | 0 |
