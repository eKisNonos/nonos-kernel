## Fuzz run `eb0f76de3b1c` (schedule)

12 targets, 12 passed, 0 crash inputs. https://github.com/eKisNonos/nonos-kernel/actions/runs/44000229790

| crate | target | status | seconds | execs | exec/s | cov | features | corpus | new | crashes |
|---|---|---|---:|---:|---:|---:|---:|---:|---:|---:|
| `nonos-attest-path` | `v3_path` | pass | 1800 | 4643368 | 2578 | 241 | 432 | 42 | 0 | 0 |
| `nonos-attest-path` | `v4_parse` | pass | 1800 | 1718237722 | 954046 | 81 | 83 | 86 | 0 | 0 |
| `userland/admission_proofs` | `id_cert` | pass | 1800 | 191390235 | 106268 | 303 | 374 | 359 | 0 | 0 |
| `userland/admission_proofs` | `manifest` | pass | 1800 | 232982085 | 129362 | 339 | 618 | 577 | 3 | 0 |
| `userland/capsule_linux_proofs` | `linux_inputs` | pass | 1800 | 13154365 | 7303 | 1298 | 4425 | 12183 | 344 | 0 |
| `userland/capsule_linux_proofs` | `serve_wire` | pass | 1800 | 69377807 | 38521 | 479 | 2582 | 5981 | 26 | 0 |
| `userland/driver_proofs` | `ipc_decoders` | pass | 1800 | 1175175313 | 652512 | 177 | 178 | 42 | 0 | 0 |
| `userland/kernel_proofs` | `elf_header` | pass | 1800 | 1924129402 | 1068367 | 35 | 36 | 6 | 0 | 0 |
| `userland/market_proto` | `linux_policy` | pass | 1800 | 339107254 | 188288 | 107 | 110 | 13 | 0 | 0 |
| `userland/net_proofs` | `dns` | pass | 1800 | 324815507 | 180352 | 217 | 839 | 2116 | 22 | 0 |
| `userland/tls_proofs` | `tls_cert` | pass | 1800 | 4847348 | 2691 | 2056 | 4563 | 750 | 3 | 0 |
| `userland/tls_proofs` | `tls_record` | pass | 1800 | 731815668 | 406338 | 111 | 307 | 890 | 9 | 0 |
