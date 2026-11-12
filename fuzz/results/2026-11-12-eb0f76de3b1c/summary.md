## Fuzz run `eb0f76de3b1c` (schedule)

13 targets, 13 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/43138753336

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 3342013 | 1855 | 241 | 432 | 42 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1671422847 | 928052 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 262677078 | 145850 | 303 | 362 | 357 | 0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 268822842 | 149263 | 339 | 618 | 557 | 6 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 12693981 | 7048 | 1293 | 4399 | 10156 | 581 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 68654590 | 38120 | 479 | 2582 | 5805 | 71 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1156014148 | 641873 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1657293417 | 920207 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 498098089 | 276567 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 295362448 | 163999 | 217 | 830 | 1946 | 14 | 0 |
| `userland/net_proofs` | `net_packets` | pass | 1800 | 1179226923 | 654762 | 212 | 504 | 2118 | 45 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 3959652 | 2198 | 2050 | 4544 | 734 | 6 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 895347245 | 497138 | 111 | 307 | 780 | 10 | 0 |
