# Subsystem: install

## install/collect_disk_info.sh
- Layer: utility
- Language: sh

## install/entrypoint.sh
- Layer: utility
- Language: sh

## install/install_nomad.sh
- Doc: Project N.O.M.A.D.
- Layer: utility
- Language: sh
- Symbols:
  - `header` (function, line 47)
  - `header_red` (function, line 52)
  - `check_has_sudo` (function, line 57)
  - `check_is_bash` (function, line 69)
  - `check_is_debian_based` (function, line 79)
  - `check_is_x86_64` (function, line 89)
  - `ensure_dependencies_installed` (function, line 104)
  - `check_is_debug_mode` (function, line 140)
  - `generateRandomPass` (function, line 149)
  - `ensure_docker_installed` (function, line 159)
  - `check_docker_compose` (function, line 220)
  - `setup_nvidia_container_toolkit` (function, line 230)
  - `get_install_confirmation` (function, line 355)
  - `accept_terms` (function, line 370)
  - `create_nomad_directory` (function, line 391)
  - `download_management_compose_file` (function, line 410)
  - `download_helper_scripts` (function, line 445)
  - `start_management_containers` (function, line 472)
  - `get_local_ip` (function, line 481)
  - `verify_gpu_setup` (function, line 488)
  - `success_message` (function, line 598)

## install/migrate-disk-collector.sh
- Doc: Project N.O.M.A.D. — Disk Collector Migration Script  Script                | Project N.O.M.A.D.
- Layer: utility
- Language: sh
- Symbols:
  - `check_is_bash` (function, line 46)
  - `check_has_sudo` (function, line 55)
  - `check_confirmation` (function, line 65)
  - `check_docker_running` (function, line 81)
  - `check_compose_file` (function, line 93)
  - `stop_old_host_process` (function, line 103)
  - `backup_compose_file` (function, line 122)
  - `remove_old_bind_mount` (function, line 134)
  - `add_disk_collector_service` (function, line 153)
  - `restart_stack` (function, line 186)
  - `verify_disk_collector_running` (function, line 203)

## install/run_updater_fixes.sh
- Doc: Project N.O.M.A.D. - One-Time Updater Fix Script  Script                | Project N.O.M.A.D.
- Layer: utility
- Language: sh
- Symbols:
  - `check_is_bash` (function, line 55)
  - `check_confirmation` (function, line 64)
  - `check_has_sudo` (function, line 75)
  - `check_docker_running` (function, line 85)
  - `check_compose_file` (function, line 97)
  - `check_sidecar_dir` (function, line 106)
  - `backup_compose_file` (function, line 119)
  - `fix_sidecar_volume_mount` (function, line 130)
  - `download_updated_sidecar_files` (function, line 153)
  - `rebuild_sidecar` (function, line 170)
  - `restart_sidecar` (function, line 179)
  - `verify_sidecar_running` (function, line 197)

## install/start_nomad.sh
- Layer: utility
- Language: sh

## install/stop_nomad.sh
- Layer: utility
- Language: sh

## install/uninstall_nomad.sh
- Doc: Project N.O.M.A.D.
- Layer: utility
- Language: sh
- Symbols:
  - `check_has_sudo` (function, line 27)
  - `check_current_directory` (function, line 39)
  - `ensure_management_compose_file_exists` (function, line 46)
  - `get_uninstall_confirmation` (function, line 53)
  - `ensure_docker_installed` (function, line 71)
  - `check_docker_compose` (function, line 78)
  - `storage_cleanup` (function, line 88)
  - `uninstall_nomad` (function, line 105)

## install/update_nomad.sh
- Doc: Project N.O.M.A.D.
- Layer: utility
- Language: sh
- Symbols:
  - `check_has_sudo` (function, line 31)
  - `check_is_bash` (function, line 43)
  - `check_is_debian_based` (function, line 53)
  - `get_update_confirmation` (function, line 63)
  - `ensure_docker_installed_and_running` (function, line 81)
  - `check_docker_compose` (function, line 97)
  - `ensure_docker_compose_file_exists` (function, line 107)
  - `force_recreate` (function, line 114)
  - `get_local_ip` (function, line 128)
  - `success_message` (function, line 136)
