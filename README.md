# NAS-Information

A curated list about [NAS][nas] hardware and software, tips and tricks. This list is licenced by the [MIT license][mit_license].

## NAS manufacturer

These are manufacturer of [NAS][nas] systems and they offer their devices with their own [OS][operating_system] installed.

- [ASUSTOR][asustor], founded in 2011
- [Buffalo][buffalo], first [NAS][nas] in 2003
- ~~[Drobo][drobo]~~ [Does not exist anymore][ex_drobo], 2005-2023
- ~~[kobol][kobol]~~ [Does not exist anymore][ex_kobol], 2017-2021
- [iXsystems][ixsystems], founded in 1991, offers also [NAS hardware][ixsystems_hardware] for their [OS][ixsystems]
- [PiBox][pibox], founded in 2019
- [PROMISE Technology][promise]
- [QNAP][qnap], founded in 2004
- [Synology][synology], founded in 2000
- [TerraMaster][terra_master], founded in 2010
- [Thecus][thecus], founded in 2004
- [UGreen][ugreen], founded in 2012, first [NAS][nas] in 2024
- [Western Digital][western_digital], founded in 1970

## Pimp a commercial NAS

There are some tricks available to pimp a commercial [NAS][nas].

- [Synology][synology]
  - [RAM upgrade DS920+][synology_ds920p_ram]
- [TerraMaster][terra_master]<sup>1)</sup>
  - [OMV on F2-220 (German)][terra_master_f2_220_omv]
  - [RAM upgrade F5-221][terra_master_f5_221_ram]
- [UGreen][ugreen]<sup>2)</sup>
  - [Unleash UGreen NAS with TrueNAS instead of UGOS (German)][ugreen_truenas]
- [Western Digital][western_digital]
  - [OMV on PR4100][western_digital_pr4100_omv]
  - [RAM upgrad PR4100][western_digital_pr4100_ram]

<sup>1)</sup> Most of the [TerraMaster][terra_master] [NAS][nas] systems use an USB stick with the OS installed. It seems to be easy to install any kind of OS you want. Maybe the [Proxmox Virtual Environment][proxmox] is working?
<sup>2)</sup> It seems that at least the 4 bay model is using an internal SSD for the OS. It seems to be easy to install any kind of OS you want. Maybe the [Proxmox [Proxmox Virtual Environment][proxmox] is working?

## DIY NAS hardware builds

In case you want to build your own [NAS][nas], you can find several instructions:

- [Brian Moses][brian_moses]
- [Elefacts, a German site][elefacts]
- [Heise Verlag, a German site][heise_nas]
- [Jeff Gerling][jeff_gerling] - Various [RPi][raspberry_pi] based [NAS][nas]
- [Michael Lynch][michael_lynch]
- [NASsie][diy_nas_nassie] - a [RPi][raspberry_pi] based [NAS][nas] using the compute module
- [Serverbuilds, a kind of NAS community][server_builds]
- [Technikaffe, a German Site][technikaffe]

## DIY NAS operating systems

For a DIY [NAS][nas] you need an [operating system][operating_system]. Here are some potential ones:

- [Openmediavault][omv]
- [TrueNAS Core][truenas_core], based on [FreeBSD][freebsd] since 2005
- [TrueNAS Scale][truenas_scale], based on [Debian][debian] since 2022
- [Unraid][unraid] (commercial)
- [XigmaNAS][xigmanas]

## DIY NAS hardware

Promising [NAS][nas] hardware will be listet here:

- [Fractal Node Series][case_fractal_node] - PC cases for [NAS][nas]
- [Geekworm Pi Cases/hats][geekworm_rpi_nas] - various solutions for [RPi][raspberry_pi] based [NAS][nas]
- [ICY Box internal storage solutions][icybox_internal_storage] - Internal cases and more, e. g. 3 bay cage in size of two 5 1/4, or 5 bay cage in size of three 5 1/4 default case slots
- [Interceptor Carrier Board][axzez_interceptor] for [RPi][raspberry_pi] compute module, supports 5 SATA drives
- [Jonsbo N1][case_jonsbo_n1] - PC case for [NAS][nas]
- [Radxa SATA hat][radxa sata hat] for [RPi][raspberry_pi]
- [Topton NAS boards][ae_topton] - For the brave: Topton mainboards on AliExpress
- ~~[Wiretrustee][ex_wiretrustee]~~ - Project stopped, plans for hardware are public available

## External cases

Maybe you want to use a PC in front of the storage. In this case you may regard an external [RAID][raid] case supporting USB or thunderbolt.

- [Highpoint][highpoint]
- [OWC][owc]
- [Raidsonic][raidsonic]

## Disk drive informations

- [Backblaze][backblaze]
- [Shingled Magnetic Recording vs Conventional Magnetic Recording][smr_vs_cmr]

[ae_topton]: https://www.aliexpress.com/w/wholesale-topton-nas-board.html?spm=a2g0o.home.search.0
[asustor]: https://www.asustor.com/en/about/about_asustor
[axzez_interceptor]: https://www.axzez.com/axzez-circuit-boards
[backblaze]: https://www.backblaze.com/b2/hard-drive-test-data.html
[brian_moses]: https://blog.briancmoses.com/categories/diy-nas/
[buffalo]: https://www.buffalo-technology.com
[case_fractal_node]: https://www.fractal-design.com/de/products/cases/node/
[case_jonsbo_n1]: https://www.jonsbo.com/en/products/N1.html
[debian]: https://www.debian.org
[diy_nas_nassie]: https://github.com/CyberLeader3000/NASsie
[drobo]: https://www.drobo.com
[elefacts]: https://www.elefacts.de/kategorie-nas_hardware-1
[ex_drobo]: https://en.wikipedia.org/wiki/Drobo
[ex_kobol]: https://blog.kobol.io/2021/08/25/we-are-pulling-the-plug/
[ex_wiretrustee]: https://github.com/wiretrustee/cm4-sata-board
[freebsd]: https://www.freebsd.org
[geekworm_rpi_nas]: https://geekworm.com/search?type=product&q=NAS
[heise_nas]: https://www.heise.de/preisvergleich/?cat=WL-1682454&hocid=ct
[highpoint]: https://www.highpoint-tech.com/raid-storage-enclosures
[icybox_internal_storage]: https://dev.icybox.de/products/interne_speicherloesungen
[ixsystems]: https://www.truenas.com/
[ixsystems_hardware]: https://www.truenas.com/truenas-mini/
[ixsystems_truenas]: https://www.truenas.com/software-status/
[jeff_gerling]: https://www.jeffgeerling.com
[kobol]: https://kobol.io/
[michael_lynch]: https://mtlynch.io/building-a-vm-homelab/
[mit_license]: ./LICENSE
[nas]: https://en.wikipedia.org/wiki/Network-attached_storage
[omv]: https://www.openmediavault.org
[operating_system]: https://en.wikipedia.org/wiki/Operating_system
[owc]: https://www.owc.com
[pibox]: https://pibox.io
[promise]: https://www.promise.com/
[proxmox]: https://www.proxmox.com/en/
[qnap]: https://www.qnap.com
[radxa sata hat]: https://radxa.com/products/accessories/penta-sata-hat/
[raid]: https://en.wikipedia.org/wiki/RAID
[raidsonic]: https://icybox.de/en/product-list.php?id=1
[raspberry_pi]: https://www.raspberrypi.com/
[server_builds]: https://www.serverbuilds.net
[smr_vs_cmr]: https://www.elefacts.de/test-160-nas_festplatten_mit_smr_oder_cmr_ein_ueberblick_im_jahr_2021
[synology]: https://www.synology.com
[synology_ds920p_ram]: https://www.youtube.com/watch?v=3Ls5E5uTzVU
[technikaffe]: https://www.technikaffe.de/nas-eigenbau/
[terra_master]: https://www.terra-master.com
[terra_master_f2_220_omv]: https://www.bachmann-lan.de/terramaster-f2-220-nas-mit-openmediavault/
[terra_master_f5_221_ram]: https://www.youtube.com/watch?v=hk_wPRqOSKE
[thecus]: https://www.thecus.com
[truenas_core]: https://www.truenas.com/truenas-core/
[truenas_scale]: https://www.truenas.com/download-truenas-scale/
[ugreen]: https://nas.ugreen.com/
[ugreen_truenas]: https://www.youtube.com/watch?v=BWNH_JzMNPc
[unraid]: https://unraid.net
[western_digital]: https://www.westerndigital.com
[western_digital_pr4100_omv]: https://forum.openmediavault.org/index.php?thread/37009-can-i-install-omv-on-a-wd-nas/
[western_digital_pr4100_ram]: https://www.youtube.com/watch?v=rMvw9gGN7dc
[xigmanas]: https://xigmanas.com/xnaswp/
