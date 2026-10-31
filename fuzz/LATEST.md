# Latest fuzz run

`eb0f76de3b1c`, 2026-10-31T20:45:14+00:00, push. https://github.com/eKisNonos/nonos-kernel/actions/runs/41228050090

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 255265 | 240 |  | 427 |  | 31 |  | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 83673416 | 81 |  | 83 |  | 76 |  | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 22044637 | 301 |  | 355 |  | 229 |  | 0 |
| `userland/admission_proofs` | `manifest` | pass | 16027050 | 330 |  | 502 |  | 226 |  | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 2065948 | 1164 |  | 3499 |  | 1061 |  | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 7997626 | 429 |  | 1419 |  | 225 |  | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 83555362 | 177 |  | 178 |  | 41 |  | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 85784980 | 35 |  | 36 |  | 5 |  | 0 |
| `userland/market_proto` | `linux_policy` | pass | 20555214 | 107 |  | 110 |  | 13 |  | 0 |
| `userland/net_proofs` | `dns` | pass | 20668762 | 213 |  | 786 |  | 366 |  | 0 |
| `userland/net_proofs` | `net_packets` | pass | 54844242 | 203 |  | 424 |  | 198 |  | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 355076 | 1759 |  | 3884 |  | 387 |  | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 67133621 | 103 |  | 227 |  | 84 |  | 0 |
