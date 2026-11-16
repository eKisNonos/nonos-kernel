## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/43789910514

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 5346288 | 2968 | 241 | 432 | 42 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1199252177 | 665881 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 213894255 | 118764 | 303 | 374 | 359 | 0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 274726063 | 152540 | 339 | 618 | 574 | 2 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 12945158 | 7187 | 1298 | 4424 | 11839 | 349 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 66343382 | 36836 | 479 | 2582 | 5955 | 28 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1513136388 | 840164 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1263029262 | 701293 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 485003859 | 269296 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 188555174 | 104694 | 217 | 839 | 2094 | 20 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 793656590 | 440675 | 212 | 504 | 2207 | 6 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 5103741 | 2833 | 2054 | 4559 | 747 | 4 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 722347882 | 401081 | 111 | 307 | 881 | 18 | 0 |
