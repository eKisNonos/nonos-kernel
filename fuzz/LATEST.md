# Latest fuzz run

`eb0f76de3b1c`, 2026-11-11T04:11:07+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/42943367951

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 3263668 | 241 | +0 | 432 | +0 | 42 | +0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1647219782 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 280461214 | 303 | +2 | 362 | +7 | 357 | +1 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 226070605 | 339 | +0 | 618 | +0 | 551 | +7 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 11747663 | 1291 | +2 | 4390 | +13 | 9575 | +458 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 70507854 | 479 | +0 | 2582 | +0 | 5734 | +49 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1550486553 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1646496387 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 323073679 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 334775913 | 217 | +0 | 829 | +0 | 1932 | +24 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 821323255 | 212 | +0 | 504 | +0 | 2073 | +85 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 4153286 | 2050 | +0 | 4536 | +4 | 728 | +5 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 732734191 | 111 | +0 | 307 | +0 | 770 | +7 | 0 |
