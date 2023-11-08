# Changelog

## 1.0.0 (2023-11-08)


### Features

* Add akmods signing keys ([00b1a67](https://github.com/antuan1996/akmods/commit/00b1a67b7fb891484f717a3acd227b0a7371c561))
* add all-builds check job ([1d58504](https://github.com/antuan1996/akmods/commit/1d58504fab4c8594a734a42d998658bdcd6b091c))
* add broadcom legacy wl driver ([14b9def](https://github.com/antuan1996/akmods/commit/14b9def3cf609cdb6b3e2c5f9260ad60547c4c22)), closes [#3](https://github.com/antuan1996/akmods/issues/3)
* Add evdi kmod to support displaylink ([de8dbed](https://github.com/antuan1996/akmods/commit/de8dbed3050de11232472c415d5e1b02a21fe6c2))
* Add gcadapter_oc driver kmod ([33487af](https://github.com/antuan1996/akmods/commit/33487afb2585b2d3189060e3ebcbdef28211b124))
* Add Google Coral TPU Gasket & Apex drivers ([238d8be](https://github.com/antuan1996/akmods/commit/238d8bea41225fc4b24f1911707e546af9252e5b))
* Add nct6687 kernel module for certain B550 chipset motherboards ([#65](https://github.com/antuan1996/akmods/issues/65)) ([14a14bd](https://github.com/antuan1996/akmods/commit/14a14bd8d601da8dacb1953d968a637a3b502982))
* Add new ublue-os/akmod copr repo ([b2c0452](https://github.com/antuan1996/akmods/commit/b2c0452a234a357f9377619e6b0290322aaa4375))
* add nvidia kmod builds and ublue-os-nvidia-addons ([eb462ee](https://github.com/antuan1996/akmods/commit/eb462ee50a40eeaf54b594f015a81a3712b94c7e))
* Add OpenRazer kmod ([#63](https://github.com/antuan1996/akmods/issues/63)) ([57c91c7](https://github.com/antuan1996/akmods/commit/57c91c70cf901ede5287a5b3723136ba7d84b258))
* Add OpenRGB kernel modules ([9f870f4](https://github.com/antuan1996/akmods/commit/9f870f42865a24a3f5e7f27528b2844487bdb5c6))
* Add ryzen_smu kmod ([#64](https://github.com/antuan1996/akmods/issues/64)) ([48bf5aa](https://github.com/antuan1996/akmods/commit/48bf5aa69f084a9e332485481b3a72e53cf9d685))
* Add steamdeck driver kmod ([a51dbe3](https://github.com/antuan1996/akmods/commit/a51dbe37467248825c9b2a6b068d928f85f783e0))
* Add winesync ([#76](https://github.com/antuan1996/akmods/issues/76)) ([c730077](https://github.com/antuan1996/akmods/commit/c73007718f262fb1e09f525569d988c550cc4bca))
* add xbox controller kmods ([b35d0fd](https://github.com/antuan1996/akmods/commit/b35d0fdc1712ae12823cdcfea7846c6110d6121c))
* Add xpad-noone driver ([205d07f](https://github.com/antuan1996/akmods/commit/205d07f6f2e01b955eeeb6f19593668eb67d3edc))
* auto-generate CDI yaml for nvidia ([#75](https://github.com/antuan1996/akmods/issues/75)) ([b726c52](https://github.com/antuan1996/akmods/commit/b726c52b25e955daaa87609d1362adefe8c10e24))
* build wl driver again ([bba4766](https://github.com/antuan1996/akmods/commit/bba4766cf8ce2c1cc705d62842ea189f93999d76))
* enable 3rd party repos for akmods ([f2fec1b](https://github.com/antuan1996/akmods/commit/f2fec1b3f18a98ee2a823c33bce09dad53268964))
* enable builds with Fedora 39 ([#50](https://github.com/antuan1996/akmods/issues/50)) ([37628a2](https://github.com/antuan1996/akmods/commit/37628a2bf372435af51b0e54886e0e65c43bbedf))
* Enable Surface akmods for Fedora 39 ([#80](https://github.com/antuan1996/akmods/issues/80)) ([097bc2b](https://github.com/antuan1996/akmods/commit/097bc2b3edc4ad3c51be8c61ddfbff45eb8cb3d0))
* Re-enable Xbox kmods for Fedora 39 ([#79](https://github.com/antuan1996/akmods/issues/79)) ([7aec937](https://github.com/antuan1996/akmods/commit/7aec937f65d5399ffdf3a3cef706e70f4ec23c71))
* split nvidia akmods into distinct images ([#54](https://github.com/antuan1996/akmods/issues/54)) ([4007e0c](https://github.com/antuan1996/akmods/commit/4007e0cb22a9715634eda8cd773315c5e74b1a6a))
* update to new repo for nvidia-container-toolkit ([45719c8](https://github.com/antuan1996/akmods/commit/45719c8d4f2320772f8a4584c70a3b715fbfd88b))
* Upgrade to steamdeck drivers from SteamOS 3.5 ([383b5f9](https://github.com/antuan1996/akmods/commit/383b5f9b7abd0d205e4b7a100defb27267fd2a6a))


### Bug Fixes

* Added link from /usr/bin/rpm-ostree to /usr/bin/ dnf ([52f0433](https://github.com/antuan1996/akmods/commit/52f0433d0c2b940090a79db8c7523f4140f1d07a))
* attempt fix build with extra quotes ([#9](https://github.com/antuan1996/akmods/issues/9)) ([caff9d3](https://github.com/antuan1996/akmods/commit/caff9d33ceb7b3e7741d74486183ef6dd29fb9df))
* **ci:** Set kernel flavor in image build args ([#72](https://github.com/antuan1996/akmods/issues/72)) ([96f54e5](https://github.com/antuan1996/akmods/commit/96f54e58b7a807f28d7698b0f0452335f14b2cc2))
* disable xone until as it disables too many controllers ([e0135d0](https://github.com/antuan1996/akmods/commit/e0135d08d0528cf02098d9576b7671007058c0ac))
* everything asus and surface ([#73](https://github.com/antuan1996/akmods/issues/73)) ([70af399](https://github.com/antuan1996/akmods/commit/70af39999c681566bd1c66f23834daa37b996aaa))
* Remove no longer needed ltrf216a driver ([7144d4b](https://github.com/antuan1996/akmods/commit/7144d4b20a1044ba1473fba16612a2ba44c14e04))
* Restore steamdeck and gcadapter_oc akmods ([b2c0452](https://github.com/antuan1996/akmods/commit/b2c0452a234a357f9377619e6b0290322aaa4375))
* sign akmods-nvidia images properly ([e71d7b2](https://github.com/antuan1996/akmods/commit/e71d7b22c30f63fe273ba2015fe8cdc40c755690))
* Switch to building jupiter driver instead of steamdeck ([e9c0078](https://github.com/antuan1996/akmods/commit/e9c0078220e1cff3cb8192d9c1de930092b05c17))
* temporarily disable xone kmod build ([76806ad](https://github.com/antuan1996/akmods/commit/76806adc856db2163c188125ba7546362282cee2))
* typo in v4l2loop rpm query ([#8](https://github.com/antuan1996/akmods/issues/8)) ([ff5f9b8](https://github.com/antuan1996/akmods/commit/ff5f9b874842e2b2314355293534c27aceabc9e3))
* use correct signing key 20230518 ([686c8d0](https://github.com/antuan1996/akmods/commit/686c8d0522155e213a262eee9e67a8b376686b5d))
* Use existing ublue-os/akmods repo file instead of redownloading, fix removed file for negativo17 repo akmods ([1fd1ad7](https://github.com/antuan1996/akmods/commit/1fd1ad78a43998377f43c04738895b085cdc97ba))
* use proper step output for image name ([f1c48ab](https://github.com/antuan1996/akmods/commit/f1c48ab3e98b5819c01f7146237e2506b1fdc718))
