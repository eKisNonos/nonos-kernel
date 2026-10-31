# NØNOS Benchmark Run

Output: `benchmarks/runs/41228050090-1`

- `boot-evidence` status `pass` elapsed `469804` ms
- `nonos.bench.bootlog.v1` status `pass` elapsed `` ms
- `nonos.bench.boot.matrix.v1` status `pass` elapsed `` ms
- `build-verify-fast` status `pass` elapsed `203274` ms
- `nonos.bench.host.v1` status `recorded` elapsed `` ms

Boot phases:
- `capsule_attest_ms` `96` ms
- `capsule_attest_to_runqueue_ms` `11` ms
- `capsule_install_ms` `7` ms
- `capsule_preflight_ms` `100` ms
- `first_display_flush_ms` `3770` ms
- `first_spawn_ms` `107` ms
- `first_surface_register_ms` `3611` ms
- `kernel_core_ms` `125` ms
- `microkernel_init_ms` `118` ms
- `userspace_entry_ms` `2512` ms

Sample aggregates:
- `capsule_attest_ms` count `28` min `81` avg `103.464` max `533` ms
- `capsule_attest_to_runqueue_ms` count `28` min `3` avg `6.786` max `44` ms
- `capsule_install_ms` count `28` min `1` avg `4.286` max `41` ms
- `capsule_preflight_ms` count `28` min `83` avg `105.964` max `536` ms
- `first_display_flush_ms` count `1` min `3770` avg `3770.0` max `3770` ms
- `first_spawn_ms` count `28` min `85` avg `110.25` max `577` ms
- `first_surface_register_ms` count `1` min `3611` avg `3611.0` max `3611` ms
- `kernel_core_ms` count `1` min `125` avg `125.0` max `125` ms
- `microkernel_init_ms` count `1` min `118` avg `118.0` max `118` ms
- `userspace_entry_ms` count `1` min `2512` avg `2512.0` max `2512` ms

Boot matrix aggregates:
- `capsule_attest_ms` count `1` min `96` avg `96.0` max `96` ms
- `capsule_attest_to_runqueue_ms` count `1` min `11` avg `11.0` max `11` ms
- `capsule_install_ms` count `1` min `7` avg `7.0` max `7` ms
- `capsule_preflight_ms` count `1` min `100` avg `100.0` max `100` ms
- `first_display_flush_ms` count `1` min `3770` avg `3770.0` max `3770` ms
- `first_spawn_ms` count `1` min `107` avg `107.0` max `107` ms
- `first_surface_register_ms` count `1` min `3611` avg `3611.0` max `3611` ms
- `kernel_core_ms` count `1` min `125` avg `125.0` max `125` ms
- `microkernel_init_ms` count `1` min `118` avg `118.0` max `118` ms
- `userspace_entry_ms` count `1` min `2512` avg `2512.0` max `2512` ms
