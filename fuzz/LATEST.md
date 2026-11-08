# Latest fuzz run

`eb0f76de3b1c`, 2026-11-08T03:26:51+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/42436908869

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 4461558 | 241 | +0 | 432 | +0 | 42 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1649677392 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 267553177 | 301 | +0 | 355 | +0 | 356 | +0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 259156002 | 339 | +0 | 618 | +19 | 535 | +9 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 10504158 | 1276 | +9 | 4316 | +27 | 8005 | +544 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 70260503 | 479 | +0 | 2581 | +23 | 5552 | +103 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1173089123 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1577358192 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 484126234 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 332025291 | 217 | +0 | 829 | +0 | 1818 | +57 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 797868020 | 212 | +0 | 495 | +0 | 1872 | +33 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 3411126 | 2047 | +0 | 4500 | +3 | 695 | +5 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 683132457 | 111 | +0 | 307 | +0 | 715 | +12 | 0 |
