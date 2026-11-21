# Latest fuzz run

`eb0f76de3b1c`, 2026-11-21T03:23:09+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/44853744321

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 3344498 | 241 | +0 | 432 | +0 | 42 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1844117817 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 201574246 | 303 | +0 | 406 | +0 | 375 | +0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 394473657 | 339 | +0 | 618 | +0 | 591 | +0 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 17939369 | 1300 | +2 | 4447 | +11 | 13171 | +348 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 69585187 | 479 | +0 | 2582 | +0 | 6088 | +21 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 2051314083 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 2003659467 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 337022489 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 324108559 | 217 | +0 | 848 | +0 | 2184 | +13 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1206742555 | 212 | +0 | 504 | +0 | 2249 | +11 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 5408596 | 2058 | +0 | 4585 | +0 | 771 | +6 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 750822833 | 111 | +0 | 307 | +0 | 938 | +26 | 0 |
