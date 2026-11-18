# Latest fuzz run

`eb0f76de3b1c`, 2026-11-18T03:33:00+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/44220483149

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 3298208 | 241 | +0 | 432 | +0 | 42 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1661243742 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 209974185 | 303 | +0 | 374 | +0 | 359 | +0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 226240739 | 339 | +0 | 618 | +0 | 582 | +5 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 15929979 | 1298 | +0 | 4431 | +6 | 12453 | +270 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 87254122 | 479 | +0 | 2582 | +0 | 6011 | +30 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1261991688 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1862704457 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 450716644 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 413475827 | 217 | +0 | 839 | +0 | 2132 | +16 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1097975812 | 212 | +0 | 504 | +0 | 2212 | +5 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 5309395 | 2056 | +0 | 4564 | +1 | 751 | +1 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 735914349 | 111 | +0 | 307 | +0 | 899 | +9 | 0 |
