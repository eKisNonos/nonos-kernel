## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/42147934974

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 5323173 | 2955 | 241 | 432 | 42 | 2 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 2066722397 | 1147541 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 239276487 | 132857 | 301 | 355 | 356 | 0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 231790745 | 128701 | 339 | 599 | 511 | 12 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 18186863 | 10098 | 1265 | 4223 | 6935 | 790 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 73743681 | 40945 | 479 | 2556 | 5317 | 156 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1513172548 | 840184 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1270031302 | 705181 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 384622999 | 213560 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 325509103 | 180737 | 217 | 829 | 1695 | 73 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 1076828629 | 597905 | 212 | 492 | 1782 | 42 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 2996435 | 1663 | 2044 | 4469 | 671 | 8 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 723773952 | 401873 | 111 | 307 | 670 | 45 | 0 |
