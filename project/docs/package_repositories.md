<!-- https://en.opensuse.org/Package_repositories -->

## Package Repositories

Package Repositories are locations where software, updates, bugfixes, security patches, etc. are accessed. A Repository can be located on local media such as a DVD, a Local Area Network, or online.

These are the official openSUSE repositories. Well tested packages, security and bugfixes are provided. Online ones are convenient to use if you have good bandwidth. For information on how to add them, see [[SDB:Add package repositories|Add package repositories]].}}

### On-disk official repositories
The first repositories that you may have seen are the DVDs. You can have several sorts of such repositories, with different contents. None of them, including the huge two layer DVD of the boxed version, includes all the openSUSE packages, so you will also need the online repositories if possible.

- The '''[[SDB:Download_help|downloadable DVD]]''' is one single layer 4.7 GB DVD. It hosts the most important packages, but this makes only a very small subset of the whole openSUSE.
- The '''[[Buy openSUSE|boxed DVD]]''' consist of a double layer DVD and is available from your dealer for a fee that includes installation support. But even this double DVD doesn't hold all the openSUSE packages.

### Using online repositories
- For [[YaST]], there is no difference between '''online (internet)''' and on disk (DVD or hard drive) repositories, all the packages are seen as if they are on a very big drive.
- If you keep your computer always connected via a broadband connection, you can remove the "repository" OSS DVD if you install the standard online repository below.
- If you have enough disk space, you can also download a repository snapshot, but be advised that this can take up to 20 GB or even more.

---

## Official Repositories
The following is a list of official repositories supported by openSUSE.
{{Info|'''Note:''' You may have added one or more of the repositories below during installation, and the necessary repositories are added by default at the time of installation. Please check which repositories have already been added to your system to avoid running into problems.}}

### OSS
The main repository: open source software only.
{{Version_note|Tumbleweed|http://download.opensuse.org/tumbleweed/repo/oss/}}
{{Version_note|Leap 15.2|http://download.opensuse.org/distribution/leap/15.2/repo/oss/}}

### Non-OSS
Non-free (as in freedom) software, such as [[Opera]] and [[Steam]].
{{Version_note|Tumbleweed|http://download.opensuse.org/tumbleweed/repo/non-oss/}}
{{Version_note|Leap 15.2|http://download.opensuse.org/distribution/leap/15.2/repo/non-oss/}}

### Update
Repository of official security and bugfix updates for OSS packages.
{{Version_note|Tumbleweed|http://download.opensuse.org/update/tumbleweed/}}
{{Version_note|Leap 15.2|http://download.opensuse.org/update/leap/15.2/oss/}}

### Update Non-OSS
Repository of official security and bugfix updates for non-OSS packages.
{{Version_note|Leap 15.2|http://download.opensuse.org/update/leap/15.2/non-oss/}}

### Src-OSS
Source RPMs. Advanced users only.
{{Version_note|Tumbleweed|http://download.opensuse.org/tumbleweed/repo/src-oss}}
{{Version_note|Leap 15.2|http://download.opensuse.org/source/distribution/leap/15.2/repo/oss/}}

### Src-Non-OSS
Source RPMs. Advanced users only.
{{Version_note|Tumbleweed|http://download.opensuse.org/tumbleweed/repo/src-non-oss}}
{{Version_note|Leap 15.2|http://download.opensuse.org/source/distribution/leap/15.2/repo/non-oss/}}

### Debug
Debuginfo packages. Advanced users only.
{{Version_note|Tumbleweed|http://download.opensuse.org/debug/tumbleweed/repo/oss/}}
{{Version_note|Leap 15.2|http://download.opensuse.org/debug/distribution/leap/15.2/repo/oss/ and updates http://download.opensuse.org/debug/update/leap/15.2/oss/}}

---

## Semi official repositories
These are repositories available which are not officially supported by openSUSE, but they contain useful packages which you should feel free to '''use at your own risk'''.

### Contrib
The [[openSUSE:Contrib|Contrib]] repository is now '''obsolete'''.

### KDE
See [[KDE repositories]].

### GNOME
See [[GNOME repositories]].

### LXDE
See [[LXDE repositories]].

### Xfce
See [[Xfce repositories]].

### Fonts
{{Version_note|Tumbleweed|http://download.opensuse.org/repositories/M17N:/fonts/openSUSE_Tumbleweed}}
{{Version_note|Leap 15.2|http://download.opensuse.org/repositories/M17N:/fonts/openSUSE_Leap_15.2/}}

### OwnCloud
- OwnCloud Server:
{{Version_note|Tumbleweed|http://download.owncloud.org/download/repositories/10.0/openSUSE_Tumbleweed/}}


- OwnCloud Desktop Client:
{{Version_note|Tumbleweed|http://download.opensuse.org/repositories/isv:/ownCloud:/desktop/openSUSE_Tumbleweed/}}
{{Version_note|Leap 15.2|http://download.opensuse.org/repositories/isv:/ownCloud:/desktop/openSUSE_Leap_15.2/}}

---

## Factory and Project repositories
When you encounter a bug in an openSUSE package and you cannot wait for your problem to be solved, there is a good chance that the bug does not appear in a recent version, either because it has been explicitly fixed or because it disappeared by itself. In order to test for this, you can try "bleeding edge" packages built by project developers. In order to get at the most recent version, go to the [http://software.opensuse.org/ Software Portal] and install the package with the most recent version number.

{{Warning|Those packages are unsupported and may introduce further bugs that may corrupt or destroy your data, so use caution and back up often!}}

---

## See also
- [[Additional package repositories]]
- [[SDB:Add package repositories|Add package repositories]]
- [[SDB:Vendor_change_update|Vendor change update]]

---

## External links
- [http://software.opensuse.org/search openSUSE Build Service Software Search]
- [http://packman.links2linux.org/packages Packman Package Search]

[[Category:Repositories]]

[[de:Paket_Repositorys]]
[[es:Repositorios de software]]
[[fr:Package Repositories]]
[[it:Package repositories]]
[[pl:Repozytoria]]
[[pt:Package Repositories]]
[[ru:Package Repositories]]
[[ja:パッケージリポジトリ]]
[[zh:主要供应源]]
