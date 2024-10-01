## 0.1.8 (2024-10-01)


### Bug Fixes

* Bind mount `/tmp/.X11-unix` for newer version of WSL2 ([#57](https://github.com/Isac-1507/wsl-distrod/issues/57)) ([921bc3c](https://github.com/Isac-1507/wsl-distrod/commit/921bc3c2262aae4cd4656be800371bbbde5770eb)), closes [#56](https://github.com/Isac-1507/wsl-distrod/issues/56)
* ci: Fix version command reported wrong version ([#58](https://github.com/Isac-1507/wsl-distrod/issues/58)) ([fd9bbdc](https://github.com/Isac-1507/wsl-distrod/commit/fd9bbdcce953b2660207aad2b59ec91ab210a621))
* Clean up /etc/environment when distrod is disabled. ([#32](https://github.com/Isac-1507/wsl-distrod/issues/32)) ([fc28178](https://github.com/Isac-1507/wsl-distrod/commit/fc281789900c561eb933d460e6b39483191fbca2))
* Fix a tar archive containing files with log path/linkname was not handled correctly (Fix [#6](https://github.com/Isac-1507/wsl-distrod/issues/6)) ([aeb96fd](https://github.com/Isac-1507/wsl-distrod/commit/aeb96fd3fc5a01eac88ca858d3c246ee13cf0e18))
* Fix autostart was failing for light-weight images from linuxcontainers.org ([6e73743](https://github.com/Isac-1507/wsl-distrod/commit/6e73743efa723fbe4e03cc6b1fb2758a5702b531))
* Fix mount argument, which caused undocumented behavior ([b59c6f6](https://github.com/Isac-1507/wsl-distrod/commit/b59c6f698e5310e7361402a37fce0c8f9f369f57))
* Fix scheduling task was not working on Windows of non-English locale. (Fix [#4](https://github.com/Isac-1507/wsl-distrod/issues/4)) ([b5ded6f](https://github.com/Isac-1507/wsl-distrod/commit/b5ded6fba0e6d43fd0f719efa9ed7e314dd178d7))
* Fix set_default_user was not working on Win11 with distros with custom names ([765fc9f](https://github.com/Isac-1507/wsl-distrod/commit/765fc9f3bf329350f025b86c41e55a99d6bd6735))
* Fix SystemdUnitDisabler followed absolute symbolic links ([#34](https://github.com/Isac-1507/wsl-distrod/issues/34)) ([533ee3f](https://github.com/Isac-1507/wsl-distrod/commit/533ee3f942d31f205755c65f6ca934b2086f66c3))
* Fix WSL's correct resolv.conf was removed during installation on Windows ([3a029e4](https://github.com/Isac-1507/wsl-distrod/commit/3a029e44c3e13bc8910dd33828ddfc659ca53ed2))
* Network services are now completely disabled for robustness rather than tweaked ([806073b](https://github.com/Isac-1507/wsl-distrod/commit/806073b25453137e2db4127a1c66c6ecbb47a0cf))
* Update hostname in hosts ([#33](https://github.com/Isac-1507/wsl-distrod/issues/33)) ([973f9e9](https://github.com/Isac-1507/wsl-distrod/commit/973f9e9406de7d84e6aa763e7fa7f367c9f282f0))


### Reverts

* Revert "Testing adding a after the first distrod launch" ([78b2bb3](https://github.com/Isac-1507/wsl-distrod/commit/78b2bb326abd95a7d22d67ffc86efe9c1553c3d4))



