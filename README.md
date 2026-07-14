Tested on

![Red Hat](https://img.shields.io/badge/Red%20Hat-EE0000?style=for-the-badge&logo=redhat&logoColor=white)
![Rocky Linux](https://img.shields.io/badge/-Rocky%20Linux-%2310B981?style=for-the-badge&logo=rockylinux&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

fortune-mod
=========

Compile and install fortune-mod from https://github.com/shlomif/fortune-mod.


Role Variables (defaults)
--------------

| variable | value | description |
| --- | --- | --- |
| `packages_redhat` | see *defaults/main.yml* | Packages needed for Red Hat |
| `packages_debian` | see *defaults/main.yml* | Packages needed for Debian / Ubuntu|
| `dest_dir` | `~/fortune-mod` | Destination directory (will be created) |
| `release` | `fortune-mod-3.24.0` | Which release to use |
| `file_extension` | `.tar.xz` | |
| `build_dir` | `{{ dest_dir }}/{{ release }}/build` | Build directory will be created |
| `download_url` | see *defaults/main.yml* | Where to fetch the release from |

Example Playbook
----------------

    - hosts: servers
      roles:
         - fortune-mod

License
-------

MIT

Author Information
------------------

4munix
