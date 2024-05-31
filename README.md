# NAS-Information

A curated list about [NAS][info_nas] hardware and software, tips and tricks. This list is licenced by the [MIT license][license_mit].

<!-- Common (NAS) infos -->

[info_nas]: https://en.wikipedia.org/wiki/Network-attached_storage
[info_operating_system]: https://en.wikipedia.org/wiki/Operating_system
[info_raid]: https://en.wikipedia.org/wiki/RAID
[license_mit]: ./LICENSE

## NAS manufacturer

These are manufacturer of [NAS][info_nas] systems and they offer their devices with their own [OS][info_operating_system] installed.

- [ASUSTOR][nas_asustor], founded in 2011
- [Buffalo][nas_buffalo], first [NAS][info_nas] in 2003
- ~~[Drobo][nas_drobo]~~ [Does not exist anymore][nas_drobo_ex], 2005-2023
- ~~[kobol][nas_kobol]~~ [Does not exist anymore][nas_kobol_ex], 2017-2021
- [iXsystems][nas_ixsystems], founded in 1991, offers both, hardware for [NAS][info_nas] and public available [OS][info_operating_system] (TrueNAS) in variants
- [PiBox][nas_pibox], founded in 2019
- [PROMISE Technology][nas_promise]
- [QNAP][nas_qnap], founded in 2004
- [Synology][nas_synology], founded in 2000
- [TerraMaster][nas_terra_master], founded in 2010
- [Thecus][nas_thecus], founded in 2004
- [UGreen][nas_ugreen], founded in 2012, first [NAS][info_nas] in 2024
- [Western Digital][nas_western_digital], founded in 1970

<!-- NAS Manufacturers -->

[nas_asustor]: https://www.asustor.com/en/about/about_asustor
[nas_buffalo]: https://www.buffalo-technology.com
[nas_drobo]: https://www.drobo.com
[nas_drobo_ex]: https://en.wikipedia.org/wiki/Drobo
[nas_ixsystems]: https://www.truenas.com/
[nas_kobol]: https://kobol.io/
[nas_kobol_ex]: https://blog.kobol.io/2021/08/25/we-are-pulling-the-plug/
[nas_pibox]: https://pibox.io
[nas_promise]: https://www.promise.com/
[nas_qnap]: https://www.qnap.com
[nas_synology]: https://www.synology.com
[nas_terra_master]: https://www.terra-master.com
[nas_thecus]: https://www.thecus.com
[nas_ugreen]: https://nas.ugreen.com/
[nas_western_digital]: https://www.westerndigital.com

## Pimp a commercial NAS

There are some tricks available to pimp a commercial [NAS][info_nas].

- [Synology][nas_synology]
  - [RAM upgrade DS920+][tweak_synology_ds920p_ram]
- [TerraMaster][nas_terra_master]<sup>1)</sup>
  - [OMV on F2-220 (German)][tweak_terra_master_f2_220_omv]
  - [RAM upgrade F5-221][tweak_terra_master_f5_221_ram]
- [UGreen][nas_ugreen]<sup>2)</sup>
  - [Unleash UGreen NAS with TrueNAS instead of UGOS (German)][tweak_ugreen_truenas]
- [Western Digital][nas_western_digital]
  - [OMV on PR4100][tweak_western_digital_pr4100_omv]
  - [RAM upgrad PR4100][tweak_western_digital_pr4100_ram]

<sup>1)</sup> Most of the [TerraMaster][nas_terra_master] [NAS][info_nas] systems use an USB stick with the [OS][info_operating_system] installed. It seems to be easy to install any kind of [OS][info_operating_system] you want. Maybe the [Proxmox Virtual Environment][os_proxmox] is working?

<sup>2)</sup> It seems that at least the 4 bay model is using an internal SSD for the [OS][info_operating_system]. It seems to be easy to install any kind of [OS][info_operating_system] you want. Maybe the [Proxmox Virtual Environment][os_proxmox] is working?

<!-- NAS tweaks -->

[tweak_synology_ds920p_ram]: https://www.youtube.com/watch?v=3Ls5E5uTzVU
[tweak_terra_master_f2_220_omv]: https://www.bachmann-lan.de/terramaster-f2-220-nas-mit-openmediavault/
[tweak_terra_master_f5_221_ram]: https://www.youtube.com/watch?v=hk_wPRqOSKE
[tweak_ugreen_truenas]: https://www.youtube.com/watch?v=BWNH_JzMNPc
[tweak_western_digital_pr4100_omv]: https://forum.openmediavault.org/index.php?thread/37009-can-i-install-omv-on-a-wd-nas/
[tweak_western_digital_pr4100_ram]: https://www.youtube.com/watch?v=rMvw9gGN7dc

## DIY NAS hardware builds

In case you want to build your own [NAS][info_nas], you can find several instructions:

- [Brian Moses][builder_brian_moses]
- [Elefacts, a German site][builder_elefacts]
- [Heise Verlag, a German site][builder_heise]
- [Jeff Gerling][builder_jeff_gerling] - Various [RPi][hardware_raspberry_pi] based [NAS][info_nas]
- [Michael Lynch][builder_michael_lynch]
- [NASsie][builder_nassie] - a [RPi][hardware_raspberry_pi] based [NAS][info_nas] using the compute module
- [Serverbuilds, a kind of NAS community][builder_server_builds]
- [Technikaffe, a German Site][builder_technikaffe]

<!-- DIY NAS builds -->

[builder_brian_moses]: https://blog.briancmoses.com/categories/diy-nas/
[builder_elefacts]: https://www.elefacts.de/kategorie-nas_hardware-1
[builder_heise]: https://www.heise.de/preisvergleich/?cat=WL-1682454&hocid=ct
[builder_jeff_gerling]: https://www.jeffgeerling.com
[builder_michael_lynch]: https://mtlynch.io/building-a-vm-homelab/
[builder_nassie]: https://github.com/CyberLeader3000/NASsie
[builder_server_builds]: https://www.serverbuilds.net
[builder_technikaffe]: https://www.technikaffe.de/nas-eigenbau/

## DIY NAS operating systems

For a DIY [NAS][info_nas] you need an [OS][info_operating_system]. Here are some potential ones:

- [Openmediavault][os_omv]
- [TrueNAS Core][os_truenas_core], based on [FreeBSD][os_freebsd] since 2005
- [TrueNAS Scale][os_truenas_scale], based on [Debian][os_debian] since 2022
- [Unraid][os_unraid] (commercial)
- [XigmaNAS][os_xigmanas]

<!-- NAS operating systems -->

[os_debian]: https://www.debian.org
[os_freebsd]: https://www.freebsd.org
[os_omv]: https://www.openmediavault.org
[os_proxmox]: https://www.proxmox.com/en/
[os_truenas_core]: https://www.truenas.com/truenas-core/
[os_truenas_scale]: https://www.truenas.com/download-truenas-scale/
[os_unraid]: https://unraid.net
[os_xigmanas]: https://xigmanas.com/xnaswp/

## DIY NAS hardware

Promising [NAS][info_nas] hardware will be listet here:

- [Fractal Node Series][hardware_fractal_node] - PC cases for [NAS][info_nas]
- [Geekworm Pi Cases/hats][hardware_geekworm_rpi] - various solutions for [RPi][hardware_raspberry_pi] based [NAS][info_nas]
- [ICY Box internal storage solutions][hardware_icybox_internal_storage] - Internal cases and more, e. g. [3 bay cage][hardware_icybox_cage_3] in size of two 5 1/4, or [5 bay cage][hardware_icybox_cage_5] in size of three 5 1/4 default case slots
- [ICY Dock][hardware_icydock] - Internal cases and more, e. g. [3 bay cage][hardware_icydock_cage_3] in size of two 5 1/4, or [5 bay cage][hardware_icydock_cage_5] in size of three 5 1/4 default case slots
- [Interceptor Carrier Board][hardware_axzez_interceptor] for [RPi][hardware_raspberry_pi] compute module, supports 5 SATA drives
- [Jonsbo][hardware_jonsbo] - PC cases for [NAS][info_nas] builds
- [hardware_radxa sata hat][hardware_radxa sata hat] for [RPi][hardware_raspberry_pi]
- [Topton NAS boards][hardware_topton] - For the brave: Topton mainboards on AliExpress
- ~~[Wiretrustee][hardware_wiretrustee_ex]~~ - Project stopped, plans for hardware are public available

<!-- DIY NAS hardware -->

[hardware_axzez_interceptor]: https://www.axzez.com/axzez-circuit-boards
[hardware_fractal_node]: https://www.fractal-design.com/de/products/cases/node/
[hardware_geekworm_rpi]: https://geekworm.com/search?type=product&q=NAS
[hardware_icybox_cage_3]: https://dev.icybox.de/product/interne_speicherloesungen/IB-573SSK-12G
[hardware_icybox_cage_5]: https://dev.icybox.de/product/interne_speicherloesungen/IB-575SSK-12G
[hardware_icybox_internal_storage]: https://dev.icybox.de/products/interne_speicherloesungen
[hardware_icydock]: https://global.icydock.com/
[hardware_icydock_cage_3]: https://global.icydock.com/product_58.html
[hardware_icydock_cage_5]: https://global.icydock.com/product_65.html
[hardware_jonsbo]: https://www.jonsbo.com/en/product/ComputerCase/NASMotherboardSeries.html
[hardware_radxa sata hat]: https://radxa.com/products/accessories/penta-sata-hat/
[hardware_raspberry_pi]: https://www.raspberrypi.com/
[hardware_topton]: https://www.aliexpress.com/w/wholesale-topton-nas-board.html?spm=a2g0o.home.search.0
[hardware_wiretrustee_ex]: https://github.com/wiretrustee/cm4-sata-board

## External cases

Maybe you want to use a PC in front of the storage. In this case you may regard an external [RAID][info_raid] case supporting USB or thunderbolt.

- [Highpoint][hardware_highpoint]
- [hardware_owc][hardware_owc]
- [Raidsonic][hardware_raidsonic]

<!-- DIY NAS hardware -->

[hardware_highpoint]: https://www.highpoint-tech.com/raid-storage-enclosures
[hardware_owc]: https://www.owc.com
[hardware_raidsonic]: https://icybox.de/en/product-list.php?id=1

## Disk drive informations

- [Backblaze Hard Drive Data and Stats][info_backblaze_hdd]
- [Shingled Magnetic Recording vs Conventional Magnetic Recording (German)][info_smr_vs_cmr]

<!-- Common (NAS) infos -->

[info_backblaze_hdd]: https://www.backblaze.com/b2/hard-drive-test-data.html
[info_smr_vs_cmr]: https://www.elefacts.de/test-160-nas_festplatten_mit_smr_oder_cmr_ein_ueberblick_im_jahr_2021
