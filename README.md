Tested on

![Red Hat](https://img.shields.io/badge/Red%20Hat-EE0000?style=for-the-badge&logo=redhat&logoColor=white)

fortune-mod
=========

Compile and install fortune-mod from https://github.com/shlomif/fortune-mod.


Role Variables (defaults)
--------------

| variable | value | description |
| --- | --- | --- |
| `packages_redhat` | see *defaults/main.yml* | packages needed for Red Hat |
| `dest_dir` | `~/fortune-mod` | Destination directory |
| `release` | `fortune-mod-3.24.0` | Which release to use |
| `file_extension` | `.tar.xz` | |
| `build_dir` | `{{ dest_dir }}/{{ release }}/build` | Build directory will be created |
| `download_url` | see *defaults/main.yml* | Where to fetch the release from |

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - fortune-mod

License
-------

MIT

Author Information
------------------

4munix
