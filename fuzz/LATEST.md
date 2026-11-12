# Latest fuzz run

`eb0f76de3b1c`, 2026-11-12T04:11:05+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/43138753336

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 3342013 | 241 | +0 | 432 | +0 | 42 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1671422847 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 262677078 | 303 | +0 | 362 | +0 | 357 | +0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 268822842 | 339 | +0 | 618 | +0 | 557 | +6 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 12693981 | 1293 | +2 | 4399 | +9 | 10156 | +581 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 68654590 | 479 | +0 | 2582 | +0 | 5805 | +71 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1156014148 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1657293417 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 498098089 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 295362448 | 217 | +0 | 830 | +1 | 1946 | +14 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1179226923 | 212 | +0 | 504 | +0 | 2118 | +45 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 3959652 | 2050 | +0 | 4544 | +8 | 734 | +6 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 895347245 | 111 | +0 | 307 | +0 | 780 | +10 | 0 |
