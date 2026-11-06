# Latest fuzz run

`eb0f76de3b1c`, 2026-11-06T04:09:30+00:00, schedule. https://github.com/eKisNonos/nonos-kernel/actions/runs/42147934974

Coverage and corpus against the previous run of each target for the same length of time.

| crate | target | status | execs | cov | Δ cov | features | Δ features | corpus | Δ corpus | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 5323173 | 241 | +0 | 432 | +0 | 42 | +2 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 2066722397 | 81 | +0 | 83 | +0 | 86 | +0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 239276487 | 301 | +0 | 355 | +0 | 356 | +0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 231790745 | 339 | +0 | 599 | +0 | 511 | +12 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 18186863 | 1265 | +4 | 4223 | +48 | 6935 | +790 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 73743681 | 479 | +0 | 2556 | +0 | 5317 | +156 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1513172548 | 177 | +0 | 178 | +0 | 42 | +0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1270031302 | 35 | +0 | 36 | +0 | 6 | +0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 384622999 | 107 | +0 | 110 | +0 | 13 | +0 | 0 |
| `userland/net_proofs` | `dns` | pass | 325509103 | 217 | +0 | 829 | +0 | 1695 | +73 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1076828629 | 212 | +0 | 492 | +5 | 1782 | +42 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 2996435 | 2044 | +3 | 4469 | +10 | 671 | +8 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 723773952 | 111 | +0 | 307 | +0 | 670 | +45 | 0 |
