# [NAS][info_nas]-Information

A curated list about [NAS][info_nas] hardware and software, tips and tricks. This list published using the [MIT license][license_mit].

<!-- Common (NAS) infos -->

[info_backup]: https://en.wikipedia.org/wiki/Backup
[info_docker]: https://en.wikipedia.org/wiki/Docker_(software)
[info_jbod]: https://en.wikipedia.org/wiki/Non-RAID_drive_architectures#JBOD
[info_nas]: https://en.wikipedia.org/wiki/Network-attached_storage
[info_operating_system]: https://en.wikipedia.org/wiki/Operating_system
[info_raid]: https://en.wikipedia.org/wiki/RAID
[info_raid_0]: https://en.wikipedia.org/wiki/Standard_RAID_levels#RAID_0
[info_raid_1]: https://en.wikipedia.org/wiki/Standard_RAID_levels#RAID_1
[info_raid_5]: https://en.wikipedia.org/wiki/Standard_RAID_levels#RAID_5
[info_raid_6]: https://en.wikipedia.org/wiki/Standard_RAID_levels#RAID_6
[info_wtf]: https://en.wikipedia.org/wiki/Fuck#Modern_usage
[license_mit]: ./LICENSE

## [NAS][info_nas] manufacturer

These are manufacturer of [NAS][info_nas] systems and they offer their devices with their own [OS][info_operating_system] installed.

- [Amber][nas_amber]
- [ASUSTOR Inc.][nas_asustor], founded in 2011
- [Buffalo EU B.V.][nas_buffalo], first [NAS][info_nas] in 2003
- ~~[Drobo][nas_drobo]~~ [Does not exist anymore][nas_drobo_ex], 2005-2023
- ~~[kobol][nas_kobol]~~ [Does not exist anymore][nas_kobol_ex], 2017-2021
- [fantec][nas_fantec]<sup>1)</sup>
- [ioSafe][nas_iosafe]
- [iXsystems, Inc.][nas_ixsystems], founded in 1991, offers both, hardware for [NAS][info_nas] and public available [OS][info_operating_system] ([TrueNAS][nas_ixsystems_truenas]) in variants
- [OWC Network Attached Storage][nas_owc], founded in 1988, they use [TrueNAS Scale][os_truenas_scale] on some [devices][nas_owc_jupiter_mini]
- [PiBox][nas_pibox], founded in 2019
- [Promise Technology Europe][nas_promise]
- [QNAP Systems, Inc.][nas_qnap], founded in 2004
- [Synology Inc.][nas_synology], founded in 2000
- [TerraMaster Technology Co., Ltd.][nas_terra_master], founded in 2010
- [Thecus - Subsidiary of Ennoconn][nas_thecus], founded in 2004
- [Ugreen Amerika Limited][nas_ugreen], founded in 2012, first [NAS][info_nas] in 2024
- [Western Digital Corporation][nas_western_digital], founded in 1970
- [Zima][nas_zima], offers both, hardware for [NAS][info_nas] and public available [OS][info_operating_system] ([CasaOS][os_casaos])

<sup>1)</sup>The fantec [NAS CL-35B2][nas_fantec_cl35b2] is outdated

<!-- NAS Manufacturers -->

[nas_amber]: https://amberpro.net/de/products
[nas_asustor]: https://www.asustor.com/
[nas_buffalo]: https://www.buffalo-technology.com/products/?tab=nas
[nas_drobo]: https://www.drobo.com/
[nas_drobo_ex]: https://en.wikipedia.org/wiki/Drobo
[nas_fantec]: https://www.fantec.de/en
[nas_fantec_cl35b2]: https://www.fantec.de/en/products/storage-devices/external-hard-drives/35-inch-external-hard-drives/produkt/details/artikel/1558_fantec_cl_35b2/
[nas_iosafe]: https://iosafe.com/
[nas_ixsystems]: https://www.truenas.com/
[nas_ixsystems_truenas]: https://en.wikipedia.org/wiki/TrueNAS
[nas_kobol]: https://kobol.io/
[nas_kobol_ex]: https://blog.kobol.io/2021/08/25/we-are-pulling-the-plug/
[nas_owc]: https://www.owc.com/
[nas_owc_jupiter_mini]: https://www.owc.com/solutions/jupiter-mini
[nas_pibox]: https://pibox.io/
[nas_promise]: https://www.promise.com/
[nas_qnap]: https://www.qnap.com/
[nas_synology]: https://www.synology.com/
[nas_terra_master]: https://www.terra-master.com/
[nas_thecus]: https://www.thecus.com/
[nas_ugreen]: https://nas.ugreen.com/
[nas_western_digital]: https://www.westerndigital.com/
[nas_zima]: https://www.zimaspace.com/

## Tune a commercial [NAS][info_nas]

There are some tricks available to tune a commercial [NAS][info_nas].

- [QNAP devices][nas_qnap]
  - [OMV][tweak_qnap_omv] on TS-453A
  - [TrueNAS Core][tweak_qnap] on TS-253A and TS-453A
  - [TrueNAS Core][tweak_qnap_x86] for x86 based devices
- [Synology devices][nas_synology]
  - [RAM upgrade DS920+][tweak_synology_ds920p_ram]
- [TerraMaster devices][nas_terra_master]<sup>1)</sup>
  - [OMV on F2-220 (German)][tweak_terra_master_f2_220_omv]
  - [Proxmox on T6-423 (German)][tweak_terra_master_t6_423]
  - [Proxmox on F4-424 (German)][tweak_terra_master_f4-424]
  - [RAM upgrade F5-221][tweak_terra_master_f5_221_ram]
- [UGreen devices][nas_ugreen]<sup>2)</sup>
  - [Unleash UGreen NAS with TrueNAS instead of UGOS (German)][tweak_ugreen_truenas]
- [Western Digital devices][nas_western_digital]
  - [OMV on PR4100][tweak_western_digital_pr4100_omv]
  - [RAM upgrad PR4100][tweak_western_digital_pr4100_ram]

<sup>1)</sup> Most of the [TerraMaster][nas_terra_master] [NAS][info_nas] systems use an USB stick with the [OS][info_operating_system] installed. It seems to be easy to install any kind of [OS][info_operating_system] you want. Maybe the [Proxmox Virtual Environment][os_proxmox] is working?

<sup>2)</sup> It seems that at least the 4 bay model is using an internal SSD for the [OS][info_operating_system]. It seems to be easy to install any kind of [OS][info_operating_system] you want. Maybe the [Proxmox Virtual Environment][os_proxmox] is working?

<!-- NAS tweaks -->

[tweak_qnap]: https://www.truenas.com/community/threads/installing-truenas-on-qnap-devices.91484/
[tweak_qnap_omv]: https://forum.qnapclub.de/blog/entry/602-alternatives-betriebssystem-backup-mit-openmediavault-auf-einem-qnap-nas/
[tweak_qnap_x86]: https://nascompares.com/2022/09/21/how-to-install-truenas-core-on-a-qnap-nas/
[tweak_synology_ds920p_ram]: https://www.youtube.com/watch?v=3Ls5E5uTzVU
[tweak_terra_master_f2_220_omv]: https://www.bachmann-lan.de/terramaster-f2-220-nas-mit-openmediavault/
[tweak_terra_master_f4-424]: https://www.youtube.com/watch?v=IattZevg7xY
[tweak_terra_master_f5_221_ram]: https://www.youtube.com/watch?v=hk_wPRqOSKE
[tweak_terra_master_t6_423]: https://www.youtube.com/watch?v=OMAgRPBngZI
[tweak_ugreen_truenas]: https://www.youtube.com/watch?v=BWNH_JzMNPc
[tweak_western_digital_pr4100_omv]: https://forum.openmediavault.org/index.php?thread/37009-can-i-install-omv-on-a-wd-nas/
[tweak_western_digital_pr4100_ram]: https://www.youtube.com/watch?v=rMvw9gGN7dc

## DIY [NAS][info_nas] hardware builds

In case you want to build your own [NAS][info_nas], you can find several instructions:

- [Brian Moses][builder_brian_moses]
- [Elefacts, a German site][builder_elefacts]
- [Heise Verlag, a German site][builder_heise]
- [Jeff Gerling][builder_jeff_gerling] - Various [RPi][hardware_raspberry_pi] based [NAS][info_nas]
- [Michael Lynch][builder_michael_lynch]
- [NASsie][builder_nassie] - a [RPi][hardware_raspberry_pi] based [NAS][info_nas] using the compute module
- [Serverbuilds, a kind of NAS community][builder_server_builds]
- [Technikaffe, a German site][builder_technikaffe]

<!-- DIY NAS builds -->

[builder_brian_moses]: https://blog.briancmoses.com/categories/diy-nas/
[builder_elefacts]: https://www.elefacts.de/kategorie-nas_hardware-1
[builder_heise]: https://www.heise.de/preisvergleich/?cat=WL-1682454&hocid=ct
[builder_jeff_gerling]: https://www.jeffgeerling.com/
[builder_michael_lynch]: https://mtlynch.io/building-a-vm-homelab/
[builder_nassie]: https://github.com/CyberLeader3000/NASsie
[builder_server_builds]: https://www.serverbuilds.net/
[builder_technikaffe]: https://www.technikaffe.de/nas-eigenbau/

## DIY [NAS][info_nas] operating systems

For a DIY [NAS][info_nas] you need an [OS][info_operating_system]. Here are some potential ones:

- [CasaOS: Your Personal Cloud OS][os_casaos]<sup>1)</sup> - Runs on top of Debian/Ubuntu/Rasperry Pi OS and others
- [Cosmos - Escape the cloud][os_cosmos]: A [Docker][info_docker] based [OS][info_operating_system]
- [libreCMC][os_librecmc] - The _libre_ Embedded GNU/Linux Distro<sup>2)</sup>, used on [GnuBee][hardware_gnubee]
- [Openmediavault][os_omv] - The open network attached storage solution, since 2009
- [Proxmox][os_proxmox] - A hypervisor where you can run any OS in virtual machines
- [TrueNAS Core][os_truenas_core], based on [FreeBSD][os_freebsd] since 2005
- [TrueNAS Scale][os_truenas_scale], based on [Debian][os_debian] since 2022
- [Turnkey Linux Fileserver][os_turnkey_linux], since 2008
- [umbrelOS][os_umbrelos] - The no-brainer home cloud OS<sup>3)</sup>
- [Unraid][os_unraid] (commercial), since 2005
- [XigmaNAS][os_xigmanas], fork of FreeNAS<sup>4)</sup>, since 2012

<sup>1)</sup> The [OS][info_operating_system] does not support [RAID][info_raid], more a [Docker OS][info_docker], the `Merge Storage` option (Beta) seems to bundle the disks like [JBOD][info_jbod].

<sup>2)</sup> The code is NOT on GitHub but on their own [server][os_librecmc_repos]

<sup>3)</sup> The [OS][info_operating_system] does not support [RAID][info_raid], more a [Docker OS][info_docker].

<sup>4)</sup> The former FreeNAS project is also the root of [TrueNAS Core][nas_ixsystems_truenas] of the copmany [iXsystems][nas_ixsystems].

<!-- NAS operating systems -->

[os_casaos]: https://casaos.io/
[os_cosmos]: https://cosmos-cloud.io/
[os_debian]: https://www.debian.org/
[os_freebsd]: https://www.freebsd.org/
[os_librecmc]: https://librecmc.org/
[os_librecmc_repos]: https://gogs.librecmc.org/libreCMC
[os_omv]: https://www.openmediavault.org/
[os_proxmox]: https://www.proxmox.com/
[os_truenas_core]: https://www.truenas.com/truenas-core/
[os_truenas_scale]: https://www.truenas.com/download-truenas-scale/
[os_turnkey_linux]: https://www.turnkeylinux.org/
[os_umbrelos]: https://umbrel.com/umbrelos#install
[os_unraid]: https://unraid.net/
[os_xigmanas]: https://xigmanas.com/xnaswp/

## DIY [NAS][info_nas] hardware

Promising [NAS][info_nas] hardware will be listet here:

- [Fractal Node Series][hardware_fractal_node] - PC cases for [NAS][info_nas]
- [Geekworm Pi Cases/hats][hardware_geekworm_rpi] - various solutions for [RPi][hardware_raspberry_pi] based [NAS][info_nas]
- [GnuBee][hardware_gnubee] - GnuBee: [NAS][info_nas] for a personal cloud
- [ICY Box internal storage solutions][hardware_icybox_internal_storage] - Internal cases and more, e. g. [3 bay cage][hardware_icybox_cage_3] in size of two 5 1/4, or [5 bay cage][hardware_icybox_cage_5] in size of three 5 1/4 default case slots
- [ICY Dock][hardware_icydock] - Internal cases and more, e. g. [3 bay cage][hardware_icydock_cage_3] in size of two 5 1/4, or [5 bay cage][hardware_icydock_cage_5] in size of three 5 1/4 default case slots
- [Interceptor Carrier Board][hardware_axzez_interceptor] for [RPi compute module][hardware_raspberrypi_compute_module4], supports 5 SATA drives
- [Jonsbo][hardware_jonsbo] - PC cases for [NAS][info_nas] builds
- [Radxa Penta SATA HAT][hardware_radxa sata hat] for [RPi][hardware_raspberry_pi]
- [Silverstone][hardware_silverstone] - PC cases for [NAS][info_nas] and more, e. g. [5 bay cage][hardware_silverstone_cage_5] in size of three 5 1/4 default case slots or the [5 bay NAS case][hardware_silverstone_nas_case]
- [Topton NAS boards][hardware_topton] - For the brave: Topton mainboards on AliExpress
- [Waveshare "PiBox"][hardware_waveshare_pibox] - Similar case to [PiBox][nas_pibox], for two 2 1/2" disk drives and a large display
- [Waveshare "Flashtor"][hardware_waveshare_flashtor] - Case with carrierboard for [Raspberry Pi Compute Module 4][hardware_raspberrypi_compute_module4] and two M2 NVME slots, similar to [Asustor Flashtor][hardware_asustor_flashtor]
- ~~[Wiretrustee][hardware_wiretrustee_ex]~~ - Project stopped, plans for hardware are public available

<!-- DIY NAS hardware -->

[hardware_asustor_flashtor]: https://www.asustor.com/de/product?p_id=79
[hardware_axzez_interceptor]: https://www.axzez.com/axzez-circuit-boards
[hardware_fractal_node]: https://www.fractal-design.com/de/products/cases/node/
[hardware_geekworm_rpi]: https://geekworm.com/search?type=product&q=NAS
[hardware_gnubee]: http://gnubee.org/
[hardware_icybox_cage_3]: https://dev.icybox.de/product/interne_speicherloesungen/IB-573SSK-12G
[hardware_icybox_cage_5]: https://dev.icybox.de/product/interne_speicherloesungen/IB-575SSK-12G
[hardware_icybox_internal_storage]: https://dev.icybox.de/products/interne_speicherloesungen
[hardware_icydock]: https://global.icydock.com/
[hardware_icydock_cage_3]: https://global.icydock.com/product_58.html
[hardware_icydock_cage_5]: https://global.icydock.com/product_65.html
[hardware_jonsbo]: https://www.jonsbo.com/en/product/ComputerCase/NASMotherboardSeries.html
[hardware_raspberrypi_compute_module4]: https://www.raspberrypi.com/products/compute-module-4/?variant=raspberry-pi-cm4001000
[hardware_radxa sata hat]: https://radxa.com/products/accessories/penta-sata-hat/
[hardware_raspberry_pi]: https://www.raspberrypi.com/
[hardware_silverstone]: https://www.silverstonetek.com/
[hardware_silverstone_cage_5]: https://www.silverstonetek.com/en/product/info/storage/FS305-12G/
[hardware_silverstone_nas_case]: https://www.silverstonetek.com/en/product/info/computer-chassis/CS351/
[hardware_topton]: https://www.aliexpress.com/w/wholesale-topton-nas-board.html?spm=a2g0o.home.search.0
[hardware_waveshare_pibox]: https://www.waveshare.com/cm4-nas-double-deck-c4a.htm?sku=23880
[hardware_waveshare_flashtor]: https://www.waveshare.com/cm4-nvme-nas-box.htm
[hardware_wiretrustee_ex]: https://github.com/wiretrustee/cm4-sata-board

## DIY [NAS][info_nas] software

The basic job of a [NAS][info_nas] is to provide storage over the network. But nowadays a [NAS][info_nas] is more like a home server and offers countless opportunities for

- File synchronization with [Syncthing][app_syncthing]
- Network wide ad filtering by [AdGuard][app_adguard] or [Pi-hole][app_pihole]
- Organizing images by [Photoprism][app_photoprism]
- Smart home control by [Home Assistant][app_homeassistant]
- Streaming movies and/or music by [Emby][app_emby], [Jellyfin][app_jellyfin] or [Plex][app_plex]

So most of this software is avaliable for [Docker][info_docker]. There is native support for [Docker][info_docker] available at least in [OMV][os_omv], [TrueNAS Core][os_truenas_core] and [TrueNAS Scale][os_truenas_scale].

But there are also [OS][info_operating_system] which forces the usage of [Docker][info_docker] with less the focus on classical [NAS][info_nas] features like [CasaOS][os_casaos], [cosmos-cloud][os_cosmos] or [umbrelOS][os_umbrelos].

[app_adguard]: https://adguard.com/en/welcome.html
[app_emby]: https://emby.media/
[app_homeassistant]: https://www.home-assistant.io/
[app_jellyfin]: https://jellyfin.org/
[app_photoprism]: https://www.photoprism.app/
[app_pihole]: https://pi-hole.net/
[app_plex]: https://www.plex.tv/en-gb/
[app_syncthing]: https://syncthing.net/

## External cases

Maybe you want to use a PC in front of the storage. In this case you may regard an external [RAID][info_raid] case supporting USB or thunderbolt.

- [Highpoint][hardware_highpoint]
- [OWC External Drives][hardware_owc]
- [Raidsonic][hardware_raidsonic]

<!-- DIY NAS hardware -->

[hardware_highpoint]: https://www.highpoint-tech.com/raid-storage-enclosures
[hardware_owc]: https://www.owc.com/solutions/external-drives
[hardware_raidsonic]: https://icybox.de/en/product-list.php?id=1

## Disk drive informations

- [Backblaze Hard Drive Data and Stats][info_backblaze_hdd]
- [Buffalo: CMR vs SMR Hard Drives in Network Attached Storage (NAS)][info_buffalo_cmr_smr]
- [NAS Compares: SMR, CMR and PMR NAS Hard Drives- A Buyers Guide 2021][info_nas_disk_drives]
- [Shingled Magnetic Recording vs Conventional Magnetic Recording (German)][info_smr_vs_cmr]

<!-- Common (NAS) infos -->

[info_backblaze_hdd]: https://www.backblaze.com/b2/hard-drive-test-data.html
[info_buffalo_cmr_smr]: https://www.buffalotech.com/resources/cmr-vs-smr-hard-drives-in-network-attached-storage-nas-msp
[info_nas_disk_drives]: https://nascompares.com/2021/04/22/smr-cmr-and-pmr-nas-hard-drives-a-buyers-guide-2021/
[info_smr_vs_cmr]: https://www.elefacts.de/test-160-nas_festplatten_mit_smr_oder_cmr_ein_ueberblick_im_jahr_2021

## Configurations

These section will describe possible configurations which are common used.

### [NAS][info_nas] with one disk drive

A [NAS][info_nas] with one disk drive (named 1-bay) offers storage in the network. There is no security mechanism against hardware failures. In case the disk drive gets somehow broken, all data is lost.

### [NAS][info_nas] with two disk drives

A [NAS][info_nas] with two disk drives (named 2-bay) offers at least three variants of storage. There are

- [JBOD][info_jbod] - all disks drives are logically grouped and seems to be like one drive. The disks may have different sizes. The available storage size is the sum of both disk drives. To loose data is very high if a disk drive somehow gets broken.
- [RAID 0][info_raid_0] (striping) - all disk drives are logically grouped and seems to be like one drive. The disk drives must have the same size. The available storage size is the sum of both disk drives. If one disk drives gets somehow broken, all data is lost.
- [RAID 1][info_raid_1] (mirroring) - all disk drives are logically grouped and seems to be like one drive. The disk drives must have the same size. The available storage size is the size of one disk drive. If one of the disk drives gets somehow broken, the data is still available from the other disk.

### [NAS][info_nas] with four disk drives

A [NAS][info_nas] with four disks (named 4-bay) offers various configuration options. There are

- [JBOD][info_jbod] - see description above
- [RAID 0][info_raid_0] - see description above
- [RAID 1][info_raid_1] - see description above
- [RAID 5][info_raid_5] (distributed parity) - all disk drives are logically grouped and seems to be like one drive. The disks must have the same size. The available storage size is the sum of three disk drives. If one of the disk drives gets somehow broken, the data is still available from the other disk drives.
- [RAID 6][info_raid_6] - all disk drives are logically grouped and seems to be like one drive. The disks must have the same size. The available storage size is the sum of two disk drives. If one or two of the disk drives gets somehow broken, the data is still available from the other disk drives.

### [NAS][info_nas] with more than four disk drives

For [NAS][info_nas] systems with more than four disk drives there are all listed configurations possible and even combinations of [RAID levels][info_raid] of them. This is more related to professional usage and not relevant for private use.

## Szenarios

### Distributed [NAS][info_nas] system

A distributed [NAS][info_nas] system - [WTF][info_wtf]? This needs explanation. Most users misunderstand a [NAS][info_nas] system as kind of [backup][info_backup] system. But this is wrong. A [NAS][info_nas] provides some kind of snapshot of data. A [backup][info_backup] offers access to data missing in the snapshot. And for security reasons, the [backup][info_backup] should be located on a different location than the snapshot data. In concrete this means that the [NAS][info_nas] is at my home for example and the [backup][info_backup] at my parents home.

The app [Syncthing][app_syncthing] is important for the distributed [NAS][info_nas]. Assume that you have two parties, and each of them will have private data in size of aproximately 1 TB. So let's have two [NAS][info_nas] systems, one bay with a disk size of 4 TB. One moment - one bay [NAS][info_nas]? What about if the disk drive gets somehow broken? The data is almost save!

First of all install [Syncthing][app_syncthing] on the local PC and on the [NAS][info_nas]. Then establish a two way synchronization between the PC and the [NAS][info_nas]. This has to be done for both parties.

In a second step establish also an additional two way synchronization between the two [NAS][info_nas] systems. This time ensure that in the section [File Versioning][info_syncthing_fileversioning] you choose the right versioning system for your demands. For example a `staggered file versioning` is much better than `simple file versioning`. Why? Assume you get files containing a timestamp. While using the `staggered file versioning` somewhere old versions will be deleted. The same scenario using the `simple file versioning` will never delete any old version and will bloat the storage size used by [Syncthing][app_syncthing].

As summary you have

- Your data on your [NAS][info_nas]
- Have a [backup][info_backup] of your data
  - On your [NAS][info_nas]
  - On the second parties [NAS][info_nas]

Et voilá - this ia a distributed [NAS][info_nas]. See the image for more details. To `sync` a folder means that the folder is shared between the clients.

Let's define the term `NODE` as for a local [NAS][info_nas] with a [Syncthing][app_syncthing] installation.

![Distributed NAS](/assets/distributed_nas.png)

#### Sample config

In case you own a [Synology Inc.][nas_synology] using the [DSM 7.x][app_dsm], follow the described steps to turn it into a `NODE`:

- Install the `Container Manager` package to run the Docker version of [Synology Inc.][nas_synology].
- Important hint: The package `Web Station` is not used for a `NODE`.
- Create a `shared folder`, e. g. `syncthing`, to store the data.
- Create a folder `data` in this share.
- Connect via SSH and set permission of the folder `/volume1` to 777 and to the created share `/volume1/syncthing` to 777. If not, [Syncthing][app_syncthing] will be unable write to the share.
- In `Container Manager` create a project, e. g. `syncthing`, upload the [compose file][data_node_ds124] and **SKIP** the support in `Web Station`.
- The UI will be available by this URL: `http://<IP-OF-YOUR-NAS>:8384`

[app_dsm]: https://en.wikipedia.org/wiki/Synology#Synology_DiskStation_Manager_(DSM)
[data_node_ds124]: ./assets/docker-compose-ds124.yml
[info_syncthing_fileversioning]: https://docs.syncthing.net/v1.27.7/users/versioning
